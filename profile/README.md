<p align="center">
  <a href="https://wrench-project.org" target="_blank"><img src="https://wrench-project.org/images/logo-horizontal.png" width="350" alt="WRENCH Project" /></a>
  <br /><i>Cyberinfrastructure Simulation Workbench</i>
  <br /><br />
  <a href="https://github.com/wrench-project/wrench/releases" target="_blank"><img src="https://img.shields.io/github/release/wrench-project/wrench/all.svg" /></a>
  <img src="https://img.shields.io/badge/License-LGPL%20v3-blue.svg" />
  <img src="https://img.shields.io/github/contributors/wrench-project/wrench?style=flat" />
  <a href="https://join.slack.com/t/wrench-project/shared_invite/zt-g88hfxj7-pcuxOBMS7jSBkq1EhAn2~Q" target="_blank"><img src="https://img.shields.io/badge/slack-%40wrench--project-yellow?logo=slack" /></a>
</p>

[WRENCH](https://wrench-project.org/) is an open-source framework that 
provides high-level simulation abstractions to ease the development of 
accurate and scalable simulators of distributed computing applications, 
systems, and platforms. It has been used successfully for research, 
development, and education.

WRENCH builds on the open-source [SimGrid](https://simgrid.org/) simulation 
framework for simulation accuracy (via its validated simulation models), 
scalability (low ratio of simulation time to simulated time, ability to run 
large simulations on a single computer with low compute, memory, and energy 
footprints), and expressivity (ability to simulate arbitrary platform, 
application, and execution scenarios). WRENCH provides high-level simulation 
abstractions on top of SimGrid to make it possible to implement simulators 
of complex scenarios with minimal development effort.

<p align="center">
  <img src="https://wrench-project.org/images/wrench-architecture.png" width="450" />
</p>

In a nutshell, WRENCH makes it possible to:

- Develop in-simulation implementations of runtime systems that execute 
  application workloads on distributed hardware platforms managed by various 
  software services commonly known as Cyberinfrastructure (CI) services; and
- Quickly, scalably, and accurately simulate, on a single computer, arbitrary 
  application and platform scenarios for these runtime system implementation.
