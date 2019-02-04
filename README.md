# Car_Service_Management_System
Project is a management system for Car repair and maintenance focused on Database operations 

Manage folder contains all the required functional flow
SQL folder contains the sql scripts to create, insert and delete data.

Project details:
Entities and the respective task performed by them.

Project deals with the development of Cars Service Management System. Application deals with following components - <br>
- Role based access to the task list <br>
- Car registration <br>
- Schedule / Reschedule service and see Service History <br>
- Inventory management of the tools required for the service<br>
- Tools ordering<br>
- Notifications in case of delay in order <br>
- Two services offered - Repair and Maintenance<br>
- Payroll management <br>
- View Profile and Update Profile<br>
- Add New Employee<br>

Tools and Technology - Java, Oracle sql database <br>
DBMS features used - DDL, DML, Triggers, Procedures <br>

*Customer*

The account for customers shall be created from the application. When logged in as a customer,
the homepage displays the following options:
● View and Update Profile : This will have the following sub-menus
○ View Profile: The logged in customer should be able to view his profile
information.
○ Update Profile: The logged in customer should be able to update his profile
information.
● Register Car: A customer should be able to register a car with a service center. He
should be allowed to only register cars that belong to an approved maker list (Honda,
Nissan, and Toyota)
● View and Schedule Service : This will have the following sub-menus:
○ View Service History : A customer should be able to see service history for his
car using the car’s license plate number.
○ Schedule Service : A customer should be able to schedule a new
maintenance/repair service appointment for his car using the car’s license plate
number. This will have the following sub-menus:
■ Schedule Maintenance
■ Schedule Repair
○ Reschedule Service: A customer should be able to reschedule a service
appointment for his car using the car’s license plate number.
● View Invoices : A customer should be able to view invoices billed to him.

*Receptionist*

The account for receptionist can be created only by the manager. When logged in as a
receptionist, the homepage displays the following options:
● View and Update Profile : This will have the following sub-menus
○ View Profile: After logging in a receptionist should be able to view his profile
information.
○ Update Profile: After logging in a receptionist should be able to update his
profile information.
● View Customer Profile: A receptionist should be able to view a customer’s profile
information.
● Register Car: A receptionist should be able to register a customer’s car for service. He
should be allowed to only register cars that belong to an approved maker list (Honda,
Nissan, and Toyota).
● View Service History : A receptionist should be able to see service history for all cars a
customer gets serviced at the current service center.
● Schedule Service : A receptionist should be able to schedule a new maintenance/repair
service appointment for a customer car using the car’s license plate number. This will
have the following sub-menus:
○ Schedule Maintenance
○ Schedule Repair
● Reschedule Service: A receptionist should be able to reschedule a service appointment
for a customer using the car’s license plate number.
● View Invoices : A receptionist should be able to view invoices billed to a particular
customer.
● Daily Task - Update Inventory : A receptionist should be able to run a daily task to
update the counts of parts to be used that day, basically adjusted (decrementing them)
to reflect the fact the parts will be removed and actually used that day.
● Daily Task - Record Delivered Orders : A receptionist should be able to run a daily task
to update the status of any pending orders whose items have arrived to “complete” and
update their counts. For any pending orders that have not arrived and are past the
delivery window change their status to “delayed” and generate a notification for the
manager.

*Manager*

The account for manager shall be created using SQL Scripts and not from the application.
When logged in as an manager, the homepage displays the following options:
● View and Update Profile : This will have the following sub-menus
○ View Profile: After logging in a manager should be able to view his profile
information.
2
○ Update Profile: After logging in a manager should be able to update his profile
information.
● View Customer Profile: A manager should be able to view a customer’s profile
information.
● Add New Employee: A manager should be able to add new receptionists and
mechanics at the service center he manages.
● View Payroll Information : A manager should be able to view the payroll information for
all employees at the service center he manages.
● View Inventory : A manager should be able to view the inventory for the service center
he manages.
● View and Place Orders : This will have the following sub-menus:
○ View Order History: A manager should be able to see order history for any
orders involving his service center.
○ Place Orders: A manager should be able to place orders for any part in the
inventory. He should also be able to add new parts to the inventory at his location
via this menu option. Whenever an order is placed this using this option, it will be
assumed that the part will be supplied by the authorized distributor only.
● View Notifications : A manager should be able to view all notifications generated at this
service center.
● Register New Car: A manager should be able to register a new car model from the
approved makers (Honda, Nissan, and Toyota) into the system and assign service
details for the new model.
● View Service Details: A manager should be able to see service details (service
schedule, parts required etc.) for all car models.
● View Service History : A manager should be able to see service history for any car
serviced at his service center.
● View Invoices : A manager should be able to view all invoices billed to any customer at
his service center.
