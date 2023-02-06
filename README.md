# Extreme Programming

- Preface

## Chapter 1 - Extreme Programming   
`XP is a discipline of software development with values of simplicity, communication, feedback and courage. We focus on the roles of customer, manages and programer and accord key rights and responsibilities to those in those roles.`
- The Customer Role
- The Programmer Role
- The Manager Role

### Rights/Responsibilities  
----
`XP is validation-centric rather than Product-centric`
- Are we developing the right software?   
`Analysis and Validation`
- Are we developing the software right?  
`Design and Construction`

## Chapter 2 - Circle of Life
`
An XP project succeeds when the customers select business value to be implmented, based on the team's seasured ability to deliver functionality over time
`

define -> estimate -> choose -> build -> repeate

## Chapter 3 - On-site Customer
`
An XP project needs a full-time ustomer to provide guidance.
`
- Requirements - User stories
- Communication is the key

- On-site customers do real work
- If the customers can't be there 
  - represent them locally
  - get them at least for the planning
  - visit the customer
  - deliver frequently to the customer 
  - expect missunderstanding and prepare for them

## Chapter 4 - User Stories
`Define requirements with stories written on cards.`

## Chapter 5 - Acceptance Tests
`Surely you aren't going to assume you're what you need. Prove that it works! Acceptance tests allow the customer to know the system works, and tell the programmer what needs to be done.`

- Automating the tests
- Timeliness

## Chapter 6 - Story Estimation
`Customers need to know how much stories will cost, in order to choose which ones to do and which to defer. Programmers evaluate stories to provide that information.`

- estimate by comparison
- early on, start with intuitive estimates
- spike solutions


### Sense of completion
`XP's nested planning and programming cycles keep the project on track and provide a healthy sense of accomplishment at frequent intevals`

- Programmers set the rhythm

### Chapter 7 - Small Releases
`The outermost XP cycle is the release. Small and frequent releases provide early benefit to the customer while providing early feedback to the prоgrammers.`

- All or nothing
- Personnel system
- Tax package
- Distributed manufacturing control system
- Air traffic control system

### Chapter 8 - Customer Defines Release
`In each release cycle, the customer controls scope, deciding what to do and what to defer, to provide the best possible release by the due date. Work fits into the calendar, based on business value, difficulty and the team's implmentation velocity`

### Chapter 9 - Iteration Planning
`Inside each release, an Extreme team plans just a few weeks at a time, with clear objectives and solid estimates`

- The planning meeting
  - Customer presents User Stories
  - Team braninstorms ENgineering Tasks
  - Programmers sign up for work and estimate

- Customer presents User Stories  
`The customer presents the user stories to ensure that the team understands what is to be done. The most effective way to understand a requirement is to discuss it`

- Team brainstorms Engineering Tasks
`The team brainstorms the engineering tasks to build a common pictue of the system design, down to the detail necessary to implment the stories. This step often allows the customer to see places where the programmers don't understand the story at all. Observing the design process builds common knowledge and confidence throughout the team.`

- Programmer signs up for work and estimates
`Programmers sign up for work to allow individuals or pairs to accept the primary responsibility for completion of specific work. The team does not force assignments to anyone, although someone signing up may ask for help from anyone, and will receive it. 
Programmers esimate their own work to provide the most accurate possible prediction of what will be accomplished. In addition, programmers feel more commitment to work which is scheduled for completion in a time they can believe in.`

- Sign up for stories
- An Iteration Planning Practice

### Chapter 10 - Quick Design Session
`Within each iteration, programmers don't stand alone.`

### Chapter 11 - Programming
`It's called XP after all.`

- Collective Code Ownership  
`I'm not afraid to change my own code. And it's all my own code.`
- Simple Design  
`SImplicity is more complicated than you think, but it's well worth it.`
- Refactoring  
`We keep the code simple at all the time. This minimizes investemnt in excess framework and support code. We retain the neccessary flexibility through refactoring.`
- Continuous Integration   
`Ìntegration is a bear, we can't put it off forever, let's do it all the time instead.`
- Coding Standard   
`I can always read my own code, but it's all my own code.`
- 40-Hour Week

