# Nexmo-SMS-module
This is a module for Mendix which uses the Nexmo SMS service for sending text messages

Dependencies 
Made in modeler 5.16.1, but the java and Jar file should be compatible with all versions of Mendix
Dependancy on the nexmo-sdk.jar that is included in the package, but otherwise can be downloaded from the nexmo website
Installation
Just call the java action for sending a message. The module itself can be deleted once you have moved the java-action to a logic place in your existing application

Configuration

1. Go to https://dashboard.nexmo.com/sign-up to sign up

2. Activate account and log in

3a. At the top right you see a tab API settings. Click on edit to see all the info you need to set this module up (your API Key and API secret). A screenshot of the page is included in the screenshots with this widget

3b. If you are using a test account you need to add to which mobile numbers sms messages are allouwed to be sent. This is done on API settings page with the Test Phone Numbers fields.

4. In the Java action use these keys for sending your sms message

5. Make sure you format your mobile number correctly, with the country code and without spaces or plus signs or leading zeros.  An example of how a number should be formatted is shown in the screenshots

Known bugs 
None
