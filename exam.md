# Notes for the exam

# Development methods

## Waterfall model

Not very flexible. It flows in one direction, downwards like a waterfall. 
The main concept here is that you split development into phases, and once a phase is done, you move on to the next phase.

In Royce's original waterfall model, the following phases are followed in order:
1. System and software requrements: captured in a product requirements document.
2. Analysis: resulting in models, schema and business rules.
3. Design: resulting in the software architecture.
4. Coding: the development, proving and integration of software.
5. Testing: the systematic discovery and debugging of defects.
6. Operations: the installation, migration, support and maintenance of complete systems.

### Supporting arguments

Time spent early in the software production cycle can reduce costs at later stages. For example, a problem found in the early stages (such as requirements specification) is cheaper to fix than the same bug found later on in the process (by a factor of 50 to 200).

It puts emphasis on documentation and models, as these to a large degree need to be present before coding starts.

The approach is also very structured and easy to wrap your head around. The teams focus is very clear as each phase has a distinct focus. 

It might also the more clear to the customer how far the product has come in to production by looking at which phase the development team is currently working in.

It is argued that the waterfall model can be suited to projects where requirements and scope are fixed, the product itself is firm and stable, and the technology is clearly understood.

### Criticism

The biggest flaw of the waterfall method is the fact that most customers usually don't really know what they want. The have a general idea, but that might quickly change as development moves forward. The waterfall method is very poor at adapting to such changing requirements.

## Fusion


## Rational Unified Process (RUP)

RUP is an iterative software development process framework.  It divides the development process into four distinct phases that each involve business modeling, analysis and design, implementation, testing, and deployment. The four phases are:
1. **inception** - The idea for the project is stated. The development team determines if the project is worth pursuing and what resources will be needed.
2. **Elaboration** - The project's architecture and required resources are further evaluated. Developers consider possible applications of the software and costs associated with the development.
3. **Construction** - The project is developed and completed. The software is designed, written, and tested.
4. **Transition** - The software is released to the public. Final adjustments or updates are made based on feedback from end users. 

The RUP development methodology provides a structured way for companies to envision create software programs. Since it provides a specific plan for each step of the development process, it helps prevent resources from being wasted and reduces unexpected development costs.

The Rational Unified Process is structured around six fundamental best-practices, which are so-named due to their common use throughout the inustry:


- **Develop Software Iteratively**: Encourages iterative development by locating and working on the high-risk elements within every phase of the software development life cycle.
- **Manage Requirements**: Describes how to organize and keep track of functionality requirements, documentation, tradeoffs and decisions, and business requirements.
- **Use Component-Based Architectures**: Emphasizes development that focuses on software components which are reusable through this project and, most importantly, within future projects.
- **Visually Model Software**: Based on the Unified Modeling Language (UML), the Rational Unified Processprovides the means to visually model software, including the components and their relationships with one another.
- **Verify Software Quality**: Assists with design, implementation, and evaluation of all manner of tests throughout the software development life cycle.
- **Control Changes to Software**: Describes how to track and manage all forms of change that will inevitably occur throughout development, in order to produce successful iterations from one build to the next.

## Agile Modeling

Agile Modeling (AM) is a practices-based software process whose scope is to describe how to model and document in an effective and agile manner. The practices of AM should be used, ideally in whole, to enhance other, more complete software process such as eXtreme Programming (XP), the Rational Unified Process (RUP), Disciplined Agile Delivery (DAD), and the Enterprise Unified Process (EUP) to name a few.

### Core practices

**Documentation**
- Document continuously. Documentation is made throughout the life-cycle, in parallel to the creation of the rest of the solution.
- Document late. Documentation is made as late as possible, avoiding speculative ideas that are likely to change in favor of stable information.
- Executable specifications. Requirements are specified in the form of executable "customer tests", instead of non-executable "static" documentation.
- Single-source information. Information (models, documentation, software), is stored in one place and one place only, to prevent questions about what the "correct" version / information is.

