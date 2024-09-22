Setting up Stripe Checkout with Flask

Want to use this project?
Fork/Clone

Create and activate a virtual environment:

$ python3 -m venv venv && source venv/bin/activate
Install the requirements:

(venv)$ pip install -r requirements.txt
Create a .env file with the following data

STRIPE_PUBLISHABLE_KEY=<YOUR_STRIPE_PUBLISHABLE_KEY>
STRIPE_SECRET_KEY=<YOUR_STRIPE_SECRET_KEY>
STRIPE_ENDPOINT_SECRET=<YOUR_ENDPOINT_SECRET_KEY>

Run the server:

(venv)$ FLASK_ENV=development python app.py
Navigate to http://localhost:5000.
