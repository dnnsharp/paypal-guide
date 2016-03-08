# PayPal - Credit Card (using REST API)

**Breaking Changes** Increased minimum requirements to .NET 4.5 

Start by adding a new form on the page. On the Initialization Screen, either use the template or start with a blank form. If latter, then add a button the form. From the list of actions select one of the paypal actions under Payments section. Check screenshot below for exact location. 
![](paypal-actions.png)

### How to setup a test account ### 

PayPal integration Credit Card (using REST API) 

go to https://developer.paypal.com/ 

Login 

go to Dashboard 

go to Applications -> My Apps 

Create a new app.

After you created the app, you can click on it in the apps list, and you will see the Client ID and the Secret. 
![](PayPal credit card REST API.png)

You can use then the credentials in your module settings, as seen in the above image. 

### PayPal integration Express Checkout 

Test your application by creating a Sandbox account for each user entity represented in your PayPal transactions. When testing, use the test accounts in place of all the live accounts you will use while processing live transactions. 

Create a PayPal account and log in to the Developer website at developer.paypal.com. 

Create a set of virtual Sandbox test accounts. 

go to https://developer.paypal.com/ 

Login 

go to Dashboard 

go to Applications -> Accounts 

On Sandbox test accounts -> Create accounts 

If not seen when created, you can check the credentials for each facilitator and buyer pair by clicking on their profile link on the list, as seen below: 
![](Sandbox Test Accounts   PayPal Developer.png)
![](Sandbox Test Accounts   PayPal Developer credentials.png)

Format your PayPal API requests using the details from your test accounts as seen below. ![][96] When filling the form, for testing purposes, use the other account, the buyer one, credentials.

