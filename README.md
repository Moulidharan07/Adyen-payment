##    Adyen payment integration
## Objective
          Adyen provides payment processing solutions for businesses, enabling them to accept payments from customers through various channels such as online, in-store, and mobile. Adyen's integrations allow businesses to seamlessly incorporate Adyen's payment capabilities into their existing platforms, websites, or applications.
## Dependencies 
    •	Studio pro version 9.24.6
## Configuration
    •	Import the module Adyen Module from the mendix marketplace.
    •	Go to the URL to create a developer account in Adyen portal, URL: https://www.adyen.com/signup
    •	Sign up for the Adyen portal by filling in your details. You will receive a username, account name, and password reset link via email. Use that link to create a new password.
## Going live
    •	To access the live endpoints, you need an API key from your live Customer Area.
## Going Test
    •	After creating your password, log in to the Adyen portal and switch to the "Test" tab. Then, log in using your username, account name, and password.
    •	Go to Developer-> API Credentials.
    •	Click on “Username” -> ws
    •	Provide a description and generate an API key. Save the changes. (Note: If you have Apple Pay, Samsung Pay, or Google Pay certificates, add them and save the changes)
    •	Go to Settings -> Merchant accounts and retrieve the merchant account ID.
    •	The API key and merchant account should be placed in the default value of API Key constant which is available inside the module.
## Available API:
    •	Card Payment
    •	Pay through payment link (Payment URL will be generated)
    •	Order (Create/Cancel order)
    •	Recurring (Create/Delete Adyen account)
## Screenshots
![image](https://github.com/Moulidharan07/Adyen-payment/assets/119506038/aea85fff-b4c6-44e2-8c34-4bd143a3ff49)
![image](https://github.com/Moulidharan07/Adyen-payment/assets/119506038/d925bad6-e463-4e0b-821e-778e314336f1)
![image](https://github.com/Moulidharan07/Adyen-payment/assets/119506038/7f51b65f-0e64-40dd-9e09-55424dd74a75)
![image](https://github.com/Moulidharan07/Adyen-payment/assets/119506038/333e38e1-3f7b-4314-9fee-d505846c3afe)




 
 

 
 
