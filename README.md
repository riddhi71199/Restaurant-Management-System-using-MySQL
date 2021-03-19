# Restaurant-Management-System-using-MySQL
Restaurant Management System is developed to automate the daily activity of a restaurant. The purpose of this system is to provide a service facility to the restaurant workers and also to the customers. This restaurant management system can be used by the employees in a restaurant to handle the clients, their orders, reservation and can help them easily find free tables or place orders.

The services provided are:

Customer information management
Employee information management
Menu information management
Inventory information management
Bill details
This restaurant management system is for a small-scale restaurant with only one location. The entities and their respective attributes required are as follows:

Employees – The restaurant needs a huge work force of competent and efficient staff to ensure the effective management of the restaurant. The restaurant must keep track of each employee’s ID, name, phone number and hire-date.
Attributes: ● Employee ID (number) e.g. 5683223 ● Employee Name (varchar) e.g. Vikrant ● Phone number (number) e.g. 9999988888 ● Hire-Date(date) e.g. 6/6/2015

The restaurant hires these employees and differentiates them into 3 categories based on their work:

a) Manager – The manager are the employees who manages and instructs waiters. The restaurant needs to store, for every manager, a personal number and contact number where they can be reached in case of emergency.

b) Chef – The chef are the members of the work staff whose job is to cook the meal and look after the customer’s requirements as per their desired cuisine.

c) Waiter – They are the employees who manage the day-to-day activities of the restaurant. They are an integral part of the efficient management of the restaurant affairs.

d) Employee – They are the employees who assist chefs and also assist waiters.

Customer– The customers are the people who come to the restaurant to eat delicious meal as per their desire. The restaurant needs to store customer ID, Name, phone number, address.
Attributes: ● Customer ID (number) e.g. 5683223 ● Name (varchar) e.g. Meghna ● Address (varchar) e.g. 14 pq rd, Kandivali ● Phone number (number) e.g. 9989998989

Inventory– The restaurant needs a variety of raw materials to prepare the items as per the customer. They need to store the details of every inventory such as inventory number, name, quantity left, last date of entry. They also need to keep a record of when a particular inventory was bought.
Attributes: ● Inventory no. (number) e.g. 27 ● Instrument Item name (varchar) e.g. Tomato ● Quantity left (number) e.g. – 4 kg ● Last date of Entry (date) e.g. 2020-02-15

Menu – The restaurant has the menu list where the manager can get the details of the food items. The restaurant needs to keep a record of the details of each item like ID, name, price and quantity. The restaurant needs to also keep a record of the items ordered by each customer.
Attributes: ● Item-no (number) e.g. 43 ● Item name (varchar) e.g. Shahi paneer ● Price (number) e.g. 343 ● Quantity (number) e.g. 2

Bill– Every customer need to pay bills after his or her meal. The restaurant needs to keep records of the bill ID, amount, method of payment.
Attributes: ● Bill ID (number) e.g. 99 ● Amount (number) e.g. Rs 650 ● Method of payment e.g. Google-pay

The cardinalities, relation, schema of the entities were further dertemined. They were also represented by using an E-R Diagram. The code for this was executed by taking the values/details of the entities and some SQL queries were written to check its working and do the analysis.
