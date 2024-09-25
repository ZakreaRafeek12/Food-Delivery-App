# Food Delivery App - Automation Testing Project

## Project Overview

This project focuses on testing the functionalities of a large food delivery application. The app allows users to browse restaurants, place orders, track deliveries, and manage their accounts. The testing process is automated to ensure efficiency, accuracy, and scalability.

## Features to Test

### 1. User Registration
- *Scenario:* New users should be able to register an account to use the app.
- *Test Objectives:* Validate successful account creation, field validation, and error handling for invalid inputs (e.g., email format, password strength).
- *Automation Strategy:* Use automated test scripts to fill forms, submit data, and verify successful or unsuccessful registration.

### 2. User Login
- *Scenario:* Registered users should be able to log in using valid credentials.
- *Test Objectives:* Ensure correct authentication, error handling for incorrect login credentials, and account lockout after multiple failed attempts.
- *Automation Strategy:* Automated scripts will simulate valid and invalid logins and check the system’s response.

### 3. Restaurant Browsing and Search
- *Scenario:* Users can browse restaurants by categories or search for specific ones.
- *Test Objectives:* Ensure that search results are accurate and relevant, restaurant listings load correctly, and filtering options work as expected.
- *Automation Strategy:* Use automated tools to search, filter, and compare displayed results to the expected outcomes.

### 4. Add to Cart
- *Scenario:* Users can add food items from the restaurant menu to their cart.
- *Test Objectives:* Verify that items are added to the cart correctly, quantity is updated, and any restrictions (e.g., maximum quantity) are handled properly.
- *Automation Strategy:* Scripts will simulate the addition of multiple items and validate the contents of the cart.

### 5. Checkout and Payment
- *Scenario:* Users should be able to checkout and pay for their orders using different payment methods (e.g., credit card, wallet, cash on delivery).
- *Test Objectives:* Ensure smooth checkout, proper handling of payment methods, and validation of payment processing.
- *Automation Strategy:* Automate the checkout process with various payment methods and ensure that orders are processed correctly.

### 6. Order Tracking
- *Scenario:* Users can track the status of their order in real-time from preparation to delivery.
- *Test Objectives:* Validate the accuracy of the order tracking feature and ensure that status updates are displayed correctly (e.g., order confirmed, food being prepared, out for delivery).
- *Automation Strategy:* Use automation scripts to simulate an order lifecycle and verify status changes at each stage.

### 7. User Profile Management
- *Scenario:* Users can update their profile information (e.g., name, address, payment methods).
- *Test Objectives:* Ensure that all profile updates are saved correctly and displayed properly.
- *Automation Strategy:* Automate the process of updating profile details and validate that the changes are reflected in the user's account.

### 8. Push Notifications
- *Scenario:* Users receive push notifications for order updates and promotional offers.
- *Test Objectives:* Verify that notifications are triggered correctly and that users can enable or disable them.
- *Automation Strategy:* Test the notification system by simulating various triggers, such as order updates or promotional campaigns.

### 9. Multi-Language Support
- *Scenario:* Users can switch the app language between English, Arabic, and other supported languages.
- *Test Objectives:* Ensure that all content is properly translated and the language switch affects the entire app.
- *Automation Strategy:* Automate language switching and validate that translations and layouts adjust accordingly.

### 10. Promotions and Coupons
- *Scenario:* Users can apply promotions or discount coupons during checkout.
- *Test Objectives:* Validate that applicable promotions and coupons are applied correctly, and ensure error handling for invalid codes.
- *Automation Strategy:* Automate the application of valid and invalid coupons during the checkout process.

## Tools Used for Automation Testing

- *Selenium:* To automate web-based test cases, covering restaurant browsing, ordering, and user profile updates.
- *TestNG:* For test management and execution, ensuring all test cases are organized and run efficiently.
- *Postman:* To automate API testing for endpoints related to user management, order processing, and payment verification.
- *Jenkins:* For Continuous Integration (CI), running automated tests on a regular schedule and providing feedback to the development team.
- *Appium:* For automating mobile app testing across Android and iOS platforms.

## Automation Strategy

1. *Test Case Coverage:*
   - Automate high-priority user journeys, including user registration, login, restaurant browsing, adding items to the cart, checkout, and order tracking.
   - Focus on areas with frequent changes or high traffic, such as payment gateways and order placement.
   
2. *Data-Driven Testing:*
   - Use data-driven testing approaches to test various inputs (e.g., different payment methods, delivery addresses, and coupon codes) efficiently.
   
3. *API Testing:*
   - Automate the testing of backend APIs to ensure seamless communication between the mobile app and the server. This includes user authentication, order placement, and real-time updates on order status.

4. *Regression Testing:*
   - Run regression tests after every major app update or code change to ensure that no existing functionality is broken.

## Test Coverage

- *User Flows:* End-to-end tests for the complete user journey, from registration to order completion.
- *Edge Cases:* Automated test cases to handle unexpected inputs (e.g., invalid data, network issues, expired coupons).
- *Performance Testing:* Automated scripts to simulate high traffic on key app functionalities and ensure the system handles peak loads.

## Conclusion

This automation testing project aims to ensure the high reliability, usability, and security of the food delivery application. By leveraging advanced automation tools and strategies, we aim to streamline testing processes and provide thorough coverage for all core features of the app.


## link for  project 
https://www.figma.com/design/sjdwOAZLwLbbPSuvsgwqFr/Food-Delivery-App-(Community)?node-id=223-3474&node-type=canvas&t=AYQJYLudiJjlAADM-0
