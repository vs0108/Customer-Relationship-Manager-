# Customer Relationship Management System (CRMS)

# Overview
The Customer Management System (CMS) is a comprehensive solution for managing customer information. 

It includes implementations in Java (GUI-based and console-based) and a simple web-based interface using HTML and JavaScript.

The system provides functionality to add, delete, search, and display customer information.

# Features

1. Java GUI-based CMS:
   
- Add Customer: Allows the user to input customer details like name, email, contact, address, and company name.
  
- Delete Customer: Enables deletion of selected customer information.
  
- Custom List Renderer: Displays customer details in a formatted list.
  
- Welcome Screen: Includes an interactive welcome screen with a background image and navigation to the main application.
  
2. Web-based CMS:
   
- Add Customer: Users can add customer details using an intuitive form.

- Customer List Display: Displays the list of added customers in a table.

- Interactive Design: Utilizes jQuery for adding and managing customer data dynamically.

3. Console-based CRM:

- Add Customer: Supports adding customers through the console.

- Remove Customer: Provides functionality to remove customer records.

- Search Customer: Searches for customers by name, address, or phone.

- Interactive Menu: Offers a menu-driven interface for user interaction.

# Prerequisites

1. Java GUI-based CMS:

- JDK 8 or later

- Java Swing Library

- Image Path Configuration: Ensure that the image file cus_ser.jpg is available at the specified path in the code.

2. Web-based CMS:

- HTML5 and JavaScript-compatible browser

- jQuery Library

  3. Console-based CRM:

- JDK 8 or later

- Basic knowledge of console input/output

# How to Run

1. Java GUI-based CMS:

Compile and run the CMS.java file using:

> javac CMS.java

> java cms.CMS

Ensure the background image file (cus_ser.jpg) is in the specified path or update the path in the code accordingly.

2. Web-based CMS:

> Save the HTML code in a file, e.g., index.html.

> Open the file in a web browser.

3. Console-based CRM:

Compile and run the console program:

> javac CRM.java

> java CRM

# File Structure

CMS/
│

├── GUI/

│   ├── CMS.java  # Java Swing-based GUI application

│   └── cus_ser.jpg  # Background image for the welcome screen

│

├── Web/

│   └── index.html  # Web-based customer management system

│

└── Console/

    └── CRM.java  # Console-based customer management system

# Future Enhancements

- Database Integration: Add support for persistent storage using MySQL or other databases.

- Enhanced Search: Include advanced search filters for easier data retrieval.

- Reporting Features: Generate detailed customer reports.

- Mobile Compatibility: Extend web interface for mobile-friendly usage.

- REST API Integration: Build APIs for backend integration with other platforms.

# Credits

Developed as a comprehensive customer management solution to explore GUI, web, and console-based application development.






