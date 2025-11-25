# Bracketed - Sports and Esports Pick'ems

## Table of Contents

- [Bracketed - Sports and Esports Pick'ems](#bracketed---sports-and-esports-pickems)
  - [Table of Contents](#table-of-contents)
  - [Team Members](#team-members)
  - [Project Abstract](#project-abstract)
  - [Project Description](#project-description)
  - [User Stories and Design Diagrams](#user-stories-and-design-diagrams)
    - [User Stories](#user-stories)
    - [Design Diagrams](#design-diagrams)
      - [Level 0](#level-0)
      - [Level 1](#level-1)
      - [Level 2](#level-2)
  - [Project Tasks and Timeline](#project-tasks-and-timeline)
    - [Task List](#task-list)
    - [Timeline](#timeline)
    - [Effort Matrix](#effort-matrix)
  - [ABET Concerns Essay](#abet-concerns-essay)
  - [PPT Slideshow](#ppt-slideshow)
  - [Self-Assessment Essays](#self-assessment-essays)
  - [Professional Biographies](#professional-biographies)
    - [Luke Myers](#luke-myers)
      - [Contact Info](#contact-info)
      - [Co-op Work Experience](#co-op-work-experience)
      - [Skills](#skills)
      - [Areas of Interest](#areas-of-interest)
    - [Michael Rhode](#michael-rhode)
      - [Contact Information](#contact-information)
      - [Co-Op Work Experience](#co-op-work-experience-1)
        - [Information Systems Intern, Copeland, Sydney, Ohio. (Spring, Fall 2023):](#information-systems-intern-copeland-sydney-ohio-spring-fall-2023)
        - [Engineering Co-Op, Thompson Metal Fabrication, Hamilton, Ohio. (Summer 2024, Spring-Summer 2025):](#engineering-co-op-thompson-metal-fabrication-hamilton-ohio-summer-2024-spring-summer-2025)
      - [Skills/Expertise](#skillsexpertise)
      - [Interests](#interests)
      - [Capstone Projects Sought](#capstone-projects-sought)
    - [Sam Winkelmann](#sam-winkelmann)
      - [Co-op Work Experience](#co-op-work-experience-2)
        - [Quality Assurance Co-op](#quality-assurance-co-op)
        - [Software Development Co-op](#software-development-co-op)
        - [Software Development Intern](#software-development-intern)
      - [Project Sought](#project-sought)
    - [William Braun](#william-braun)
      - [Co-op or Other Experience and Responsibilities](#co-op-or-other-experience-and-responsibilities)
        - [**Computer Science Intern, Modern Technology Solutions, Inc., Dayton, Ohio. (3 semesters)**](#computer-science-intern-modern-technology-solutions-inc-dayton-ohio-3-semesters)
        - [**Psychiatry Student Co-op, Cincinnati Children's Hospital and Medical Center, Cincinnati, Ohio. (2 semesters)**](#psychiatry-student-co-op-cincinnati-childrens-hospital-and-medical-center-cincinnati-ohio-2-semesters)
        - [**Registered Pharmacy Technician, Meijer Pharmacy, Cincinnati, Ohio. (4 years)**](#registered-pharmacy-technician-meijer-pharmacy-cincinnati-ohio-4-years)
      - [Skills/Expertise Areas](#skillsexpertise-areas)
      - [Areas of Interest](#areas-of-interest-1)
      - [Types of Projects Sought](#types-of-projects-sought)
  - [Budget](#budget)
  - [Appendix](#appendix)

## Team Members
Luke Myers - myers2le@mail.uc.edu  
Michael Rhode - rhodemr@mail.uc.edu  
Sam Winkelmann - winkelse@mail.uc.edu  
William Braun - braunwb@mail.uc.edu  
Giovani Abuaitah (Advisor) - abuaitgi@ucmail.uc.edu

## Project Abstract
Bracketed is a web-based platform that unifies pick’em competitions across both sports and Esports. The platform aims to simplify user participation by offering a central hub where fans can make weekly predictions, track leaderboards, and compare results with others. The project emphasizes intuitive design, seamless database integration, and responsive web functionality. Our backend will handle user authentication, match data retrieval, and scoring automation. Bracketed’s long-term goal is to provide a scalable, community-oriented environment for competitive sports and Esports prediction enthusiasts.​

## Project Description
Bracketed is a web-based platform where users can join or create "pick’em" contests across multiple sports and esports in one unified hub. Users predict winners, track scores, and compete with friends in leagues or leaderboards.

## User Stories and Design Diagrams
### User Stories
- As a sports fan, I want to make weekly pick'em predictions across multiple leagues so that I can compete with my friends and track my performance.
- As an Esports follower, I want to view leaderboards for different competitions so that I can see how my predictions compare to others in the community.
- As a casual user, I want to access both sports and Esports pick'ems on the same platform so that I don't have to use multiple apps or websites.
- As a competitive user, I want to see the results of my past picks so I can analyze my performance and improve over time.
- As a new user, I want a simple and intuitive interface so I can start making picks right away without the need of complex instructions.

### Design Diagrams
#### Level 0 
[Design Diagram Level 0](DesignDiagrams/DD01.png)
- The most basic description of our project's design. Instead of focusing on technical systems, this diagram illustrates the general flow that will be followed when using the application. Users will be authenticated, predicitons will be made, and scores and results will be calculated when the games finish.

#### Level 1 
[Design Diagram Level 1](DesignDiagrams/DD02.png)
- More detail is added in this diagram. Interactions between the user, UI, and backend of the application are depicted. A similar flow from the first diagram is shown, but now each step is associated with a system of the application.

#### Level 2
[Design Diagram Level 2](DesignDiagrams/DD03.png)
- The most detailed diagram- depicting the UI, API, and Data Control layer. Each input by the user will have a reaction that goes down each layer, all the way to the database, and evetually lead to an output returned back to the user.

## Project Tasks and Timeline
### Task List
[Task List](Assignments/TaskList.md)

### Timeline 
[Timeline](Assignments/Timeline.xlsx)

### Effort Matrix
[Effort Matrix](Assignments/EffortMatrix.xlsx)

## ABET Concerns Essay
Our project will interact with economic, legal, security, and ethical concerns. 

Economic:  
While some API’s may charge a fee for a subscription to connect to their databases, some are free such as API-Football which is a good contender for what we will use. It may cost some money from us in the form of power usage when hosting the server/database or performing tests on a locally hosted webpage, but this cost is negligible in the longterm. Our final product will not be connected to UC or any other external help besides the API that we have decided to use for this project, so our costs should stay low.  

Security concerns:  
Because our project will have a login system, there exists the possibility that user information such as passwords could be retrieved from the database should someone try to access the system.  We will also include some basic personal information such as users’ names so that other users will be able to identify each other more easily if they are added as friends.  We would recommend that users keep their passwords unique so that there is no risk of any larger impact should they get leaked.  Security is always a concern, no matter the size or scope of the project, since user information should always be kept private. 

Legal:  
A major legal constraint for Bracketed involves the use of intellectual property from professional sports and esports leagues such as the NFL, NBA, League of Legends, and Overwatch. These organizations control the use of their logos, team names, and other branded materials. Therefore, our project will have to use only publicly available data such as scores, schedules, and statistics obtained from approved or open-source APIs. If Bracketed was to ever be expanded beyond a senior project, we would need to pursue official licensing or data agreements to ensure full legal compliance.  

Ethical:  
In its current state, there will be little to no ethical constraints for the project. However, if the project expands, there will be some ethical concerns that will need to be addressed. The website will have the ability for users to add friends and invite them to challenges, which will start to create a community. It will be an ethical obligation to monitor this community to prevent harassment, hateful activity, and bullying. Many sports games often involve gambling, and if any monetary transactions or rewards were ever included into the site, it would be important that effects of sports betting and gambling addiction would not be abused or capitalized on just for the benefit of the website. 

## PPT Slideshow
[Slideshow](Assignments/Fall_Design_Presentation.pdf)

## Self-Assessment Essays
[Luke Meyers](Assignments/Assignment3_CapstoneAssessment/IndividualCapstoneAssessment_Myers.pdf)

[Sam Winkelmann](Assignments/Assignment3_CapstoneAssessment/CapstoneAssessment_Winkelmann.pdf)

[William Braun](Assignments/Assignment3_CapstoneAssessment/IndividualCapstoneAssessment_Braun.pdf)

## Professional Biographies

### Luke Myers
#### Contact Info
- myers2le@mail.uc.edu

#### Co-op Work Experience
*Developer, London Computer Systems, Cincinnati, OH. (4 Semesters, August 2023 - August 2025)*
- Worked on TenantWebAccess and RMResident, propety management software
- Wrote front end code in HTML, Typescript, and CSS
- Developed applications using Angular and ASP.NET framework
- Wrote back end and API code in C#
- Helped work on three major projects, such as maintenance scheduling, a FAQ page, and tenant self inspections
- Worked on over 40+ smaller bugs and feature updates
- Created Android and IOS builds using Andriod Studio and XCode

*Quality Assurance Tester, London Computer Systems, Cincinnati, OH. (1 Semester, January 2023 - April 2023)*
- Wrote detailed test plans for bug fixes and new features for Rent Manager Express
- Executed these test plans, verifying if each step performed as expected
- Thoroughly documented defects, how to produce them, and the what the expected result should be
- Communicated with developers to explain defects

#### Skills
- Programming: C#, TypeScript, C++, Java
- Database: SQL
- Web Development: HTML, CSS

#### Areas of Interest
- Full Stack Development
- Mobile Development
- Video Game Design and Development
- Software designed to use location for functionality

### Michael Rhode
#### Contact Information
- Phone: 513-601-6275 
- Email: Rhodemr@mail.uc.edu

#### Co-Op Work Experience
##### Information Systems Intern, Copeland, Sydney, Ohio. (Spring, Fall 2023):
- Elevated procedures by turning manual data uploading to an online form
- Restructured the process for internal recieving from other facilities
- Eliminated redundant and unnecessary tasks from the scanning process.
- Structured a read only application on the internal site to lower confusion between engineers
- Added error detection to the recieving department

##### Engineering Co-Op, Thompson Metal Fabrication, Hamilton, Ohio. (Summer 2024, Spring-Summer 2025):
- Developed a routine maintenance schedule for all machines
- Designed a process to automatically email us when certain maintenance was due on our machines
- Optimized metal utilization using CAM software to nest parts
- Designed parts for internal shop needs

#### Skills/Expertise
- Programming: C++, Python, SQL
- Web Development: HTML, .NET
- Database Programming: SQL(Server)
- CAM software: BySoft CAM, AutoCAD
- General Computer Skills: Word, Excel

#### Interests
- Artificial Intelligence
- Application Creation
- Database Management
- Website Development

#### Capstone Projects Sought
- Create an application that watches how you aim when you play videogames and creates a summary as to how you can improve your aim
- Create an AI to analyze the music you like and give you song recommendations

### Sam Winkelmann
#### Co-op Work Experience
##### Quality Assurance Co-op
London Computer Systems – January 2023 – April 2023

•	 Experienced the workflow and habits of being a QA tester firsthand to improve future relationships with QA testers while in a development role, as their experience is familiar. 

•	Honed communication skills in daily and weekly meetings to give quick, concise project updates using clear language to help those not associated with the projects.

##### Software Development Co-op
London Computer Systems – August 2023 - December 2023, May 2024 – August 2024

•	Introduced to Angular, HTML, and CSS languages and worked to improve skills via experience and asking questions, as well as specialized courses throughout the duration of this co-op experience. 

•	Worked with a team of other developers and QA specialists to fully understand the software development workflow, including regular meetings and frequent communication with other developers. 

•	Contributed to a project with a short deadline, gaining experience in working with a team to coordinate multiple features at once, turning around changes efficiently, and dealing with new specifications. 

•	Assisted in overhauling an existing page on the software, which included logic changes, new features being added, visual/styling changes, and the consideration of future components using this new code.

##### Software Development Intern
Medpace – January 2025 – August 2025

•	Modernized a legacy web application into Angular, improving the function and look of the frontend, as well as updating the backend and database as necessary.

•	 Learned and experienced some Microsoft Azure tools while setting up new features for the Angular application, such as sign-in features, user verification, and shared user-session abilities.

•	Collaborated with team members across the United States, as well as other countries, leading to increased need to capitalize on time that we could interact directly, which allowed me to better manage time spent working with them.

#### Project Sought
I am looking to work on a project that is fun and engaging, that also challenges me to improve my skills and/or learn new skills.  My experience is primarily with frontend and backend on web projects, but I am happy to branch out and learn something new to increase my overall experience. 

### William Braun
Cincinnati, OH • (513) 908-7454 • braunwb@mail.uc.edu  
[LinkedIn](https://www.linkedin.com/in/william-braun-/?) • [GitHub](https://github.com/William-Braun)

#### Co-op or Other Experience and Responsibilities
##### **Computer Science Intern, Modern Technology Solutions, Inc., Dayton, Ohio. (3 semesters)**
- Worked as a software developer on an aircraft simulation project, contributing to the design, implementation, improvement, and testing of new and existing features
- Applied Agile and Scrum principles to plan, prioritize, and complete work in iterative sprints
- Participated in daily standups, sprint planning, and retrospectives
- Collaborated with a small development team to enhance simulation functionality while ensuring code quality, scalability, maintainability, and readability
- Coordinated frequently with another software team that focused on emerging capabilities in our project, ensuring both teams could work in parallel
- Participated in code reviews, integrating peer feedback and providing insights to align with project standards and best practices
- Integrated new versions of libraries and environments to maintain compatibility, improve performance, and leverage updated features to add new functionality

##### **Psychiatry Student Co-op, Cincinnati Children's Hospital and Medical Center, Cincinnati, Ohio. (2 semesters)**
- Prepared, tested, and executed MATLAB scripts to assist with the preprocessing and analysis of neurophysiological data collected in patients with Fragile X syndrome and typically developing controls
- Implemented and tested various algorithms to determine the method that best removes non-brain artifact from EEG signals while preserving neural activity
- Developed a visual discrimination paradigm that makes use of eye tracking, positive and negative feedback, and auditory distractors to allow for more interpretable results while minimizing timing inconsistencies present in performing studies with both Fragile X and typically developing control participants
- Modified an existing reversal learning behavioral paradigm to allow it to be used on multiple different operating systems, including iOS and Android, while maintaining consistent timing and fixing existing bugs

##### **Registered Pharmacy Technician, Meijer Pharmacy, Cincinnati, Ohio. (4 years)**
- Work closely with customers to manage insurance, dispense prescriptions, and amend problems with scripts
- Aid pharmacists and other technicians with processing, counting, filling, and labeling prescriptions for patients
- Engage in training of 7+ new pharmacy technicians and interns during their on-boarding processes

#### Skills/Expertise Areas
- **Programming:** C++, Python, Java, SQL
- **Web Development:** HTML, CSS, JavaScript
- **Operating Systems:** Windows, Linux
- **Applications/Tools:** Microsoft Office Suite, MATLAB, Neurobehavioral Systems Presentation Software, MIXR

#### Areas of Interest
- Simulation and modeling systems
- Game development and esports applications
- Game-related analytics and performance tools  
- Artificial intelligence and machine learning
- Cross-platform and mobile application development
- Full-stack software engineering (front-end and back-end design)

#### Types of Projects Sought
- Simulation tools for training, research, or interactive environments
- Game development projects or tools that enhance gaming experiences
- AI/ML-driven applications for predictive analytics
- Mobile or cross-platform applications
- Full-stack projects that integrate user-friendly front ends with scalable back ends

## Budget
There have not been any expenses to date for this project.

The football API at: https://www.api-football.com/ may need a subscription which would cost $19.00 per month should we exceed 100 API requests per day.

There may be additional costs if we want to host our client and server in the costs, but these have not been calculated yet

## Appendix
Time Card
- Weekly Team Meetings (Advisor Meetings Included): ~11 hours
- 10 Assignments: ~15 hours
- Project Setup / Work ~20 hours

Meeting 1, September 17:
- Created Design Diagrams for Assignment 4
- Compiled interview data about what people would want out of our application
- Divided research topics amongst ourselves to talk about in the following meeting

Meeting 2, September 24:
- Wrote out task lists to roughly be even between all 4 members
- Decided who would deal with what aspects of the project

Meeting 3, October 1:
- Created timeline of tasks and when they are do through out both semesters

Meeting 4, October 8:
- Brainstormed ideas that may cause snags within the project during its development
  
Meeting 5, October 15:
- Decided on using Node.js for the backend with PostGreSQL as the database
- Quick meeting to check in on if anyone was having issues with the project

Meeting 6, October 22:
- Structured our powerpoint presentation
- Divided the sections into parts to record amongst ourselves.

Meeting 7, October 29:
- Officially created the github group
- Set up base application to start 

Meeting 8, November 5:
- Caught everyone up to speed to be able to run our application and get a printout on screen.
- Connected PostGres database to our Node.js backend

Meeting 9, November 12:
- Meeting was cancelled due to scheduling conflicts

Meeting 10, November 19:
- Talked about connecting an API to our system via Node.js instead of from the database itself
- Created a way to run the client and server at the same time for easier testing

Resources / References
- The API we intend to get our data from can be found at: https://www.api-football.com/
- For connecting to the API, we found good resources to learn at: https://nodejs.org/docs/latest/api/


