# Fashion Hub

Welcome to **Fashion Hub**, your ultimate online shopping destination for the latest trends in clothing and accessories. This application is built using the MERN stack and includes both user and admin functionalities.

## Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Folder Structure](#folder-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features
- **User Functionality:**
  - User registration and login
  - Browse a wide range of fashion products
  - Add products to the cart
  - Secure checkout process

- **Admin Functionality:**
  - Admin dashboard for managing products and orders
  - Ability to add, edit, or delete products

## Tech Stack
- **Frontend:** React.js, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Payment Gateways:** Razorpay, Stripe

## Folder Structure
```plaintext
FashionHub-ecommerce/
├── admin/                 # Admin code (Separate functionalities)
│   ├── node_modules/      # Installed Node.js modules for admin
│   ├── public/            # Public assets for admin
│   ├── src/               # Source files for admin functionalities
│   ├── .gitignore         # Git ignore file
│   ├── README.md          # Admin documentation
│   ├── eslint.config.js    # ESLint configuration
│   ├── index.html         # Main HTML file for admin
│   ├── package-lock.json  # NPM package lock file
│   ├── package.json       # NPM package configuration for admin
│   ├── postcss.config.js   # PostCSS configuration
│   ├── tailwind.config.js   # Tailwind CSS configuration
│   └── vite.config.js      # Vite configuration
├── backend/               # Backend code
│   ├── node_modules/      # Installed Node.js modules for backend
│   ├── config/            # Configuration files
│   ├── controllers/       # Logic for handling requests
│   ├── middleware/        # Middleware functions
│   ├── models/            # MongoDB models
│   ├── routes/            # API routes
│   ├── package-lock.json  # NPM package lock file
│   ├── package.json       # NPM package configuration for backend
│   └── server.js          # Main server file
├── frontend/              # Frontend code (User interface)
│   ├── node_modules/      # Installed Node.js modules for frontend
│   ├── public/            # Public assets
│   ├── src/               # Source files for frontend functionalities
│   ├── .gitignore         # Git ignore file
│   ├── README.md          # Frontend documentation
│   ├── eslint.config.js    # ESLint configuration
│   ├── index.html         # Main HTML file for frontend
│   ├── package-lock.json  # NPM package lock file
│   ├── package.json       # NPM package configuration for frontend
│   ├── postcss.config.js   # PostCSS configuration
│   ├── tailwind.config.js   # Tailwind CSS configuration
│   └── vite.config.js      # Vite configuration
└── README.md              # Project documentation
```
## Installation
To get a local copy up and running, follow these steps:

1.Clone the repository:

```git clone https://github.com/hariom029/FashionHub-ecommerce.git  ```

2. Navigate to the project directory:

```cd FashionHub-ecommerce```

3.Install the necessary dependencies:

 (i) For the backend:

```
cd backend
npm install
```

  (ii) For the frontend:

  ```
    cd frontend
    npm install
  ```

(iii) For the admin:

```
  cd admin
  npm install
```

(iv) Create a .env file in each directory (admin, backend, and frontend) and add your environment variables:

```
JWT_SECRET=<your_jwt_secret>
STRIPE_SECRET_KEY=<your_stripe_secret_key>
VITE_BACKEND_URL=<your_backend_uri>
VITE_RAZORPAY_KEY_ID=<your_razorpay_key_id>
RAZORPAY_KEY_SECRET=<your_razorpay_secret_key>
MONGODB_URL ==<your_mongodb_uri>
CLOUDINARY_API_KEY = <your_cloudinary_key>
CLOUDINARY_SECRET_KEY =<your_cloudinary_secret_key>
CLOUDINARY_NAME = <your_cloudinary_name>
ADMIN_EMAIL=<Admin_Email>
ADMIN_PASSWORD =<Admin_Password>
```

## Usage : 

- Navigate to http://localhost:5173 for the user interface.
- Navigate to http://localhost:5174 for the admin dashboard.
- Register or log in to your account.
- Browse products, add them to your cart, and proceed to checkout.

## Contributing

Contributions are welcome! Please follow these steps:

Fork the repository.
- Create a new branch (git checkout -b feature/YourFeature).
- Make your changes and commit them (git commit -m 'Add some feature').
- Push to the branch (git push origin feature/YourFeature).
- Create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.






