# Chapter I

 ## Software architecture
Software architecture is an abstraction of a software system. among the miriads of concrete definitions :
  - ISO y IEEE "Fundamental concepts or properties of a system in its environment embodied in its elements, relationships, and in the principle of its design and evolution." the key points are:
  - Software architecture in practice "The software architecture of a program or computing system is the structure or structures of the system, which comprise software elements, the externally visible properties of those elements, and the relationships among them."
 
**SA concerns itself with defining and detailing structures and their relationships. It focus on the public aspect of the elements and how they interact with other. It does not deal with the private implementation details of those elements.**
Consists of important decisions that shape the system. It is made up of the structures and components that are significant to the quality, longevity, and usefulness of the system.

### expectations
1. Providing leadership
2. Assiting project manager, including cost and effort estimation
3. mentoring team members
4. Helping on team members recruitment
5. Understanding the business domain
6. Participating in gathering and analyzing requirements
7. Comunicating with a variety of technical and non-technical stackeholders.
8. Having a vision for future proiducts
9. Tech topics:
 1. Understanding non-functional requirements and quality attributes.
 2. Being able to effectively design software architectures.
 3. Understanding patterns and best practices software development
 4. Having a deep knowledge of software architecture patterns an their pros and cons and knowing when to choose one over another.
 5. Knowing how to handle cross-cutting concerns.
 6. Ensuring performance and security requirements are met.
 7. Being able to document and review software architectures.
 8. Having an understanding of devops and deployment process.
 9. Knowing how to integrate and work with legacy applications.
 10. Being able to design software architectures that adapt to change and evolve over time.
 
## Quality attributes
Are measurable and testable properties of a system:
1. Maintenability
2. Interoperatibility
3. Security
4. Performance

# Chapter II

## Types of software architects
1. Enterprise architect
2. Solution architect
3. Application architect
4. Data architect / Information architect
5. Security architect
6. Cloud architect
## Software development methodologies

### The waterfall model
Consist on a series of secuential steps which are accomplished one after another for example
1. Requirements
2. Design
3. Implementation
4. Verification
5. Maintenance

### Agile
There are a variety of models: Scrum, kanban, XP, Crystal. Each has it's particularity but all of them focus on being adaptable to change and the attempt to find a balance betweennot having enought processes and having too much of them.

Agile Manifesto core values states [4 core principles of agile software](https://agilemanifesto.org/)
1. individuals and interactions over processes and tools
2. Working software over documentation
3. Customer interaction and continous engagement over contract negotiation
4. Adaptation over following a plan



## Project management
### project schedule changes management
In order to get a project back on schedule there are a number of approaches:
1. working overtime
2. Reducing scope
3. Adding resources
4. Reallocatin resources

## Office politics
## Software risk management
### Categories of risk
1. Functional. Incorrect requirements, lack of participation, confliting business goals
2. Technical. Complexity, unknown technology, vendor or subcontractors dependencies.
3. Personnel. unexperienced team members, unable to staff the project, productivity issues with team members.
4. Financial. insufficient funding, difficult ROI constraint.
5. Legal.
6. Management. unexperienced, incorrect planning, lack of communication, organizational issues.

### Management
For every project make [a risk impact likelihood](https://www.researchgate.net/profile/David_Slater12/publication/305884008/figure/fig4/AS:391894946336772@1470446444374/Generic-Risk-Matrix-or-Probability-Impact-Graph-PIG.png) this will be a living picture.

Techniques:
1. Avoidance. Eliminate it  by changing the project.
2. Transfering. Hire other to manage it.
3. Mitigating. Reduce the likelihood.
4. Aceptance. Just asume any possible consequence.

## Configuration management
**Software configuration manager (SCM) team.** Its responsabilities include: identify configuration items, define/implement a change control process and tools.
**Change Control Board (CCB)**

three Approaches:
1. Every change goes through SCM Aprobal.
2. The programmer does the changes without requiring any further aprobal.
3. A balance between the above alternatives.

## Software product lines
Product lines are multiple products from a single company that address a particular need or market
**Product line engineering (PLE)**
**Core asset**

## Chapter III The Domain

### DDD
The domain is the subject and body of knowledge on which the software will applied.
**Ubiquous language**
**Entity**. Objects defined by their identity and not their attributes, they are mutable, changing its attributes do not changes its identity.
**Value Object**. Describe some characteristics or attribute but they have no concept of identity so they are not mutable.
**Aggregate** Groups of entities and value objects that area treated as a single unit.

**Subdomaining** The activity of split the domain model into multiple subdomains
**Bounded Context** Partitions in the domain model a bounded context may map to a single

### Requirements
#### Types 
**Business**
High-level business goals of the organization building the software
**Functional**
What the software must do in terms of behaviour
**Non-functional**
Conditions that must be met in order for the solutions to be effective. Quality attributes are a subset of non-functional requirements: maintenability, usability, testability, interoperatibility
**Constraints**
Some  type of restrriction on the solution that might be technical o non-technical in nature.

#### measuring and testing
Each software requirement should be unambiguous, mesurable and testable.

#### Elicit requirements
Techniques:
1. Interviews
2. Workshops
3. Brainstorming
4. Observation
5. Focus group
6. Surveys
7. Document analysis
8. Prototyping
9. Reverse engineering

### Software Quality Attributes

Quality attributes are of the utmost importance to software architects. Quality attributs are properties of a software system and a subset of its non-funtional requirements they are benchmarks that describe software systems quality and measure the fitness.
Two categories internal and external:
1. Internal. Can be measured by the system itself and visible to the development team. 
  + Qualitative: Extensibility, maintenability, Redability and code formating, clarity, well-documented, well-tested, Efficiency.
  + Quantitative: Weighted Micro Function points (WMFP), Halstead complexity measures, cyclomatic complexity
2. Externa. Externally visible: Performance, reliability, availability, usability, etc

