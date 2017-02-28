================
VNFFG User Guide
================

Abstract
========

This document describes the user guide for the OPNFV VNFFG project.

License
=======

.. This work is licensed under a Creative Commons Attribution 4.0 International License.
.. http://creativecommons.org/licenses/by/4.0

OpenStack VNFFG/SFC project
===========================

The OpenStack SFC (networking-sfc) project provides VNF Forwarding Graph
(VNFFG) capability to OpenStack networking (neutron). The feature is integrated
with the Tacker orchestrator. Multiple back-end implementations including OVS,
ONOS and ODL is described in the following documentation.

- https://docs.openstack.org/newton/networking-guide/config-sfc.html
- https://docs.openstack.org/ocata/networking-guide/config-sfc.html
- https://docs.openstack.org/developer/networking-sfc/

Integration with Openstack Tacker VNFFG Orchestrator
----------------------------------------------------
- https://specs.openstack.org/openstack/tacker-specs/specs/newton/tacker-networking-sfc.html
- https://specs.openstack.org/openstack/tacker-specs/specs/newton/tacker-vnffg.html
- https://blueprints.launchpad.net/tacker/+spec/tacker-vnffg
- https://review.openstack.org/#/c/292196/
- https://review.openstack.org/#/c/290771/

Integration with ONOS SDN controller
------------------------------------
- http://docs.openstack.org/developer/networking-onos/devref/sfc_driver.html
- http://docs.openstack.org/developer/networking-onos/specs/sfc_driver.html
- https://blueprints.launchpad.net/networking-sfc/+spec/networking-sfc-onos-driver

Integration with ODL SDN controller
-----------------------------------
- http://docs.openstack.org/developer/networking-odl/specs/sfc-driver.html
- https://blueprints.launchpad.net/networking-sfc/+spec/opendaylight-sfc-driver

Videos
------
Openstack Tacker/Neutron SFC/ONOS Controller Demo
- https://www.openstack.org/videos/austin-2016/realize-sfc-using-onos-controller

VNFFG/ONOS Framework (ONOSFW) Demo
- https://www.youtube.com/watch?v=2vWusqd3WJ4

Openstack Tacker/Neutron SFC/ODL Controller Demo
- https://www.openstack.org/videos/barcelona-2016/orchestrating-vnf-forwarding-graphs-and-sfc-using-opendaylight-neutron-and-tacker
