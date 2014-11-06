toolscripts
===========

Copyright (c)  2014  Mika Tapojärvi <mika.tapojarvi@embelin.fi>.

Distributed under the MIT License, see file LICENSE.

Tool scripts for many use. Short description:

salt-minion-setup:

  Can be used for configuring Salt Stack (http://www.saltstack.com/) minions.

  Basically minion only needs to know a Salt master IP or domain name to work, and this
  script can set that. I've used it by wrapping it to a Debian package, calling it from
  postinst script to set an IP for a minion. This way I can initialize a virtual machine
  to be managed by the Salt master I want. Maybe there will be more functionality later.
