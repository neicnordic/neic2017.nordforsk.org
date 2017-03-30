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

<img src="/assets/img/logo/indigo.png">

## 11th international dCache workshop

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

## Agenda

### Monday May 29

* 9:00 – 10:30 Parallel sessions
  * [dCache tutorial](#dcache-tutorial)
  * [Bring your site / dCache tune-up](#bring-your-site-dcache-tune-up-dcache-team) (dCache team)
  * *Coffee break 10:30 – 11:00*
* 12:30 – 13:30 Lunch
* 13:30 – 15:00
  * [Logistics - Sibel Yasar](#logistics) ~ 5 – 10 min
  * [dCache keynote](#dcache-keynote) - Patrick Fuhrmann ~ 10 min
  * [DESY Cloud](#desy-cloud) - Patrick Fuhrmann ~ 20 min
  * [dCache new features overview](#dcache-new-features-overview) - Patrick Fuhrmann ~ 20 min
  * [dCache software, how you get it?](#dcache-software-how-you-get-it) - Sibel Yasar ~ 10 min
  * [CEPH](#ceph) - Tigran Mkrtchyan ~ 10 min
* 15:00 – 15:30 Coffee
* 15:30 – 17:00
  * [What is HA dCache?](#what-is-ha-dcache) - Gerd Behrmann ~ 40 min
  * [NDGF HA current status](#ndgf-ha-current-status) - Mattias Wadenstein ~ 20 min
  * [!!!! Hands-on while talking](#hands-on-while-talking)
  * [Lightning talks](#lightning-talks) ~ 30 min, 5 min each

### Tuesday May 30

* 9:00 – 10:30
  * [NFS news](#nfs-news) - Tigran Mkrtchyan ~ 10 min
  * [SAMBA news](#samba-news) - Tigran Mkrtchyan ~ 10 min
  * [dCache with Cloud backend](#dcache-with-cloud-backend) - Tigran Mkrtchyan ~ 5 min
  * [Securing dCache communications](#securing-dcache-communications) - Anupam Ashish ~ 20 min
    * cell communication (ssl)
    * Stunnel for zookeeper
  * [RESTful dCache](#restful-dcache) - Marina Sahakyan ~ 40 min
    * QoS
    * Move to tape / move from tape
  * [REST API for Monitoring](#rest-api-for-monitoring) - Dmitry Litvintsev ~ 30 min
* 10:30 – 11:00 Coffee
* 11:00 - 12:30
  * [dCache view](#dcache-view) - Olufemi Segun Adeyemi ~ 30 min
  * [Resilient dCache](#resilient-dcache) - Dmitry Litvintsev ~ 20 min
    * configuration examples (from user perspective)
    * ! resilient + tape for cloud at DESY
  * [Macaroons](#macaroons) - Anupam Ashish ~ 40 min
* 12:30 – 13:30 Lunch
* 13:30 – 17:00
  * [INDIGO-DataCloud: CDMI/QoS](#indigo-datacloud-cdmi-qos) - Marina Sahakyan  & Anupam Ashish ~ 40 min
  * [The Book](#the-book) - Sibel Yasar ~ 10 min
  * [Fishbowl](#fishbowl) (~ 30 min)
* 15:00 – 15:30 Coffee
* 15:30 – 17:00
  * [Bring Your Site (fixing sites)](#bring-your-site-fixing-sites) - dCache team

## Abstracts

### Monday May 29

#### 9:00 – 10:30 Parallel sessions

*Coffee break 10:30 – 11:00*

##### dCache tutorial
Introduction for new administrators.

##### Bring your site /  dCache tune-up (dCache team)
A short session with dCache installation basics for newcomers. In parallel site
admins can rise their problems which can be solved with the help of dCache
developers and other admins.

#### 12:30 – 13:30 Lunch

#### 13:30 – 15:00

##### Logistics
Sibel Yasar ~ 5 – 10 min

Introduction to workshop logistic, agenda and team.

##### dCache keynote
Patrick Fuhrmann ~ 10 min

High-level view of dCache; funding, projects, vision

##### DESY Cloud
Patrick Fuhrmann ~ 20 min

High level overview of dCache's project status, its fundings, and the impact of
modern storage technology on upcoming developments.

##### dCache new features overview
Patrick Fuhrmann ~ 20 min

A deeper dive into new features of the latest dCache versions and an outlook on
upcoming functionalities.

##### dCache software, how you get it?
Sibel Yasar ~ 10 min

How and from where do I get my latest dCache release.

##### CEPH
Tigran Mkrtchyan ~ 10 min

Current status of CEPH (free-software storage platform) integration with dCache.
We’ll describe existing  unctionality and first experience.

#### 15:00 – 15:30 Coffee

#### 15:30 – 17:00

##### What is HA dCache ?
Gerd Behrmann ~ 40 min

Starting with version 3.0, dCache supports high availability deployments. This
allows central services to be scaled horizontally, provides fault tolerance for
central services, as well as zero-downtime staged upgrades. Such a setup
typically involves a redundant setup of ZooKeeper and PostgreSQL in addition to
dCache, and typically relies on a redundant load balancer such as HAProxy.

##### NDGF HA current status
Mattias Wadenstein ~ 20 min

NDGF has used such a setup since fall 2016 and has build quite some experience
with dCache HA. This talk will describe the concepts involved, give pointers on
how to migrate existing setups towards HA in steps, as well as a short demo.

##### !!!! Hands-on while talking

##### Lightning talks
~ 30 min, 5 min each

This is a great opportunity for you to have a short, 5 min, presentation the
areas you are using dCache for.


### Tuesday May 30

#### 9:00 – 10:30

##### NFS news
Tigran Mkrtchyan ~ 10 min

##### SAMBA news
Tigran Mkrtchyan ~ 10 min

##### dCache with Cloud backend
Tigran Mkrtchyan ~ 5 min

As being an industry standard, there are many players in the NFS protocol
community. We will present the current state of the NFS protocol family, news
from other vendors and dCache's internal developments.

##### Securing dCache communications
Anupam Ashish ~ 20 min

* cell communication (ssl)
* Stunnel for zookeeper

Distributed dCache instances become increasingly attractive for geographically
distributed installations. One of the aspects of such deployments is securing
the inter-component communication. We will present how to run dCache in a
distributed manner over wide area networks.

##### RESTful dCache
Marina Sahakyan ~ 40 min

* QoS
* Move to tape / move from tape

As we demonstrated during the Barcelona workshop, dCache has a new RESTful
interface, providing direct access to the chimera namespace. This time we will
present a set of new API calls to move files from/to a tape backend

##### REST API for Monitoring
Dmitry Litvintsev ~ 30 min

The RESTful interface is not only used for data management, but as well can be
the source for a monitoring infrastructure. We will share our ideas on
monitoring via the new RESTful interface and we will demonstrate the currently
available functionality.

#### 10:30 – 11:00 Coffee

#### 11:00 - 12:30

##### dCache view
Olufemi Segun Adeyemi ~ 30 min

During last years workshop we introduced dCache-view, the component utilising
the RESTful API to generate web pages for graphically uploading and downloading
files and to manipulate their quality of service. This year we will elaborate on
extended functionalities of that tool and on an enhanced look-and-feel.

##### Resilient dCache
Dmitry Litvintsev ~ 20 min

* configuration examples (from user perspective)
* ! resilient + tape for cloud at DESY

One of the ways to increase data resiliency in dCache is to keep multiple copies
of precious files. In dCache this feature used to be provided by the Replica
Manager. Based on a large set of new requirements by our customers it became
necessary to redesign and improve this component now called Resilient Manager.
We will demonstrate new and exciting features of this subsystem and will present
a typical migration path from its predecessor.

##### Macaroons
Anupam Ashish ~ 40 min

With the increasing availability of automated computing platforms (PaaS) and
scientific portals, allowing scientists to focus on their scientific work
instead of forcing them to become an IT expert, storage systems are no longer
directly accessed by processes under the control of the user but, instead, by a
chain of intermediate agents. Consequently, when it comes to authorisation, the
resource owner might have to grant permissions, on behave of the user, with
narrowing privileges, along that chain. To enable infrastructures to tackle this
issue, dCache is implementing Macaroons, a distributed authorisation method,
introduced by Google. We will provide examples on how Macaroons have been
integrated into dCache and how they can be used in complex computing and storage
infrastructures.

#### 12:30 – 13:30 Lunch

#### 13:30 – 17:00

##### INDIGO-DataCloud: CDMI/QoS &
Marina Sahakyan  & Anupam Ashish ~ 40 min

INDIGO-DataCloud (INtegrating Distributed data Infrastructures for Global
Exploitation) is a European project in the framework of the H2020 program aiming
to develope a data and computing platform targeting scientific communities,
deployable on multiple hardware and provisioned over hybrid private or public
e-infrastructures. This presentation will describe goals of the INDIGO-DataCloud
and dCache's involvement in terms of cloud storage and quality of service in
storage.  

##### The Book
Sibel Yasar ~ 10 min

Documentation is an essential component of any software product. Unfortunately,
it's always behind the actual development and is always out of date. To fix that
issue, we decided to switch to an easy-to-use tool chain to allow internal and
external contributors to update and publish the 'dCache Admin Book'. We'll
present the tool and its workflow.

##### Fishbowl
~ 30 min

This is our traditional open discussion about Life, the Universe and dCache.

#### 15:00 – 15:30 Coffee

#### 15:30 – 17:00

##### Bring Your Site (fixing sites)
dCache team

Site admins can raise their problems which are supposed to be solved with the
help of dCache developers and other admins.
