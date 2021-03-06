# Airport-management
## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites
* Composer
* PHP 7.2.* or higher
* MySQL
* NPM
### Installing
* Run those commands on terminal:
```
composer install
```
```
npm install
```
* Open MySQL console or PhpMyadmin and create a database with the name "airport"
* Create the database schema
1. Open the project in your IDE
2. Go to terminal and run:
```
php bin/console make:migration
```
```
php bin/console doctrine:migrations:migate
```
3. The database schema will be created automaticaly when you run the project.
## Running the project
To run the project: 
``` php bin/console server:run ``` On the browser: http://127.0.0.1:8000
### Login
![Capture](https://user-images.githubusercontent.com/41878409/71700807-473a5080-2dc6-11ea-88c6-1dd1a0d8c258.PNG)

### Register Page
![register](https://user-images.githubusercontent.com/41878409/71700805-46a1ba00-2dc6-11ea-856c-dd8721048d4a.PNG)

### Airplanes list(for Admin role)
![AirplanList](https://user-images.githubusercontent.com/41878409/71700806-46a1ba00-2dc6-11ea-88a6-4a36e6b645ed.PNG)
## Author
Ilyass JANAH [LinkedIn](https://www.linkedin.com/in/janah-ilyass-1354a7a0/)
