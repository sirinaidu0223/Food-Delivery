🍕 Food Delivery — Frontend
A modern, responsive food delivery web application built with React.js. Users can browse food categories, add items to cart, place orders, and track their delivery — all through a clean and intuitive interface.

🚀 Live Demo

Add your deployed link here (e.g., Vercel / Netlify / Render)


📸 Screenshots

Add screenshots of your app here


✨ Features

🏠 Home Page — Hero section with featured food items
🍔 Food Menu — Browse items by category with filtering
🛒 Cart — Add, remove, and update item quantities
🔐 Authentication — Login / Signup popup with JWT support
📦 Order Placement — Enter delivery address and place orders
📋 My Orders — View order history and status
📱 Responsive Design — Works seamlessly on all screen sizes


🛠️ Tech Stack
TechnologyPurposeReact.jsFrontend UI frameworkReact RouterClient-side routingContext APIGlobal state managementAxiosAPI requests to backendCSS / ModulesStyling and layout

📁 Project Structure
frontend/

├── public/

│   └── index.html

├── src/

│   ├── assets/  # Images and icons

│   ├── components/      # Reusable components

│   │   ├── Navbar/

│   │   ├── Footer/

│   │   ├── FoodItem/

│   │   ├── FoodDisplay/

│   │   ├── LoginPopup/
│   │   └── ExploreMenu/

│   ├── context/         # Global state (Cart, Auth)

│   ├── pages/           # Page-level components

│   │   ├── Home/

│   │   ├── Cart/

│   │   ├── PlaceOrder/

│   │   └── MyOrders/

│   ├── App.jsx

│   └── main.jsx

├── package.json

└── .env

⚙️ Getting Started
Prerequisites

Node.js (v16 or above)
npm or yarn

Installation

Clone the repository

bashgit clone https://github.com/sirinaidu0223/Food-Delivery.git
cd Food-Delivery/frontend

Install dependencies

bashnpm install

Set up environment variables

Create a .env file in the frontend/ directory:
envVITE_API_URL=http://localhost:4000

Replace with your backend server URL if deployed.


Start the development server

bashnpm run dev
The app will be running at http://localhost:5173

🔗 Backend
This frontend connects to a Node.js + Express + MongoDB backend.
👉 See the backend folder for setup instructions.

🌐 Deployment
To build the project for production:
bashnpm run build
The output will be in the dist/ folder, ready to deploy on platforms like Vercel, Netlify, or Render.

🤝 Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.

Fork the repository
Create your feature branch: git checkout -b feature/your-feature
Commit your changes: git commit -m 'Add your feature'
Push to the branch: git push origin feature/your-feature
Open a Pull Request


📄 License
This project is open source and available under the MIT License.

👤 Author
Siri Naidu

GitHub: @sirinaidu0223
