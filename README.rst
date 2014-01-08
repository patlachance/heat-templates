==============
Heat Templates
==============

Heat is a service to orchestrate multiple composite cloud applications using
templates

This repository provides:

* Example templates which demonstrate core Heat functionality
* Related image-building templates
* Template-related scripts and conversion tools

================
Attention points
================

* RHEL 6 / CentOS 6: ZeroConf is enable and add a route to 169.254/16 which prevents metadata retrieval. To fix this issue, one must add the "NOZEROCONF=yes" directive in the ifcfg-eth0 file. (http://www.cyberciti.biz/faq/fedora-centos-rhel-linux-disable-zeroconf-route-169-254-0-0/)
