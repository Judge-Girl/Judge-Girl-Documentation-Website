# Env Spec

The spec that describes for this problem, **what kinds of environment 
should the [submitted codes](domain/submission/submitted-code/) be run in**.

For example, the problem named `Dot Product (OpenCL)` requires at least one GPU in 
order to run OpenCL codes, or a problem named `OOP practice 1` requires JRE environment
in order to run Java codes. There may be various requirement problems might specify
in order to run their codes.

- There are four attributes the Env Spec can have:
    - Language (e.g. C/C++/Java/python, ...and so on)
    - Environment (e.g. Normal, Hadoop, Windows, ...and so on)
    - CPU (number of CPU required)
    - GPU (number of GPU required) 

Example Env Spec 1
---

Attribute | Value |
------ | ------ | 
Language |  C |
Environment |  Normal |
CPU |  2 |
GPU |  2 |


Example Env Spec 2
---

Attribute | Value |
------ | ------ | 
Language |  Java |
Environment |  Hadoop |
CPU |  4 |
GPU |  0 |


