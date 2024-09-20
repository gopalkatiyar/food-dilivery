
# Food Delivery App

This is a full-stack Food Delivery Application where users can browse through restaurants, add food items to their cart, place orders, and securely pay using Stripe. The app includes features like real-time order tracking, an admin panel for managing restaurants, food items, and orders, and a responsive user interface.

## Features

- **User Authentication**: Sign up, log in, and log out with JWT for security.
- **Browse and Select**: Users can browse items, view menus, and add food items to their cart.
- **Order Placement**: Place orders for selected food items and view order history.
- **Payment Integration**: Secure payments through Stripe.
  
## Tech Stack

- **Frontend**: 
  - React.js
  - React Router for routing
  
- **Backend**:
  - Node.js
  - Express.js
  - MongoDB
  - JWT for authentication
  - Stripe for payment processing

## Installation

### Prerequisites

- Node.js installed on your machine
- MongoDB (local or cloud like MongoDB Atlas)
- Stripe account for payment processing

### Steps

1. Clone the repository:

```bash
git clone https://github.com/gopalkatiyar/food-dilivery.git
```

2. Install server dependencies:

```bash
cd backend
npm install
```

3. Install client dependencies:

```bash
cd ../frontend
npm install
```

4. Set up environment variables by creating a `.env` file in the `backend` directory with the following values:

```bash
MONGO_URI=your-mongodb-uri
JWT_SECRET=your-jwt-secret
STRIPE_SECRET_KEY=your-stripe-secret-key
CLOUDINARY_CLOUD_NAME=your-cloudinary-name
CLOUDINARY_API_KEY=your cloudinary-api-key
CLOUDINARY_API_SECRET=your-cloudinary-api-secret
```

5. Run the backend server:

```bash
cd backend
npm run server
```

6. Run the frontend:

```bash
cd ../frontend
npm run dev
```

## Features Breakdown

1. **Authentication**:
   - JWT-based authentication for login and signup.
   - Bcrypt used for password hashing.
   
2. **Payment Integration**:
   - Stripe integration for secure payments.
  
## Future Enhancements

- **Real-time notifications** for order status updates.
- **Multiple payment options** support.

## License

This project is licensed under the MIT License.
