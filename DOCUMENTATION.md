Documentation of the Smart City Guide
=============================================


The Smart City Guide is a set of software services that creates a unique user experience for
exploring cities with your friends in a social way.


Software Stack
==============

As a supporter of the open web technologies the prefered stack comprises of

  - HTML5
  - CSS3
  - JavaScript

on the client side, and the MEAN stack on the server side:

  - MongoDB
  - Express
  - AngularJS
  - NodeJS




Components
==========

The SCG consists of different components which are loosely coupled through Ajax and REST calls (SOA).
Also we aim towards an exchangability of components via standard protocols.
In theory you can exchange each component though the mileage may vary.

To support this we intend to support this exchangability by a set of instructions
(configuration standards etc) that ease this task.

The fragmentation to several services is intended because we try to nurture exchangeability for different
business models.


Social Network Enabler
------------------------

This component is responsible for social features like
  
  - user registration and sign-in
  - user profile
  - text status updates
  - picture upload status and status updates
  - etc

This software component will be the pump.io server: http://pump.io/
This is a federated social server software.



Signaling Server
----------------

For simple messaging purposes a signaling server based on socket.io will be used. This component is used by the other components as a messaging server with a simple state machine.

Namely he first service to use this is the video component, which is implemented on the client side via WebRTC.


External Components
-------------------

External components are systems to provide Point Of Interest (P.O.I.) information and recommendation engines. Intended components are:

  - Local Information SE (Orange)
  - Local Information SE (Fokus)
  - Recommendation Engine SE (Orange)
  - Identity Management GE (UPM)


Installation
------------

  t.b.d
