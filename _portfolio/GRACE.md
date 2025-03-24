---
title: "GRACE"
excerpt: "GRACE is a GPU-accelerated solver for the general-relativistic hydrodynamics equations<br/><img src='/images/grace_logo.png'>"
collection: portfolio
---

GRACE, a GPU-accelerated framework for numerical relativistic simulations
=======

**GRACE** (GPU-accelerated Relativistic Astrophysics Code Engine) is a next-generation simulation framework for solving the equations of general-relativistic hydrodynamics (GRHD) on modern massively parallel architectures. It is designed from the ground up to leverage GPU acceleration, enabling high-resolution, long-timescale simulations critical for modeling binary neutron star mergers, relativistic outflows, and other multi-messenger astrophysics scenarios.

The code is based on a custom-built GPU-accelerated adaptive mesh refinement (AMR) infrastructure based on the [p4est](https://www.p4est.org/) library and uses high-resolution shock-capturing (HRSC) schemes with support for advanced approximate Riemann solvers such as HLLC and HLLE. GRACE is written in modern C++ and relies on [Kokkos](https://kokkos.org) for performance portability across heterogeneous platforms, including NVIDIA and AMD GPUs.

---

<div style="text-align: center;">
  <video style="max-width: 100%; height: auto;" controls>
    <source src="/files/hllc_bw.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>

---

This video shows the evolution of the Kelvin-Helmholtz instability in a special-relativistic hydrodynamics test case using the HLLC and HLLE solvers implemented in GRACE. The GPU-accelerated infrastructure enables high spatial resolution and rapid time evolution on modern supercomputing systems.

![GRACE Performance on AMD Mi50 card](/images/GRACE_evol_roofline_Mi50.png)
*Figure: Performance of GRACE's evolution loop in simulation of inviscid Burgers equation on an AMD Mi50 card.*

More details and documentation will be made available soon.


