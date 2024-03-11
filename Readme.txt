
You can run available unittests from VS terminal using command: python manage.py test tests/

Don't forget to create a virtual environment and install requirements after activating it using :
pip install -r requirements.txt

And Also don't forget to create your mysql database and configure it in settings.py and then migrate models to it

# This path for static HTML content with images and styles
/restaurant

API paths:

# JDOSER endpoint, for example, to make POST request and create new user
/auth/users/ 

# to login and auth get token
/api-token-auth/ 
# to login using JDOSER endpoint
/auth/token/login 

# menu items
/restaurant/menu/
/restaurant/menu/{menuItemId}

# table booking 
/restaurant/booking/tables/
/restaurant/booking/tables/{bookingId}

