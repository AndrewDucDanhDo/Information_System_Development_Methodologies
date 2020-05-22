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
A major travel company currently uses an in-house call management centre to make sales with customers who wish to travel. The current system is complicated, unreliable and slow, which can delay business operations for the travel company. Hence, the project objective is to develop a more reliable and intuitive information system for both customers and relationship managers in order to improve business operations of their in-house call management centre. A stakeholder analysis must be conducted in order to clearly define stakeholder requirements and to meet the objectives of the project.
 
In order to achieve the desired outcomes of the project, it is crucial to ensure that the project is in reach of our budget and that enough time is allocated to tasks to ensure that there is enough time to complete tasks.
 
Goals are SMART: specific, measurable, achievable, Relevant and timely. In order for the project objectives to be met, a logical strategy must be implemented and followed in order for goals to be met.
 
A major travel company would like to develop a more intuitive and reliable system for both relationship managers and customers. Hence one of the project objectives is to develop a more reliable system to support relationship managers and customers. Goals can be measured through tracking progress. By committing changes on GitHub, progress can be measured and the team can track. In order for the goal to be achieved, the team must collaborate together and work on achieving the goal. This can be done through assigning tasks to different team members, hence the completion of certain tasks can be effectively achieved through assigning different roles to different team members.
By creating a time plan and allocating time for each task, the team can ensure that tasks are completed within the given timeframe.


## **3. Problem Definition** ##
A major travel company uses a call management centre as a way of attempting to sell holiday packages to people who want to travel. They want an information system to be developed which will improve the overall operation of their call management centre. 
 
The main features of this system would include: matching relationship managers (RM) and customers based on their profiles such as RM skills and customer’s post codes; creating a profile for each RM which details their skill matrix and adjusts based on how they perform in selling products; generating a target list where RMs need to do outbound calls for potential customers; assigning customers a score based on how likely they are to make a purchase which determines how long they need to wait before talking to an RM; and directing customers to an Interactive Voice Response Unit before being redirected to an RM during busy times.

Without these features, it is assumed that the company’s call management centre has difficulties in their overall performance, where relationship managers would be more likely to talk to customers who will most likely not purchase a holiday package. This means that the travel company is less likely to reach their target customers, which can be accentuated by the current call rate, call routing and dynamic call flow control processes. These circumstances would result in the company’s targeted customers to purchase from a different company that would probably use a system which is more efficient in enabling customers talking to sales employees.




## **4. Stakeholders** ##
### Empathy Maps: ###
Relationship Managers
![github](https://github.com/AndrewDucDanhDo/Information_System_Development_Methodologies/blob/master/images/RM.jpg)

Inbound Customers
![github](https://github.com/AndrewDucDanhDo/Information_System_Development_Methodologies/blob/master/images/Inbound.jpg)

Outbound Customers
![github](https://github.com/AndrewDucDanhDo/Information_System_Development_Methodologies/blob/master/images/Outbound.jpg)

Travel Company
![github](https://github.com/AndrewDucDanhDo/Information_System_Development_Methodologies/blob/master/images/Travel%20Company.jpg)

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
* As a customer, i want to fill out the 10 minute questionnaire truthfuly and swiftly so that i will be used to build a profile and place me in the correct skill matrix.
* As a relationship manager, i want to successfuly speak to outbound customers enticingly so that i can attempt to make them inbound customers. 
* As a relationship manager i want to improve the call flow rate so that customers are matched based on RM performence and product knowledge. 
* 

## **9. Advantages** ##


## **10. Conclusion** ##
