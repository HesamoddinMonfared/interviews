- `# R1. sdadad`  
# Table of Contents

- [Table of Contents](#table-of-contents)
  - [Interviews](#interviews)
  - [History behind](#history-behind)
  - [My vision](#my-vision)
  - [What interviewer might ask you](#what-interviewer-might-ask-you)
    - [Data Structures](#data-structures)
    - [Algorithms](#algorithms)
    - [Coding Skills](#coding-skills)
    - [Low-Level Programming](#low-level-programming)
    - [Architecture/OOD](#architectureood)
    - [Database](#database)
    - [Testing](#testing)
    - [General](#general)
    - [Non-technical](#non-technical)
  - [What you can ask the interviewer](#what-you-can-ask-the-interviewer)
    - [Company](#company)
    - [Project](#project)
  - [Spring Boot](#spring-boot)
  - [References](#references)
    
## Interviews

I decided to arrange a list of ....

## History behind

At some point in my professional career, ....
## My vision

I want to ....

## What interviewer might ask you

### Data Structures

- What is a priority queue?
- What is a heap?
- What is B-tree?
- What is 2-3-tree?
- What is RB-tree? What is AVL-tree?
- What is Set?
- What are HashMap and HashSet? Difference between them
- Implement a linked list during an interview
- Implement a graph during an interview

### Algorithms

- Given a stream of Arabic numerals. Find the one that occurs maximum times.
- Reverse a linked list during an interview
- Convert a binary tree into a doubly linked list during an interview
- Find a loop in a linked list during an interview
- Sort an array of integers during an interview
- Search an element in a sorted and shifted array during the interview (5, 6, 1, 2, 3)
- What is an in-place sorting algorithm?
- Write an algorithm to rotate an image 90 degrees clockwise
- What is an NP problem? How to identify it?
- What is O(n) notation? Come up with some examples
- What is a hash collision? What are the ways to handle it?
- What is a good hash function?
- Describe a Travelling Salesman Problem
- What is dynamic programming?
- What is memoization?
- Find intersection between 3 sorted arrays: [2,6,7,8], [3,6,8,10], [4,5,6,8] => [6,8]
- Generate a [sequence of unique random numbers.](https://stackoverflow.com/questions/196017/unique-non-repeating-random-numbers-in-o1)

### Coding Skills

- OOP
- OOP weaknesses
- procedural / functional / OO: can you describe them?
- Why OOP was favored by the industry for so many years?
- What is the value object? Why should you use them?
- What is IoC?
- What is Dependency Inversion?
- What is Dependency Injection?
- Why are interfaces important?
- What is the difference between an exception and a validation error? When an exception should be thrown and when you should catch an exception?
- Concurrency
  - Why do we need concurrency?
  - Multithreading concepts
  - What is `Thread`? What is `Task`? What is `Process`?
  - What async/await does underneath?
  - Difference between optimistic and pessimistic concurrency models
  - Difference between being async and concurrent
  - Sync primitives - semaphore, mutex, monitor?
  - What is lock()? What is lock() underneath?
  - Describe a race condition with a real-world example
  - What are non-blocking/non-waiting algorithms?
  - Which types of threads do we have?
  - Where the threads come from?
- Explain the concepts of coupling and cohesion and how they relate to maintainability. As a follow-up, please explain afferent coupling and efferent coupling, and how those concepts fit above.
- LINQ, lazy execution, EF limitations.
- What is an ORM? Why is it useful and why not?
- What is refactoring?
- Please refactor some given piece of code and comment your actions.
- What is covariance? What is contravariance?
- Implement a singleton during the interview
- What is unsafe code? When should you use it?

### Low-Level Programming

- What is Garbage Collector? What problem does it solve?
- How does Garbage Collector work? What are the steps?
- GC Generations
- What is non-deterministic finalization?
- Explain weak references
- Describe the process of memory allocation
- IDisposable and Finalizer
- How is using() construct useful? How can it result in resource leaks?
- Stack/heap. What is a stack overflow physically?
- Large object heap
- SIMD
- What are WebSockets? Where can you use them?
- What is the difference between polling and long polling in sockets?

### Architecture/OOD

- Design an Instagram
- SOLID
- What are GoF design patterns? Why should you care?
- What's can go wrong with Active Record pattern?
- What do you think about `null`? How to avoid it?
- What is [composition over inheritance](https://stackoverflow.com/questions/49002/prefer-composition-over-inheritance)?
- What should you return concrete implementation or abstraction? E.g. `List` or `IList`? When you would pick one approach over another? Think about performance as well.
- What is the difference between IoC and service locator?
- Name a few anti-patterns
- What is MVC? Explain it using ASP.NET example. Define responsibilities.
- What is MVVM? Define responsibilities for each component.
- Layered architecture
- Explain pub/sub to me
- [What is CQRS](https://www.youtube.com/watch?v=y819dMehw6M)?
- What is CQS and how it relates to CQRS?
- What is a command in CQRS terms?
- What is the difference between command and event?
- What command handler is and what it does?
- Which type of projects is the best to introduce CQRS?
- Difference between stateful and stateless service.
- What is the blue DDD book?
- What is DDD?
- What is the domain model?
- What is the anemic domain model? Is it useful?
- What is the bounded context? How to identify a bounded context? Describe the example of two bounded contexts in terms of the same domain.
- What is the difference between a bounded context and a subdomain?
- Aggregate, AggregateRoot, Entity, ValueObject - what are those? Describe the difference between them
- What is an ubiquitous language? Why is that important?
- Immutability - what is that? Should commands or events be immutable?
- What is saga? Come up with a real-world example to explain sagas.
- What is event sourcing?
- What is snapshotting in terms of event sourcing?
- What is a projection?
- Describe the role of aggregate in CQRS/ES/DDD environment. Go deep on two-phase commit on writing an event to the event store and publishing event to a bus. Are transactions good candidates for that kind of case? If not, how to avoid transactions in that case?
- Can you send a command to another bounded context in CQRS/ES/DDD environment? Can you publish an event to another bounded context in CQRS/ES/DDD environment?
- What is AOP? Which parts of the system would you move to aspects?
- [Messaging patterns](https://www.enterpriseintegrationpatterns.com/patterns/messaging/)
  - What is [CorrelationId](https://www.enterpriseintegrationpatterns.com/patterns/messaging/CorrelationIdentifier.html)?
  - When a retry policy is suitable in general? When should you retry your command/API call?
- How to design against vendor lock-in?


### Database

- What is CAP theorem?
- Why CAP theorem is obsolete? Is it?
- What is RAFT? How does it solve the problem?
- What is ACID? Is it still a thing?
- What is eventual consistency?
- Is the use of GUID as IDs a good practice?
- What is sharding?
- What is partitioning?
- How to design a good partitioning?
- What is an index? Clustered/Non-clustered?
- How much clustered indexes might be? What is clustered index physically? What kind of data structures could be used for indexes? Why index lookups are fast? Is clustered index faster than non-clustered? Why?
- Explain the difference between index seek and index scan
- What is column-store index? When would you use it?
- How can databases be replicated?
- What is cold data and hot data?
- How would you migrate an application from one database to another, for example from MySQL to PostgreSQL? If you had to manage that project, which issues would you expect to face?
- What is lazy loading? What are the drawbacks of this approach?
- How to find the most expensive queries in an application? How to monitor your database health and load?
- What are database normalization rules? Is it acceptable to have denormalized database? If so, in which cases?
- How to do blue-green deployments including database?
- How NoSQL databases scale? How SQL databases scale?
- When to use NoSQL and when to use SQL?

### Testing

- What is a unit test? Academic definition vs real world definition
- What is the difference between unit/integration/automated test? Discuss examples
- What is TDD?
- What is BDD?
- What is performance testing?
- What is load testing?
- What is smoke testing?
- What is regression testing? Is that correct that benchmarking is a part of the regression testing process?
- What is [chaos testing](https://boyter.org/2016/07/chaos-testing-engineering/)?
- Why in TDD are tests written before code?
- How to test a distributed system? Which types of test will you write? Which instruments would you use?
- What is a [test pyramid](https://martinfowler.com/articles/practical-test-pyramid.html)?

### General

- How testing frameworks such as xUnit & NUnit know what methods to run?
- What is the most interesting thing you've made?
- What is Docker?
- How Dockerfile relates to Docker image layers?
- What is Kubernetes?
- What happens when [you run `kubectl run --image=nginx --replicas=3`](https://github.com/jamiehannaford/what-happens-when-k8s)?
- What is [blue-green deployment](https://martinfowler.com/bliki/BlueGreenDeployment.html)?
- What is [CanaryRelease](https://martinfowler.com/bliki/CanaryRelease.html)?
- What is the concept of [infrastructure as code](https://www.thoughtworks.com/de/insights/blog/infrastructure-code-reason-smile)?
- What is the difference between authorization and authentication?
- What is .NET standard?
- What is merge and rebase, the difference between them?
- [Git hooks](https://www.atlassian.com/git/tutorials/git-hooks)
- Git reset, revert, checkout
- What is the difference between Mongo and Redis?
- What is the difference between queue and topic in messaging systems?
- What is REST? RESTful?
- What is idempotency? in terms of HTTP and/or messaging
- What is RPC? What are the general pitfalls of RPC?
- What is gRPC? When it could be useful?
- What is the difference between RPC and gRPC?
- What is SOAP?
- What is HATEOAS?
- What is HAL?
- What is eventual consistency? BASE?
- What is reactive programming?
- What is tail recursion?
- What is cyclomatic complexity?
- Public API versioning, how to do that right.
- What is [feature toggling/flagging](https://martinfowler.com/articles/feature-toggles.html)? [[1]](https://www.youtube.com/watch?v=7qTOdbUAqno) [[2]](https://www.pluralsight.com/courses/dotnet-featuretoggle-implementing) [[3]](http://swreflections.blogspot.com/2014/08/feature-toggles-are-one-of-worst-kinds.html)
- [What happens when you type 'google.com' into the browser address bar and press Enter](https://dev.to/antonfrattaroli/what-happens-when-you-type-googlecom-into-a-browser-and-press-enter-39g8)?
- What is public IP, private IP? NAT? IPv4? IPv6? [[0]](https://www.digitalocean.com/community/tutorials/understanding-ip-addresses-subnets-and-cidr-notation-for-networking) [[1]](https://www.digitalocean.com/community/tutorials/an-introduction-to-networking-terminology-interfaces-and-protocols)
- Explain event hub over service bus, consumer groups and other concepts related.
- What is partitioned consumer pattern? [Competing Consumer](https://docs.microsoft.com/en-us/azure/architecture/patterns/competing-consumers)?
- What is tracing, spans, [opentracing](https://github.com/opentracing/specification/blob/master/specification.md)?
- What is [ELK stack](https://www.elastic.co/elk-stack)?
- What is [structured logging](https://nblumhardt.com/2016/06/structured-logging-concepts-in-net-series-1/)? Does it have any advantages over plaintext logging?
- [Why does array index start with '0' in most languages?](https://www.cs.utexas.edu/users/EWD/transcriptions/EWD08xx/EWD831.html)
- What are dynamic- and static-typed languages? Which one to pick for developing enterprise software? Explain your thoughts.
- What is overengineering? How can it affect enterprise software in the short run and in the long run?
- What is the difference between pattern matching and just a switch clause?
- Pretend you have a time machine and pretend that you have the opportunity to go to a particular point in time during Java's (or C#, Python, Go or whatever) history, and talk with some of the JDK architects. What would you try to convince them of? Removing checked exceptions? Adding unsigned primitives? Adding multiple-inheritance?
- How to explain legacy code to non-technical person e.g. Project Manager or Product Owner? Why it's important to care about legacy code? How would you deal with legacy code?
- When to use cache? When it can be not useful or even dangerous?
- I want to refactor a legacy system. You want to rewrite it from scratch. Argument. Then, switch our roles.
- What is GOTO statement? [What's wrong with it](https://homepages.cwi.nl/~storm/teaching/reader/Dijkstra68.pdf)? Do we still have GOTO statements or something similar to them in modern programming languages?
- What is monorepo and what is multirepo? When it's better to chose one over another? [[0]](https://medium.com/@adamhjk/monorepo-please-do-3657e08a4b70) [[1]](https://medium.com/@mattklein123/monorepos-please-dont-e9a279be011b)
- Tell me about your favorite language/framework. Is it really that good? Does it have any weaknesses?

### Non-technical

- What motivates you?
- What do you think of technical conferences/meetups? Are they important and why?
- [Why are you looking for a job?](Answers/Non-technical/Why%20are%20you%20looking%20for%20a%20job.md)
- Tell about your last project
- What are you learning right now? Teach me this.
- Last book you read
- How much time do you need to start working full time for us?
- What do you do when you get stuck on some problem for too long?
- Tell me your 3 best/last failures
- Describe what Human Resources means to you.
- What is broken around you?
- When was the last time when you did not agree with some blog post/book/video? What was that and why you did not agree?
- When was the last time when you shared the knowledge with somebody else? Did you like it? Why did you do that?
- Explain to me your learning process, validation of the information and using it in practice.

## What you can ask the interviewer

Don't ask them if you just want to make an impression because you will. And this is not going to be a very positive impression - asking by template without any enthusiasm. Instead, you should at least seem interested.
What I also really like to do is to start doing 96 so after recruiter asked you "Where do you see yourself in 5 years" it's totally reasonable to ask where the company sees itself in 5 years.

### Company

- Why have you left your last company for this?
- How do you train/ramp up engineers who are new to the team?
- Do you have your [onboarding process documented](https://twitter.com/housecor/status/1142153344179429378)?
- Who is your ideal candidate and how can I make myself more like them?
- Describe what Human Resources means to you.
- How do you find the best talents? Are you focused on acquiring the best ones?
- Do you have a shower to use at your place? Does anyone use it?
- Do you have a library at your place? Name a few books there.
- Do you have any teambuildings and what they look like?
- Do you know anything about your employees' hobbies? What they are interested in?
- How much vacation does the average employee take?
- Do you enforce a minimum number of days of taken vacation per year? (Secret: a lot of “unlimited vacation day” policies actually lead to employees taking less time off because they feel guilty.)
- Do you have any internal tech talks to improve the technical expertise of your employees? If so, who is in charge of that?
- Do you use any time logging system?
- Describe the paid vacations policy.
- Describe the process of salary review/performance review. What are the factors included in forming my salary?
- Do you have any competence matrix?
- Will I be able to work remotely? If so, then how much time/month?
- How flexible the schedule is?
- What do you think of remote-async workflow?
- How often will I have to over-time and how it's paid?
- Which devices will I be provided to work with - laptops/PCs, monitors, smartphones for testings, etc?
- Do you provide any insurance? If so, describe it briefly.
- Do you offer parking space for your employees? For car/bike.
- Do you have any probationary period for new employees?
- Do you have something like 13th salary / any other bonuses?
- What are the weaknesses of the organization?
- What do you consider as the strongest advantage of your company over others?
- What are the educational opportunities?
- How often are 1:1s conducted?
- What opportunities are available to switch roles? How does this work?
- If you could change one thing about the company, whether it's a process, technology used, or anything else, what would it be?
- What is the toughest problem company've faced so far, aside from not enough people, and how did you or plan to solve it?

### Project

- What project I will start with? Describe the problem it solves. Describe the technical stack chosen, why it is like that and which tasks I will be asked to solve there.
- Do you have any code review process?
- What is the structure of the environment I will be working in? Will I have managers attached to me and, if so, then how much? Who will provide me with the work to do?
- Will I have the ability to communicate with the client side? How much time will I communicate in English everyday?
- Which instruments does your company use for development? Are there any limitations?
- What level of responsibilities will I have?
- Does the project offer any business trips/on sites?

## Spring Boot
- `# R1. Notes about spring.jpa.hibernate.ddl-auto:`
   - `# spring.jpa.hibernate.ddl-auto is used for database initialization. We set the value to update value so that a table will be created in the database automatically corresponding to defined data model. Any change to the model will also trigger an update to the table. For production, this property should be validate.`
   
- `# R1. spring.jpa.hibernate.ddl-auto default value:`
   - `# jpa. hibernate. ddl-auto explicitly and the standard Hibernate property values are none , validate , update , create-drop . Spring Boot chooses a default value for you based on whether it thinks your database is embedded (default create-drop ) or not (default none ).`
   
- `# R1. What is difference between generation type auto and identity?:`
   - `# AUTO: Hibernate selects the generation strategy based on the used dialect, IDENTITY: Hibernate relies on an auto-incremented database column to generate the primary key, SEQUENCE: Hibernate requests the primary key value from a database sequence, TABLE: Hibernate uses a database table to simulate a sequence.`
   
### JPA
- `# R1. one-to-many example:`
   - `# https://www.bezkoder.com/jpa-one-to-many/`
   

   
## Java Core
- `# R1. Default access modifier in java:`
   - `# Any Java members such as class or methods or data members when not specified with any access modifier they are by default considered as default access modifiers. These methods or data members are only accessible within the same package and they cannot be accessed from outside the package.`
   
- `# R1. Optional orElseThrow() method in Java with examples:`
   - `# https://www.geeksforgeeks.org/optional-orelsethrow-method-in-java-with-examples/`
   
## References
-https://stackoverflow.com/
-https://www.bezkoder.com/jpa-one-to-many/
-https://thorben-janssen.com/
-https://www.geeksforgeeks.org/