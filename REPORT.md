# Information_System_Development_Methodologies Report

## **0. Tutorial & Team Information** ##
Subject | Tutorial Group | Team Group Number
--------|----------------|-------------
31257 Information System Development Methodologies | 7 | 3


Name | Student ID 
-----|-----------
Adam Kondonis | 13560471
Andrew Do | 12876520
Louis Henderson | 13609096
Nimrod Ktalav | 12900268



## **1. Executive Summary** ##

## **2. Objectives** ##
The following report proposes an information system that will improve the operations of a major travel company's in-house call management centre (CMC). The objective is to provide an information system that improves call routing and dynamic call flow control for Relationship Managers (RM) that are allocated queries from inbound and outbound customers based on suitability. 
 
### System Objectives: Functional & Non-Functional Requirements ###

Functional Requirements 
--------|
The system matches the relationship managers and customers based on the RM's performance, profiles and product knowledge.
The system stores the user's profile information into a database.
The system has Profiler Tool that creates profiles for the RM and customers.
The system produces a questionnaire and skill matrix of the RMs.
The system gneerates guidelines and a script to assist RMs with their customer service.
The system generates a target list of suitable customers for the RM to call.
The system has a call routing and distribution routine that minimises inbound call costs by reduing per-call handling time.
The system generates a priority-based score for customers in which higher customer scores are served first.
The system has an Interactive Voice Response unit that automatically prompts the user for information while they are waiting in a queue.


Non-Functional Requirements | Purpose 
--------|----------------
Responsive | Because inbound customers can potentially be waiting in a queue when they call the CMC, the system's timeliness is essential to allocating suitable RMs and maximising potential travel package sale opportunities.
Usable | RMs require an user-friendly interface that provides easy-to-understand scripts and customer information to resolve customer inquiries efficiently.
Extensible | Future extensions to the call routing system can be applied to improve the system's service quality.
Maintainable | System failures and bugs are inevitable; constant maintenance can mitigate these issues.
Data Architecture | Because the travel company manages several holiday package options, user profiles and performance reports, the system requires a logical structure for organising the data to prevent memory overflows.
Secure | The system handles user sensitive data that should adhere to the Australian Data Privacy Act 1988.

### Team Objectives ###
Team goals can be measured through Github's version control features and opened issues. In order for the goals to be achieved, the team will hold weekly meetings, commit an update for their assigned task to github at least once a week and comment on the opened issues if there are any inquiries. Each team member will be assigned a role with task responsibilities for this project (Further clarification can be found in Section 6: Agile Methodologies). The team objective to achieve an High Destinction for this report as well as satisfactory team collaboration and morale.

## **3. Problem Definition** ##
A major travel company uses a call management centre as a way of attempting to sell holiday packages to people who want to travel. They want an information system to be developed which will improve the overall operation of their call management centre. 
 

Without these features, it is assumed that the company’s call management centre has difficulties in their overall performance, where relationship managers would be more likely to talk to customers who will most likely not purchase a holiday package. This means that the travel company is less likely to reach their target customers, which can be accentuated by the current call rate, call routing and dynamic call flow control processes. These circumstances would result in the company’s targeted customers to purchase from a different company that would probably use a system which is more efficient in enabling customers talking to sales employees.


