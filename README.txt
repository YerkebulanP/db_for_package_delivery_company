Project description:
The task of the project is to compile a database for package delivery company. 
- The project consists of 19 tables.
- They are: bill, card, company, contract, customer, employee, 
hazardous materials, international shipments, invoice, location, order, 
package, package employee, package tracking system, payment, prepaid, 
tracking system, transport, warehouse.

Explaining what is where:
- Customer has credit cards, by this cards they can pay for the order.
- Each payment has their invoice information
- In addition, customer may prepay for the shipment
- Each customer will have bill account
- Some of the customers have a contract with the company 
- The company have many employees, who will handle the packages
- We have the table package_employees, which performs the role of the bridge 
between employee and package
- Packages must be sent to customers. In order to do this, it puts into 
transport.
- Each transport will have the tracking system to find the location
- We will have for the beginning only 10 location points. 
- 2 of the locations are the Warehouses (Almaty and Nur-Sultan)
- Each package will also have the tracking system, information will be stored 
in package tracking system
- Packages also may have hazardous materials. It will be shown in hazardous
materials table
- Packages also can be delivered to another countries. To show this, we have 
the table international shipments, with the information about description of 
the document.