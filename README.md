Developer
    | 
Review (all the stds are met, syntax is correct, best practices are followed) 
    | 
QA agent (ensures the quality of the output, test all the edge cases)
    | - Test cases are written for all new features 
    | - Edge cases are identified and tested 
    | - Performance is tested and optimized
 Fix agent (fixes any issues found during the review and QA process) 
    | - Bugs are fixed 
    | - Code is refactored for better readability and maintainability 
    | - Performance is improved based on QA feedback
 Final report (summarizes the entire process, outcomes, and any follow-up actions)

 ##Real engineering workflow involves:

1.Developers
2.Reviewers
3.Testers
4.Fixers/Developers

##Architecture for the project:

    User requirements (what the user wants to achieve)
            |
            V
    Developer agent (translates user requirements into code)
            |
            V
    (a)Review agent (reviews the code for correctness, style, and best practices)
            |
            V
    QA agent (ensures the quality of the output, test all the edge cases)
    Decision making (LOGIC written in graph and conditional edges)
    /             \
   V               V
Fix             Final report
|                   |
V                   V
Review Agent(a)     END

##Nodes:
1.Developer Node
2.Review Node
3.QA Node
4.Fix Node
5.Final Report Node


##State:
1.User requirements: str
2.Generated code: str
3.Review feedback: str
4.QA feedback: str
5.needs_fix: routing agent/decision: Bool
6.final report: str
7.iteration_count: int
Decision making of the routing agent is based on Router function (Logic) and the condition_edge (routing mechanism).