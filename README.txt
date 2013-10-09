==============================
``edem.shim.content.css``
==============================
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
CSS Shim for E-Democracy
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

:Author: `Bill Bushey`_
:Contact: Bill Bushey <bill.bushey@e-democracy.org>
:Date: 2013-10-08
:Organization: `E-Democracy.org`_
:Copyright: This document is licensed under a
  `Creative Commons Attribution-Share Alike 3.0 License`_
  by `E-Democracy.org`_.

Introduction
===========

This egg customizes the shim CSS for E-Democracy.org. It customizes 
`gs.shim.content.css`_.

Currently this egg provides general site icons and jQuery icons.

This egg should not be needed after the deployment of the new design.

jQuery UI Icons and CSS
=================

Included in this modules are icons and CSS from `jQuery UI 1.8.6`_. The icons
are made available to clients via configure.zcml. The CSS is not, and it is
believed that the CSS is never used by forums.e-democracy.org. However, the 
CSS is kept in this egg for consistency with previous code.

It is worth noting that this egg only contains icons and CSS from jQuery UI.
It does not contain any JavaScript from that library.

Resources
=========

- Code repository: https://github.com/e-democracy/edem.shim.content.css
- Questions and comments to http://groupserver.org/groups/development
- Report bugs at https://redmine.iopen.net/projects/groupserver

.. _GroupServer: http://groupserver.org/
.. _E-Democracy.org: http://e-democracy.org/
.. _Bill Bushey: http://groupserver.org/p/wbushey
.. _Creative Commons Attribution-Share Alike 3.0 License:
   http://creativecommons.org/licenses/by-sa/3.0/
.. _gs.shim.content.css: 
   https://source.iopen.net/groupserver/shim/gs.shim.content.css/
.. _jQuery UI 1.8.6: http://blog.jqueryui.com/2010/11/jquery-ui-1-8-6/
