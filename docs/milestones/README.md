# Milestones

## MS1: Proof Of Concept (Judge-K8S)
`2020/4/1 ~ 2020/5/20`

- Achievements:
    - Successfully integrate **Kubernetes** as our resource scheduler that schedules `Judger`
    to a proper node that has sufficient CPU/GPU capacity. (See [Code Submission & Judge Flow](software-design/system-architecture/#code-submission-amp-judge-flow))
    - Successfully rewrite the system into **[Microservices Architecture](software-design/system-architecture/)** 
    so as to demonstrate the state-of-the-art distributed system design applied in the real-world.
    - Re-design the Judge Girl's website to enhance the **user experience** to motivate the Students.
    - Re-modularize and rewrite Judge Girl in Java to enhance its maintainability, extensibility, scalability and readability.
    

## MS2-1: CMS & Exam
`2020/8/30 ~ 2020/12/1`

- Objectives:   
    - Currently, Judge Girl lacks of a **Content Management System (CMS)** to allow the 
    TAs or the system admins to produce Judge Girl's content (i.e. Problems) easily.
    - Support the **[Exam](domain/exam/)** use case 
    
## MS2-2: Code Quality Inspection
`2020/8/30 ~ 2020/12/1`

- Objectives:
    - Survey and Integrate a **Code Quality Inspection mechanism** in our `Judger`
    so that each Problem can apply different **rules** to strictify the judges based on the programming styles.
