# PayPal - Credit Card (using REST API)

**Breaking Changes** Increased minimum requirements to .NET 4.5 

Start by adding a new form on the page. On the Initialization Screen, either use the template or start with a blank form. If latter, then add a button the form. From the list of actions select one of the paypal actions under Payments section. Check screenshot below for exact location. 
![][92] 

### How to setup a test account ### 

PayPal integration Credit Card (using REST API) 

go to https://developer.paypal.com/ 

Login 

go to Dashboard 

go to Applications -> My Apps 

Create a new app.

After you created the app, you can click on it in the apps list, and you will see the Client ID and the Secret. 
![][93] 

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
![][94] 
![][95] 

Format your PayPal API requests using the details from your test accounts as seen below. ![][96] When filling the form, for testing purposes, use the other account, the buyer one, credentials.
[1]: /_/rsrc/1380524206563/config/customLogo.gif?revision=3
[2]: http://action-form.dnnsharp.com/
[3]: http://www.dnnsharp.com/dnn/modules/action-form-builder/download
[4]: http://www.dnnsharp.com/DesktopModules/RegCore/Api.aspx?cmd=buy&product=AFORM
[5]: http://www.dnnsharp.com/dnn/modules/action-form-builder
[6]: http://action-form-v2.dnnsharp.com/
[7]: /home
[8]: /home/breaking-changes
[9]: /home/examples-troubleshooting
[10]: /home/faq-2-0
[11]: /home/getting-started
[12]: /home/how-to
[13]: /home/video-tutorials
[14]: /appearance
[15]: /appearance/jquery-theme
[16]: /appearance/template
[17]: /bindings-aka-dynamic-forms
[18]: /conditions
[19]: /creating-new-form
[20]: /creating-new-form/contact-form
[21]: /creating-new-form/create-from-scratch
[22]: /creating-new-form/login-form
[23]: /creating-new-form/registration-form
[24]: /creating-new-form/subscribe-to-mailchimp
[25]: /debugging
[26]: /display-mode
[27]: /drafts
[28]: /drafts/modifysomething
[29]: /extensibility
[30]: /extensibility/custom-actions
[31]: /extensibility/custom-predefined-forms
[32]: /extensions
[33]: /extensions/authorize-net
[34]: /extensions/authorize-net/make-a-payment-with-credit-card-cc
[35]: /extensions/authorize-net/make-a-payment-with-electronic-check-echeck
[36]: /extensions/authorize-net/simple-checkout
[37]: /extensions/campaign-monitor
[38]: /extensions/clickatell
[39]: /extensions/constant-contact
[40]: /extensions/dnn-advanced-search
[41]: /extensions/dnn-aweber
[42]: /extensions/singature-pad-control
[43]: /extensions/dnn-module-actions
[44]: /extensions/page-actions
[45]: /extensions/dnn-podio
[46]: /extensions/dnn-sharp-drawing
[47]: /extensions/excel
[48]: /extensions/generate-pdf
[49]: /extensions/job-application
[50]: /extensions/mailchimp-dnn-integration
[51]: /extensions/my-action-form-uniqueizer
[52]: /extensions/paypal-express-checkout
[53]: /extensions/salesforce
[54]: /extensions/stripe
[55]: /extensions/xml-add-on
[56]: /form-actions
[57]: /form-actions/context
[58]: /form-actions/data
[59]: /form-actions/email
[60]: /form-actions/form-state
[61]: /form-actions/message
[62]: /form-actions/parsing
[63]: /form-actions/payments
[64]: /form-actions/redirect
[65]: /form-actions/security
[66]: /form-actions/user
[67]: /form-events
[68]: /form-fields
[69]: /form-fields/address
[70]: /form-fields/buttons
[71]: /form-fields/date-time
[72]: /form-fields/dnn
[73]: /form-fields/files
[74]: /form-fields/hidden-data
[75]: /form-fields/image
[76]: /form-fields/multiple-choice
[77]: /form-fields/security-fields
[78]: /form-fields/statistics
[79]: /form-fields/text
[80]: /form-fields/user
[81]: /form-layout
[82]: /form-settings
[83]: /form-settings/import-export-settings
[84]: /form-settings/initialization-scripts
[85]: /form-settings/localization
[86]: /free-resources
[87]: /lifecycle
[88]: /tokens
[89]: /validations
[90]: /where-is-my-data
[91]: /system/app/pages/sitemap/hierarchy
[92]: http://action-form.dnnsharp.com/_/rsrc/1425321994341/extensions/paypal/paypal-actions.png
[93]: http://action-form.dnnsharp.com/_/rsrc/1425452991964/extensions/paypal/PayPal%20credit%20card%20REST%20API.png
[94]: http://action-form.dnnsharp.com/_/rsrc/1425453047449/extensions/paypal/Sandbox%20Test%20Accounts%20%20%20PayPal%20Developer.png
[95]: http://action-form.dnnsharp.com/_/rsrc/1425453119908/extensions/paypal/Sandbox%20Test%20Accounts%20%20%20PayPal%20Developer%20credentials.png
[96]: http://action-form.dnnsharp.com/_/rsrc/1425453241916/extensions/paypal/PayPal%20express%20checkout.png
[97]: http://www.dnnsharp.com/dnn/modules/action-form-builder/whats-new
[98]: http://www.dnnsharp.com/Support#opturl=%2Faction-form
[99]: http://www.dnnsharp.com/support/request-a-video-tutorial
[100]: https://www.google.com/a/UniversalLogin?service=jotspot&continue=http://sites.google.com/a/dnnsharp.com/action-form-v2/extensions/paypal
[101]: /system/app/pages/recentChanges
[102]: /system/app/pages/reportAbuse
[103]: javascript:;
[104]: http://sites.google.com
  

