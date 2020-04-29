# Mainline Menswear Front End Technical Test

Hello and welcome to the Mainline Menswear Front End Technical Test.

This test is an opportunity to showcase your development skills as well as your attention to detail. You are welcome to develop this web application using any frontend and/or css framework of your choice. Please note though, that we develop our web applications using a Javascript framework called **NuxtJS** and a CSS framework called **Bulma**. So please keep this in mind, as you'll be using this style of framework in future if you are given a front end role at Mainline Menswear.

This github repository provides all of the designs required to create the product enquiry web application. So please place close attention to the designs. We have provided screenshots of all the pages that are required along with examples and how errors should be displayed. There is a style guide for both light and dark themes. Both themes use two fonts from **Google Web Fonts** and icons from **FontAwesome 5**.

In terms of the backend, we have built and developed an API and provided you three endpoints. Two of the three endpoints will **GET** the list of products and the product information in **JSON format** you need to display in your web application. The third endpoint will **POST** your enquiry. You are required to build a web form using AJAX to post your enquiry to the submit endpoint. 

The endpoint URLs are list below:
- https://frontendtest.mainlinemenswear.co.uk/products
- https://frontendtest.mainlinemenswear.co.uk/product/{productId}
- https://frontendtest.mainlinemenswear.co.uk/submit

The table below lists all the fields needed in your form. If advice is given, it's to help you understand how we expect this returned in the form when you submit your enquiry. If no advice is given, it is because we expect that you understand how this field should be returned without needing any guidance.

| Form Field ID| Required Format| Advice        |
| ------------ | -------------- | ------------- |
| productId    | number         |               |
| sizeSelected | string         |               |
| fullname     | string         |               |
| email        | string         |               |
| competitor   | string         | yes or no     |
| competitorUrl| string         | optional      |
| enquiry      | string         |               |

Please make sure to test your submissions and look out for any errors returned from the URL endpoints when building your web application. We expect errors to be displayed and for you to put validation in certain form fields.

All the data that is sent to us will remain in our database for 2 weeks. We will only use this data to confirm whether you have done the test or not. No personal information provided will be passed on or shared.

## What we're looking for
We're looking to see at what stage you're at in terms of your career in web development. There are bonus points for using NuxtJS, building your own CSS framework, attempting both themes and developing in ES6 Javascript. 

We want you to impress!

## Submission
Once you're happy with your test, please commit all your work into your own github repostitory and add **mmw-frontend** as a contributor to your repo. There must be clear instructions on how to initialise your web application if you have not used NuxtJS.

Good luck and we look forward to seeing your product enquiry web application!

