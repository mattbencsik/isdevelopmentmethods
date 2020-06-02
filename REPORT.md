# System Redevelopment Report for Call Management Centre 

Presentation: https://youtu.be/3FN3XoITqWw 

## Statement/Problem

A major Travel Company is wanting to improve their customer service during their inbound and outbound calls, which involves the process of selling travel holiday packages to customers (or potential customers). Currently, call flow rates haven't been effectively adjusted to suitable Relationship Managers (RM) and the system operation is overcomplicated by the variation of holiday packages available. Their aim is to implement a system that will provide assistance to RM's in serving customers, as well as routing calls between high level RM's and customers. This will be executed through a Skill Matcher system that will match customer profiles using a 'Profiler Tool', with the RM's built profile and skill matrix. Subsequently, this will help maximise the performance of RM's during their calls, by matching their product knowledge and skills with the end buyer(s) and thus improving customer satisfaction and ultimately leading to an increase in sales. 


## Objectives

- Increase purchases of holiday packages by 20% in the next 2 months during inbound and outbound calls
- Decrease per-call handling time so that RM's are more efficient during their shifts (increase call rate per day)
- Increase customer retention by matching high skilled and appropriate RM's to the customer 
- Improve the quality of the customer service by providing RM's with a script and guidelines that suits the customer's enquiry
- Continuously update RM skill score after each call performance to have the most accurate data in the system

## Stakeholders

Stakeholders are any individual or parties that are directly affected by the final outcome of a product or system, and for the CMC, there are a variety of stakeholders. 
 
The Relationship Manager (RM) is a key stakeholder that is responsible for the selling of a holiday package to a customer through the communication means of telephone call; either an inbound or an outbound call. An RM uses a script or guideline, provided by the system, to help improve the overall customer service in the process of selling a holiday package to the customer. The RM's are ultimately responsible for the selling of a holiday package to a customer. 
 
A second stakeholder is the customer who either receives a phone call from an RM to purchase a holiday package or the customer calls the centre and notifies the RM of their desire to purchase a holiday package. The system ranks them with a score between 1-10; the higher the score, the higher the likeliness of a customer to purchase a package, and thus can determine the amount of sales for the CMC. 
 
Another stakeholder is the system developer. The developer is responsible for ensuring the system is maintained of the highest quality and efficiency. They create the guideline or script that an RM uses to help facilitate the sale of a holiday package to a customer. Also, the developer must ensure the confidential information of customers is safeguarded. The developer needs to  ensure the system matches a RM to a customer based on the RM's skill levels to increase overall efficiency of a potential sale. The Interactive Voice Response must also be maintained so that during high-traffic periods so that the customer can be transferred to the next best-matched available RM.
 
The system that is the backbone of the call management centre that is essential for running the business. It forwards calls to match RM's with great product knowledge and conversational skills through a target list with customers to ensure the highest possibility of a potential sale. Furthermore, the system has a Profiler Tool. This stores both personal information and experience of an RM to ensure they are matched with the right customer on either an inbound or outbound call. The system also uses a call routing mechanism which helps minimise costs of calls inbound to the business to help with overhead cost management. It also makes a criterion for a customer, which ranks them with a score from 1-10, based on their likelihood to purchase a product. 


## Assumptions

1. The telephone number provided to customers does not direct them to a specific RM, rather directs them to the Automatic Call Distributor. From here they will either be directed to an RM via the Skill Matcher, or to the Interactive Voice Response.
2. There are different RM departments, specialising in different areas of customer care and travel knowledge. For example, one department may specialise in 'Hiking Trips' and issuing refunds.
3. There is a group of superior, high-ranking RMs. These RM's are the head of each department, and have high levels of expertise across multiple areas. High ranking customers will be directed to them. (A high score means between 7-10)
4. One element of the system is the Skill Matcher. This comprises of the profiler tool, RM profiles and customer profiles and deals with inflows of data. 
5. The system prioritizes inbound calls. During quiteter periods RM's will request a customer target list, and the Skill Matcher System will automatically dial a potential customer and display a script. 
6. The Skill Matcher system considers customer scores between 7-10 to be high scores.
7. The interactive voice response may alter the decision made by the Skill Matcher on which RM they may be directed to, as it extrapolates information about the reason for a customer call. 
8. RM's have the capability to transfer calls within and across departments, should they find a customer inquiry does not suit their area of expertise. This customer will be placed to the front of a queue. 
9. There is an external actor, Online Banking Tool, where payments are handled. The RMs deal directly with this service.
10. After a call has taken place, an RM will fill out a brief form to assist the system in updating customer and RM profiles.


