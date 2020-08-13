# Software-Engineering
Project Plan Document for Admin Portal

Purpose of Plan:

The Project Plan defines the following:
•	Project purpose
•	Goals & objectives
•	Scope
•	Risk analysis
•	Resourcing plan
•	Implementation plan
•	Project schedule
•	User Stories
•	Release for each story
•	Testing Plan

Project Scope:
We are planning to build an application called Admin Portal for a company which allows its internal employees to access the portal and perform admin functions on behalf of company clients.

Goals and Objectives:
The admin portal should have following objectives:
•	Application is accessible only on company network.
•	Access to the links is role based i.e. only authenticated internal admins are able to access the portal and what links you can access once on the portal is determined based on what roles you have. So, same link will not be visible to other admin who doesn't have appropriate role to access the link.
•	There are some global links that are available to all admins.
•	The links redirect users to the admin application that is not developed by you.

Risk Analysis:
The initial attempts to identify, characterize, prioritize and document a mitigation approach relative to those risks which can be identified prior to the start of the project.

Resourcing Plan:
The resources required for this project will depend on the size of project. As this is internal project for company employees it should require Project Manager who will be responsible for managing his team regarding the completion of each user story that is assigned to team, also the Project Manager will conduct weekly meeting for progress status of project. A SME (Subject Matter Expert) will be required who will analyze the requirements of project, the business objectives and goals and also provides help in risk analysis and implementation of project.
The Project Manager will form different teams such as Development, Testing etc. Each team will be of 1-5 members depending upon the project delivery span. If the project delivery span is low, more team members will be required.

Implementation Plan:
The implementation plan will depends on number of user stories assigned for this project.

User Stories:
User stories are defined to capture project functionality form the customer’s perspective. The goals and objectives which were defined above such as the portal will be accessible only on company’s network. Below is the user story table for admin portal application.
 
Testing Plan:
The application is tested by testing team with respect to each user story defined above.
For example consider the user story (1): The admin portal should be accessible only on company’s network not on outside of organization. So here the development will develop the Authentication gateway such as single sign on so that only organization users can access the portal. The single sign on authentication validates the user in such a way that the portal validates the user based on the windows credential or say the unique username and password the user used to login. The testing validates these by creating a test case to test this functionality and that the application works on only organization’s network.
User Story Description 
User Story (1) As an Internal admin I should be able to access the application.
User Story (2) As an authenticated user, I should be able to access the links on the admin portal.
User Story (3) As an admin I should be able to access the global links on the portal. 
User Story (4) As an internal admin I should be able to update my profile details. 
User Story(5)  As a system admin I should be able to provide access to other users of this portal.

Quality Measurement Plan:
The QAT (Quality assurance team) will test the admin portal application for preventing the defects in developed application before delivering it to the customer. The QAT team identifies the defects developed in the application and then consult that defect and creates a defect log report which contains information such as the frequency of occurrence of defect, whether this defect is application related, steps to resolve the defect etc. The application will be deployed on QA environment so that the QAT team will test the application there and identifies the bug and report them to the respective team. The QA environment is same as production but it is for QAT testing team.

Deployment Plan:
After testing the application by the Testing team and QAT team, a deployment plan will be created to deploy the application on live environment or say the production environment. A schedule will be created for product deployment on the production environment.

Maintenance Plan:
After deploying the application on production environment a Support team will be created to report a bug or defect that is persisting on the client side. The process is such that client report bug to the support team an incident will then be created for the bug and its priority will be defined whether the incident is of high, low and medium impact. The support team will assign the incident to respective team and the further process will flow until the incident is resolved.
