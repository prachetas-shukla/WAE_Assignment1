# BPMN Process Models - Exercise 1

Prachetas Shukla

This repository contains the BPMN diagrams for the three scenarios in Exercise 1. 

## Scenario 1: Employee Leave Approval

This diagram maps out how an employee's time-off request is processed. It starts when the employee submits the request. The HR system first checks if they have enough leave balance. If they don't, it sends a notification and the process stops there. If they do have enough balance, the request goes to the manager. From there, if the manager approves, the system updates the balance and sends a confirmation. If the manager rejects it, it just sends a rejection notification instead.

![Employee Leave Approval Model](scenario1.png) This diagram maps out how an employee's time-off request is processed. It starts when the employee submits the request. The HR system first checks if they have enough leave balance. If they don't, it sends a notification and the process stops there. If they do have enough balance, the request goes to the manager. From there, if the manager approves, the system updates the balance and sends a confirmation. If the manager rejects it, it just sends a rejection notification instead.

## Scenario 2: Online Purchase Order Processing

This model shows what happens when a customer places an order online. First, the system checks if the product is actually in stock. If it's out of stock, it notifies the customer and ends. If the product is available, it moves on to process the payment. If the payment fails, the customer gets an error notification and the process stops. If the payment is successful, the order is confirmed, prepared for shipment, and finally shipped out, ending with a shipping confirmation email to the customer.

![Online Purchase Order Model](scenario2.png) This model shows what happens when a customer places an order online. First, the system checks if the product is actually in stock. If it's out of stock, it notifies the customer and ends. If the product is available, it moves on to process the payment. If the payment fails, the customer gets an error notification and the process stops. If the payment is successful, the order is confirmed, prepared for shipment, and finally shipped out, ending with a shipping confirmation email to the customer.

## Scenario 3: IT Service Request

This outlines how an IT help desk handles support tickets. Once an employee submits a ticket, the help desk registers it and checks how severe the issue is. Low severity issues go to a regular support technician, while high severity ones go straight to a senior technician. The assigned technician investigates. If they can fix it internally, they do. If they can't, they escalate it to an outside service provider. Either way, it ends with the help desk updating the ticket status and letting the employee know it's resolved.

![IT Service Request Model](scenario3.png) This outlines how an IT help desk handles support tickets. Once an employee submits a ticket, the help desk registers it and checks how severe the issue is. Low severity issues go to a regular support technician, while high severity ones go straight to a senior technician. The assigned technician investigates. If they can fix it internally, they do. If they can't, they escalate it to an outside service provider. Either way, it ends with the help desk updating the ticket status and letting the employee know it's resolved.

## How to view

The files are saved in the standard .bpmn format. You can just open them in Camunda Modeler, bpmn.io, or any other BPMN viewer to see the actual diagrams.