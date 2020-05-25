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
The system has Profiler Tool that creates profiles for the RM and customers.
The system produces a questionnaire and skill matrix of the RMs.
The system generates targetlist, guidelines and a script to assist RMs with their customer service.
The system generates a priority-based score for customers in which higher customer scores are served first.
The system has an Interactive Voice Response unit that automatically prompts the user for information while they are waiting in a queue.


Non-Functional Requirements | Purpose 
--------|----------------
Responsive | Because inbound customers can potentially be waiting in a queue when they call the CMC, the system's timeliness is essential to allocating suitable RMs and maximising potential travel package sale opportunities.
Usable | RMs require an user-friendly interface that provides easy-to-understand scripts and customer information to resolve customer inquiries efficiently.
Maintainable | System failures and bugs are inevitable; constant maintenance can mitigate these issues.
Data Architecture | Because the travel company manages several holiday package options, user profiles and performance reports, the system requires a logical structure for organising the data to prevent memory overflows.
Secure | The system handles user sensitive data that should adhere to the Australian Data Privacy Act 1988.

### Team Objectives ###
Team goals can be measured through Github's version control features and opened issues. In order for the goals to be achieved, the team will hold weekly meetings, commit an update for their assigned task to github at least once a week and comment on the opened issues if there are any inquiries. Each team member will be assigned a role with task responsibilities for this project, and the team objective to achieve an High Destinction for this report as well as satisfactory team collaboration and morale.

## **3. Problem Definition** ##
A major travel company uses a call management centre as a way of attempting to sell holiday packages to people who want to travel. They want an information system to be developed which will improve the overall operation of their call management centre. 
 

Without these features, it is assumed that the company’s call management centre has difficulties in their overall performance, where relationship managers would be more likely to talk to customers who will most likely not purchase a holiday package. This means that the travel company is less likely to reach their target customers, which can be accentuated by the current call rate, call routing and dynamic call flow control processes. These circumstances would result in the company’s targeted customers to purchase from a different company that would probably use a system which is more efficient in enabling customers talking to sales employees.


