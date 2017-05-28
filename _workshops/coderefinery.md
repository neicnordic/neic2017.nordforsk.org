---
layout: schedule
include: workshop
title: Mixed Martial Arts with CodeRefinery
chair: radovan-bast
color: "#ccffcc"
sessions:
    - ws-1-6-afternoon
---

## Interfacing Fortran, C, C++, and Python for Great Good!

### Instructors

- Bjørn Lindi
- Radovan Bast


### Workshop material

- [https://coderefinery.github.io/mma/](https://coderefinery.github.io/mma/)
- [https://github.com/bast/python-cffi-demo](https://github.com/bast/python-cffi-demo)
- [https://github.com/bast/cffi-mem-alloc-example](https://github.com/bast/cffi-mem-alloc-example)
- [https://github.com/bast/context-api-example](https://github.com/bast/context-api-example)


### Target audience

The programming languages Fortran, C, C++, and Python each have their strengths
and weaknesses and their own fan base. This workshop is for people who would
like to be able to combine these languages within one code project:

- When writing a high-level abstraction layer or interface to a “bare metal” legacy software written for instance in Fortran or C.
- When writing an efficient back-end to a code mainly written in a high-level language such as Python.
- When combining modules written in different programming languages.
- When writing a Python interface to a software in C or C++ or Fortran to leverage the wealth of libraries available in Python.


### Topics

- Exercise interfacing Fortran, C, C++, and Python with iso_c_binding, Python CFFI, and PyBind11
- Comparing the above with Boost Numpy bindings, SWIG, F2PY, and Cython
- Building mixed-language projects with CMake
- Automated testing of a dynamically linked Fortran library with Python
- Modular API design


### Format

Hands-on interactive workshops with type-along type of presentations, live coding and demos.


### Prerequisites

- Own laptop
- Basic Git knowledge and GitHub account
- Fortran, C, and C++ compilers installed on the laptop (e.g. the GNU compilers)
- CMake installed on the laptop
- A couple of Python packages installed through Anaconda or VirtualEnv (installation instructions will be communicated to the workshop participants before the workshop)


### Agenda

#### First session (13:30 - 15:00)

- Motivation (legacy code, higher level tooling, parallelization)
- Overview over different approaches (SWIG, F2PY, Cython, CFFI, Boost, PyBind11)
- Building mixed-language projects with CMake
- Hands-on example using PyBind11 for unit testing and prototyping of C++ code

#### Second session (15:30 - 17:00)

- API design
- How to write a C interface
- iso_c_binding to bind C and Fortran
- Python interfaces via CFFI
- Hands-on example for testing a Fortran code with Pytest and deploying the test to Travis CI
- Roadmap for migrating and modularizing legacy code
