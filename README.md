# Bracketed - Sports and Esports Pick'ems

## Table of Contents

- [Bracketed - Sports and Esports Pick'ems](#bracketed---sports-and-esports-pickems)
  - [Table of Contents](#table-of-contents)
  - [Team Members](#team-members)
  - [Project Abstract](#project-abstract)
  - [Project Description](#project-description)
  - [Poster](#poster)
  - [User Docs](#user-docs)
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
  - [PPT Slideshows](#ppt-slideshows)
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
  - [Summary of Hours](#summary-of-hours)
  - [Budget/Expenses](#budget)
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

## Poster
<img width="1296" height="972" alt="image" src="https://github.com/user-attachments/assets/3d56c27a-b524-484d-8e62-9fb87b2af3be" />

## User Docs
[User Docs](Assignments/UserDocs/UserDocs.md)

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

## PPT Slideshows
### Fall
[Slideshow](Assignments/Fall_Design_Presentation.pdf)

### Spring
[Slideshow](Assignments/Bracketed_Spring_Presentation_Senior_Design.pdf)

## Self-Assessment Essays
### Fall
[Luke Myers](Assignments/Assignment3_CapstoneAssessment/IndividualCapstoneAssessment_Myers.pdf)

[Sam Winkelmann](Assignments/Assignment3_CapstoneAssessment/CapstoneAssessment_Winkelmann.pdf)

[William Braun](Assignments/Assignment3_CapstoneAssessment/IndividualCapstoneAssessment_Braun.pdf)

### Spring
[Luke Myers](Assignments/Individual_Assessments/Myers_Self_Assessment_Spring.pdf)

[Sam Winkelmann](Assignments/Individual_Assessments/Winkelmann_Self_Assessment_Spring.pdf)

[William Braun](Assignments/Individual_Assessments/Braun_Self%20Assessment_Spring.pdf)

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

## Summary of Hours
### William Braun
My contributions primarily focused on backend development, including integrating external APIs to retrieve and store match data and implementing full user authentication across the system. I worked on designing data flow, handling inconsistencies between different league APIs, and ensuring reliable communication between the frontend, backend, and database. I also contributed to testing, debugging, and supporting system integration. These efforts required a combination of research, development, and troubleshooting across both semesters, and supporting materials such as commit history and meeting notes provide evidence of my time and contributions.  

#### Fall Semester
- Team Meetings: 11 hours
- Class Assignments: 15 hours
- Backend Architecture Planning and Design: 3 hours
- Researching External APIs / Esports APIs: 5 hours
- Setting Up Backend Development Environment: 4 hours
- Initial API Exploration and Testing: 5 hours
- Brainstorming and Defining Backend Functionality: 4 hours  
**Fall Total: 47 hours**

#### Spring Semester
- Team Meetings: 12 hours
- Class Assignments and In-Class Presentation: 10 hours
- Final Expo: 5 hours
- Integration of External APIs for Match Data: 15 hours
- Handling and Normalizing League Data Across Multiple APIs: 5 hours
- Implementing User Authentication (Backend and Frontend Integration): 6 hours
- Database Integration for Storing Match and User Data: 2 hours
- Backend Testing Using Postman: 2 hours
- Supporting Teammates with Integration and Troubleshooting: 4 hours
- Final Testing and Refinement: 3 hours  
**Spring Total: 64 hours**

#### Total Contribution
Fall: 47 hours  
Spring: 64 hours  
**Total: 111 hours**  

### Sam Winkelmann
My primary contribution to the project was the frontend development, which primarily involved html, css, and javascript implementations.  I created the original layout of the site and the page designs, as well as most of the styling choices.  Because the frontend predated much of the backend functionality, it was done mainly in the first half of the project work, with less heavy focus on the frontend taking place in the later stages of the project.  I cvontinued to contribute via bug fixes and changes to styling, and whatever new frontend features needed to be created, but the bulk of that was early on.  I attended all of our team meetings, and worked on all assignments and aspects of the presentations, poster, expo prep, etc. as well.

#### Fall Semester
- Weekly Team Meetings (Advisor Meetings Included): ~11 hours
- 10 Assignments: ~15 hours
- Brainstorming ideas/frontend sketching/ideating: 4 hrs
- Project Setup / Work ~20 hours
**Fall Total: 50 hrs**

#### Spring Semester
- Team Meetings: 12 hours
- Class Assignments and In-Class Presentation: 10 hours
- Final Expo: 5 hours
- Brainstorming final frontend layout: 2 hours
- Initial frontend development: 12 hours
- Leaderboard development: 3 hours
- Bug fixes and Visual updates: 5 hours
- Demo/expo prep: 3 hours
**Spring Total: 52 hrs**

#### Total Contribution
Fall: 50 hours  
Spring: 52 hours  
**Total: 102 hours**  

### Luke Myers

### Fall Semester
- Team Meetings: 11 hours
- Class Assignments: 15 hours
- Tech Stack Brainstorming: 2 hours
- Front end Architcture Planning and Design: 3 hours
- Setting Up Front End Development Environment: 2 hours
- Overall User Experince and Product Funcionality Brainstorming: 8 hours
- React and NodeJS learning and research: 4 hours
**Fall Total: 45 hours**

### Spring Semester
- Team Meetings: 12 hours
- Class Assignments and In-Class Presentation: 10 hours
- Final Expo: 5 hours
- Data Base System Desgin: 4 hours
- SQL Data Base Scehma Creation: 5 hours
- Setting up Neon Serverless SQL Hosting: 2 hours
- API Endpoint Design: 6 hours
- API Endpoint and SQL Querey Creation: 8 hours
- Front End React Project Structuring: 2 hours
- Finilazing Data Flow from Backend to Frontend: 3 hours
- Data Model, React Hook, and Page Creation: 8 hours
- Finalzing Front End User Experince: 3 hours
**Spring Total: 68 hours**
  
### Total Contribution
Fall: 45 hours
Spring: 68 hours
**Total: 113 hours**

## Budget/Expenses
$15 - Tri fold for expo

## Appendix
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

Meeting 11, January 20:
- Discussed long term plans for ensuring the project will be finished by the day of the EXPO.

Meeting 12, January 27:
- Made a list of what pieces of data will be needed for which portion of our application for quicker database queries.

Meeting 13, February 3:
- Set up testing plan document
- Talked about how we are going to implement our API calls to the database.

Meeting 14, February 10:
- Set up User Docs
- Set up environment variables file to secure our keys

Meeting 15, February 17:
- Running into issues with League of Legends API
- Frontend page shows what brackets a user is enrolled in and allows them to make selections for which games should be included
- Updated presentation slidedeck

Meeting 16, Febraury 26:
- Talked about getting APIs updated with frontend
- Got a postman workspace set up

Meeting 17, March 3:
- Finalized database schema for tables
- All needed external APIs are now integrated
- Started working on logic for updating tables with external APIs
- Discussed what is needed for us to be able to do a demo next week during our presentation

Meeting 18, March 10:
- Finished slideshow that we will use for our presentation tomorrow
- More updates to the frontend

Meeting 19, March 24:
- Discussed plans for EXPO demo
    - We will pull a series of games from a previous weekend several years ago
    - People at the EXPO will then be able to make selections for who they think won that past match
    - At the end of the EXPO, we will conclude those matches, marking the correct winner
    - The accounts made during the EXPO will then have their scores updated based on their picks
- Discussed what needs to be done before the EXPO
    - User authentication
    - Leaderboard
    - Saving picks and locking them once the match starts
 
Meeting 20, March 31:
- Further discussed plans for EXPO demo
- Michael will work on the leaderboard
- Luke will work on API models, data flow, and refactoring 
- Sam will work on saving picks on the frontend. All functionality should be available on the backend
- William will work on automatically pulling match results from APIs and updating our database with that data
- We also need to work on getting dummy data for the demo, as real matches will not be finishing during the EXPO

Resources / References
- The API we intend to get our data from can be found at: https://www.api-football.com/
- For connecting to the API, we found good resources to learn at: https://nodejs.org/docs/latest/api/


