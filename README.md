
The README.md does not contain screenshots, better check the word document.


# Task1

## Jumjum Ecommerce

Name: Jumjum Ecommerce

Description: Jumjum is an upcoming e-commerce platform in Egypt made specifically for tech sector. Jumjum will allow Software Engineers and IT employees to discover and explore Electronics, Stacks and Technologies Subscriptions, Deployment plans...etc, with a lot of offers and better navigation. Jumjum is expected to boost the developers’ productivity.

## Scrum Team

|No.|Name|Expertise|Role|
|--|--|--|--|
|01|Arnold|Frontend|Converts UI/UX into frontend code using ReactJS, Bootstrap, and HTML5|
|02|Shawky|Code Reviewer|Maintains source control and refining code|
|03|Hamdy|Backend|Creates API endpoints and ORM model connection to database|
|04|Huda|Software Architect|Designs and plans the software modules connections with each other|
|05|Beanuts|DevOps|Responsible for the deployment and monitioring the server requests and responses|
|06|Socrates|Unit Tester|Responsible for making unit tests on modules created and follow test-driven development process|
|07|Muller|API Tester|Makes sure API endpoints sending responses as required|
|08|Reem|Animator|Responsible for creating animated designs|
|09|Manuel|Senior UI/UX|User interface and experience design, Adobe XD, Figma|

## Stakeholders

|Name|Role|Availability|Influence|Engagement|
|--|--|--|--|--|
|Alex Sancho| Investor | Low | High | Keep Satisfied|
|Hansi Flick| Stakeholder| High| High| Actively Engaged|


## Product Vision

Sprint 1: Create a website that shows a marketplace tab which contains a lot of offers for technologies subscriptions, infrastructure plans…etc.
Create a website that has a homepage that contains details about the company and details about the website and what it offers, in addition to a tab that navigates to marketplace page which contains list of offers for technologies, subscriptions, infrastructure plans, and other products. It also contains a search bar that allows the user to search for the desired products by their name. In addition, it contains a filter bar that allows the user to show only relevant results in the marketplace based on his choices like showing subscriptions only, infrastructure plans…etc. The user also will be allowed to register on the website using his personal information like email, password, username. The user also will be able to log into the website using his personal information, which will allow him to interact with the website based on his login credentials. The user will be able to add payment methods to his account securely and use them to complete purchases from the marketplace products.

Sprint 2: Create a feed page that shows feedbacks of users about technologies subscriptions for example, comparisons, and suggestions between the users. In addition, there will be a dashboard for sellers that will allow them to add items that will be shown in the marketplace page and, they will be able to see their selling charts and numbers. There will be a customer feedback page where the user will be able to contact support team for enquires and assistance. The users and sellers will also be able to customize their profiles. Finally, there will be a blog page where users can post technical articles like feedbacks, comparisons, tutorials…etc.
## Story Points Estimation Convention

1-> Very Small User Story

3-> Small User Story

5-> Medium User Story

8-> Large User Story

11-> Very Large User Story

13 and above-> Extra Large User Story (needs to be broken into several tasks)

Each working day takes 3 story points.


## Ordering Product Backlog and Rationale

In the first sprint, we selected the homepage and logo to be the highest priority since they are the main component of our website, as it is the first page that the users will see when they open the website. Then, we selected the registration and logging in to be the following product backlog items in the priority in order to allow the user to log into the website and interact with its functionalities.  Then, coming to the main functionality of this sprint the user will be able to open the marketplace page which will allow him to explore several offers on infrastructures, subscription plans, technologies, and items as well, the user also will be able filter the results to show user selected tags like Items, or subscription plans…etc. Moving to the next PBI which is the searching functionality, it will allow the users to search for specific items using their title which will be shown in the marketplace page. The PBI are prioritized according to their added business value, the rest of the PBI are expected to be in the second sprint, since they have less business value than the first PBIs in the product backlog.
 
 

Product Backlog Item	Assignee
Logging In – Logging In Page Design UI/UX	Manuel, Arnold
Logging In – Logging In Page Implementation	Shawky, Hamdy, Huda
Logging In – Logging In Page Animation		Reem, Socartes
Registration	Hamdy
Search for Stacks, Technologies, Items, Subscriptions	Huda
Appealing Logo and Homepage	Manuel, Reem
Marketplace Page – Marketplace Subscription Implementation	Shawky, Beanuts
Marketplace Page – Marketplace Filter	Huda, Hamdy
Marketplace Page – Marketplace UI/UX Design	Reem, Arnold




