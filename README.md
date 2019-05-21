# Shopping-Cart
  Task 1:
-I implemented the list of products, in descending order by price, with de USD default currency.
-For each product I added the "add to cart" button.

  Task 2:
-I implemented here the button for editable quantity under the products name and price.
-The description pop-up is working just for the first product to my dissapointment.
-I added the "remove" button under the "add to cart" button.
-The total price per product would be implemented as a function whic multiply the product
price with the number which is selected in the quantity section.

  For the 3rd and 4th task I would implemented an array with elements of type "products"
where at the action of the button "add to cart" the respective product would be added by a push
function and removed by a pop function at the action of the button "remove".
  For the currency conversion I would use a funcion which check the currency name and made
the conversion by mathematic operations.
For example:

-the function is implemented in C++
double conversion( double price,string c)
{
    if(c=="EUR")
    {
      price=price*0.896;
    }
      else if(c=="GBP")
    {
      price=price*0.786;
    }
 return price;
 }
 

