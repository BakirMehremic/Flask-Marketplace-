This is my first web app project, built with Flask, MySQL is used to create the database and then connected 
to the Flask_SQLAlchemy ORM so it is easier to query and insert data. It uses a few of the popular flask
extensions for the admin panel, login, bycrpyt, login, forms etc. The frontend is built with html css and bootstrap
since my focus was on learning and practicing Flask.

The users can sign up, log in, post products for sale, leave comments and reviews on each others products, add to cart,
buy from cart, buy products directly, edit their products, profiles, delete accounts, delete produts, delete from cart...

To run the project, execute the sql in db.txt in MySQL Workbench, Dbeaver or some other DB tool to create the tables
and populate them with example data.
Next, configure your localhost user and password in flaskmarketplace/__init__.py
After that, just pip install -r requirements.txt and run the run.py file.