# Task2
## Sprint duration Estimation
It is expected that the team can complete up to 37-39 story points in a sprint.
## Sprint workflow
 

## Workflow Rationale
When the sprint starts, the PBIs are presented inside a TODO state, when we start working on a PBI, we move them inside the In Progress state, then after finishing it; it will be moved into Code Review state where Shawky (Code Reviewer) will review the code finished. If there is a problem the PBI will be rejected and brought back to In Progress state, but if there are no problems with it, it will go to Done state to be deployed and uploaded to the production. Any PBI moved to Done state, it can’t be brought back to the other previous states. 
## Workflow rules
1)	Only Shawky (Code Reviewer) get assigned with the tasks in the Code Review state (Assign Issue to Someone)
2)	Only Shawky (Code Reviewer) approves the tasks in Code Review and verify them for deployment (Restrict who can move an issue) 
 
## Daily Scrum Document

Team Member	Question	Sunday	Monday	Tuesday	Wednesday	Thursday
Shawky	What did you do yesterday?	Designing the Registration page API endpoints	Implemented on the Registration page	Code Reviewing	Finished the Registration page	Deploying the finished PBI to production.
	What are doing today?	Implementing the Registration page.	Code Reviewing	Finishing the Registration page.	Deploying the finished PBI to production.	Beta testing
	Is there anything blocking you?	No.	Yes, a problem with the operations team.	No.	Yes, the server is down.	No.
Hamdy	What did you do yesterday?	Integration Testing	Implemented Logging In Functionality	Making Unit tests	Finishing the Logging In Functionality.	Making integration tests.
	What are doing today?	Implementing Logging In Functionality	Making Unit Tests	Finishing the Logging In Functionality.	Making integration tests.	Design the database
	Is there anything blocking you?	No.	No.	No. 	Yes, the development server was down.	No.

Team Member	Question	Sunday	Monday	Tuesday	Wednesday	Thursday
Manuel	What did you do yesterday?	Designing the UI/UX of the PBI	Writing ReactJS code	Code Reviewing	Unit Testing for the frontend code.	Deploying the finished PBI to production.
	What are doing today?	Writing ReactJS code	Code Reviewing	Unit Testing for the frontend code.	Deploying the finished PBI to production.	Beta testing
	Is there anything blocking you?	No.	No.	No.	No.	No.
Huda	What did you do yesterday?	Designing software modules architect	Maintaining implemented code	Reviewing code.	Reviewing server requests and responses	Making integration tests.
	What are doing today?	Maintaining implemented code	Reviewing code.	Reviewing server requests and responses	Deployment of new features	Design the database
	Is there anything blocking you?	No.	No.	Cloud services were down	Yes, the development server was down.	No.

## Sprint Document

### Sprint 1
Since this is the first sprint, there were no previous sprints.
On this sprint, we did the presented the following features
1.	Navigate the website’s homepage
2.	Create an account on the website
3.	Log into the website
4.	Navigate in the Marketplace tab
5.	Search by stacks technologies, products, subscriptions, infrastructure plans on the Marketplace.

 
### Sprint 2
In the previous sprint, we were able to deliver the following features
1.	Website’s Homepage
2.	Registration
3.	Logging in
4.	Marketplace page
5.	Searching and filtering in Marketplace page.
There were several problems that we faced during the previous sprint which were like with the operations team or with the development server, but these problems did not affect the sprint duration, as the team finished the sprint. This sprint gave us the first preview of our website since they are the main features in our website so far.

In this sprint the user should be able to
1.	Add payment method to his profile
2.	Checkout on his desired items to complete purchasing process
3.	The seller should be able to add items to his dashboard so that they will be presented on the Marketplace, and he will be able to find insights on his numbers.
4.	The user should be able to navigate to feed page where he can see comparisons and discussions on several products, infrastructure plans, subscriptions…etc.

There were several problems related to cloud hosting services and Jira Management, as the cloud hosting services went down for several hours and came back online shortly. In addition, that we had to re-open the sprint again from the Reports and Burndown charts as there was a task that was not completely finished. Moving on with the previous sprint, this sprint continues presenting main features as well, which are a part of the first release of our website.
