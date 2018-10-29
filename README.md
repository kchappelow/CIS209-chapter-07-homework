# CIS209 chapter 07 homework

Invoice Class

Create a class called *Invoice* that a hardware store might use to represent an invoice for an item sold at the store.
An *Invoice* should include four pieces of information as instance variables:
* a part number (type String)
* a part description (type String)
* a quantity of the item being purchased (type int)
* a price per item (type double)

Your class should have a constructor that initializes the four instance variables.

Provide a *set* and a *get* method for each instance variable.

In addition, provide a method named *getInvoiceAmount* that calculates the invoice amount, (i.e., multiplies the quantity by the price per item), then returns the amount as a double value.

If the quantity is not positive, it should be set to 0.
If the price per item is not positive, it should be set to 0.0.

Write a test app named *InvoiceTest* that demonstrates clas Invoice's capabilities.

Create a UML class diagram for the *Invoice* class.

Submit the UML class diagram, the Invoice class and the InvoiceTest class using git.