## **4. Stakeholders** ##
### Empathy Maps: ###
Relationship Managers
![github](https://github.com/AndrewDucDanhDo/Information_System_Development_Methodologies/blob/master/images/empathy_map_relationship_manager.jpg)

Relationship managers are often under immense stress. They may feel pressure to meet sales quotas and make sales. They receive calls from inbound customers and make calls to outbound customers. Relationship managers are responsible for performing sales on holiday packages, answer customer inquiries and building a profile matrix. They may often hear complaints from customers as well as customer feedback. Relationship managers may feel pressure throuhg using a slow and inefficient system, and pressure may also arise through constantly having to meet up with sales quotas. On the other hand, having an improved system can reduce the pain and pressure experienced by relationship managers.

Inbound Customers
![github](https://github.com/AndrewDucDanhDo/Information_System_Development_Methodologies/blob/master/images/empathy_map_in_bound.jpg)

Inbound customers may feel frustration using the current system as it is slow and not intuitive. They may feel confused about which available holiday package is best suited for them. Inbound customers often ask questions to relationship managers in the call management centre and inquire about available holiday packages. Inbound customers may complain about long wait times as they wish to be served first. Inbound customers with a low score may feel frustration as they have to wait long times, however inbound customers with a high score are served first, which may reduce customers frustration.

Outbound Customers
![github](https://github.com/AndrewDucDanhDo/Information_System_Development_Methodologies/blob/master/images/empathy_map_out_bound.jpg)

Outbound customers receive calls from the travel company. They may feel frustration if they constantly receive calls from the travel company, however they may feel happy receiving offers for potential holidat packages. Outbound customers are often influenced by friends and family who have purchased holiday packages. Other individuals may often influence their decision making when looking for potential holiday packages.

Travel Company
![github](https://github.com/AndrewDucDanhDo/Information_System_Development_Methodologies/blob/master/images/empathy_map_travel_company.jpg)

The travel company perform business operations such as sales and marketing. They may feel immense pressure due to having various activities to overlook. They may be concerned with the current system as customers may hang up after waiting for a long time, which can cause a loss of customers. The travel company may feel pressure to create competitive advantage and compete with other travel companies. They often hear complaints from customers as well as feedback. They are often concerned about seeing customer satisfaction through using their services. In order to reduce any business pressure, the company should consider investing in a new information system in order to attract customer loyalty and improve business operations.

### Point-of-View Statements: ###
* Relationship Managers (RMs) need a system to control call flow for inbound and outbound calls so that the amount of calls can be effectively managed.
* RMs need a system that will match RMs and end-customers according to the RM’s skills and customers profiles so that a suitable service can be provided.
* RMs need a system that segments customers into social and cultural groups according to their postcodes and surnames so that they can be matched with suitable customers and the chances of achieving a sale or providing a service is increased.
* RMs need a system that builds a profile and skill matrix based on a questionnaire so that it provides an initial RM profile for the matching technique.
* RMs need a system that targets potential buyers with outbound calls so that it can optimise its customer service.
* RMs need a system that dials numbers automatically according to a generated customer target list so that the calling and matching process is automated.
* RMs need a system that has a call routing and distribution routine so that it minimises inbound call costs by reducing per-call handling time.
* RMs need a system that calculates a skill score based on the RM’s previous call duration and profile so that RM’s can be ranked on quality of performance.
* RM’s need a system that scores a customer from 1-10 based on the likelihood to purchase the product so that customers with the highest score can be served first.
* RM’s need a system that directs customers to an Interactive Voice Response unit prompting them for options or verbal responses and then redirects the call to an Automatic Call Distributor to be matched with an RM so that during busy times, all customers can be provided service and updates on their current position in the calling queue.
* Customers need a system that redirects their customer inquiries to a suitable RM so that they can have their queries answered.

### How Might We Statements: ###
* How might we improve call routing and dynamic call flow control for both inbound and outbound calls?
* How might we segment customers into social and cultural segments according to their postcodes and surnames?
* How might we provide assistance to RMs in serving  their end-customers?
* How might we create a supporting tool to  create customer profiles?
* How might we improve who is served first?
* How might we create a questionnaire that builds an employee profile and skill matrix?
* How might we provide RM’s with guidelines and a script to help in providing improved service to the end-customer?
* How might we change the way a customer is scored?
* How might we create a target list for each RM based on their skills and profile?
* How might we ensure that our customers are always kept happy and satisfied?
* How might we direct inbound customers to an Interactive Voice Response unit / Automatic Call Distributor?
* How might we prevent customers hanging up from long wait times?

### User Stories: ###
* As a customer, I want to speak to a relationship manager who has knowledge about my destination so that I can better decide if I want to purchase a holiday package
* As a relationship manager, I want to be matched with customers based on my skills so that I am more likely to achieve a sale
* As a customer, I want to be able to served as soon as possible so that I am less likely to experience a long wait time.
* As a relationship manager, I want to serve the customer with the highest score first so that I can maximise customer loyalty. 
* As a customer with a large score, i want to be able to ensure that i will have minimal waiting time so that i am able to make my booking faster.
* As a relationship manager i want to make sure the 'profiler tool' operatres smoothly so that customer profiles can be created.
* As a customer, i want to fill out the 10 minute questionnaire truthfuly and swiftly so that i will be used to build a profile and place me in the correct skill matrix.
* As a relationship manager, i want to successfuly speak to outbound customers enticingly so that i can attempt to make them inbound customers. 
* As a relationship manager i want to improve the call flow rate so that customers are matched based on RM performence and product knowledge. 

## **5. Design Thinking** ##
According to the Empathy Map, Relationship Managers are overwhelmed with the amount of customer calls and require a system that automates the call routing and control. Additionally, their customer service quality is insufficient due to the mismatch of the relationship manager's skill level and experience with the customer's level of query. Meanwhile, customers are frustrated with the inadequate quality of the travel company's customer service and the wait time during busy periods.
 
In defining the travel company's situation, key stakeholders from the travel company include the Relationship Manager, who requires a system that improves call routing and dynamic call flow control for inbound and outbound calls, and the End-Customer, that requires a call management centre with automated call service options, low wait times, and improved customer service quality. The travel company's issues stem from the disproportionate skill levels of the relationship managers, the complexity of the customer's query, the over-abundance of customer calls, the ability to provide customers with the correct information from a skilled relationship manager, the absence of a customer prioritisation system and the lack of an automated system to accommodate peak customer calling periods.
 
Potential solutions to these aforementioned problems include implementing a multi-faceted system that accommodates for the relationship manager's need for a call routing control system, the travel company's need for a manager-customer profile matching system and the customer's need for an automated voice response system.


## **6. Agile Methodologies** ##
The team has used the Agile Methodology to continuously develop the following report, situational analysis, models, diagrams and benefits for the proposed call management system. Iterations are conducted through weekly virtual online team meetings where individual progressions are voiced, potential issues are raised and tasks are assigned for the following scrum iteration. Consequently, the agile process fosters growth, team coordination, communication and understanding of the current status of the project according to changing requirements, newly found insights, emotional and mental workloads, and learning points. Each individual within the team is self-organised meaning that given their task, they have the decision on how they would like to accomplish their work. Assigned roles for this project are as follows: the Product Owner (Subject Coordinator), the Scrum Master (Andrew Do), and the Development Team (Adam Kondonis, Louis Henderson, and Nimrod Ktalav). The product owner will be liaised with if any issues or additional inquiries are required for the report, the scrum master is responsible for ensuring that scrum is used and that the development team is able to self-organise themselves and the development team is collectively responsible for the performance and progression of the project.

Scrum is defined by the development process that is unpredictable and requires adaptation. The weekly sprints for this agile process were the periods that each task is assigned from the backlog. Each sprint involved furthering the development and understanding of the call management system. At the beginning, a sprint planning forecasted the product backlog of items that needed to be completed including the problem analysis, design thinking process and required model diagrams. The sprint review was taken place to ensure that the project is aligning with the user requirements from the product owner. Lastly, the sprint retrospective occured at the end of each sprint to examine the ways that the team could improve the features of the call system. With each backlogged item, there is an associated user story as shown in Section 8. The finalisation of the agile process occured when every member of the team has unanimously agreed that there is no more work to do. These guidelines were followed through the entirety of this project as shown in the github version control, the backlog of issues and the continuous development of models using draw.io. 

## **7. Key Assumptions** ##
*	The company will continue to operate during the switch of new information system
*	A business plan was created before implementation
*	Supporting tool to create customer profiles exists (Profiler tool). 
*	Customers will continue to shop with the travel company after the system is in place
*	The new and improved system will have no malfunctions 
*	The system will attract new potential buyers
*	The system will serve those with the highest scores first  
*	The systems ‘know’ the scores of each customer
*	The system ‘knows’ when it is too busy and must re-direct customers to the interactive voice response control. 
*	The new system will adjust the call flow rate to suitable Relationship Managers (RM)
*	The company has resources to make the new system
*	The company has the finances to fund the new system
* Expertise is available for the creation of the new system


## **8. Workproducts & Models** ##
### User Stories: ###
* As a customer, I want to speak to a relationship manager who has knowledge about my destination so that I can better decide if I want to purchase a holiday package.
* As a relationship manager, I want to be matched with customers based on my skills so that I am more likely to achieve a sale.
* As a customer, I want to be able to be served as soon as possible so that I am less likely to experience a long wait time.
* As a relationship manager, I want to serve the customer with the highest score first so that I can maximise customer loyalty. 
* As a customer with a large score, i want to be able to ensure that i will have minimal waiting time so that i am able to make my booking faster.
* As a relationship manager i want to make sure the 'profiler tool' operatres smoothly so that customer profiles can be created.
* As a relationship, I want to fill out the 10 minute questionnaire truthfuly and swiftly so that i will be used to build a profile and place me in the correct skill matrix.
* As a relationship manager, i want to successfuly speak to outbound customers enticingly so that i can attempt to make them inbound customers. 
* As a relationship manager, I want to improve the call flow rate so that customers are matched based on RM performence and product knowledge. 
* As a relationship manager, I want to ensure that customers are receiving promotional offerings so that the travel company can maximise our product offerings.

### Use Case Diagrams ###
#### Use Case Diagram #1: Inbound ####
![github](https://github.com/AndrewDucDanhDo/Information_System_Development_Methodologies/blob/master/images/use_case_diagram_inbound.png)

Inbound calls are incoming calls, which are generally from existing or potential customers, where the relationship manager will respond to queries. This use case diagram shows the interaction between the system, the relationship managers and in bound customers. 

Additionally, this diagram further shows how a customer (or potential customer) will attempt to contact the travel company with a query or intention to purchase a holiday package. The inbound customer’s question may be answered by an automated bot or redirect them to their website depending on the inquiry. If the enquiry gets answered by the chat bot, they may hang up, If the customer ends up talking to a relationship manager about purchasing a holiday package, the customer will be asked to take a 10-minute questionnaire to build a profile which then ultimately becomes stored in the system database. Depending on the loyalty of the customer, the system will create a score for the customer which get stored in the database and will then help them get their questions answered quicker depending on their respective score. 
#### Use Case Diagram #2: Outbound ####
![github](https://github.com/AndrewDucDanhDo/Information_System_Development_Methodologies/blob/master/images/use_case_diagram_outbound.png)

This use case diagram shows how the relationship managers will attempt to contact potential customers by calling them from their target list and ask if they are interested in the holiday packages available. If they are, ask the customers to complete a 10-minute questionnaire which will allow the company to profile the customer and store their details into a system database which will hold all of their respective data including a score to match their loyalty


#### Class Diagram ####
![github](https://github.com/AndrewDucDanhDo/Information_System_Development_Methodologies/blob/master/images/class_diagram.png)

A class diagram represent various aspects of the system and are used to model the structure of the system. Thus, this diagram defines the overall structure of the system and the relationship amonst objects.

#### Activity Diagram ####


#### Collaborative Diagram ####
![github](https://github.com/AndrewDucDanhDo/Information_System_Development_Methodologies/blob/master/images/collaborative_diagram_inbound_customer.png)

![github](https://github.com/AndrewDucDanhDo/Information_System_Development_Methodologies/blob/master/images/collaborative_diagram_relationship_manager.png)


#### Sequence Diagram ####


## **9. Advantages** ##
Competitive advantage refers to an advantage gained over competitors by offering a greater value to consumers compared to other competitors within the market. Competitive advantage is essential in order for a company to distinguish their products and services from other competitors.

Competitive advantage could be achieved through the implementation of a new system for the travel company, which can result in new opportunities for the company.

THINGS TO DISCUSS IN ADVANTAGES:
- address the problems with current system
- address how new system can overcome these issues
- make links to problem definition

## **10. Conclusion** ##
