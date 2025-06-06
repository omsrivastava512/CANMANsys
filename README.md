# **Canteen Management System (PHP)** 

This pure PHP web application equips organizations with the tools to efficiently manage canteen operations. It offers a user-friendly interface for:

* **Sales Management:**
    - Process customer orders for canteen items seamlessly.
    - Calculate bills accurately to ensure fair pricing.
    - Accept payments (if applicable) using secure integration with payment gateways (implementation details depend on the chosen gateway).
    - Manage customer accounts (optional) to personalize the canteen experience.
* **Reporting:**
    - Generate informative reports on sales, revenue, and popularity of items.
    - Gain valuable data-driven insights into customer preferences to tailor your offerings.
    - Identify best-selling items and adjust inventory accordingly.
 
## Demo:


https://github.com/user-attachments/assets/97e06430-0703-4553-a9e2-151ca5b16f96



**Benefits:**

* **Implementing [AutoCrud](https://github.com/omsrivastava512/autocrud):** Dynamically generating CRUD pages based on tables in your database.
* **Enhanced Efficiency:** Streamline manual tasks and automate inventory tracking.
* **Improved Accuracy:** Reduce errors in order processing and billing.
* **Data-Driven Decisions:** Make informed choices based on sales and inventory data.
* **Cost Control:** Optimize inventory management and prevent overstocking.
* **Customer Satisfaction:** Deliver a smooth ordering experience.

**Getting Started**

**Prerequisites:**
- Tailwind css
- PHP 7.4 or later ([https://www.php.net/](https://www.php.net/))
- MySQL 8.0 or later database server ([https://www.mysql.com/](https://www.mysql.com/))
- Text editor or preferred code editor

**Installation:**

1. **Download the Code:**

   Download the project files as a ZIP archive or clone the repository using Git:

   ```bash
   git clone https://github.com/heyabhiraj/CANMANsys/
   ```

2. **Set Up Database Connection:**

   Create a MySQL database for the canteen management system.
   Edit the `admin/config.php` file to provide your database credentials:

   ```php
   <?php

   define('DB_HOST', 'your_database_host');
   define('DB_NAME', 'your_canteen_database');
   define('DB_USER', 'your_database_username');
   define('DB_PASSWORD', 'your_database_password');

   ?>
   ```

3. **Create Database Tables (optional):**

   If you're not using pre-defined database tables, create the necessary tables (e.g., `item_list`, `order_payment`, `item_order`, `registered_user`, etc.) using SQL scripts or within the code itself.

4. **Run the Application:**

   Place the project files in a web-accessible directory on your server.
   Access the application in your browser using the URL pointing to the index.php file (e.g., https://localhost/canteen-management-system/index.php).

**Usage**

The application's interface will guide you through managing canteen operations. You can typically perform actions like:

- **Adding/Editing Items:** Create new items or modify existing ones.
- **Managing Inventory:** Maintain stock levels and set reorder points.
- **Processing Orders:** Take and fulfill customer orders.
- **Generating Reports:** View insightful reports on sales and inventory.

**Security Considerations**

- Implement secure user authentication and authorization to restrict access to sensitive data.
- Validate all user input to prevent SQL injection and other vulnerabilities.
- Sanitize data before displaying it to prevent cross-site scripting (XSS) attacks.
- Consider using prepared statements for database interactions to safeguard against SQL injection.

**Contributing**

We welcome contributions to this project! Here's how you can participate:

* **Report Bugs:** If you encounter any issues, create a GitHub issue.
* **Suggest Features:** Feel free to share your ideas for new functionalities.
* **Submit Pull Requests:** Fork the repository, make your changes, and submit a pull request for review.

**License**

This project is licensed under the MIT License. See the `LICENSE` file for details.

**Additional Information**

- Consider including screenshots or a short demo video to illustrate the system's functionality.
- Outline authentication and authorization mechanisms (if implemented).
- Mention any external libraries
