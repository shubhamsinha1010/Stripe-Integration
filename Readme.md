Setting up Stripe Checkout with Flask

Want to use this project?
Fork/Clone

Create and activate a virtual environment:

$ python3 -m venv venv && source venv/bin/activate
Install the requirements:

(venv)$ pip install -r requirements.txt
Add your Stripe test secret and publishable keys as environment variables like so:

(venv)$ export STRIPE_PUBLISHABLE_KEY=<YOUR_STRIPE_PUBLISHABLE_KEY>
(venv)$ export STRIPE_SECRET_KEY=<YOUR_STRIPE_SECRET_KEY>
In case you're planning to confirm payments using webhooks you also need to add the webhook endpoint environment variable as well:

(env)$ export STRIPE_ENDPOINT_SECRET=<YOUR_ENDPOINT_SECRET_KEY>
Run the server:

(venv)$ FLASK_ENV=development python app.py
Navigate to http://localhost:5000.