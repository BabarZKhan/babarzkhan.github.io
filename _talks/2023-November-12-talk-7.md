---
title: "Accelerating the HPC I/O for Low Latency and High Throughput with 16-nanometer FPGA-based Hardware Accelerators"
collection: talks
type: "The International Conference for High Performance Computing, Networking, Storage, and Analysis (SC) 2023"
permalink: https://sc23.conference-program.com/presentation/?id=ws_whpc108&sess=sess442
venue: "This talk was given in-person at Super Computing (SC) 2023 conference in Denver, Colorado, USA, Nov, 2023"
date: "13-November-2023"
location: "Denver, Colorado, USA"
---

The existing HPC I/O stack struggles with the growing demands of HPC scientific workloads. 
To start with the latency bottleneck, there is a deeply layered kernel hierarchy to translate 
HPC I/O requests to the actual storage operations. This layered architecture adds a significant 
overhead along the entire I/O request path. Measurements have shown that it takes between 18,000 
and 20,000 instructions to send and receive a single fundamental 4KB I/O request. Our novel 
hardware/software framework, named DeLiBA, aims to bridge this gap by facilitating the 
evelopment of software components within the HPC I/O stack in user space, rather than the 
kernel space, and leverages a proven 16 nanometer (nm) FPGA framework to quickly deploy 
the FPGA-based HPC I/O accelerators. Our initial results achieve a 10% increase in 
throughput and demonstrates up to 2.3 times the I/O operations per second compared 
to conventional methods.


![](/images/sc2023.png)

