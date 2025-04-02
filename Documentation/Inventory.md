[Back to Portfolio](./)

## Parts Inventory Database
**(Inspired By ServiceTitan)**

-   **Class: CSCI 419 Database Management** 
-   **Grade: B+** 
-   **Language(s): SQL (Oracle APEX)** 
-   **Source Code Repository:** [NoahCHuber/HVACInventoryDatabase](https://github.com/NoahCHuber/HVACInventoryDatabase)  
    (Please [email me](mailto:hubercnoah@gmail.com?subject=GitHub%20Access) to request access.)

## Project description

The Small HVAC Business Parts Database is a custom-built inventory management system designed to help a small family-owned HVAC company efficiently track parts, suppliers, and orders. The application simplifies parts management for both HVAC and Plumbing departments by allowing users to search, add, update, and remove parts from inventory. The system ensures accurate inventory tracking by maintaining audit trails for all modifications and requiring user authentication to prevent unauthorized access.

This inventory database is intended for businesses with roughly 50 employees, primarily parts managers, technicians, job schedulers, and financial staff. The database will be hosted on a local machine with network connectivity to allow real-time updates. However, it will not support multi-location warehouse management or complex logistics. The goal is to create a simple and secure inventory system that enhances efficiency for HVAC and plumbing parts.

## Development

This project was developed through Oracle Apex as a database application. 
Access to the application is limited to the student and professor. 

However, the SQL used to generate the tables can be run in a separate database and will generate the proper tables. 

## UI Design

The Small HVAC Business Parts Database features a simple GUI designed for ease of use by inventory managers and technicians.
The interface is designed for simplicity, ensuring fast navigation and minimal training required for employees.

![screenshot](images/DatabaseIMG.png)  
Fig 1. Dashboard/Home screen
(Provides financial dashboard and company statistics)

![screenshot](images/Jobs.png)  
Fig 2. Jobs screen (Allows job scheduling)

![screenshot](images/Orders.png)  
Fig 3. List of all orders (List of all orders and part numbers)
(Orders can be placed from this window)

![screenshot](images/partsTable.png)
Fig 4. List of all parts (List of all parts available in inventory)
(Parts can be added to inventory from this window)

## 3. Additional Considerations

If you’re planning to use, manage, or troubleshoot the Small HVAC Business Parts Database, here are some real-world considerations you should be aware of:

**1. Internet & Network Dependencies:**
  
Since Oracle APEX is web-based, the system requires a stable internet connection. If the network goes down, users won’t be able to access the inventory.

**2. Performance Issues & Optimization:**     
Large inventory data sets can slow down queries. 
Optimize search functions to filter results efficiently rather than loading the entire database.

**3. Scalability – Can the System Handle Growth?**
If the company expands and adds more locations, this system may not be sufficient because it does not support multi-location warehouse tracking or complex distribution logistics.
If future growth is expected, consider cloud-based scalability options or a multi-instance APEX setup.

**4. Legal & Compliance Issues**     
If the system stores financial data, ensure it complies with business regulations (e.g., tax reporting, audit requirements).
Personal data protection laws (GDPR, CCPA) may apply if storing employee or supplier personal information.

For more details see [Github Oracle Apex Repo](https://github.com/oracle/apex).

[Back to Portfolio](./)
