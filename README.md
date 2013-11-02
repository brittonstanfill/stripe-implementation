stripe-implementation
=====================

Simple layouts for practice implementing Stripe on a webpage.

1. Clone the Stripe Implementation Repository: github.com/ryanleeallred/stripe-implementation

2. Setup your stripe account. Be sure to make note

3. Replace the html for the <button> with the stripe code.

Use the fancy embedded checkout in stripe's documentation to make this button active.

https://stripe.com/docs/tutorials/checkout

This page won't be connected to your server yet, but we'll practice this in the second part of the project.

4. Use the Subscription Plan folder and the instructions on this page: https://stripe.com/docs/tutorials/forms to create a custom for for a SAAS monthly subscription pricing model. 

The stripe documentation for this project can also be found here: https://stripe.com/docs/tutorials/forms

If you need extra help, a great tutorial has been written by Larry Ullman. Check it out here: 

http://www.larryullman.com/series/processing-payments-with-stripe/

Larry also gives a great example of the html file of how this could be done on the site. I have downloaded the file and saved it in the Possible Solutions folder that you can use as a reference. In your project you will want to break out the javascript into a different file. 

- Add the script file for the stripe.js library to the header of your index.html file.
- Create a custom form that has the values that you would like to capture in an object and pass to your server to be saved.
- Add an event listener on the submit button using jquery and whatever 
- In your account look up your Publishable Test API Key. You will have to plug this in your code in order to be able for a test transaction to work. When you want to make your application live you will have to switch this out with the Publishable Live API Key or else you won't be able to process transactions.
- Use the POST method to store the user information in your server. (You can use Postman if you really want to make your example full-stack.)

Create a monthly subscription for a user on the 

You will need to use the code from the stripe documentation from your own account when you are logged in because the API key that it contains is specific to your Stripe account.






