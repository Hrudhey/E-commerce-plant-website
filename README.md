E-commerce Plant Website
A full-stack e-commerce web application for selling plants online, featuring modern technologies, secure payment, and an intuitive admin dashboard.

Features
User Authentication: Account registration, login, JWT-based session management.

Product Catalog: Browse a variety of plants with images and descriptions.

Shopping Cart: Add, update, and remove plants in your cart.

Order Management: Place orders, view your order history.

Payment Integration: Secure payments via Stripe.

Image Upload: Upload product images (admin-side).

Admin Panel: Manage products, orders, and users from a dedicated admin dashboard.

Technology Stack
Frontend:

React 18 (with Vite for development)

React Router DOM

Axios

Backend:

Node.js and Express

MongoDB with Mongoose

JWT for authentication

Bcrypt for password hashing

Multer for file uploads

Stripe for payments

Admin:

Separate React app for admin functionality

Folder Structure
text
/admin      # Admin dashboard (React)
/backend    # Express API, MongoDB/Mongoose, Stripe integration
/frontend   # User-facing website (React + Vite)
Getting Started
Clone the repository:

text
git clone https://github.com/Hrudhey/E-commerce-plant-website.git
Backend setup:

Install dependencies:

text
cd backend
npm install
Copy .env.example to .env and add your environment variables.

Start server:

text
npm start
Frontend setup:

Install dependencies:

text
cd ../frontend
npm install
Start development server:

text
npm run dev
Admin dashboard setup:

Install dependencies:

text
cd ../admin
npm install
Start dashboard:

text
npm run dev
Environment Variables
Please add your environment variables for the backend in a .env file in the /backend directory:

text
PORT=
MONGODB_URI=
JWT_SECRET=
STRIPE_SECRET_KEY=
Note: Never commit your .env file or credentials to source control.

License
This project is licensed under the ISC License.
