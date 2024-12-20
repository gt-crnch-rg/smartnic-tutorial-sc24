# Leveraging SmartNICs for HPC and Data Center Applications

Tutorial on SmartNICs for Supercomputing 2024

**Held on**: November 17th, 8:30 AM - 12:00 PM Eastern Standard Time; [Room B207](https://sc24.conference-program.com/map/?location=rB207)

[Event website and Program](https://sc24.conference-program.com/presentation/?id=tut133&sess=sess409)

![BlueField 3 SmartNIC](https://github.com/gt-crnch-rg/smartnic-tutorial-sc24/blob/2b33a3f47e94bf85083d54571c9a110bd97f93bc/fig/smartnic_bf3.jpg)

## Mentimeter Audience Survey

Please take our survey using [this Mentimeter link](https://www.menti.com/alxmwy7njwi5).

## Presenters

* Richard Graham [(NVIDIA)](https://www.nvidia.com/)
* Oscar Hernandez [(Oak Ridge National Laboratory)](https://www.ornl.gov/)
* Antonio Peña [(Barcelona Supercomputing Center)](https://www.bsc.es/pena-antonio)
* Yong Qin [(NVIDIA)](https://www.nvidia.com/)
* Jeffrey Young [(Georgia Institute of Technology)](https://crnch-rg.cc.gatech.edu/)
* Richard Vuduc [(Georgia Institute of Technology)](https://crnch-rg.cc.gatech.edu/)

Supporting Contributors:

* Aaron Jezghani [(Georgia Institute of Technology)](https://research.gatech.edu/people/aaron-jezghani)
* Clay Hughes [(Sandia National Laboratories)](https://sc24.conference-program.com/presenter/?uid=142083)
* Muhammad Usman [(Barcelona Supercomputing Center)](https://www.bsc.es/usman-muhammad)
* Mariano Benito [(Barcelona Supercomputing Center)](https://www.bsc.es)
* Sergio Iserte [(Barcelona Supercomputing Center)](https://www.bsc.es/iserte-agut-sergio)) 
* Sara Karamati [(Georgia Institute of Technology)](https://hpcgarage.org/wp/)
* Will Powell [(Georgia Institute of Technology)](https://www.cc.gatech.edu/people/william-powell)

**Abstract:** The past few years have witnessed an increased support for programmable network adapters, known as “Smart-NICs", that offer additional functionalities beyond standard packet processing capabilities. These devices often feature programmable lightweight processing cores, FPGAs, and even CPU- and GPU-based platforms capable of running separate operating systems. Their primary target has been data center operations, such as infrastructure management, packet filtering, and I/O acceleration, but are increasingly being explored for high-performance computing (HPC) application acceleration.

This tutorial offers an in-depth exploration of the state-of-the-art for SmartNICs and the emerging software ecosystems supporting them. Attendees will engage in hands-on exercises to better understand how to take advantage of SmartNICs for application acceleration, including MPI collective operation offloading, OpenMP offload, system security, file I/O, and algorithmic modifications to maximize on-board processing power. Participants will have the opportunity to execute these exercises using cutting-edge SmartNICs like NVIDIA’s BlueField-3 Data Processing Unit (DPU). The tutorial presenters will discuss additional techniques for optimizing applications to harness SmartNICs as communication accelerators in HPC systems.

Please note that you must register for the SC24 tutorial track and attend this tutorial in person.

[Register here](https://sc24.supercomputing.org/attend/registration)

## Agenda

| Time          | Topic                                   | Presenters |
| :-----------: | :-------------------------------------- | :--------: |
| 8:30 - 8:40   | Introduction and Attendee Survey | Jeff |
| 8:40 - 9:10   | SmartNIC Introduction and Overview | Rich G / Jeff |
| 9:10 - 9:20   | Programming approaches for HPC with SmartNICs | Jeff |
| 9:20- 9:35    | SmartNIC Research – State of the Art | Oscar |
| 9:35 - 10:00  | DOCA MPI Implementations; Security Topics | Rich G / Yong |
| 10:00 - 10:30 | **BREAK** | |
| 10:30 - 11:10 | OpenMP offload to the SmartNIC; ODOS Demos | Antonio |
| 11:10 - 11:55 | Hands-on - Application Experiences | |
| 11:55 - 12:00 | Wrap-up | |

## Hands-on Examples

Please see the examples under the `/code` folder. The tutorial slides will have additional details on running and interacting with each example.

See [this Google Doc](https://docs.google.com/document/d/1SHleSgEKzycFDrLUNEYAbvQJKfNafu85n4f1gSbAgII/edit?usp=sharing) for instructions on using GitHub authentication to access the testbed and start working with the examples!

## Slides

Please see the tutorial slides under the [slides folder](https://github.com/gt-crnch-rg/smartnic-tutorial-sc24/blob/b0ca6986e62e50f458a15ba1bfa1fe3be914f313/slides/smartnic-tutorial-supercomputing-2024-slides.pdf).
