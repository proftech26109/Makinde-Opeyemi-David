# Makinde-Opeyemi-David


#API_project Requirements
API tester (POSTMAN), LAMMP/XAMMP/WAMMP

#Installation 
Clone/Download the project file to the htdocs server directory
Create a database in the localhost/phpmyadmin panel called "clothing_company"
import the sql database in the config folder 
Make sure the database details specified in the config/Databse.php file matches with the apache web-server det

#Runnig
Open and create new http request in your POSTMAN application.

#End points
Http://localhost/API_project/api/product/read_single.php?project_id=5
To read a single product from the products table in the database column by passing the product_id parameter
Http://localhost/API_project/api/products/read.php
To read a single product from database
Http://localhost/API_project/api/customer/read_single.php?project_id=3
To read a single customer from the customers table in the database column by passing the product_id parameter
Http://localhost/API_project/api/customers/read.php
To read a single customers from the databse 
Http://localhost/API_project/api/orders/read_single.php
To read a single order from the orders table in the database column by passing the product_id parameter
Http://localhost/API_project/api/orders/read_single.php
To read a single orders from the database
