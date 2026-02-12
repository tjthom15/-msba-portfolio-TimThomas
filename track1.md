What 3–5 source tables would you expect a real company to use for
customer churn? For each source, what does one row represent, for example
one customer, one month, one event
1. Customers - One row would be the demographic of the customer
3. Billing - Billing infomation like service and billing type
4. Usage - how often do they use the product? 
5. Subscription types - What is the standard tenture and subscription type 

o What keys would you use to connect the data, for example customer_id,
account_id, date, etc?
1. Customers= Customer_ID would be the primary key.
2. Billing= Invoice_ID Primary Key with Customer_ID as Secondary Key
3. Usage= Login_ID Primary with Customer_ID as a Secondary
4. Subscription= Sub_ID is primary with Customer_ID as Secondary
5. Support= Ticket_ID primary ID with Customer_ID as Secondary

o What are two risks and how would you reduce them? Examples of risks are
duplicates, missing IDs, using information that only exists after churn
happens, and definitions changing over time

I have had a fairly expensive watch from shinoda mailed to my house because they did 
have a check point to double check the mailing address. I just sent them an email and they
quickly changed the mailing address to mine. It was not my watch. (I called the store 
and mailed it back). People faking infomation in a data base or miss representing the data. Basic Fraud. 

People representing multiple accounts but are the same person. Many organizations 
use phone numbers or other methods to varify accounts. 