## **4. Stakeholders** ##
### Empathy Maps: ###
Relationship Managers
![github](https://github.com/AndrewDucDanhDo/Information_System_Development_Methodologies/blob/master/images/empathy_map_relationship_manager.jpg)

Relationship managers are responsible for performing sales on holiday packages, answer customer inquiries and building a profile matrix. They may often hear complaints from customers as well as customer feedback. Having an improved system can reduce the pain and pressure experienced by RMs.

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
* RMs need a system that builds a profile and skill matrix based on a questionnaire so that it provides an initial RM profile for the matching technique.
* RMs need a system that calculates a skill score based on the RM’s previous call duration and profile so that RM’s can be ranked on quality of performance.
* RM’s need a system that directs customers to an Interactive Voice Response unit prompting them for options or verbal responses and then redirects the call to an Automatic Call Distributor to be matched with an RM so that during busy times, all customers can be provided service and updates on their current position in the calling queue.

### How Might We Statements: ###
* How might we improve call routing and dynamic call flow control for both inbound and outbound calls?
* How might we create a questionnaire that builds an employee profile and skill matrix?
* How might we provide RM’s with guidelines and a script to help in providing improved service to the end-customer?
* How might we create a target list for each RM based on their skills and profile?
* How might we direct inbound customers to an Interactive Voice Response unit / Automatic Call Distributor?
* How might we prevent customers hanging up from long wait times?

## **5. Design Thinking** ##
According to the Empathy Map, Relationship Managers are overwhelmed with the amount of customer calls and require a system that automates the call routing and control. Additionally, their customer service quality is insufficient due to the mismatch of the relationship manager's skill level and experience with the customer's level of query. Meanwhile, customers are frustrated with the inadequate quality of the travel company's customer service and the wait time during busy periods.
 
In defining the travel company's situation, key stakeholders from the travel company include the Relationship Manager, who requires a system that improves call routing and dynamic call flow control for inbound and outbound calls, and the End-Customer, that requires a call management centre with automated call service options, low wait times, and improved customer service quality. The travel company's issues stem from the disproportionate skill levels of the relationship managers, the complexity of the customer's query, the over-abundance of customer calls, the ability to provide customers with the correct information from a skilled relationship manager, the absence of a customer prioritisation system and the lack of an automated system to accommodate peak customer calling periods.
 

## **6. Agile Methodologies** ##
The team has used the Agile Methodology to continuously develop the following report, situational analysis, models, diagrams and benefits for the proposed call management system. Iterations are conducted through weekly virtual online team meetings where individual progressions are voiced, potential issues are raised and tasks are assigned for the following scrum iteration. Each individual within the team is self-organised meaning that given their task, they have the decision on how they would like to accomplish their work. Assigned roles for this project are as follows: the Product Owner (Subject Coordinator), the Scrum Master (Andrew Do), and the Development Team (Adam Kondonis, Louis Henderson, and Nimrod Ktalav). 

The weekly sprints for this agile process are the periods that each task is assigned from the backlog. At the beginning, a sprint planning forecasted the product backlog of items that needed to be completed including the problem analysis, design thinking process and required model diagrams. The sprint review was taken place to ensure that the project is aligning with the user requirements from the product owner. Lastly, the sprint retrospective occured at the end of each sprint to examine the ways that the team could improve the features of the call system. With each backlogged item, there is an associated user story as shown in Section 8. The finalisation of the agile process occured when every member of the team has unanimously agreed that there is no more work to do. 

## **7. Key Assumptions** ##
* The travel company has sufficient funding to implement the new call management information system.
* The new call management system has within two to three years to implement the solution.
* The travel company has the resources to implement the new call management system.
* The Profiler Tool already exists, and will be incorporated into the new information system.
* Expertise is available for the creation of the new system


## **8. Workproducts & Models** ##
### User Stories: ###
* As a customer, I want to speak to a relationship manager who has knowledge about my destination so that I can better decide if I want to purchase a holiday package.
* As a customer, I want to be able to be served as soon as possible so that I am less likely to experience a long wait time.
* As a customer with a large score, I want to be able to ensure that I will have minimal waiting time so that I am able to make my booking faster.
* As a relationship manager, I want to make sure the 'profiler tool' operates smoothly so that customer profiles can be created.
* As a relationship, I want to fill out the 10 minute questionnaire truthfuly and swiftly so that I will be used to build a profile and place me in the correct skill matrix.
* As a relationship manager, I want to ensure that customers are receiving promotional offerings so that the travel company can maximise our product offerings.

### Use Case Diagrams ###
#### Use Case Diagram #1: Inbound ####
![github](https://github.com/AndrewDucDanhDo/Information_System_Development_Methodologies/blob/master/images/use_case_diagram_inbound.png)

This shows how a customer (or potential customer) will attempt to contact the travel company with a query or intention to purchase a holiday package. The inbound customer’s question may be answered by an automated bot or redirect them to their website depending on the inquiry. If chat bot cannot answer the query, the customer ends up talking to a relationship manager about purchasing a holiday package

#### Use Case Diagram #2: Outbound ####
![github](https://github.com/AndrewDucDanhDo/Information_System_Development_Methodologies/blob/master/images/use_case_diagram_outbound.png)

This use case diagram shows how the relationship managers will attempt to contact potential customers by calling them from their target list and ask if they are interested in the holiday packages available. If they are, ask the customers to complete a 10-minute questionnaire which will allow the company to profile the customer and store their details into a system database which will hold all of their respective data including a score to match their loyalty


#### Class Diagram ####
![github](https://github.com/AndrewDucDanhDo/Information_System_Development_Methodologies/blob/master/images/class_diagram.png)

A class diagram represent various aspects of the system and are used to model the structure of the system. Thus, this diagram defines the overall structure of the system and the relationship amonst objects.

#### Activity Diagram: Inbound Call ####
![github](https://github.com/AndrewDucDanhDo/Information_System_Development_Methodologies/blob/master/images/Activity%20Diagram%20Inbound.png)

#### Activity Diagram: Outbound Call ####
![github](https://github.com/AndrewDucDanhDo/Information_System_Development_Methodologies/blob/master/images/Activity%20Diagram%20Outbound.png)

#### Collaborative Diagram ####
![github](https://github.com/AndrewDucDanhDo/Information_System_Development_Methodologies/blob/master/images/collaborative_diagram_inbound_customer.png)

![github](https://github.com/AndrewDucDanhDo/Information_System_Development_Methodologies/blob/master/images/collaborative_diagram_relationship_manager.png)


## **9. Advantages** ##
Competitive advantage refers to an advantage gained over competitors by offering a greater value to consumers compared to other competitors within the market. Competitive advantage is essential in order for a company to distinguish their products and services from other competitors.

Competitive advantage could be achieved through the implementation of a new system for the travel company, which can result in new opportunities for the company. If the travel company were to implement a more reliable and intuitive system, this can allow the travel company to gain a competitive advantage over other travel companies. For instance, having a more reliable system would attract more customers compared to other companies who utilise a similar system to the current in-house call management centre. The new system can overcome certain issues with the current system such as long wait times for inboun customers. Hence, if the travel company were to implement a new information system, it can allow the company to gain a competitive advantage amongst other competitors within the market which can assist the company to improve their sales performance.

THINGS TO DISCUSS IN ADVANTAGES:
- address the problems with current system
- address how new system can overcome these issues
- make links to problem definition

## **10. Conclusion** ##
