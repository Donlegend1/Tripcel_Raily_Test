Laravel Project README
Introduction
This project is built using the Laravel framework, a powerful MVC PHP framework for web application development. Follow the steps below to set up and run the project on your local machine.


Requirements
Before you begin, ensure you have met the following requirements:

PHP >= 7.4
Composer
MySQL or another supported database


Installation
Step 1: Clone the Project
First, clone the project repository from GitHub to your local machine.
git clone https://github.com/Donlegend1/Tripcel_Raily_Test.git


Step 2: Navigate to the Project Directory
Change your working directory to the project folder.

Step 3: Install Dependencies
Use Composer to install all necessary dependencies.

Step 4: Set Up Environment File
Create a copy of the .env.example file and name it .env.
cp .env.example .env

Step 5: Generate Application Key
Generate a new application key. This key is used to encrypt user sessions and other sensitive data.
php artisan key:generate

Step 6: Serve the Application
Finally, serve the application using the built-in Laravel development server.

