
# Software Project Management Plan
## Team 5
### Team members:
Bodini Cristian

Di Nunzio Giovanni

Godoi Igor

Molinari Pietro

Pareti Nicholas

---


## Overview
### 1. Purpose and scope
The chat protocol permits the user to communicate with other users within their own network.
### 2. Goals and objectives
The main objective is to allow the users on a network to communicate with each other.
### 3. Assumptions and constraints
The application will run on Windows OS and will use the TCP protocol. However, it can work only with computers within a network.

---
## Startup plan
### 1. Team organization
Project manager: Cobello Grazia, De Carli Lorenzo
Scrum master: Molinari Pietro
Programmers: Bodini Cristian, Di Nunzio Giovanni, Godoi Igor, Pareti Nicholas
### 2. Project communications
The informations are given by the teachers by the school Campus.
### 3. Technical process
The project is developed by the single operators, which are given specific parts of the project to work on. At the end, all the parts are merged together.
### 4. Tools
- Programming language: Python
- Version Control System: The parts of the projects are stored in git branches, then merged on GitHub
- Build tools: The builds are edited, written and tested with  PyCharm.
## Work plan
### 1. Activities and task
The work is analyzed in detail to identify each task.
Each task, depending on the needs of the projects, will have the following attributes:

- Task name;
- Task description;
- Owner;
- Effort estimate;
- Actual effort;
- Planned start and stop dates;  
- Actual start and stop dates;
- Dependencies among other tasks.

### 2. Release plan
or day-to-day project management the release and iteration plans (described in the next section) are probably the two most important project management artifacts.

The release plan lists expected completion dates for major milestones and delivery dates of key work products. The project’s technical development process to a certain extent will dictate the choice and timing of milestones and deliverables. For example, projects following the Rational Unified Process will have four major milestones: life-cycle objectives, life-cycle architecture, initial operation capability, and product release.

### Iteration Plans
An iteration plan is a short-term fine-grained plan that shows the tasks to be completed during an iteration.
### Budget
The project budget is the projected cost of the project as a function of time. At any point in the project you should be able to say how much money has already been spent and estimate of the amount of money needed to complete the project.

## Control plan
### 1. Monitoring and control
Include in this section plans and procedures for tracking progress and controlling performance. Included here will be the approximate dates of technical as well as managerial reviews. Typically each major milestone or project phase will end in a review.

For projects that don’t have a separate communication plan, this section may also include information on the timing and content of status reports and other project review documentation.

**Partial Example**

	Weekly –  Team meeting.
	Project participants report status,
	progress and potential problems.

	28/12/2019 – Critical Design Review.
	Formal inspection of product architecture.

	03/01/2020 – Executive Review.
	The project manager presents current project
	status to project sponsor and senior executives.

## Project measurements
Product and process measures support project management and estimation by analogy. At the beginning of a project, estimates are made for product size, project cost and delivery dates.

During a project, progress is tracked with measures of actual effort, integrated lines of code and actual expenditures. Keeping track of estimates and actuals during a project helps to calibrate whatever technique is being used to make estimates. Storing project performance data on completed projects provides a rich source of data for estimating future projects.

## Supporting process plans
### 1. Risk management plan
Identify technical and managerial risks. Prioritize risks. Consider the probability of each risk turning into a problem and the likely consequences.

For the highest priority risks, what actions will be taken to minimize the probability of the risk turning into a problem and the resulting consequences? What are the contingency plans for selected risks that do become a problem? Identify processes for monitoring risks and updating the risk management plan.
### 2. Configuration management plan

Configuration management plans for this document and other baselined work products including review procedures and change management procedures.

**Partial example**

	- All work products will be stored in a centralized CVS repository running on a central server.    
	- The naming convention for documents will be: NNN-VVV.suffix where NNN is a mnemonic that reflects the function of the 	document, VVV is a 3 digit version number, and 'suffix' is the standard/normal suffix for the document type. For example, the second version of the requirements document created as a Microsoft Word document might be labeled: REQ-002.doc.    
	- All project (work products) items (documents, source code, test cases, program data, test data, etc) will be stored in the CVS repository but not all will be under change control (subject to formal change control procedures.) Only the system requirements, project plan and source code will be baselined and under configuration control.   
	- Items that are subject to change control will be considered baselined after a group review at the end of the life cycle phase during which they are created. Baselined here means that the product has undergone a formal review and can only be changed through the prescribed change control procedures.  
	- The change control procedure once a product is baselined is: 
		1. anyone wanting to make a change to a baselined item sends an email to the rest of the group describing the change, reason for the change, expected impact, and timeline for integrating the change. 
		2. if no one responds to the group within 2 days with a reason for why the change request shouldn't be permitted, it will be considered accepted and the person proposing the change may proceed with the change. If anyone does object to the change, the reason for objecting will be discussed at a meeting where everyone is invited to attend and voice their opinion. At the end of the meeting a democratic vote will be held to decide whether or not the change should be allowed.
	- Including a change history with all documents is encouraged but only required for baselined documents. The change history should be at the front of the work item and include: 
		1. the name of the person making the change, 
		2. brief description of what has changed, 
		3. reason for the change, and 
		4. the date the change was integrated.
	
### 3. Verification and validation plan
The verification and validation plan defines what actions are being taken to assure the quality of the development process and resulting software products.

**Partial example**
	
	The Verification and Validation plan is specified as a separate documented located in the version control
	system at: http://company.com/svn/project-name/docs/VandVPlan.doc

### 4. Product acceptance plan
The product acceptance plan defines what is acceptable in terms of product quality and product functionality.

Acceptance criteria should be objective and measurable. Note product success is one aspect of project success. Teams wanting to establish a clear understanding of what will be considered acceptable project performance may want to define a more general plan for project success that includes quantitative goals for delivery date, cost, etc.
