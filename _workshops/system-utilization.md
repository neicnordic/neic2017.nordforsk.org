---
layout: schedule
include: workshop
title: Monitoring HPC System Utilisation
chair: torben-rasmussen
color: "#cce4ff"
sessions:
    - ws-1-6-morning
    - ws-1-6-afternoon
---

## Monitoring HPC System Utilisation

HPC and e-Science infrastructures are tasked with providing compute systems and
services to, in many cases, a wide and varied range of scientific domains and/or
research disciplines within domains. This often means that users of the systems
and services have vastly varying levels of experience and that a wide and varied
range of software applications are running on the systems.

To ensure that the provided systems are properly and well utilised, monitoring
the utilisation of several types of resources (e.g. cpu, memory, etc.) can be
essential. Examples of novice users allocating one or several multi-core compute
nodes for a compute job, but only using one core are not uncommon and unless
there is monitoring of the cpu utilisation on the system, then such jobs will
not be easy to discover and follow up on. However, monitoring the degree of cpu
utilisation for a given job allocation is only one example of why monitoring the
utilisation of various types of resources can be useful. Other examples include
finding challenging or poorly behaved jobs as well as learning what software
applications that are running on the system and how much this software is used
with respect to core-hours, number of users, cores per job, etc.

Knowledge mined from the collected data can clearly help guide support efforts
and maybe even the design or procurement of new systems.

In this workshop, we will discuss what resources to monitor and what metrics to
collect, how to collect the metrics, how to gather metrics in a cluster, how to
store the data, and how to interface to the collected data. We will also discuss
how to use the collected data to improve the utilisation of the system resources
and identify problematic workloads, as well as what proactive support efforts
this can lead to.

If you work with system operations and/or various types of user-oriented
operational services aimed at helping users to utilise e-Science and HPC systems
and services, then this workshop is for you.

Workshop format: Presentations followed by discussions

Workshop organizers:

* Torben Rasmussen, NSC, SE
* Bjørn-Helge Mevik, USIT, NO
* Martin Dahlö, UPPMAX, SE

## Agenda

##### 9:00 - 9:30 Presentation of our ideas with the workshop and potential items for the discussions
Torben/Martin/Bjørn-Helge

##### 9:30 - 10:15 Thoughts and overview of various types of inefficiency in an academic HPC system
Peter Kjellström, NSC, SE

##### 10:15 - 10:45 Coffee

##### 10:45 - 11:15 Implementation and experiences from UPPMAX
Martin Dahlö, UPPMAX, SE

##### 11:15 - 11:45 Proposal for software utilisation monitoring in SNIC
TBD

##### 11:45 - 12:15 Software utilisation monitoring from NO
Henrik R. Nagel, NTNU, NO

##### 12:30 - 13:30 Lunch

##### 13:30 - 14:00 Experiences from NSC
Peter Bortas, NSC, SE

##### 14:00 - 14:30 Presentation of Computerome dashboard
Erland Hochheim, DTU, DK

##### 14:30 - 15:15 Monitoring of MPI lib usage at NSC
Peter Kjellström, NSC, SE

##### 15:15 - 15:45 Coffee

##### 15:45 - 16:15 Slurm-ganglia integration (Tromsø)
Roy Dragseth, UiT, NO

##### 16:15 - 17:00 Discussions and closing conclusions
All
