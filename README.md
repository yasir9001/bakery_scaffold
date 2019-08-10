# Instructions 

Add the following item to your Dashboard products and complete the provided "order.html" form to include a Client checkout integration. Have the cancel URL return back to order form, and have the success URL direct the customer to order_success.html. Pass the checkout sesssion id to the order_success.html file.

Dashboard Product:
One time purchase product
Product Name: Cupcake

SKU:
Name: Chocolate cupcake
Currency: USD
Amount: $3.25

The repository includes the following files:
/order.html: complete this form to integrate with Checkout
/order_success.html: the application should redirect here when Checkout is successful
/img/cupcake.jpg use this image for your SKU

Make a .env file from env.example and place your stripe API key in it.