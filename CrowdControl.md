[Back to Portfolio](./)

CrowdControl
===============

-   **Class:** CSCI 499
-   **Grade:** A
-   **Language(s):** Python, HTML, PHP, CSS, MySQL, JavaScript
-   **Source Code Repository:** [features/mastering-markdown](https://guides.github.com/features/mastering-markdown/)  
    (Please [email me](mailto:NRMixon@csustudent.net?subject=GitHub%20Access) to request access.)

## Project description

CrowdControl is a website backed by a database that stores prices for computer parts scraped from the web. This database is updated every 24 hours using a script so that the website's prices are always up to date. Customers are able to switch out necessary parts using dropdowns to get the best and most affordable computer for them. 

## How to compile and run the program

How to compile (if applicable) and run the project.

```bash
Need to have Laravel set up on a computer
cd pcbuilder
php artisan serve
npm run dev
Go to localhost IP in default browser
```

## UI Design

The welcome page of the website features a button that directs users to customize their PC as well as login and register options in the top right (see Fig 1). The login page allows users to log in using a valid email and password found within the database (see Fig 2). If users have not created an account before they can register by clicking the green button and this will allow them to create an account that will be stored in the database (see Fig 3). Once users are logged in, they will be redirected to the customization page where they can select the parts that they want and then submit at the bottom (see Fig 4). After all the parts are selected the user submits their order they will then see the checkout page to show the items ordered and the total price of the PC (see Fig 5).

![screenshot](images/CCImages/WelcomePage.png)  
Fig 1. Home Page

![screenshot](images/CCImages/LoginPage.png)  
Fig 2. Login Page

![screenshot](images/CCImages/RegisterPage.png)  
Fig 3. Register Page

![screenshot](images/CCImages/CustomizePage.png)  
Fig 4. Customization Page

![screenshot](images/CCImages/CheckoutPage.png)  
Fig 5. Checkout Page

## 3. Additional Considerations

Users must be logged in to customize and place an order for a PC. There is a forgot password option available on the login page that will email the user a password reset. All parts are web-scraped from Amazon and/or New Egg. 

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

[Back to Portfolio](./)
