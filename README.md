# Tomato: Food Ordering Application

Tomato is a full-stack web application designed to streamline the process of ordering food online. It provides users with a convenient platform to browse through various restaurants, view their menus, place orders, and make payments seamlessly. This README will guide you through setting up and running both the frontend and backend of the application.

## Features

- User authentication and authorization
- Browse restaurants and their menus
- Place orders for pickup or delivery
- Real-time order tracking
- Secure payment processing
- Admin Panel Management 

## Tech Stack

- **Frontend**: React.js, Redux, HTML, CSS
- **Backend**: Node.js, Express.js, MongoDB
- **Other Tools**: Stripe for payment processing, Socket.IO for real-time updates

## Prerequisites

- Node.js installed on your machine
- MongoDB installed and running locally or accessible remotely
- Stripe API keys (test mode for development)

## Getting Started

### Frontend Setup

1. **Navigate to the frontend directory**:
   ```bash
   cd frontend
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start the development server**:
   ```bash
   npm run dev
   ```

4. **Access the application**:
   Open your browser and go to [http://localhost:5173](http://localhost:5173).

### Backend Setup

1. **Navigate to the backend directory**:
   ```bash
   cd backend
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Set up environment variables**:
   - Create a `.env` file in the root of the backend directory.
   - Add the following variables:
     ```
     JWT_SECRET=<>
     STRIPE_SECRET_KEY=<>
     ```

4. **Start the backend server**:
   ```bash
   npm start
   ```

5. **The backend server will run on**:
   Open your browser and go to [http://localhost:4000](http://localhost:4000).

## Contributing

Contributions are welcome! If you have any suggestions, bug fixes, or feature implementations, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License.
