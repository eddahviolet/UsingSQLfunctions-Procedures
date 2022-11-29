# UsingSQLfunctions&Procedures
I can now create complex Procedures and Functions in SQL 

I will be using MySQL stored fuctions and procedure to peform the tasks listed below on this Orders table


<img width="313" alt="orders table" src="https://user-images.githubusercontent.com/106580846/204504098-875b92a5-7363-481e-b46b-98bd3e0adbce.png">

Task 1
Create a SQL function that prints the cost value of a specific order based on the user input of the OrderID. The expected output result should be the same as the result in the screenshot below when you call the function with an OrderID of 5.

The query

![findcost function](https://user-images.githubusercontent.com/106580846/204504334-ee690ffc-16fc-49bb-aefa-fe9909392226.png)

The result

![using find cost](https://user-images.githubusercontent.com/106580846/204504515-fc3aef93-8d18-484f-9e4f-aede75581c90.png)

Task 2
Create a stored procedure that must return the final cost of the customer’s order after the discount value has been deducted. The discount value is based on the order’s quantity. The stored procedure must have the following specifications:
-The procedure should take one parameter that accepts a user input value of an OrderID. 
-The procedure must find the order quantity of the specificOrderID. 
-If the value of the order quantity is more than or equal to 20 then the procedure should return the new cost after a 20% discount. 
-If the value of the order quantity is less than 20 and more than or equal to 10 then the procedure should return the new cost after a 10% discount.


