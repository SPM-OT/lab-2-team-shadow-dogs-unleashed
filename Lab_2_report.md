



# iPad Restaurant Application

January 29th, 2020
Team Shadow Dogs UNleashed



Submitted by:
Ethan Bautista 100657250
Saood Imran 100620420
Yale Wang 100673933

### Introduction & Why We Chose this Topic

This purpose of this project is to create an application that replaces and improves upon the conventional menus used in a restaurant. We envision the application to be more effective at capturing customers’ requests accurately as well as more clearly displaying the menu items to the customer.

We chose this topic because the end result will be a product that has a lot of real-life applications. Owning a restaurant is a difficult business, so any solution that reduces costs will greatly affect the restaurant’s success. We envision our final product to both reduce the time it takes to create or make changes on the menu, reduce the time it takes to make an order when using the menu, and reduce the time it makes decisions for the restaurateur in deciding which menu items to keep and/or remove. 

In addition to reducing the speed, our application can also reduce the need for servers. Since a big part of a restaurant’s costs is to pay employees, reducing this cost will be a big benefit. The application also reduces the need for highly-skilled employees. All of these time-saving, cost-reducing positives make this project appealing to all restaurants and appealing to us due to its demand.

### Problem Description
The problem with conventional menus on paper or other physical medium is manyfold. First, menus are incorrigible. A menu design already requires a long time to create, but after a design is implemented, there is no chance to change it without the use of ugly tape and writing over it entirely. This problem is made simple in a software-based menu. Our application will have a backend database with all the menu items, their descriptions and images attached - all of which can be changed at any point, and the iPads will reflect that change immediately. In mentioning descriptions and images, a major drawback of using physical menus is that there is limited space; a page cannot have more or less space than is included. Designing menus requires a lot of time partly because there must be a balance between aesthetic appeal and space required. If your menu has a lot of images, it will be more appealing, but it will mean the menu is thicker, and not only more difficult to read through, but more costly to create.

With respect to creating the menu, our application with eliminate the need to print menus, which is wasteful, something that’s more important in a time where environmental conscientiousness is high. When the menus are created, the workflow of ordering depends on the clarity of the customer’s orders as well as the skill of the server involved. This is problematic since in high-pressure situations, such as a busy dinner shift, there could be a high-volume of orders, which increases the likelihood of a mistake being made. Such mistakes are costly, and have long-lasting effects beyond just recreating the dish. This problem is eliminated by having the orders go directly from the customer to the kitchen without any human in-between.

One possible downside to our iPad application is that replacing the human element could potentially reduce customer-employee interactions. This factor could be a part of maintaining customer loyalty, but we believe that the positives outweigh this potential downside.

Our application also aims to accomplish tasks that are impossible for a conventional menu. For example, we mentioned above that a restaurant owner must choose between creating an aesthetically appealing menu and being concise. In our application, there is no need to conserve space since a scrolling menu in the application can have potentially infinite page-space. This does not run into the same problem as conventional menus in terms of readability since there can be tags where a customer can search and other organizational constructs such as subheadings and drop down menus. Our design also hopes to include a feature to show items in a 360 degree view, allowing more customer satisfaction. 

### Objectives
The objective of this project is to create a menu system to replace the old fashioned and time consuming menu system. Restaurants are able to create their own customizable menu through this app in which they can change the menu whenever they see fit. The food is categorized into their own categories for ease of use for the customer. Customer orders are immediately sent to the kitchen so the chefs are able to prepare the food immediately and avoid any ordering errors. Customers are able to rate the food they ordered to provide feedback to the restaurant and future customers. This new menu system will reduce the total cost of running the restaurant as it will eliminate ordering errors and reduce the number of employees.

### Measure of Success
There are a few ways to measure the success of our design. As the business we are operating in is a restaurant, the majority of them relate to the ease of use of the application and customer satisfaction while dining. Additionally, we must account for the viability of the project: will it truly make us more money? What is the break even point? Will it increase customer retention? These are the topics around which our metrics must be based. 

To that end, we must make sure that the cost of creating the app is less than the cost that would be incurred by creating new menus every year or when a new item is added. Additionally, to maintain customer satisfaction and reduce business losses, we must aim for a 0% error rate in product selection and creation. That is, the customer must be able to clearly view the item he is purchasing so that the kitchen can accurately create it. This will drive down costs from incorrect orders and also reduce customer dissatisfaction. If the money saved due to these two new changes is significant enough to offset the initial startup, the project can be considered a success on these measures alone.

From a development perspective, we know that the application must allow for a clear description of the item and all its relevant tags in an organized and easy to read manner. The menu has also to offer multiple visuals of the product and preferably also in video format so that the customer knows what they are purchasing. This can be considered a success if the customer is able to view the full description of an item, minus its reviews, on a single screen without scrolling. The reviews can be read via scrolling down. Additionally, the user must be able to return to his previous list of items by pressing the back button after having selected any single item to view detailed information about. 
The success of these measures can further be traced via a post meal voluntary survey, where the customers can rate their experience using this new system. When the supermajority (75%) of customers rate the new experience as pleasant, we will know that the project is a success.


### Infrastructure 
Our application stack will be (from the bottom-up) MySQL database to store all data, Node.js to run server-side communications, with open channels to communicate via HTTPS, accessed by an Angular.js application that is customer-facing and an Apache webserver used by the kitchen to communicate with the backend application. The webserver and database will be hosted on Amazon AWS servers (lowest cost for low-bandwidth usage). The customer-facing app will be developed in Swift. The kitchen app will be developed in Java. 

Our customer-facing app will use WIFI only Apple 10.2-inch iPad (32GB), the cheapest iPad and the best-performing tablet.
