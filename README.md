 Chatty App

Chatty is a real-time chat application built with React.js, Zustand for state management, and Socket.io for real-time communication. This app allows users to sign up, log in, chat with others, and manage their profile settings.

## Project Structure

The project is organized as follows:

/chatty-app
│
├── /public
│   ├── index.html               # Main HTML file
│   └── favicon.ico              # Favicon
│
├── /src
│   ├── /assets                  # Static files like images, icons, etc.
│   │   └── logo.png
│   │
│   ├── /components              # Reusable components (Navbar, Sidebar, etc.)
│   │   ├── Navbar.jsx
│   │   ├── Sidebar.jsx
│   │   └── ProfileCard.jsx
│   │
│   ├── /pages                   # Page components
│   │   ├── Home.jsx             # Home page
│   │   ├── Settings.jsx         # Settings page
│   │   ├── Profile.jsx          # User Profile page
│   │   └── Chat.jsx             # Chat window/page
│   │
│   ├── /store                   # Zustand store (for state management)
│   │   └── useAuthStore.js      # Store related to authentication & socket
│   │
│   ├── /lib                     # Utility files (like axios instance, etc.)
│   │   └── axios.js             # Axios configuration
│   │
│   ├── /styles                  # Tailwind CSS or custom styles
│   │   └── tailwind.config.js   # Tailwind configuration
│   │
│   ├── App.jsx                  # Main app component
│   ├── index.js                 # Entry point of the application
│   └── vite.config.js           # Vite configuration (if using Vite)
│
├── /node_modules                # Dependencies
│
├── package.json                 # Project metadata and dependencies
└── README.md                    # Project documentation (this file)

backend/
├── config/
│   └── db.js               # MongoDB connection setup
│   └── cloudinary.js        # Cloudinary configuration
│   └── jwt.js               # JWT authentication utilities
├── controllers/
│   └── authController.js    # Authentication-related functions (login, signup)
│   └── employeeController.js# Employee-related CRUD functions
│   └── flightController.js  # Flight status-related functions
├── middleware/
│   └── authMiddleware.js    # JWT authentication middleware
│   └── errorMiddleware.js   # Error handling middleware
├── models/
│   └── User.js              # User schema (for authentication)
│   └── Employee.js          # Employee schema
│   └── Flight.js            # Flight schema
├── routes/
│   └── authRoutes.js        # Auth routes (login, signup)
│   └── employeeRoutes.js    # Employee-related routes
│   └── flightRoutes.js      # Flight-related routes
├── utils/
│   └── sendSMS.js           # SMS sending functionality using Firebase
├── .env                     # Environment variables (do not share this file)
├── .gitignore               # To ignore node_modules and other sensitive files
├── server.js                # Main entry point (Express app setup)
└── package.json             # Project dependencies and scripts

PORT=5000

MONGODB_URI=.....

JWT_SECRET=yourSuperSecretJWTKey

CLOUDINARY_CLOUD_NAME=yourCloudinaryCloudName
CLOUDINARY_API_KEY=yourCloudinaryApiKey
CLOUDINARY_API_SECRET=yourCloudinaryApiSecret

NODE_ENV=development

<img width="1920" height="1080" alt="Screenshot (145)" src="https://github.com/user-attachments/assets/b8b86098-b64b-4fe9-9969-b06981e24151" />
<img width="1920" height="1080" alt="Screenshot (146)" src="https://github.com/user-attachments/assets/8fe11767-5068-460b-bb57-3e273207aabc" />
<img width="1920" height="1080" alt="Screenshot (147)" src="https://github.com/user-attachments/assets/51c736fa-5beb-4093-ae44-636f024c5638" />



