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

This covers the evolution of port-chain based Service Function Chaining(SFC)
from specification to implementation in OpenStack Newton, Ocata and Pike
releases and the associated APIs available through Neutron.

This project allows VNF orchestration applications at the northbound
Neutron networking-sfc API to be integrated with a wide variety of data-plane
implementations such as OVS or SDN controllers by means of a set of
networking-sfc southbound back-end drivers.

- https://docs.openstack.org/newton/networking-guide/config-sfc.html
- https://docs.openstack.org/ocata/networking-guide/config-sfc.html
- https://docs.openstack.org/developer/networking-sfc/

Integration with Openstack Tacker VNFFG Orchestrator
----------------------------------------------------
Tacker uses OpenStack networking-sfc to support the VNFFG Network Forwarding
Path (NFP) abstraction which maps directly to a networking-sfc Port Chain.
The Tacker specifications, including TOSCA metadata, data models and
abstractions to support orchestration are referenced.

- https://specs.openstack.org/openstack/tacker-specs/specs/newton/tacker-networking-sfc.html
- https://specs.openstack.org/openstack/tacker-specs/specs/newton/tacker-vnffg.html
- https://blueprints.launchpad.net/tacker/+spec/tacker-vnffg
- https://review.openstack.org/#/c/292196/
- https://review.openstack.org/#/c/290771/

Integration with ONOS SDN controller
------------------------------------
OpenStack networking-sfc integrates with the ONOS SDN controller using
a networking-sfc backend ONOS driver to map to the ONOS northbound API.

- http://docs.openstack.org/developer/networking-onos/devref/sfc_driver.html
- http://docs.openstack.org/developer/networking-onos/specs/sfc_driver.html
- https://blueprints.launchpad.net/networking-sfc/+spec/networking-sfc-onos-driver

Integration with ODL SDN controller
-----------------------------------
OpenStack networking-sfc integrates with the ODL SDN controller using
a networking-sfc backend ODL driver to map to the ODL northbound API.

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
