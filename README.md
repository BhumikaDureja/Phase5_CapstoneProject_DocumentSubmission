# Phase5_CapstoneProject_DocumentSubmission

As part of this project, I have done end-to-end development of QA and test environment for a healthcare website. Includes:

Browser-based end user testing using Selenium WebDriver
Unit testing for back-end elements of the website using TestNG
API testing with Postman and generating Newman report
Automating the whole testing process by a Jenkins job

Following unit tests were created as part of TestNg framework:
1) As a user, viewing product category
2) As a user, listing out products based on the selected categories
3) As a User adding Product to cart
4) As a user, performing EndToEnd test for viewing a product, adding to cart and then finally purchasing the product
5) As an admin, adding a product to a category
6) As an admin, editing details of a product
7) Running API - get call to view all products - http://localhost:8082/medicare/json/data/all/products
8) Running API - get call to view category  - http://localhost:8082/medicare/json/data/category/1/p
9) Running API - get call for most viewed product -http://localhost:8082/medicare/json/data/mv/products
10) Running API - get call for most purchased product - http://localhost:8082/medicare/json/data/mp/products
