.. index::
   single: Security

The Security Component
======================

Introduction
------------

The Security Component provides a complete security system for your web
application. It ships with facilities for authenticating using HTTP basic
or digest authentication, interactive form login or X.509 certificate login,
but also allows you to implement your own authentication strategies.
Furthermore, the component provides ways to authorize authenticated users
based on their roles, and it contains an advanced ACL system.

Installation
------------

You can install the component in many different ways:

* Use the official Git repository (https://github.com/symfony/Security);
* :doc:`Install it via Composer</components/using_components>` (``symfony/security`` on Packagist_).

Sections
--------

* :doc:`/components/security/firewall`
* :doc:`/components/security/authentication`
* :doc:`/components/security/authorization`

.. _Packagist: https://packagist.org/packages/symfony/security