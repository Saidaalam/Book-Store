# Book-Store

Bookstore Application :

A full-stack application for managing books and orders in a bookstore, with revenue calculation functionality.

Features :
Books Management: Add, update, delete, and view books.
Orders Management: Create and view orders.
Revenue Calculation: Calculate total revenue from all orders.
Error Handling: Comprehensive and user-friendly error responses.

Technologies :
Backend: Node.js, Express.js
Database: MongoDB
Language: TypeScript

API Endpoints
Books: /api/products (GET, POST, PUT, DELETE)
Orders: /api/orders (POST), /api/orders/revenue (GET)

Instruction to setting up this project:
1. Clone the Repository
2. Set Up Environment Variables :
   DATABASE_URL=mongodb+srv://bookstore:bookstore789@cluster0.j2dvp.mongodb.net/?retryWrites=true&w=majority&appName=Cluster0
   PORT=5000
3. Install Dependencies :
   npm install
4. Run the Application Locally :
   npm run dev
   
Open any browser and visit: http://localhost:5000