### Chapter 12 - Pair Programming  
`On an XP team, two programmers sitting together at the same machine write all production code.`  

### Chapter 12 - Unit Tests
`XP test everything that could possible break, using automated tests that must run perfectly al the time.`

 - Summary of testing steps  
- Testing questions
  - How do you test when you have an attached database?
  - What if your tests run really slowly?  
  - What if you can't figure out how to test a class?  
  - Is it OK to test a class by just testing the classes that use it?  
  - How do you know you have tested everything that could possibly break?
  - What do you do if you have a body already-written code, but not many tests?
  - What about errors that only show up in collaboration between classes?
  - What about real-time and multithreading errors?
  - What about GUIs?
  - My stuff can't be tested because ...
### Chapter 14 - Test-first, by Intention
`Code what you want, not how to do it. Always to to express intention in code rather than algorithm.`
### Chapter 15 - Releasing Changes
`Using collecitve code ownership and coprehensive unit tests, an XP team releases changes rapidly and reliably` 
 - Code management tools
 - Troubleshooting
 - Lots of conflicting edits
 - Lost changes
 - Conclusion
 ### Chapter 16 - Do or Do Not
 `We've now covered most of the programming aspects of XP. Here's a summary of things we do - and things we don't.`

 ### Chapter 17 - Experience improves estimates  
 `Each iteration we gain experience. Experience with stories helps us estimate future stories more easily and more accurately.`

### Chapter 18 - Resource, Scope, Quality, Time
`Who's doing what? How much is finished? How good is it? When will we be done? What metrics should we keep?`
- Resources
- Scope
- Quality
- Time
- Tracking and Reporting Scope
- Tracking and Reporting Quality
- Other metrics?
- You can't resist, can you?

### Chapter 19 - Steering
`The estimates are wrong, priorities change, you must steer`

### Chapter 20 - Steering the Iteration
`To steer each iteration, you need to track sotries getting done, and how well the task estimates are holding up`
 - Get stories done
 - Improve estimates
 - Tracking
 - Benefits of Tracking

### Chapter 21 - Steering the Release  
`To steer the release, you need to track what's done, how fats you are going, and how well the system works.`

### Chapter 22 - Handling Defects  
`Report then, schedule them, tests and fix them, avoid them. Just don't call them bugs.`
 - Reporting Problems
 - Scheduling Corrections
 - Test and Fix the Problems  
 - Preventing Defects

 ### Chapter 23 - Conclusion
  - Key practices

### Chapter 24 - We'll try
`This can be the saddest words a programmer has ever spoken, and most of us have spoken them more than once. We've covered this material in other forms already, but it bears repeating here`

 - It couldn't be that easy!
 - What if you don't have all the stories?
 - How do you get setimates?  
 - How do you explain velocity?  
 - We can't tell management our real estimates!
 - This can't possibly work
 - Not with my management!

 ### Chapter 25 - How to estimate anything
 `Sometimes estimating stories seems scary. Keep your heads, stick together, and break the story down into samll parts. You'll be surprised what you can do.`

 ### Chapter 26 - Infrastructure
 `What about that databse you need to build first? What about that framework? What about that syntax directrd command compiler? Get over it!`

### Chapter 27 - It's Chet's Fault
`Are you looking for someone to blame? This chapter explain how to know whose fault it is.Now move on and solve your problems.`  

### Chapter 28 - Balancing Hopes and Fears

### Chapter 29 - XPer Tries Java
`After the C3 project ended most of the team was transferred to work on the HR intranet. I found how there were using the principles of XP to improve their lives on a new project heartening. What follows is a description of how ex C3er and deveted XPer is introducting testing and moder development tools into an environment where none existed.`

### Chapter 30 - A Java Perspective

### Chapter 33 - Estimates and Promises
`We estiate how long the project will take. We promise to tell the truth about how we're doing.`
 - Estimate the enitre project as accurately as possible
 - Track estimates to get project velocity
 - Refine the pictre
 - Control the outcome

### Chapter 34- Everything that could possible break
`Tests everything that could possibly break.`  