## Backlog

**User Story** | **Priority** | **Solution**
------------ | ------------- | -------------
As a Relationship Manager, I want to be matched with customers based on my knowledge and skills, so that I can give customers useful information. | High | Customer-RM profile/skill matcher
As a customer, I want to talk to someone with relevant knowledge, so that I can make an informed purchase decision. | High | Interactive Voice Response/Call Distributor, RM-Customer Profiling
As a Relationship Manager, I want to know about the customer I am calling, so that I can tailor my service to the individual. | High | Customer profile
As a customer, I want to be quickly directed to a person, so that I do not waste time on hold. | High | Call routing and distributing
As a customer, I want to talk to an employee I have previously met, so that I can make another purchase of a holiday package. | High | System generated RM skill-score, Customer profiler
As a Relationship Manager, I want to measure my sales performance, so that I can track areas for improvement. | Medium | Solution: System generated RM skill-score/profile generation.
As a Relationship Manager, I want to be able to call potential customers, so that I can increase my likelihood of sales. | Medium | Target list
As a Relationship Manager, I want guidance on what to say to customers, so that I can improve my service. | Medium | A script provided when calling customers.
As a customer, I want to be recognised for my loyalty to the business, so that I can feel appreciated. | Medium | Likelihood to Purchase customer scoring/call distribution


## Point of View: 
POV | Customer | Relationship Manager
------------ | ------------- | -------------
**User** | the end-customer (or potential customer) that wants to purchase a holiday package | the RM from the call management centre trying to sell holiday packages 
**Need** | customer's need RM's with high level skills and knowledge (eg. knowledge of the particular destination they are wanting to travel to) | to grow knowledge and deliver high level information to the right customer
**Insight** | customers aren't being convinced enough by RM's performance in selling packages during their calls. | currently RM's aren't performing to their best standard and current sales have been stagnant 


## How Might We (HMW) Statements:

- How might we improve RM empathic intelligence  
- How might we improve RM communication skills and product knowledge
- How might we improve customer satisfaction without face-to-face interaction
- How might we increase customer retention in the long term
- How might we provide a competitive edge from other competing services 


## Design Thinking

Our project exploits a design thinking approach, which is a non-linear, solution-based process to solving problems. It iterates through stages of empathy, problem definition, ideation, prototyping and testing with aim to obtain a final product.

During the empathy stage, empathy maps were created to further analyse the stakeholders and their views. We gathered that the RM was mainly concerned with the customer, their rating and selling to them. Whereas, customers focus on themselves; budget, potential enjoyment, and experiences. System developers’ primary goal is to develop a functional system, under time and cost constraints, aiming to satisfy their customer. Finally, the system empathy map shows both the problems encountered and the gains made from the use of the system.

Empathising led us to define the problem, starting with the POV statements of the Customer and RM. These are inferences made based on empathising stages (and later stages of design thinking). The customer reveals a need for highly skilled and knowledgeable RM’s who can effectively inform them of their travel package. An insight from customers is that they are limited by the RM’s performance and thus will be unconvinced to purchase the package. Whereas, insights from the RM show potential underperformance and therefore, need to boost their delivery skills and knowledge. Then the backlog of user stories was created and prioritised to help define the problem at hand.

In the ideate stage, HMW statements were made which spark inspiration for solutions. The iterative nature of design thinking allowed us to redefine the problem and improve the objectives in the previous stage. As it is difficult to test an intangible prototype, models are analysed to further improve ideas and better understand the problem and perspective of the users.


## Scrum Methodology

Scrum is an iterative and incremental process used in projects with activities undertaken to ensure requirements and solutions are constantly evolving. Although an application was not being developed, GitHub and Scrum methodologies were used to understand Agile in the industry. The iterations were made by separate branches in GitHub, recording the logic using commit messages. The backlog of user stories followed by POV and HMW statements correlate to the stages before the scrum sprints. The next stage of models and prototypes were built to reflect the iterative sprints of the product being built considering a tangible product couldn’t be created.

