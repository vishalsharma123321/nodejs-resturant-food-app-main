<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Food App</title>
</head>
<body>
    <h1>Restaurant Food App <img src="https://via.placeholder.com/30x30?text=🍽️" alt="Food App Icon"></h1>

    <p>A full-stack restaurant food application built with Node.js and Express. This application allows users to manage food categories, view and order food items, and handle user authentication.</p>

    <h2>Features</h2>
    <ul>
        <li>User authentication and authorization 🔒</li>
        <li>CRUD operations for food items and categories 🍲</li>
        <li>RESTful API endpoints for managing data 🌐</li>
        <li>Admin middleware for protected routes 🛡️</li>
    </ul>

    <h2>File Structure</h2>
    <pre>
<code>
nodejs-resturant-food-app-main
├── config
│   └── db.js                 # Database connection configuration
├── controllers
│   ├── authControllers.js    # User authentication logic
│   ├── categoryController.js # Category management logic
│   ├── foodController.js     # Food item management logic
│   ├── resturantController.js # Restaurant management logic
│   ├── testController.js     # Test logic
│   └── userController.js     # User management logic
├── middlewares
│   ├── adminMiddleware.js    # Middleware for admin routes
│   └── authMiddleware.js     # Middleware for authentication
├── models
│   ├── categoryModel.js      # Category schema and model
│   ├── foodModal.js          # Food item schema and model
│   ├── orderModel.js         # Order schema and model
│   ├── resturantModel.js     # Restaurant schema and model
│   └── userModel.js          # User schema and model
├── routes
│   ├── data.js               # Example routes file
├── package-lock.json
├── package.json              # Project dependencies and scripts
└── server.js                 # Entry point of the application
</code>
    </pre>

    <h2>Installation</h2>
    <ol>
        <li>Clone the repository:</li>
        <pre><code>git clone https://github.com/yourusername/restaurant-food-app.git</code></pre>

        <li>Navigate to the project directory:</li>
        <pre><code>cd restaurant-food-app</code></pre>

        <li>Install the dependencies:</li>
        <pre><code>npm install</code></pre>

        <li>Configure the database connection in <code>config/db.js</code>.</li>

        <li>Start the server:</li>
        <pre><code>npm start</code></pre>
    </ol>

    <h2>Usage</h2>
    <p>Access the application at <a href="http://localhost:3000">http://localhost:3000</a>.</p>
    <p>API endpoints:</p>
    <ul>
        <li><code>POST /api/auth/login</code> - Login a user 🏷️</li>
        <li><code>POST /api/auth/register</code> - Register a new user ✍️</li>
        <li><code>GET /api/categories</code> - Get all categories 📋</li>
        <li><code>POST /api/categories</code> - Create a new category 🆕</li>
        <li><code>GET /api/food</code> - Get all food items 🍽️</li>
        <li><code>POST /api/food</code> - Add a new food item 🍲</li>
    </ul>

    <h2>Contributing</h2>
    <p>Feel free to submit issues or pull requests if you have any suggestions or improvements. 🤝</p>

    <h2>License</h2>
    <p>This project is licensed under the MIT License - see the <a href="LICENSE">LICENSE</a> file for details.</p>

    <h2>Contact</h2>
    <p>For any questions, please reach out to me at <a href="mailto:vishalsharma2@shooliniuniversity.com">vishalsharma2@shooliniuniversity.com</a> 📧</p>
</body>
</html>
