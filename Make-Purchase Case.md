### USE CASE : MAKE PURCHASE

**Description:** This use case describes how the User can purchase a item from the e-store catalog.

**Primary Actor:** User (Registered Customer, Credit payment service, Identity provider, Paypal)

**Stakeholders and Interests:**
-	Customer: 	Wants Secure transaction.
                         Wants a easy and fast buying experience.

-	Identity Provider:    Wants to collect customer information. 
-   Credit payment service: Wants to receive the order to pay for the item, Interested on commision fee. 
-   Paypal: Wants to receive the order to pay for the item, Interested on commision fee.

**Preconditions:** The user must be registered Customer (a new customer must to do Client Register case)

**Basic flow:**

1.	Already login customer search for a item.

2.	Select the item and click on Make Purchase.

3.  The customer insert the credit card information.

4.  The Credit payment service check the credit card information and retreive OK

5.  The credit payment service pay to the vendor for the item and add the payment on the Credit card mothly bill

6.  The customer receive that the item was purchased

**Alternate Flow:**

3a. Customer insert his Paypal account information

4a. Paypal check the account information (If the customer is not login ask to login)

5a. Paypal pay to the vendor for the item and add the payment on the Paypal registerd credit card

**Exceptions**

The site validate that the customer is active 

