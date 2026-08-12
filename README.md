# Swag Labs - E-Commerce Website Manual Testing

##  Project Overview
This repository contains the manual testing documentation and bug reports for **Swag Labs** (saucedemo.com), a demo e-commerce web application. The testing process covers the core functionalities of the website to ensure a seamless user experience.

## Tools & Technologies Used
* **Test Case Management:** Microsoft Excel / Google Sheets
* **Bug Tracking & Agile Management:** Jira Software
* **Application Under Test:** [Swag Labs](https://www.saucedemo.com/)

## Modules Tested
1. **Authentication:** User Login & Logout (Valid/Invalid scenarios, Locked out user handling).
2. **Product Inventory:** Viewing products, Sorting functionalities (Price, Name).
3. **Shopping Cart:** Adding/Removing items, Cart badge updates.
4. **Checkout Process:** Form validation, Complete order workflow.

## Test Execution Summary
* **Total Test Cases Executed:** 10
* **Passed:** 7
* **Failed (Bugs Found):** 3

## Bug Reports (Jira)
During the testing phase, the following major bugs were identified and logged in Jira:
1. `[BUG-01]` Product images display incorrectly (broken images) for specific users.
2. `[BUG-02]` 'Last Name' input field is disabled/un-typeable on the checkout page.
3. `[BUG-03]` Product sorting filter does not change the order of items.
4. `[BUG-04]` Significant performance delay (5+ seconds) during user login.

*(Note: Check the uploaded screenshots to view the detailed Jira tickets and the Kanban board).*

## Author
**Heshani Nethmini** 
*ICT Student | QA Enthusiast*
