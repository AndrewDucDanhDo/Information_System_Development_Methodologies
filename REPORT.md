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


## **3. Problem Definition** ##
A major travel company uses a call management centre as a way of attempting to sell holiday packages to people who want to travel. To ensure that sales are being made efficiently, customers are assigned a rank, where higher ranking customers will have priority in regards to how long they need to wait before being served. Their rank is based on factors, such as whether they are a repeat customer or what area they live in that determine how likely they are to purchase a holiday package. 
Additionally, inbound customers can talk to an Interactive Voice Response Unit during busy times. They may be asked why they called before being redirected to a relationship manager (people who sell holiday packages). These processes can be enough to influence customers to not purchase from this company where both the use of a phone system and customers waiting for a potentially long time would be perceived as outdated and unfair. This means that the travel company would struggle to compete against other companies who use modern systems to sell their products. 
 
Sales are also designed to be more efficient to make by matching relationship managers and customers based on factors such as skills and language proficiency. 
The travel company has a target list of certain potential buyers generated for each relationship manager based on their skills. This is used for outbound calls. However, since this technique in selling has a negative reputation for annoying people, it is very likely that a lot of potential buyers would not want to purchase a holiday package from this company. 
 
Therefore, the current use of a phone system which includes an Interactive Response Unit, determining which customers are served first, and a potential long waiting time can severely affect this travel company’s overall performance if an information system is not developed as a means of reducing the amount of customers lost.


## **4. Stakeholders** ##
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


## **5. Design Thinking** ##
According to the Empathy Map, Relationship Managers are overwhelmed with the amount of customer calls and require a system that automates the call routing and control. Additionally, their customer service quality is insufficient due to the mismatch of the relationship manager's skill level and experience with the customer's level of query. Meanwhile, customers are frustrated with the inadequate quality of the travel company's customer service and the wait time during busy periods.
 
In defining the travel company's situation, key stakeholders from the travel company include the Relationship Manager, who requires a system that improves call routing and dynamic call flow control for inbound and outbound calls, and the End-Customer, that requires a call management centre with automated call service options, low wait times, and improved customer service quality. The travel company's issues stem from the disproportionate skill levels of the relationship managers, the complexity of the customer's query, the over-abundance of customer calls, the ability to provide customers with the correct information from a skilled relationship manager, the absence of a customer prioritisation system and the lack of an automated system to accommodate peak customer calling periods.
 
Potential solutions to these aforementioned problems include implementing a multi-faceted system that accommodates for the relationship manager's need for a call routing control system, the travel company's need for a manager-customer profile matching system and the customer's need for an automated voice response system.


## **6. Agile Methodologies** ##


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
* As a customer, I want to be able to served as soon as possible so that I am less likely to experience a long wait time.
* As a relationship manager, I want to serve the customer with the highest score first so that I can maximise customer loyalty. 

## **9. Advantages** ##


## **10. Conclusion** ##