GitHub allows for each team member to provide their own commits to the project which are reviewable before we merge them onto the branch. This gave us the extensibility when changes occurred and allowed us to easily adapt to changes in the requirements. Also, raising “Issues” makes it easier for members to view any problems, errors and thus, fix them in future iterations (robustness). Agile methods also require the team to track the progress tasks to be completed, in progress and completed. This is achieved in the projects tab of GitHub where cards can be created and assigned to prevalent sections.

## Competitive Advantages
 
Stakeholders are any individual or parties that are directly affected by the final outcome of a product or system, and for the CMC, there are a variety of stakeholders. 
 
The Relationship Manager (RM) is a key stakeholder that is responsible for the selling of a holiday package to a customer through the communication means of telephone call; either an inbound or an outbound call. An RM uses a script or guideline, provided by the system, to help improve the overall customer service in the process of selling a holiday package to the customer. The RM's are ultimately responsible for the selling of a holiday package to a customer. 
 
A second stakeholder is the customer who either receives a phone call from an RM to purchase a holiday package or the customer calls the centre and notifies the RM of their desire to purchase a holiday package. The system ranks them with a score between 1-10; the higher the score, the higher the likeliness of a customer to purchase a package, and thus can determine the amount of sales for the CMC. 
 
Another stakeholder is the system developer. The developer is responsible for ensuring the system is maintained of the highest quality and efficiency. They create the guideline or script that an RM uses to help facilitate the sale of a holiday package to a customer. Also, the developer must ensure the confidential information of customers is safeguarded. The developer needs to  ensure the system matches a RM to a customer based on the RM's skill levels to increase overall efficiency of a potential sale. The Interactive Voice Response must also be maintained so that during high-traffic periods so that the customer can be transferred to the next best-matched available RM.
 
The system that is the backbone of the call management centre that is essential for running the business. It forwards calls to match RM's with great product knowledge and conversational skills through a target list with customers to ensure the highest possibility of a potential sale. Furthermore, the system has a Profiler Tool. This stores both personal information and experience of an RM to ensure they are matched with the right customer on either an inbound or outbound call. The system also uses a call routing mechanism which helps minimise costs of calls inbound to the business to help with overhead cost management. It also makes a criterion for a customer, which ranks them with a score from 1-10, based on their likelihood to purchase a product. 
  

## Effects If The Project/System Fails
 
For the call management centre, there would be drastic effects to the business if the internal system fails.

There will be no computer matching between an RM and a customer. This means that random customers will call/be called by a random RM that are not best suited to aid the potentiality of a holiday package sale. This leads to no script/guideline appearing during an outbound call, which leads to decreasing the efficiency of the RM’s performance. This requires the employee to improvise and learn about the customer and their potential to purchase a holiday package during the call, decreasing overall customer relationship management.

Furthermore, during busy call times, there would be no ‘Interactive Voice Response Unit’ and thus no automatic call distributor to help queue and manage a large volume of customer calls. This will result in customers hanging up the phone if they are unwilling to wait in which they may not call back. Customers could move to competitor businesses, decreasing sales for the CMC.


Diagram | Link
------------ | -------------
**Empathy Maps** | https://miro.com/app/board/o9J_ksErVdY=/
**Use Case Diagram** | https://app.lucidchart.com/documents/view/717afc45-d047-45cf-bcb8-db5cb7128260#
**Inbound Activity Diagram** | https://app.lucidchart.com/documents/view/008d64da-691b-4486-be65-d36d17d19ab0
**Outbound Activity Diagram** | https://app.lucidchart.com/documents/view/a91ee78c-6a57-4384-8e85-2e2c7a804377
**Class Diagram** | https://app.lucidchart.com/documents/view/34ca8009-2f17-457c-ba90-75349f143d69/HWEp-vi-RSFO
**Inbound Collaborative Diagram** | https://app.lucidchart.com/documents/view/70212197-db0a-4785-b6d9-f15bdc9fed05#
**Outbound Collaborative Diagram** | https://app.lucidchart.com/documents/view/ac39b509-3d78-4a51-8c6c-da6260872f2d/0_0
**Inbound Sequence Diagram** | 
**Outbound Sequence Diagram** | 


