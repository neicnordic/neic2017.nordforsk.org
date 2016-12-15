---
layout: schedule
include: workshop
title: dCache
chair: sibel-yasar
color: "#ffcccc"
sessions:
    - ws-1-2-morning
    - ws-1-2-afternoon
    - ws-2-2-morning
    - ws-2-2-afternoon
---

### 11th international dCache workshop

We are happy to announce the 11th International dCache workshop, collocated with
NeIC 2017 Conference in Umeå from 2017-05-29 to 2017-05-30.

As with earlier workshops, the dCache team is eager to maintain and strengthen
the relationship to dCache system administrators, experienced or novice.
Contributions to the workshop will focus on presenting mechanisms helping
sysadmins to run secure and fault tolerant dCache systems. Furthermore, as
usual, the team will elaborate on ongoing and future developments. In more detail:

 As CEPH is becoming the standard for Object Storage Technologies, we’ll
introduce CEPH as a backend storage system, operated underneath dCache version
3.0. First production experiences, tips and pitfalls will be presented.

Starting with dCache 3.0 sysadmins are enabled to build an almost fully fault
tolerant dCache instance, surviving failure of a single arbitrary component.
As a side effect, we will be able provide help on how to upgrade systems without
downtime. Presentations will cover how to setup redundant core components and
how to run those in a production environment.

During the workshop we will demonstrate on how a geographically highly
distributed dCache installation can be sufficiently secured, even being operated
over the public wide area internet. We’ll show on how to setup the inter-domain
communication in a multi-site configuration and we will present the new “Tunnel
auto-discovery mechanism” as well as configuration updates to the Zookeeper cluster.

In order to provide a consistent name space management, we extended the already
presented RESTful interface to the dCache name space system. Besides a variety
of new name space functions, calls have been added, allowing users to query and
modify the Quality of the dCache Storage service provided by dCache itself and
its custodial back-ends.

Last but not least, our graphical interface into the dCache namespace has been
finalised. We’ll provide demos and instructions on how to enable and use the new
‘dCache-view’ component.

On top of those demos and presentations we’ll offer plenty of time for you to
meet your colleague-sysadmins and of course the dCache developers, to discuss
your experiences in running a dCache or to push for improvements simplifying
your life or triggering new features for your storage customers.
