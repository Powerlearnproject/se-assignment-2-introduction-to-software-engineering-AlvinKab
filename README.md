[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/-ucQIGTc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15218551&assignment_repo_type=AssignmentRepo)
# SE-Assignment-2
Assignment: Introduction to Software Engineering
Instructions:
Answer the following questions based on your understanding of software engineering concepts. Provide detailed explanations and examples where appropriate.

Questions:

## Define Software Engineering
**What is software engineering, and how does it differ from traditional programming?**

Software engineering is the systemic application of engineering principles, methods, and tools to the development and maintenance of high-quality software systems.
It differs from traditional programming in the sense that it is broader. While traditional programming mainly deals with code, software engineering is concerned with the entire software development life cycle.

[Source 1](https://www.phoenix.edu/blog/programmer-vs-software-engineer-key-differences.html#:~:text=Programmers'%20primary%20role%20is%20to,including%20concept%2C%20design%20and%20coding.)

[Source 2](https://www.indeed.com/career-advice/finding-a-job/software-engineer-vs-programmer#:~:text=As%20coding%20specialists%2C%20programmers%20work,to%20their%20areas%20of%20expertise.)

## Software Development Life Cycle (SDLC)
**Explain the various phases of the Software Development Life Cycle. Provide a brief description of each phase.**

The SDLC consists of the following phases:
- **Requirements:** User needs and system requirements are taken into heavy consideration when developing software. Thus, they are gathered and documented so as to determine the type of software that is to be developed.
- **Design:** High level and detailed designs of the software architecture and user interface are conceptualised and created.
- **Implementation:** Code is written and the software is built based on design specifications.
- **Testing:** Various tests are conducted to ensure that the software meets quality standards and functional requirements.
- **Deployment:** The software is released to users/clients.
- **Maintenance:** This is the process of providing ongoing support, updates and enhancements to the software after deployment to ensure that it still functions properly and does not become outdated.

## Agile vs. Waterfall Models
**Compare and contrast the Agile and Waterfall models of software development. What are the key differences, and in what scenarios might each be preferred?**
- In the agile model, there is frequent interaction with the client while in the tradiitional model, there is a hands-off approach where goals and expected outcomes are expected from the beginning.
- The agile model is more flexible than the waterfall model.
- The agile model requires team initiative ans short-term deadlines while the waterfall model relies on comlpeting deliverables to progress to the next stage.

The waterfall model is best suited for projects with a defined end goal due to it's linear progression, for example, developing an application.
The agile model may be preferred in projects where the outcoem may be more dependent on research or testing sinc it leaves a lot of room to adapt and change course as te project develops.

[Source](https://www.forbes.com/advisor/business/agile-vs-waterfall-methodology/)

## Requirements Engineering
**What is requirements engineering? Describe the process and its importance in the software development life cycle.**

Requirements engineering is the process of identifying, eliciting, analyzing, specifying, validating, and managing the bneeds and expectations of stakeholders/clients for a software system.

The requirements engineering process involves the following steps:
- **Feasibility study:** Includes economic, technical,operational, schedule and legal feasibility.
- **Requirements elicitation:** It is related to the various ways used to gain knowledge about the projeect domain and requirements.
- **Requirements specification:** This activity is used to produce formal software requirement models.
- **Requirements verification and validation:** Verifiction refers to the set of tasks that ensures that the software correctly implements a specific function, while validation refers to a different set of tasks that ensure that the software that has been built is traceable to customer requirements.
- **Requirements management:** This is the process of analyzing, documenting, tracking, prioritizing, and agreeing on the requirement and controlling the communication with relevant stakeholders.

Requirements management is a critical step in the software development life cycle as it helps to ensure that the software system being developed meets the needs and expectations of stakeholders and that it is developed on time, within budget, and to the required quality. It also helps to prevent scope creep and to ensure that the requirements are aligned with the project goals.

[Source](https://www.geeksforgeeks.org/software-engineering-requirements-engineering-process/)

## Software Design Principles
**Explain the concept of modularity in software design. How does it improve maintainability and scalability of software systems?**

In software design, modularity refers to the practice of dividing soft ware into separate, independent modules, each responsible for a distinct feature or functionality. This approach promotes better maintainability, scalabitity, and reusability of code by isolating functional boundaries, making complex systems easier to manage and evolve.

[Source](https://www.ituonline.com/tech-definitions/what-is-modularity-in-software-design/#:~:text=Modularity%20is%20a%20fundamental%20design,the%20understandability%20of%20the%20system.)

## Testing in Software Engineering
**Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing). Why is testing crucial in software development?**

- Unit testing involves testing individual components or modules of software.
- Integration testing is testing interactions between different components or subsystems.
- System testing is testing the entire software system as a whole.
- Acceptance testing involves testing the software against user requirements to ensure it meets user needs.

Testing is crucial in software development since it helps in identifying and fixing defects early in the development process, leading to higher quality autonated products.

## Version Control Systems
**What are version control systems, and why are they important in software development? Give examples of popular version control systems and their features.**

Version control systems are software tools for tracking changes to source code and coordinating work among team members.

Version control encourages a culture of continuous peer review and collaboration, leading to significant improvements in code quality.

Examples of version control systems are Git and Subversion.

Features of Git:
- Tracks history.
- Free and open source.
- Supports non-linear development.

Features of Subversion:
- Branching and tagging are cheap operations.
- File locking.
- Atomic commits.

[Source 1](https://about.gitlab.com/topics/version-control/#:~:text=Version%20control%20encourages%20a%20culture,to%20best%20practices%20and%20standards.)

[Source 2](https://www.simplilearn.com/tutorials/git-tutorial/what-is-git)

[Source 3](https://subversion.apache.org/features)

## Software Project Management
**Discuss the role of a software project manager. What are some key responsibilities and challenges faced in managing software projects?**

The role of a software project manager is to oversee the planning, execution and delivery of software projects.

Key responsibilities in project management:
- Risk management.
- Managing time.
- Accountability.
- Project planning.
- Project scooping.

Challenges faced in managing software projects:
- Scope creep.
- Limited budget.
- Unrealistic deadlines.
- Lack of communication.
- Lack of clear goals and success criteria.
- Inadequate skills of team members.

[Source](https://kissflow.com/project/project-management-challenges/)

## Software Maintenance
**Define software maintenance and explain the different types of maintenance activities. Why is maintenance an essential part of the software lifecycle?**

Software maintenance is the process of providing ongoing support, updates, and enhancements to the software after deployment.

Types of maintenance activities:
- **Corrective maintenance:** This refers to changes made to repair defects in the design, coding and implementation of the software.
- **Preventive maintenance:** Involves changes made to a software to reduce the chance of the software failing.
- **Adaptive maintenance:** Involves making changes to a software to evolve its functionality to changing needs.
- **Perfective maintenance:** Involves making enhancements to improve processing performance, interference usability, or to add desired, but not necessarily required system features.

## Ethical Considerations in Software Engineering
**What are some ethical issues that software engineers might face? How can software engineers ensure they adhere to ethical standards in their work?**

Ethical issues that software engineers might face:
- Data privacy.
- Accessibility.
- Additive design.
- Algorthmic bias.
- Software security.

How software engineers can ensure they adhere to ethical standards in their work:
- Acting consistently with the public interest.
- Acting in a manner that is in the best interests of their client and employer, consisten with the public interest.
- Ensuring that their products and related modifications meet the highest professional standards possible.
- Maintaining integrity and independence in their professional judgement.
- advancing the integrity and reputation of the profession, consistent with the public interest.

[Source 1](https://x-team.com/blog/5-ethical-issues-in-software-development/)

[Source 2](https://www.computer.org/education/code-of-ethics)
