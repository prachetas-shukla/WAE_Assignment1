# BPMN Process Models - Exercise 1

Prachetas Shukla

This repository contains the BPMN diagrams for the three scenarios in Exercise 1. 

## Scenario 1: Employee Leave Approval

This diagram maps out how an employee's time-off request is processed. It starts when the employee submits the request. The HR system first checks if they have enough leave balance. If they don't, it sends a notification and the process stops there. If they do have enough balance, the request goes to the manager. From there, if the manager approves, the system updates the balance and sends a confirmation. If the manager rejects it, it just sends a rejection notification instead.

<img width="2502" height="726" alt="Scenario1_Employee_Leave_Approval" src="https://github.com/user-attachments/assets/49b5ef32-05f0-41c2-ab81-d82f5dc02983" />
 This diagram maps out how an employee's time-off request is processed. It starts when the employee submits the request. The HR system first checks if they have enough leave balance. If they don't, it sends a notification and the process stops there. If they do have enough balance, the request goes to the manager. From there, if the manager approves, the system updates the balance and sends a confirmation. If the manager rejects it, it just sends a rejection notification instead.

## Scenario 2: Online Purchase Order Processing

This model shows what happens when a customer places an order online. First, the system checks if the product is actually in stock. If it's out of stock, it notifies the customer and ends. If the product is available, it moves on to process the payment. If the payment fails, the customer gets an error notification and the process stops. If the payment is successful, the order is confirmed, prepared for shipment, and finally shipped out, ending with a shipping confirmation email to the customer.

<img width="3390" height="726" alt="Scenario2_Online_Purchase_Order_Processing" src="https://github.com/user-attachments/assets/8b941687-c4c2-45df-b9a2-76bd1f33e509" />
 This model shows what happens when a customer places an order online. First, the system checks if the product is actually in stock. If it's out of stock, it notifies the customer and ends. If the product is available, it moves on to process the payment. If the payment fails, the customer gets an error notification and the process stops. If the payment is successful, the order is confirmed, prepared for shipment, and finally shipped out, ending with a shipping confirmation email to the customer.

## Scenario 3: IT Service Request

This outlines how an IT help desk handles support tickets. Once an employee submits a ticket, the help desk registers it and checks how severe the issue is. Low severity issues go to a regular support technician, while high severity ones go straight to a senior technician. The assigned technician investigates. If they can fix it internally, they do. If they can't, they escalate it to an outside service provider. Either way, it ends with the help desk updating the ticket status and letting the employee know it's resolved.

<img width="4242" height="630" alt="Scenario3_IT_Service_Request_Fixed" src="https://github.com/user-attachments/assets/9edd3c4b-0631-4dff-91de-1c56447dbecd" />
 This outlines how an IT help desk handles support tickets. Once an employee submits a ticket, the help desk registers it and checks how severe the issue is. Low severity issues go to a regular support technician, while high severity ones go straight to a senior technician. The assigned technician investigates. If they can fix it internally, they do. If they can't, they escalate it to an outside service provider. Either way, it ends with the help desk updating the ticket status and letting the employee know it's resolved.

## How to view

The files are saved in the standard .bpmn format. You can just open them in Camunda Modeler, bpmn.io, or any other BPMN viewer to see the actual diagrams.
