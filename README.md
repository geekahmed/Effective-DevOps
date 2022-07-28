This is my summary of the Effective DevOps, by Jennifer Davis and Ryn Daniels. Contributions: Issues, comments and pull requests are super welcome.
<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->
# Table of Contents
- [Table of Contents](#table-of-contents)
- [Chapter 1. The Big Picture](#chapter-1-the-big-picture)
- [Chapter 2. What Is Devops?](#chapter-2-what-is-devops)
- [Chapter 3. A History of Devops](#chapter-3-a-history-of-devops)
- [Chapter 4. Foundational Terminology and Concepts](#chapter-4-Foundational-Terminology-and-Concepts)
- [Chapter 5. Devops Misconceptions and Anti-Patterns](#chapter-5-Devops-Misconceptions-and-Anti--Patterns)
- [Chapter 6. The Four Pillars of Effective Devops ](#chapter-6-The-Four-Pillars-of-Effective-Devops)
- [Chapter 7. Collaboration: Individuals Working Together](#chapter-7-living-in-a-world-of-systems)
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

