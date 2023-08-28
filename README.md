# Power Up Program Final App Challenge: Adventure Works Cycles - Employee Discount Program

# Overview
The final assignment of the Microsoft Power Up Program was centered around creating a robust app for Adventure Works Cycles to facilitate their Employee Discount Program. The objective was to leverage the Power Platform to design an app that enabled employees to purchase products at a discounted rate of 20% and meet other specific business requirements.

# Business Scenario
Adventure Works Cycles, a global bicycle company, sought a solution to enhance their employee discount program. The goal was to provide employees with an intuitive interface to browse products, apply the employee discount, and streamline the purchasing process.

## User Requirements
Adventure Works Cycles provided a list of requirements for the employee discount program app:

1. **Catalog of Products:** The app should display a catalog of products available for purchase.

2. **Discounted Prices:** Employees should see products with their regular prices and the discounted prices after the 20% discount.

3. **User Roles:** The app should have different roles for Employees, Line Managers, and Administrators.

4. **Approval Workflow:** Line Managers must approve orders placed by employees.

5. **Order History:** Employees should be able to view their order history.

6. **Checkout Process:** Employees should be able to add products to their shopping cart and proceed to checkout.

7. **Shopping Cart:** The app should display a shopping cart showing selected items and their quantities.

8. **Order Confirmation:** After checkout, employees should receive an order confirmation email.

9. **Approval Notifications:** Line Managers should receive email notifications for order approvals.

10. **Stock Management:** Stock quantities should be updated as orders are placed.

11. **Dashboard for Line Managers:** Line Managers should have access to a dashboard displaying order statistics and approval status.

12. **Import Stock Details:** Administrators should be able to import initial stock details through an Excel file.

13. **Order Approval Status:** Employees should see the approval status of their orders.

## Solution Steps:
1. **App Setup:** I created a PowerApps app with screens for welcoming the user, product catalog, shopping cart, and order history.

2. **Data Source:** I used a sharePoint list and Dataverse to manage product details, orders, and stock information.

3. **Product Catalog:** Display products with regular and discounted prices based on the 20% discount.

4. **Shopping Cart:** Enable employees to add products to their cart and proceed to checkout.
  
6. **Checkout Process:** I implemented a checkout process with confirmation and email notifications.

7. **Order Approval Workflow:** I created Power Automate flows to initiate order approval by Line Managers and also notifications to the Employee who placed the order.

8. **Order History:** I created a screen to allow employees to view their order history and approval status.

9. **Stock Management:** I created a Power Automate flow to import initial stock details from an Excel file and update the quantity on the Sharepoint list after orders are placed then updating the same on Dataverse allowing the Administrator to track the stock information.

11. **Line Manager Dashboard:** I developed a Power BI dashboard showing order statistics and approval status.

12. **Order Approval Status Display:** I created an order details screen to display the approval status of orders for employees.

# Final Submission
For my final submission, I recorded a video demonstrating the app's functionalities as per the user requirements. Showcasing the app's screens, workflows, data management, user roles, and the Line Manager dashboard, highlighting how the app meets the business needs and fulfills the employee discount program.

# Acknowledgement
This assignment was successfully completed with gratitude to the Microsoft Power Up Program. Over the course of 12 weeks, the program imparted invaluable skills and knowledge that enabled the creation of this impactful app. The comprehensive training in PowerApps, Power Automate, SharePoint, Dataverse, and Power BI equipped me to develop solutions that align with real-world business needs.

# Conclusion
The Adventure Works Cycles Employee Discount Program app leverages PowerApps, Power Automate, SharePoint, Dataverse, and Power BI to create a comprehensive solution that provides employees with a seamless shopping experience and line managers with tools to manage approvals and monitor orders. The app's features cater to the specific business needs of Adventure Works Cycles and enhance the employee discount program.
