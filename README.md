# bechdenits
🌀 BECHDE - E-commerce project made with React ,Express ,Node ,Mongo

### User Permissions
---

#### Students
* register himself on the app
* provide various details like  profile link, email, phone number, username
* upload details of a product to be sold online (to be verified by admin)
* can view all products from all sellers
* edit the products he has uploaded
* edit privacy settings
* change his password
* search for various products and contact the concerned student by live chatting 
* delete a product when it is sold
* can give feedback 

#### Admin
* view and edit the products user has uploaded 
* approve a product (if admin flags as appropriate then only, all users will be able to see that product online. This is to ensure that no fake or obscene images are uploaded as   well as no vulgar language is used )
* view the feedback section of different user
* view the information of all users
* view the status of orders i.e order pending, order rejected, order success
* upload details of his own product to be sold online

### A note to the viewers
---

1. You can try logging in as an admin by entering the following credentials:
* **Email:** Pranjal112@gmail.com
* **Passward:** Pranjal112

2.You can also register yourself as a student and then login to view the options available to a student or use the following credentials:
* **Email:** pranjaldas5003@gmail.com
* **Passward:** pranjaldas5003

## View Live App
**Hosted at**: https://bechdenits.herokuapp.com/

### Tech Stack Used
* **MongoDB** - Document database - to store data as JSON
* **Express.js** - Back-end web application framework running on top of Node.js
* **React** - Front-end web app framework used
* **Node.js** - JavaScript runtime environment

### Middleware
* Mongoose
* JWT authentication

### Steps followed to setup the project
---
#### Setting up server and database
1. Initialise a package.json file by entering the following command in terminal, after getting into the project directory :

```Javascript
npm init
```
