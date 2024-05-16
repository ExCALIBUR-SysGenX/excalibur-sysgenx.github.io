---
layout: page
title: Accelerated Python with Numba
---

## Special Guest Seminar - Graham Markall (NVIDIA)

**8th May 2024 14:00 BST**

[Recording](https://www.youtube.com/watch?v=eTcDSUKxMKw)
[Slides](https://github.com/gmarkall/excalibur-sysgenx-numba-talk/raw/main/accelerated-python-with-numba.pdf)
[Github Repository](https://github.com/gmarkall/excalibur-sysgenx-numba-talk)

[Numba](https://numba.pydata.org, https://numba.readthedocs.io) is a
Python compiler focused on accelerating workloads common in the Data
Science, AI, and HPC ecosystems. It supports compiling many numerical
functions as part of its basic functionality, but is also highly
extensible and embeddable. It sits within an ecosystem of related
tools and libraries; composability of Numba with these other
frameworks is a key feature.

Many users use it directly in their Python code to improve performance
whilst maintaining a single source language for an entire codebase. In
other use cases, library and application developers enable their users
to customise applications by writing User-Defined Functions (UDFs) in
Python that are compiled by Numba and executed as part of an
application workflow.

Numba also enables Python functions to run on NVIDIA GPUs, both
standalone and in conjunction with accelerated CUDA C/C++
libraries. It is used for custom workflows in RAPIDS, NVIDIA, and
third-party libraries including
[cuDF](https://docs.rapids.ai/api/cudf/stable/),
[DALI](https://developer.nvidia.com/dali), and
[NeMo](https://www.nvidia.com/en-gb/ai-data-science/products/nemo/).

This talk will give an overview of the use of Numba and how it works,
summarising the pipeline from an interpreted, duck-typed language to
compiled, statically-typed implementations. Some tips on using Numba
both as a straightforward Python compiler and as an embedded UDF
compiler will be given, with the aim that attendees will feel
well-placed to start using Numba to accelerate their applications.


### Speaker Bio

Graham Markall is a Principal Software Engineer in the RAPIDS team at
NVIDIA, where he maintains Numba's CUDA target and supports its use in
RAPIDS libraries such as cuDF, and works more broadly on supporting
the CUDA and Python ecosystem.

He has a background in compilers and numerical methods, having
completed a PhD in Computing at Imperial College, where he worked on
code generation for Finite Element solvers with PyOP2 and
Firedrake. Following his study, he worked on compiler technology for
Java, Python, C, C++, and Fortran in various organisations before
joining NVIDIA in 2019.
