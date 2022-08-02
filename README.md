# Effective DevOps - Building a culture of collaboration, affinity, and tooling at scale

This is my summary of the Effective DevOps, by Jennifer Davis and Ryn Daniels. Contributions: Issues, comments and pull requests are super welcome.

If you want to download the book, please use this link: https://www.oreilly.com/library/view/effective-devops/9781491926291/

<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->
# Table of Contents
- [Chapter 1. The Big Picture](#chapter-1-the-big-picture)
- [Chapter 2. What Is Devops?](#chapter-2-what-is-devops)
- [Chapter 3. A History of Devops](#chapter-3-a-history-of-devops)
- [Chapter 4. Foundational Terminology and Concepts](#chapter-4-Foundational-Terminology-and-Concepts)
- [Chapter 5. Devops Misconceptions and Anti-Patterns](#chapter-5-devops-misconceptions-and-anti-patterns)
- [Chapter 6. The Four Pillars of Effective Devops ](#chapter-6-The-Four-Pillars-of-Effective-Devops)
- [Chapter 7. Collaboration: Individuals Working Together](#chapter-7-Collaboration-Individuals-Working-Together)
- [Chapter 8. Collaboration: Misconceptions and Troubleshooting](#chapter-8-Collaboration-Misconceptions-and-Troubleshooting)
- [Chapter 9. Affinity: From Individuals to Teams](#)
- [Chapter 10. Affinity: Misconceptions and Troubleshooting](#)
- [Chapter 11. Tools: Ecosystem Overview](#)
- [Chapter 12. Tools: Accelerators of Culture](#)
- [Chapter 13. Tools: Misconceptions and Troubleshooting](#)
- [Chapter 14. Scaling: Inflection Points](#)
- [Chapter 15. Scaling: Misconceptions and Troubleshooting](#)
- [Chapter 16. Building Bridges with the Four Pillars of Effective Devops](#)
- [Chapter 17. Bridging Devops Cultures: Learning from Our Stories](#)
- [Chapter 18. Bridging Devops Cultures: Fostering Human Connections](#)
- [Chapter 19. Conclusion](#)
<!-- /TOC -->

# Chapter 1. The Big Picture
- Devops is a way of thinking and a way of working.
	- It is a framework for sharing stories and developing empathy, enabling people and teams to practice their crafts in effective and lasting ways.
## A Snapshot of Devops Culture
- Etsy's process of devops make the new engineer able to get involved quickly in the work process.
## The Evolution of Culture
- Buy-in from management, freedom to experiment and work on non-customer-facing code, and trust across various teams all allowed these tools to be deployed and along with them, a culture of tooling, sharing, and collaboration.
## The Value of the Story
- Each of us thinks our own thoughts. Our concepts we share.
- It is important to link between abstract cultural practices and real-world experiences in order to draw from them.
# Chapter 2. What Is Devops?
- Devops is a cultural movement that changes
	- how individuals think about their work
	- values the diversity of work done
	- supports intentional processes that accelerate the rate by which businesses realize value
	- measures the effect of social and technical change
## A Prescription for Culture
- Devops is about finding ways to adapt and innovate social structure, culture, and technology together in order to work more effectively.
## The Devops Equation
- A sustainable, successful business is more than the development and operations teams.
- Limiting our thinking to just those teams who write software or deploy it into production does the entire business a disservice.
### Devops as Folk Model
- DevOps has become a folk model, a term used with different intent that leads to miscommunication and misunderstanding.
### The Old View and the New View
- In an environment where humans are blamed and punished for errors, a culture of fear can build up walls that prevent clear communication and transparency.
- Contrast this with a blameless environment, where issues are addressed cooperatively and viewed as learning opportunities for individuals and the organization.
### The Devops Compact
- The heart of devops starts with people working not only as groups but as teams with a desire for mutual understanding.
# Chapter 3. A History of Devops
Focusing on the culture and processes encourages iteration and improvement in how and why we do things. When we shift our focus from what to why, we are given the freedom and trust to establish meaningfulness and purpose for our work, which is a key element of job satisfaction. Engagement with work impacts outcomes without concentrating on achieving a specific outcome, allowing for happy and productive humans building the next leap for humankind.
# Chapter 4. Foundational Terminology and Concepts
- Devops is not so rigidly defined as to prohibit any particular methodology.
## Software Development Methodologies
- The process of splitting up development work, usually into distinct phases, is known as a software development methodology.
	- Specification of deliverables or artifacts
	- Development and verification of the code with respect to the specification
	- Deployment of the code to its final customers or production environment
- The waterfall methodology or model is a project management process with an emphasis on a sequential progression from one stage of the process to the next.
- Agile is the name given to a group of software development methodologies that are designed to be more lightweight and flexible than previous methods such as waterfall.
- Scrum is a software development methodology that focuses on maximizing a development team’s ability to quickly respond to changes in both project and customer requirements.
## Operations Methodologies
- ITIL, formerly known as Information Technology Infrastructure Library, is a set of practices defined for managing IT services.
- Control Objectives for Information and Related Technology (COBIT) is an ISACA framework for governance and management of information and technology first released in 1996.
- COBIT is based on 5 principles:
	- meeting stakeholder needs;
	- covering the enterprise from end to end;
	- applying a single integrated framework;
	- enabling a holistic approach; and
	- separating governance from management.
## Systems Methodologies
- Some methodologies focus on thinking about systems as a whole, rather than limiting focus to more specific areas such as software development or IT operations.
- Lean systems focus on the parts of the system that add value by eliminating waste everywhere else, whether that be overproduction of some parts, defective products that have to be rebuilt, or time spent waiting on some other part of the system.
## Development, Release, and Deployment Concepts
- A version control system records changes to files or sets of files stored within the system.
- In test-driven development, the code developer starts by writing a failing test for the new code functionality, then writes the code itself, and finally ensures that the test passes when the code is complete.
- Application deployment is the process of planning, maintaining, and executing on the delivery of a software release.
- Continuous integration (CI) is the process of integrating new code written by developers with a mainline or “master” branch frequently throughout the day.
- Continuous delivery (CD) is a set of general software engineering principles that allow for frequent releases of new software through the use of automated testing and continuous integration.
- Continuous deployment (CD) is the process of deploying changes to production by defining tests and validations to minimize risk.
- The idea of the minimum viable product (MVP) is to create a prototype of a proposed product with the minimum amount of effort required to determine if the idea is a good one.
## Infrastructure Concepts
- Configuration management is the process of establishing and maintaining the consistency of something’s functional and physical attributes as well as performance throughout its lifecycle.
- A key part of devops is being able to assess and evaluate different tools and processes to find the most effective one for your environment, and it is absolutely possible to do that without moving to cloud-based infrastructure.
- Infrastructure automation is a way of creating systems that reduces the burden on people to manage the systems and their associated services, as well as increasing the quality, accuracy, and precision of a service to its consumers.
- An artifact is the output of any step in the software development process.
- Software containers are isolated structures that can be developed and deployed relatively independently from the underlying operating system or hardware.
## Cultural Concepts
- A retrospective is a discussion of a project that takes place after it has been completed, where topics such as what went well and what could be improved in future projects are considered.
- Unlike the planned, regular nature of a retrospective, a postmortem occurs after an unplanned incident or outage, for cases where an event’s outcome was surprising to those involved and at least one failure of the system or organization was revealed.
- Blamelessness is a concept that arose in contrast to the idea of blame culture.
- Incident retrospectives would be more effective if they focused on learning rather than punishment.
- Organizational learning is the process of collecting, growing, and sharing an organization’s body of knowledge.
- Organizational learning as a goal is part of what separates blameful cultures from blameless ones, as blameful cultures are often much more focused on punishment than on learning, whereas a blameless or learning organization takes value from experiences and looks for lessons learned and knowledge gained, even from negative experiences.
# Chapter 5. Devops Misconceptions and Anti-Patterns
## Common Devops Misconceptions
### Devops Only Involves Developers and System Administrators
- There is no one definitive list of which teams or individuals should be involved or how, just as there is no one-size-fits-all way to “do devops.”
- Ideas that help development and operations teams communicate better and work more efficiently together can be applied throughout a company. Any team within the organization should be considered.
### Devops Is a Team
- Creating a team called devops, or renaming an existing team to devops, is neither necessary nor sufficient for creating a devops culture.
- Keep in mind that devops is a culture and a process, and name and structure your teams accordingly.
### Devops Is a Job Title
- It might be necessary to have the developers deploying the code and maintaining the infrastructure in the early days of an organization, but as a company matures and grows, it makes sense to have people become more specialized in their job roles.
- When choosing your job, make sure that the higher salary doesn’t come at the cost of less personal time and higher rates of burnout.
### Devops Is Relevant Only to Web Startups
- Web startups are not alone in benefiting from improved collaboration, affinity, and tools. It is easier to iterate on team structures and processes at a small startup; enterprises have been trained to resist rapid change and governmental agencies even more so with laws that may actively restrict and impede change.
- Change is possible even in these sorts of organizations, however.
### You Need a Devops Certification
- A significant part of devops is about culture: how do you certify culture? There is no 60-minute exam that can certify how effectively you communicate with other people, how well teams in your company work together, or how your organization learns.
- Devops doesn’t have required technology or one-size-fits-all solutions. Certification exams are testing knowledge where there are clear right or wrong answers, which devops generally does not have.
### Devops Means Doing All the Work with Half the People
- Devops doesn’t save money by halving the number of engineers your company needs. Rather, it allows organizations to increase the quality and efficiency of their work, reducing the number and duration of outages, shortening development times, and improving both individual and team effectiveness.
### There Is One “Right Way” (or “Wrong Way”) to Do Devops
- Devops encourages critical thinking about processes, tools, and practices; being a learning organization requires questioning and iterating on processes, not accepting things as the “one true way” or the way that things have always been done.
- Cargo culting processes and tools into an environment can lead to the creation of additional silos and resistance to change.
- **Cargo culting** describes the practice of emulating observed behaviors or implementing tools into an environment without fully understanding the reasoning or circumstances that led to success using those strategies.
### It Will Take X Weeks/Months to Implement Devops
- Because so much of devops is cultural, it is harder to predict how long some of those changes will take: how long will it take people to break old siloed habits and replace them with new collaborative ones? This cannot be easily predicted, but don’t let that stop you from working toward these kinds of significant cultural transformations.
### Devops Is All About the Tools
- While tools are valuable, devops does not mandate or require any particular ones. This misconception is a contributing factor to the idea that devops is only for startups, as enterprise companies are often less able to adopt new technologies.
- Devops is a cultural movement. Within your environment the tools you use currently are part of your culture.
### Devops Is About Automation
- Automation is critical to us as systems become more complex and organizations become interdependent due to shared services. Without shared mutual context or concern for human needs, however, automation creates unknown additional risk.
- Automation may make work faster, but in order to be most effective it must also increase transparency, collaboration, and understanding.
### Devops Is a Fad
- Many of the driving ideas behind the devops movement have indeed been around for some time under different names, but the zeitgeist of devops as something more than the sum of its parts is new and different.
- People have certainly argued against functional silos before, suggested learning organizations, advocated for humane systems, or advocated for automation and measurement.
## Devops Anti-Patterns
### Blame Culture
- A blame (or blameful) culture is one that tends toward blaming and punishing people when mistakes are made, either at an individual or an organizational level.
- Heavily segregated or segmented environments that lack an appreciation for transparency are fertile ground for blame culture.
- When people are too focused on simply avoiding having a finger pointed at them, they are less focused on learning and collaboration.
### Silos
- A departmental or organizational silo describes the mentality of teams that do not share their knowledge with other teams in the same company. Instead of having common goals or responsibilities, siloed teams have very distinct and segregated roles.
- Silos come from a lack of communication and collaboration between teams, not simply from a separation of duties.
### Root Cause Analysis
- Root cause analysis (RCA) is a method to identify contributing and “root” causes of events or near-misses/close calls and the appropriate actions to prevent recurrence.
### Human Error
- Human error, the idea that a human being made a mistake that directly caused a failure, is often cited as the root cause in a root cause analysis.
- In a blameful culture, discussion stops with the finding that a specific person made a mistake, with the focus often being on who made the mistake and its end result. In a blameless culture or a learning organization, a human error is seen as a starting point rather than an ending one, sparking a discussion on the context surrounding the decision and why it made sense at the time.
# Chapter 6. The Four Pillars of Effective Devops
- The four pillars of effective devops:
	- Collaboration
	- Affinity
	- Tools
	- Scaling
- The combination of these four pillars will enable you to address both the cultural and technical aspects of your organization.
## Collaboration
- Collaboration is the process of building toward a specific outcome through supporting interactions and the input of multiple people.
## Affinity
- In addition to the growth and maintenance of collaborative relationships between individuals, teams and departments within an organization and across the industry at large need to have strong relationships.
## Tools
- Tools are an accelerator, driving change based on the current culture and direction.
## Scaling
- Scaling is a focus on the processes and pivots that organizations must adopt throughout their lifecycles.
# Chapter 7. Collaboration: Individuals Working Together
- Collaboration is the process of building toward a specific outcome through the interactions, input, and support of multiple people.
- Effective collaboration includes communication, equal participation, and Theory of Mind (ToM).
- Theory of Mind (ToM) is the ability to recognize one’s own perspective, and that others have a distinct and different perspective born from their own context.
- There are great benefits to be gained from diverse teams in terms of creativity, problem solving, and productivity, but this differentiation can lead to short-term interpersonal conflicts, either personally or professionally.
- Professional Backgrounds:
	- Enterprise versus startup experience
	- Technical fluency
	- Role hierarchies
	- Different paths to engineering
	- Years of experience
- When looking at the people on your team, it’s important to consider how effective they are at teaching or mentoring, in addition to just their technical skills, to ensure that your growth isn’t blocked by access to the experienced talent pool.
- Increasing the diversity of a team means ensuring a wider range of personal backgrounds. Including aspects such as gender, sexuality, race, class, primary language, ability, and education level, diverse personal backgrounds can increase the strength of an engineering, product-focused, or customer-support-driven organization by bringing a greater number of experiences and points of view to the table.
- Diversity also leads to increased friction, so that the teams should make adjustments to their expectations, processes, and potentially behaviors in order to alleviate this friction.
- The value of these initiatives is to foster an environment of safety, respect, and inclusion. Without personal safety, there is unlikely to be trust between employees. Personal backgrounds tend to contribute to power differentials that can affect or even prevent negotiation.
- While team members work toward the same goals and share responsibility for success, individuals on a team may have different personal and professional goals that can add to conflict when these differences are construed negatively. Being aware of these different motivations can help establish better understanding and empathy between team members.
- Friction between individuals can also arise from the different ways people process information, or their cognitive style.
- Key styles that might come into play in a workplace environment:
	- Introvert, ambivert, and extrovert
		- **Introvert**: recover energy by being alone or in small well-known groups.
		- **Extrovert**:  recharge by being around and interacting with lots of people.
		- **Ambivert**: are somewhere in the middle, capable of recharging alone or with others depending on circumstances.
	- Asker versus guesser
		- **Asker**: feels that it’s all right to ask for most things, with the understanding that they may well get “no”.
		- **Guesser**: tend to read more into situations and avoid asking for things unless they’re fairly certain that the answer will be “yes.”
	- Starter versus finisher
		- **Starters**: are people who love coming up with new ideas and getting them off the ground; they are energized by the process of beginning a new project.
		- **Finishers**: like tying up loose ends, fixing any remaining issues in a project.
	- Analytical, critical and lateral thinkers
		- **Analytical thinkers**: focuse on facts and evidence, dissects complex issues into simpler pieces, and eliminates extraneous information or invalid alternatives.
		- **Lateral thinkers**: gathers information more indirectly, finds missing elements, examines issues from multiple perspectives, and eliminates stereotypical patterns of thought.
		- **Critical thinkers**: involve evaluating and analyzing information and reflecting upon it in order to form judgments.
	- Purist versus pragmatist
		- **Purist**: look to use the absolute best technology to solve a problem, and if that perfect technology doesn’t exist, they will want to create their own.
		- **Pragmatist**: much more focused on practicality, weighing the cost of trying to create an ideal solution versus working within the realities of their current environments and constraints.
- If your team doesn’t have a good balance between starters and finishers, and purists and pragmatists, that can lead to issues with overall team productivity and quality.
- **Mentorship**: Organizations that are willing to invest in the growth and development of junior engineers will have a competitive advantage, not only because it grows the organization’s talent pool, but because skilled engineers are much more likely to stay in a place where they feel supported regardless of their current level of experience.
	- Setting up a formal mentoring program can go a long way here.
- **Sponsorship**: It’s important for organizations to create a comprehensive program that educates employees on what is required to be a sponsor, how to assess a potential protégé, and how to find and assess a sponsor.
- **Education**: Train people well enough so they can leave, treat them well enough so they don’t want to.
- 
