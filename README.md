# E-Commerce-Billing-System

<b>Objective:</b>
<br>
Create an advanced billing system for an e-commerce application that allows users to input product details, apply GST, select discount offers, remove products, and calculate the final bill. The system should provide a detailed invoice with a breakdown of each item, taxes, discounts, and the total amount in Indian Rupees (₹).

<b> Explaination: </b>
<br>
<ul>

<li> Initialization of Lists: </li>

ProductIdList, ProductNameList, QuantityList, UnitPriceList, and SubTotalList are initialized as empty lists to store product details.

<li> Input Function: </li>

A loop collects product details (ID, name, quantity, unit price) from the user until they choose to stop.
It ensures each product ID is unique.

<li> Displaying Product List:</li>

Prints the list of products added by the user.

<li> Removing a Product:</li>

Asks the user if they want to remove a product.
If yes, it removes the product with the specified ID and displays the updated list.

<li> Subtotal Calculation: </li>

Calculates the subtotal for each product (quantity * unit price) and adds it to SubTotalList.

<li> Final Total Calculation: </li>

Sums up all subtotals to get the FinalTotal.

<li> GST Calculation: </li>

Asks if the user wants to add GST.
If yes, calculates GST based on the provided rate and updates the total with GST (totalwithGst).
If no, sets GST to 0.

<li> Discount Function: </li>

Provides three discount options: percentage on total, fixed amount, and discount on a specific product.
Calculates the discount based on the selected option and updates the final total after the discount (FinalTotalafterdiscount).

<li> Applying Discount: </li>

Asks if the user wants to apply a discount and calls the discount function if yes.

<li> Invoice Output: </li>

Prints the invoice with details of each product, the total before discount, GST amount, discount amount, and the final total.
</ul>

<b> Input Overview: </b>


![image](https://github.com/user-attachments/assets/a25b23ae-a24a-4cfa-99ed-6baa4f67e104)


<b> OverView of the Output: </b>

![Screenshot 2024-08-02 165132](https://github.com/user-attachments/assets/21b07f11-488e-418c-b201-3c0a86616e2b)

