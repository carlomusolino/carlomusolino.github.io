---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Relativistic Astrophysics, Goethe University Frankfurt, October 2021 - August 2025 (expected)
- Thesis (working title): _Effects of neutrinos on multi-messenger signatures of BNS mergers_
- Supervisor: Prof. Dr. Luciano Rezzolla
- Mark: N/A 

* M.Sc. in Theoretical Physics, University of Parma, October 2019 - July 2021
- Thesis: _Gravitational Waves from Relativistic Stars as probes of their interior composition_
- Supervisor: Prof. Dr. Roberto De Pietri 
- Mark: 110/110 cum laude

* B.Sc. in Physics, University of Parma, October 2019 - July 2021
- Thesis: _Neutron Stars dynamics and instabilities in full General Relativity_
- Supervisor: Prof. Dr. Roberto De Pietri 
- Mark: 110/110 cum laude

Research Experience
====================
**PhD Researcher** Goethe University Frankfurt (2021-Present)
* Developed `FIL-M1`, a neutrino transport module based on the truncated moment formalism
* Applied the code to GRMHD simulations of binary neutron star mergers.
* Proposed a model for extended emission from fallback accretion in GRBs.
* Led development of `GRACE`, a GPU-accelerated AMR framework for relativistic simulations.
* Contributed to the maintenance of a local HPC cluster (30+ nodes, 2000+ cores).
  
Computational Grants
======
* GRACE Preparatory Access Project, HLRS Stuttgart (2024)
- Role: **Principal Investigator**
- Machine:  GPU partition of HAWK
- Granted resources: 2500 node hours
* Extension of BNSMIC Project, HLRS Stuttgart (2023)
- Role: **Project Manager**
- Machine:  HPE-HAWK
- Granted resources: 100M CPUh
* Extension of BNSMIC Project, HLRS Stuttgart (2022)
- Role: **Project Manager**
- Machine:  HPE-HAWK
- Granted resources: 100M CPUh

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

Technical Skills 
=====
* **Programming**: 
- _Proficient_: C, C++, FORTRAN, Mathematica, Python, Bash
- _Experienced_: Rust, MATLAB, R

* **Parallel computing** 
- _Proficient_: MPI, OpenMP, HIP, CUDA, Kokkos, PyTorch
- _Experienced_: OpenACC, Sycle, taskflow, VirtualTransport, TensorFlow

* **Tools**
- _Proficient_: SLURM, PBSPro, ValGrind, Nvidia-Nsights, Perfetto
- _Experienced_: GDB, rocmprof

Languages
=========
* Italian (native)
* English (fluent)
* German (intermediate)

References 
==========
References are available upon request.
