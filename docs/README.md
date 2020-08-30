# Judge Girl

Judge Girl, an **Online Judge System** where [students](domain/student/)
 can upload or write codes in an online platform for [submissions](domain/submission/) 
to solve certain [problems](domain/problem/).
 
 ## Online Judge & Grading System
 

Those submissions are then judged by the system. 
 Every [judge](domain/judge/) is labeled with a status, for example: All-Correct (AC), Wrong-Answer (WA) or Time Limit Exceeds (TLE). 
 
 Judge Girl also can be used as a grading system.
 Every judge is based on several [test cases](domain/test-case/) specified in a problem. <br>
 A test case is assigned a grade point so a judge can be 
 calculated its total grade point based on customized policies. 

 ## Various Test Case I/O Mechanisms
 
 * Judge Girl supports the two essential ways of providing test case's 
 input and output:
     - From Standard input / output
     - From Input Files / Output Files
     
 
 ## Customized Judge Policies
 
 * Judge Girl supports various judging mechanisms thanks to it well-modularization with a plugin architecture.
 
 You can easily specify **different judge policies** for problems.
Let's say, instead of judging the program's output by an exact string matching, 
you'd rather use **Regex** to judge the output. 
 
 
 ## One-Click Deployment
 
Since there is a ton of demands for such an Online Judge and Grading System from educational institutions, 
as well as modern online judge systems tend to be distributed and hard to deploy,

Judge Girl is **well-designed into Microservices and can be deployed very easily via Kubernetes or Docker**. 
 
 
 * Judge Girl supports two cloud-native ways of deployment:
    - **Kubernetes** 
    - **Docker-Compose** (Support in the future release)
    
    
## Development Guide

- [Understand Judge Girl's Domain](domain/)
- [Software Design](software-design/)
- [Project Milestones](milestones/)


## Benchmark

- [Benchmark](benchmark/)