**Modeling**
- Active stakeholder participation. Stakeholders of the solution/software being modelled should be actively involved with doing so. This is an extension of the on-site customer practice from Extreme Programming.
- Architecture envisioning. The team performs light-weight, high-level modeling that is JBGE at the beginning of a software project so as to explore the architecture strategy that the team believes will work.
- Inclusive tools. Prefer modelling tools, such as whiteboards and paper, that are easy to work with (they're inclusive).
- Iteration modeling. When a requirement/work item has not been sufficiently explored in detail via look-ahead modeling they team may choose to do that exploration during their iteration/sprint planning session. The need to do this is generally seen as a symptom that the team is not doing sufficient look-ahead modeling.
    Just barely good enough (JBGE). All artifact, including models and documents, should be just sufficient for the task at hand. JBGE is contextual in nature, in the case of the model it is determined by a combination of the complexity of whatever the model describes and the skills of the audience for that model.
- Look-ahead modeling. An agile team will look down their backlog one or more iterations/sprints ahead to ensure that a requirement/work item is ready to be worked on. Also called "backlog grooming" or "backlog refinement" in Scrum.
- Model storming. A short, often impromptu, agile modeling session. Model storming sessions are held to explore the details of a requirement or aspect of your design.
- Multiple models. Agile modelers should know how to create a range of model types (such as user stories, story maps, data models, Unified Modeling Language (UML) diagrams, and more) so as to apply the best model for the situation at hand.
- Prioritized requirements. Requirements should be worked on in priority order.
- Requirements envisioning. The team performs light-weight, high-level modeling that is JBGE at the beginning of a software project to explore the stakeholder requirements.

### Limitations

There is a significant dependence on personal communication and customer collaboration. Agile modeling can be dificult to apply
- On large teams without adequate tooling support
- Where team members are unable to share and collaborate on models
- When modeling skills are weak or lacking

## Agile

Agile is the ability to create and respond to change. It is a way of dealing with, and ultimately succeding in, an uncertain and turbulent environment.

Agile software development is an umbrella term for a set of frameworks and practices based on the values and principles expressed in the Manifesto for AGile Software Development and the 12 Priciples behind it.

Agile development breaks down some classical principles in workflow. The managers are much less hands-on than in traditional workflows. The managements role in agile development is to create a good environment where the team will thrive and come up with good solutions.

The teams are not labeled and seperated into different tasks as much a normal. The teams are much more diverse and able to handle all manor of tasks, not just one specific field.

This lack of strict roles in a team allows anyone to work any task. So if the frontend needs a bug sorted out, the development does not need to wait for the frontend team/person to finish their current task, anyone can go in and fix the bug. This allows the team to adapt more quickly than team using a more traditional and role-based system.

In an agile environment the developers will have a pretty close relationship with the customer. This is so that the customer can provide feedback during development and the team can implement new features or changes that the customer might want after development has started.

### Agile manifesto

We are uncovering better ways of developing
software by doing it and helping others do it.
Through this work we have come to value:

Individuals and interactions over processes and tools
Working software over comprehensive documentation
Customer collaboration over contract negotiation
Responding to change over following a plan

That is, while there is value in the items on
the right, we value the items on the left more.

### Principles behind the Agile Manifesto

- Our highest priority is to satisfy the customer
through early and continuous delivery
of valuable software.

- Welcome changing requirements, even late in
development. Agile processes harness change for
the customer's competitive advantage.

- Deliver working software frequently, from a
couple of weeks to a couple of months, with a
preference to the shorter timescale.

- Business people and developers must work
together daily throughout the project.

- Build projects around motivated individuals.
Give them the environment and support they need,
and trust them to get the job done.

- The most efficient and effective method of
conveying information to and within a development
team is face-to-face conversation.

- Working software is the primary measure of progress.

- Agile processes promote sustainable development.
The sponsors, developers, and users should be able
to maintain a constant pace indefinitely.

- Continuous attention to technical excellence
and good design enhances agility.

- Simplicity--the art of maximizing the amount
of work not done--is essential.

- The best architectures, requirements, and designs
emerge from self-organizing teams.

- At regular intervals, the team reflects on how
to become more effective, then tunes and adjusts
its behavior accordingly.

## eXtreme Programming

Extreme programming is all about customer satisfaction, and achieves this by providing the software you need, as you need it. Extreme programming empowers developers to confidently respond to changing customer requirements, even late in the life cycle.

Extreme Programming emphasizes teamwork. Managers, customers, and developers are all equal partners in a collaborative team. Extreme Programming implements a simple, yet effective environment enabling teams to become highly productive. The team self-organizes around the problem to solve it as efficiently as possible. 

Extreme Programming improves a software project in five essential ways; communication, simplicity, feedback, respect, and courage. Extreme Programmers constantly communicate with their customers and fellow programmers. They keep their design simple and clean. They get feedback by testing their software starting on day one. They deliver the system to the customers as early as possible and implement changes as suggested. Every small success deepens their respect for the unique contributions of each and every team member. With this foundation Extreme Programmers are able to courageously respond to changing requirements and technology.

### Rules of eXtreme Programming

**Planning**

- User Stories User stories are written.
- Release planning creates the release schedule.
- Make frequent small releases.
- The project is divided into iterations.
- Iteration planning starts each iteration.

**Managing**

- Give the team a dedicated open work space.
- Set a sustainable pace.
- A stand up meeting starts each day.
- The Project Velocity is measured.
- Move people around.
- Fix XP when it breaks.

**Designing**

- Simplicity
- Choose a system metaphor.
- User CRC cards for design sessions.
- Create spike solutions to reduce risk.
- No functionality is added early.
- Refactor whenever and wherever possible.

**Coding**

- The customer is always availible.
- Code must be written to agreed standards.
- Code the unit test first.
- All production code is pair programmed.
- Only one pair integrates code at the time.
- Integrate often.
- Set up a dedicated integration computer.
- Use collective ownsership.

**Testing**

- All code must have unit tests.
- All code must pass all tests before it can be released.
- When a bug is found tests are created.
- Acceptance tests are run often and the score is published.

### XP Flow
![xp-flow](/res/xp-flow.png)
