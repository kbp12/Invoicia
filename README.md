# Invoicia Web App
Invoicia is a web application for managing invoices of users by an organization.
Basically organization can issue invoices using Invoicia app and can send it to users with the help of emails.
Once user gets invoice he/she will have certain amount of time to pay money for that invoice and application
will keep track of status of invoice and before deadlines reminder mails will be sent to users.

# Getting Started With App
Before getting started, Keep in mind you should have atleast `Node.js` and `Git` downloaded in your system. Now you have to follow below mentioned steps-
- git clone `https://github.com/kbp12/Invoicia.git`
- cd `Invoicia/invoicia_frontend` 
- `npm install`

Now onwards to start app go to `/invoicia_frontend` folder and do `npm start`.


# Contributing Guidelines
* You can find our Contributing guidelines [here](/CONTRIBUTING.md).

# Features (from server side)
- [x] Create a new invoice
- [x] Ability to update the status of the invoice
- [x] Send the invoice via email
- [x] View invoices including status (paid, outstanding, late, etc.)
- [x] Add a due date to an invoice
- [x] View late invoices
- [x] User authentication

## Feature to be added (from client side)
- `/Invoicia/invoicia_frontend/src` folder strcuture:-
```
    │   App.css
    │   App.js
    │   App.test.js
    │   index.css
    │   index.js
    │   reportWebVitals.js
    │   routes.js
    │   setupTests.js
    │
    ├───components
    │   ├───Auth
    │   │       auth_styles.css
    │   │       forget_password.js
    │   │       login.js
    │   │       signup.js
    │   │
    │   ├───Dashboard
    │   │       dashboard_styles.css
    │   │       home.js
    │   │       new_invoice.js
    │   │
    │   ├───Footer
    │   │       footer.css
    │   │       footer.js
    │   │
    │   ├───Header
    │   │       header.css
    │   │       header.js
    │   │
    │   └───User
    │           edit_profile.js
    │           profile.js
    │           user_styles.css
    │
    └───contexts
            authContext.js
```
- As shown in above structure `Auth`, `Dashboard`, `Footer`, `User`, `contexts` are folders that contains file which needs to be modified or implemented.
- Auth folder contains login page, signup page and forget password page for app, you are required to implement same in `login.js`, `signup.js` and `forget_password.js` file and styling will be in `auth_styles.css` file. 
- User folder contains profile page, edit_profile for app, you are required to implement same in `profile.js` and `edit_profile.js` file and styling will be in `user_styles.css` file. 
- Header folder contains header(which will include navigation) for app, you are required to implement same in `header.js` file and styling will be in `header.css` file.
- Footer folder contains footer for app, you are required to implement same in `footer.js` file and styling will be in `footer.css` file.
- Dashboard folder contains dashboard for the app which will show all invoices for users as well as will have a form to create a new invoice, you are required to implement same in `home.js` and `new_invoice.js` file and styling will be in `dashboard_styles.css` file. 
- context folder contains react contexts used in data management. There is `utContext.js` file you have to modify to make user remain loggedin and you can create other contexts as well upon your requirmnets.
- In `routes.js` file you have to put all the routes fo client side.
<br><br/>
```
Note(s):- 1) Design and specification are completely dependent on you but pages must have standard fields there
            and you may add extra fields as well.
          2) More information related to each and every page will be shared with you once it is assigned to you. 
          3) You have to strictly use react.js conventions while implementing features.
          4) You can test them based on dummy data as well, no need to worry about backend and other things)`.
          
```


- For any doubts and queries feel free to contact me on [Email](mailto:ykk11@iitbbs.ac.in) or [LinkedIn](https://www.linkedin.com/in/yogesh-kansal-044a75194/).

<h3 align="center">Happy coding!!!<h3/>
