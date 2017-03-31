---
layout: schedule
include: workshop
title: Containers
chair: abdulrahman-azab
color: "#c6c6ec"
sessions:
    - ws-1-4-morning
    - ws-1-4-afternoon
---

## Building and Managing Linux Containers for Local Deployment and HPC

**Format**: Hands-on Tutorial

**Prerequisites**: Basic knowledge of Linux (basic knowledge of Slurm and HTCondor
is a plus for the HPC part), own laptop with ssh access (Install Putty for
windows)

Linux containers, with the build-once-run-anywhere approach, are becoming
popular among scientific communities for software packaging and sharing.
[Docker](https://www.docker.com/) is the most popular and user friendly platform
for running and managing Linux containers.
[Singularity](http://singularity.lbl.gov/) is a platform for deploying
light-weight containers for HPC systems.

This workshop is mainly a hands-on tutorial that is organized as follows:

- Overview of the Linux containers technology
- Docker: Installation, building and managing Docker containers
- Singularity: Installation, building and running Singularity containers, and creating Singularity containers from Docker containers
- Containers for HPC: using Docker and Singularity containers in HPC job scripts
