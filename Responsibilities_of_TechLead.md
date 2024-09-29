# Reponsibilities of a Tech Lead / Software Architect

## Zoom in, Zoom out
- don't get lost in details (in code)
- Big Picture view
- but when necessary, go into details

## Domain Expertise
- understand the domain (use DDD) you're working in

## Understand tradeoffs
- balancing pro & cons for a decision / technology

## Care about infrastructure
- all topics around DevOps
- virtualizing / container technologies

## Strategic Coder
- ready to use blueprints
- reusable components / code
- ready to use local development environment (i.e. IDE configuration)
- avoiding boilerplate coding
- providing skeletons for i.e. REST-APIs, Dockefiles

## Caring about non-functional requirements
- scalability
- maintainability (modular, clean & reusable code)
- security

## Cost sensitivity
- taking care of costs

## "Kümmerer" Mentality

- Sorry, but the german word explains it best (sich kümmern = take care about sth.)
- It's someone who takes care about evertyhing, not only Software Development.
- Tech Lead takes care about overall-architecture, frontend-design, backends, UX, Client needs, Mood etc.

## Knowing when Not to code

- Recall YAGNI
- Less code is better
- Does the code bring really value to the customer?
  (In case Not, drop it)
- "Stand on the shoulders of giants" / "Don't reinvent the wheel"
  - Meaning, use libraries, code or techniques from big companies such as Google, Facebook etc. instead of implementing all on your own.

## How to build a feature?

- Focusing on outcomes for real people, not on problems
- Don't Gather Requirements — Dig for Them !
- ask the 5 Whys to really understand the customers need - see https://en.wikipedia.org/wiki/Five_whys
- Very often the customer requests a specific feature instead of describing a problem. Dig for the root cause of the feature!
- Using the 5-Whys could reveal the root cause! In my personal experience, 3-Whys are often enough.

## How to architect a system ?

- https://www.educative.io/path/scalability-system-design

## How to implement patterns & paradigmes ?

- Design Patterns - https://www.tutorialspoint.com/design_pattern/index.htm

## How to adopt new technologies ?

- "Hybrid-Implementation" when introducing/implementing new technologies
  - i.e. introducing a new DB when still using the old DB for a certain amount if time

## How to tackle technical debt?

- Refactoring is part of your daily life -> Test-Driven-Development (TDD) helps a lot !!!
- "Hybrid-Implementation" when introducing/implementing archirectual/design changes

## How to Clean Code ?

- learning Clean Code Development -> https://clean-code-developer.com/

## How to program ?

- Complexity knowledge - O(n)
- Coding Techniques - https://www.educative.io/courses/grokking-the-coding-interview
  - Sliding window
  - fast & slow pointers
  - Data Structures (Trees, Graph, Linked Lists etc.)
- Sort & Search algorithms
  - you don't need to know by heart, know the complexity level and pros/cons
  - try to go for O(1) if possible i.e. HashMap
- Recursion
  - Stack-Frame-Copy (https://dev.to/muirujackson/call-stack-recursion-40eh)
  - Use "Tail Call Optimaization (TCO)" when possible

# Links

- "Lessons Learned From My Software Engineering Mentor" - https://medium.com/gitconnected/lessons-learned-from-my-mentor-d10058a462a2
