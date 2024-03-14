## Introduction
This is a food ordering app built using the MERN stack (MongoDB, Express.js, React.js, Node.js). It allows users to browse through  
available menu items, place orders, and make payments securely using Stripe integration.
## Description

The Food Ordering App is a web application designed to streamline the process of ordering food online. It provides users with a platform to browse through available menu items, place orders, and make payments securely using Stripe integration.

## Technologies

The Food Ordering App is built using the MERN stack (MongoDB, Express.js, React.js, Node.js) along with other technologies for robustness, security, and user-friendliness:

- MongoDB: NoSQL database used for storing application data.
- Express.js: Web application framework for Node.js used for building RESTful APIs.
- React.js: JavaScript library for building user interfaces.
- Node.js: JavaScript runtime environment for server-side development.
- CSS, Bootstrap: For styling and ensuring a responsive design for the web application.
- Stripe: Payment processing platform used for secure online payments.
- Heroku: Cloud platform used for deploying and hosting the web application.

## How to Run

To run the Food Ordering App locally on your machine, follow these steps:

1. Clone the repository from GitHub.
2. Install dependencies by running `npm install` in the root directory.
3. Navigate to the server folder and install dependencies by running `npm install`.
4. Configure environment variables by creating a `.env` file in the root directory and filling in the required values (refer to the README for details).
5. Start the server from the server folder by running `node index.js` or `nodemon index.js`.
6. Start the app in the development mode by running `npm start` in the root directory.
7. Access the application through your web browser at [http://localhost:3000](http://localhost:3000).

## Environment Variables

To store your environment variables, create a `.env` file in the root of your project and fill in the following values:
STRIPE_SECRET_KEY=""
STRIPE_WEBHOOK_SECRET=""
REACT_APP_STRIPE_PUBLISHABLE_KEY=""
REACT_APP_FIREBASE_CONFIG_API_KEY=""
REACT_APP_FIREBASE_CONFIG_AUTH_DOMAIN=""
REACT_APP_FIREBASE_CONFIG_PROJECT_ID=""
REACT_APP_FIREBASE_CONFIG_STORAGE_BUCKET=""
REACT_APP_FIREBASE_CONFIG_MESSAGING_SENDER_ID=""
REACT_APP_FIREBASE_CONFIG_APP_ID=""
REACT_APP_FIREBASE_CONFIG_MEASUREMENT_ID=""

## Usage

- Browse Menu: Users can browse through available menu items.
- Place Order: Users can place orders by selecting items and specifying quantities.
- Make Payment: Secure online payment using Stripe integration.
- View Order History: Users can view their order history and track the status of their orders.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

If you have any questions or suggestions regarding the Food Ordering App, feel free to contact us at chaitanya.chaudhari91@gmail.com