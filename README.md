# SRS

Software Requirements Specification
for
Takeout Ordering System
Version 1.0 Draft
Prepared by Alex van der Meulen for CEN 3073
Amimoto
04/24/22
 
Table of Contents
Table of Contents	2
Revision History	2
1.	Introduction	1
1.1	Purpose	1
1.2	Scope	1
1.3	Project Overview	2
1.4	Definitions	3
2.	References	4
3.	Specific Requirements	4
4.	Verification	10
5.	Appendices	11
5.1	Assumptions and dependencies	11
5.2	Acronyms and abbreviations	11

Revision History
Name	Date	Reason For Changes	Version
Alex van der Meulen	04/24/22	Initial Draft	Version 1.0 Draft
			








1. Introduction
1.1 Purpose
The system allows customers to place takeout orders without interacting with the front-of-house staff, who are often overwhelmed. In the takeout system, customers will be able to view allergy information for the different menu items. They will also be notified of the expected time at which they can pick up their order. The system will archive all customer orders. The proposed system will increase accessibility of ordering, customer satisfaction, business profits, and staff productivity.
1.2 Scope
Product Name
Takeout Ordering System
Overview
The system allows customers to place takeout orders without interacting with the front-of-house staff. In the takeout system, customers will be able to view allergy information for the different menu items. They will also be notified of the expected time at which they can pick up their order.
Goals
•	Customer satisfaction for takeout orders will increase by at least 25% following one month after the implementation of the system. This will be verified through surveys before the new system and after it is implemented and used.
•	Front of house staff productivity will be increased through the use of the system. Front of house staff will be able to take orders from dine in guests 30% faster on average, measured from the time the group sits down until the order is placed, after 3 months when the takeout ordering system is fully in use.
•	Business profits from takeout orders will be increased by at least 15% following three months after the system is implemented. Current records of takeout orders will be compared to new records that are archived by the system to verify.
Out of Scope
•	The system will not modify how front of house staff takes orders from guests who are dining in the restaurant.
•	The system will not save user accounts or information.
•	The system will not take reservations.
1.3 Product Overview
1.3.1 product perspective
 



 
1.3.2 Product functions
•	Receive takeout order from customer
•	Notify kitchen of takeout order
•	Accept payment information
•	Bill customer
•	Display menu
•	Display answer to frequently asked questions
1.3.3 User Characteristics
•	Customers: use system to place take-out orders.
•	Front of house staff: use system to identify orders and deliver to the appropriate customers.
•	Kitchen staff: Use system to receive orders.
1.3.4 Limitations
 
1.4 Definitions
Drop - start preparing a dish
Comp - give something away for free
Fire - Order that is given to start prepping food
In the weeds - busy or overwhelmed
2. References
Tony Manabe, restaurant owner
Andy Vullo, front of house staff
http://ibisworld.com 
Amimoto Facebook Page
3. Specific Requirements
  
 



Primary Actor	Use Cases
Customer	1. View menu
2. Order takeout
Kitchen staff	      3. Receive order
      4. Update ingredients
Restaurant Owner	      5. Change menu

UC ID and Name:	UC-1. View menu
Created By:	Alex van der Meulen	Date Created:	3/15/22
Primary Actor:	Customer	Secondary Actors:	
Trigger:	
Description:	A customer views a menu displayed by the ordering system
Preconditions:	PRE-1. A customer has accessed hte onlin eordering system
Postconditions:	POST-1. Menu is displayed to the customer
Normal Flow:	1.	A user accesses the system
2.	System displays the menu of available items
Alternative Flows:	1.	A user searches for menu items
1.1 Only desired items are displayed by the system
Exceptions:	
Priority:	Very High
Frequency of Use:	100+ times daily
Business Rules:	
Other information:	
Assumptions:	


UC ID and Name:	UC-2. Order takeout
Created By:	Alex van der Meulen	Date Created:	3/15/22
Primary Actor:	Customer	Secondary Actors:	Kitchen Staff
Trigger:	
Description:	A customer places a takeout order that will be received by the kitchen staff
Preconditions:	PRE-1. Items are available
PRE-1. Amimoto is currently taking orders
Postconditions:	POST-1. Kitchen staff receives order
POST-2. Item quantity in system adjusted
Normal Flow:	1.	A customer accesses the system
2.	Customer views the menu (UC-1)
3.	Customer selects item to order
4.	inputs payment method
5.	places order
Alternative Flows:	1.	customer does not input payment method
1.1. customer pays in store
Exceptions:	
Priority:	Very high
Frequency of Use:	20+ times daily
Business Rules:	
Other information:	
Assumptions:	

UC ID and Name:	UC-3. Receive order
Created By:	Alex van der Meulen	Date Created:	3/15/22
Primary Actor:	Kitchen staff	Secondary Actors:	Customer
Trigger:	
Description:	The ktichen staff receives a takeout order placed by a customer
Preconditions:	PRE-1. Customer placed a takeout order
Postconditions:	POST-1. Kitchen staff makes the order
Normal Flow:	1.	customer places order
2.	kitchen staff receives the order
Alternative Flows:	None.
Exceptions:	
Priority:	High
Frequency of Use:	20+ times daily
Business Rules:	
Other information:	
Assumptions:	
UC ID and Name:	UC-4. Update ingredients
Created By:	Alex van der Meulen	Date Created:	3/15/22
Primary Actor:	Kitchen staff	Secondary Actors:	
Trigger:	
Description:	The kitchen staff manually updates the ingredients available to the system
Preconditions:	PRE-1. The amount of ingredients available changed
Postconditions:	POST-1. Ingredient amounts are updated on the system
Normal Flow:	1.	kitchen staff is authorized by the system
2.	kitchen staff updates the amount of ingredients available
Alternative Flows:	1.	kitchen staff is not authorized by the system
1.1. kitchen staff cannot make any changes
Exceptions:	
Priority:	Medium
Frequency of Use:	Once daily
Business Rules:	
Other information:	
Assumptions:	

UC ID and Name:	UC-5. Change menu
Created By:	Alex van der Meulen	Date Created:	3/15/22
Primary Actor:	Restaurant owner	Secondary Actors:	
Trigger:	
Description:	The restaurant owner changes the available menu items or prices in the system
Preconditions:	PRE-1. Restaurant owner is authorized to change menu
Postconditions:	POST-1. Menu is updated
Normal Flow:	1.	Restaurant owner logs into the system
2.	Owner modifies available items/prices
3.	restaurant owner saves the changes
Alternative Flows:	1.	Restaurant owner does not save changes
1.1. menu is reverted to previous state
Exceptions:	
Priority:	Medium
Frequency of Use:	Once monthly
Business Rules:	
Other information:	
Assumptions:	
4. Verification
 



5. Appendices
5.1 Assumptions and dependencies
Customers will want to make takeout orders and use the system as opposed to calling the restaurant as they did before.
Customers will be able to use the takeout ordering system without needing help from any staff.
5.2 Acronyms and abbreviations
COGS - The cost of goods sold
FOH - Front of house
FIFO - First in first out
POS - Point of sale
BOH – Back of House

