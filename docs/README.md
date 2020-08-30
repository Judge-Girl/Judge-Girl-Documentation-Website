# Judge Girl

Judge Girl, an **Online Judge System** where [students](domain/student/)
 can upload or write codes in an online platform for [submissions](domain/submission/) 
to solve certain [problems](domain/problem/).
 
 ## Online Judge & Grading System

The submissions are judged aad labeled with a status.

> For example: All-Correct (AC), Wrong-Answer (WA) or Time Limit Exceeds (TLE). 
 
 **Judge Girl also can be used as a grading system**. 
 Every judge is based on several [test cases](domain/test-case/) specified in a problem. 
 A test case is assigned a grade point so a judge can be calculated its total grade point based on customizable policies.
 
 ## GPU related Submission Codes
 
 Judge Girl supports **GPU related Submission**, which means that the codes Judge Girl runs **can be allocated GPU devices**. 
 This is currently achieved by Kubernetes and Nvidia-Docker.  

 ## Various Test Case I/O Mechanisms
 
 * Judge Girl supports the two essential ways of providing test case's 
 inputs and outputs:
     - From Standard input / output
     - From Input Files / Output Files
 
> So it can do more complicated judges, such as asking the program to read from a file and write to another file. 
Not as simple as other Online Judge Systems do!
 
 ## Customizable Judge Policies
 
 * Judge Girl supports various judging mechanisms thanks to its well-modularization and the plugin architecture.
 You can easily specify **different judge policies** for different problems.

> Let's say, instead of judging the program's output by an exact string matching, 
you'd rather use **Regex** to judge the output, which is feasible in Judge Girl!
 
 
 ## One-Click Deployment
 
Since there is a ton of demands for such an Online Judge and Grading System from _educational institutions_.
Also, modern online judge systems tend to be distributed and hard to deploy,

Judge Girl is **well-designed into Microservices and can be deployed very easily via Kubernetes or Docker-Compose**. 
 
 
 * Judge Girl supports two cloud-native ways of deployment:
    - **Kubernetes** 
    - **Docker-Compose** (Support in the future release)
    
    
## Development Guide

For those who wants to understand how Judge Girl works or contribute to Judge Girl, 
you may want to follow the following documents.

- **[Understand Judge Girl's Domain](domain/)**
- **[Software Design](software-design/)**
- **[Project Milestones](milestones/)**


## Benchmark

To demonstrate how Judge Girl plays well in its distributed judges with resource scheduling, 
some simple benchmark can be found **[here](benchmark/)**
