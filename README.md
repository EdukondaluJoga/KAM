KAM website Hosted Link : https://kam-frontend.onrender.com/

The project Overview:

The Key Account Manager (KAM) Lead Management System is a comprehensive tool designed to support Key Account Managers in efficiently managing relationships with large restaurant accounts. The system offers various functionalities to streamline lead tracking, interaction management, and account performance analysis. Below are the key highlights and features:

Manager Tracking and Insights:
A dedicated List of Key Account Managers feature enables seamless tracking of all managers using the system.
Includes a search functionality to quickly find and review manager-specific details, recent activities, and overall performance.

Restaurant Directory with Roles:
A curated list of restaurants with detailed contact information is available for easy reference.
Clearly defines roles and responsibilities within the restaurant accounts, helping managers understand key stakeholders.

Interaction Logs for Comprehensive History:
A structured interaction log maintains detailed records of all interactions between KAMs and restaurants.
Tracks query status, pending resolutions, and follow-up requirements to ensure seamless communication and accountability.

Query Status and Follow-Up Management:
Enables managers to monitor query resolution progress, flagging unresolved or delayed queries for necessary follow-ups.
Enhances client satisfaction by ensuring consistent and timely communication.

Modern Technology Stack:
Frontend: Developed using Vit_React, integrating HTML, CSS, and JavaScript for a user-friendly and responsive interface.
Backend: Built with Node.js and Node Express, leveraging a SQL database to ensure robust data handling and quick access to information.

Enhanced User Experience:
Features an intuitive and interactive interface that simplifies navigation across multiple functionalities.
Designed to optimize workflow, allowing KAMs to focus on building strong client relationships while maintaining high efficiency.

System requirements:   basic PC with windows/Mac/Linux works with IOS/Android.

Installation instructions :  using command line tools or terminal download npm, node.js, sql, html, css, with javascript package.

Running instructions : go to backend folder KAM-restaurant-main and call npm i to install libraries and call npm start in terminal.
Now go to frontend folder Frontend and call npm i to install libraries and call npm run dev in terminal.

Test execution guide : you can use postman to test the app with backend folder or use hosted link to test the website and experience the website.

API documentation : 
1. Dashboard APIs

1.1 Get All Leads
	•	Endpoint: /api/dashboard/leads
	•	Method: GET
	•	Purpose: Fetches all leads (restaurants).

 1.2 Get Today’s Pending Calls
	•	Endpoint: /api/dashboard/today-calls
	•	Method: GET
	•	Purpose: Fetches all interactions scheduled for today that require follow-up.

 1.3 Get Recent Interactions
	•	Endpoint: /api/dashboard/recent-interactions
	•	Method: GET
	•	Purpose: Fetches recent interactions within the last 7 days.

1.4 Search Leads
	•	Endpoint: /api/dashboard/search
	•	Method: GET
	•	Purpose: Searches for leads by name, address, or KAM.

2. Contact APIs

2.1 Get Contacts by Restaurant
	•	Endpoint: /api/contacts/:restaurantId
	•	Method: GET
	•	Purpose: Fetches all contacts for a specific restaurant.

2.2 Create Contact
	•	Endpoint: /api/contacts
	•	Method: POST
	•	Purpose: Adds a new contact.

 3. Interaction APIs

3.1 Get Interactions by Restaurant
	•	Endpoint: /api/interactions/:restaurantId
	•	Method: GET
	•	Purpose: Fetches all interactions for a specific restaurant.

 3.2 Log New Interaction
	•	Endpoint: /api/interactions
	•	Method: POST
	•	Purpose: Logs a new interaction.

4. KAM APIs

4.1 Get All KAMs
	•	Endpoint: /api/kams
	•	Method: GET
	•	Purpose: Fetches all Key Account Managers (KAMs).

4.2 Create KAM
	•	Endpoint: /api/kams
	•	Method: POST
	•	Purpose: Adds a new KAM.

 5. Restaurant APIs

5.1 Get All Restaurants
	•	Endpoint: /api/restaurants
	•	Method: GET
	•	Purpose: Fetches all restaurants.

 5.2 Create Restaurant
	•	Endpoint: /api/restaurants
	•	Method: POST
	•	Purpose: Adds a new restaurant.

 5.3 Update Restaurant
	•	Endpoint: /api/restaurants/:id
	•	Method: PUT
	•	Purpose: Updates restaurant details.

Sample usage examples: Use the hosted Link for sample usage and examples.
