A Phone store created with Django :

Functionality:

Product Listing:

Display a list of Realme phones available in the store.
Show product details such as name, image, price, and description.

Product Detail Page:

Provide a dedicated page for each  phone with detailed information.


Shopping Cart:

Allow users to add  phones to their shopping cart.
Display the contents of the cart, including product names, quantities, and total price.

User Authentication:

Implement user authentication to allow users to register, log in, and log out.
Authenticated users can make purchases.

Order Processing:

Allow users to place orders and view their order history.
Send order confirmation emails to users.

Admin Panel:

Provide an admin panel to manage Realme products, orders, and user accounts.




Setup to run the application

first thing to do is to clone repository :

    $ git clone https://github.com/WebDevZakaria/phonestore.git
     
    $ cd phonestore
    
Create a virtual environment to install dependencies in and activate it:

    $ virtualenv venv
    
    $ venv\Scripts\activate

    
Then install the dependencies:

    (venv) $ pip install -r requirements.txt
    
Note the (venv) should be in the front of the prompt. this indicate that the terminal session is in a virtual env

Once downloading the dependencies has finished you can start the server by running:

(env) $ python manage.py runserver

And go to your browser and navigate to http://127.0.0.1:8000.





