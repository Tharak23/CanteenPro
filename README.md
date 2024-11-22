CANTEENPRO
Your go-to solution for seamless canteen management! CANTEENPRO combines user-friendly design with powerful functionality, enabling customers to effortlessly place orders and providing canteen owners with full control over operations.
Canteen Owner Dashboard
A comprehensive dashboard for canteen owners to manage menu items, track orders, update order statuses, and view sales analytics, all in a user-friendly interface.

Features
Menu Management
Add, edit, and delete items.
Categorize items into sections like Snacks, Beverages, Meals, Juices, Milkshakes, etc.
Set item availability (e.g., In Stock, Out of Stock).
Dynamic pricing updates for menu items.
Upload images for items for better user representation.
Order Management
Real-Time Order Tracking:

View current orders with status: Preparing, Ready, Taken.
Update status dynamically with a single click.
Timers for tracking preparation and delivery times.
Previous Orders:

Access history with itemized breakdowns and total costs.
Filter orders by date range, status, or user.
Analytics Dashboard
Sales Insights:
Daily, weekly, and monthly revenue reports.
Identify top-selling items.
Feedback Summary:
Collect and analyze customer feedback on menu items and overall experience.
Receipt Management
Automatically generate receipts for completed orders.
Download or email receipts directly to customers.
View past receipts with order details and costs.
Getting Started
Prerequisites
Ensure you have the following installed:

Node.js (v16 or higher)
MongoDB (for database storage)
React (for frontend interface)
Express.js (for backend)
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/username/canteen-owner-dashboard.git
cd canteen-owner-dashboard
Install dependencies:
bash
Copy code
npm install
Start the development server:
bash
Copy code
npm run dev
Open the app in your browser:
arduino
Copy code
http://localhost:3000
Usage
Menu Management
Navigate to the Menu tab to add or edit items.
Fill in details like name, price, category, availability, and image.
Order Tracking
Access Current Orders to view real-time status.
Use buttons to update status between Preparing, Ready, Taken.
View Previous Orders for history and receipts.
Analytics
Go to the Analytics tab for insights on sales, performance, and feedback.
Project Structure
bash
Copy code
CANTEENPRO/
├── src/
│   ├── components/
│   │   ├── auth/                     # Authentication components
│   │   │   └── CanteenRegistration.tsx
│   │   ├── Analytics.tsx            # Analytics dashboard
│   │   ├── Dashboard.tsx            # Main admin dashboard
│   │   ├── Feedback.tsx             # Feedback management
│   │   ├── FoodItems.tsx            # Menu and food items management
│   │   ├── Notifications.tsx        # Notifications for orders and updates
│   │   ├── Orders.tsx               # Current and past orders
│   │   ├── Payments.tsx             # Payment details and transactions
│   │   ├── Settings.tsx             # User settings
│   │   ├── Sidebar.tsx              # Sidebar navigation
│   │   └── TopBar.tsx               # Top navigation bar
│   ├── context/                     # Global state management
│   │   ├── AppContext.tsx
│   │   └── AuthContext.tsx
│   ├── types/                       # TypeScript type definitions
│   ├── App.tsx                      # Root app component
│   ├── main.tsx                     # App entry point
│   └── index.css                    # Global CSS styles
├── tailwind.config.js               # Tailwind CSS configuration
├── vite.config.ts                   # Vite configuration
└── tsconfig.json                    # TypeScript configuration
Contact
For queries or support, contact:
Tharak Nagaveti
Email: tharaknagaveti@example.com
