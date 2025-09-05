**Food-It Project**

This project has three parts:

-Backend
-Frontend
-Admin Panel
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Backend Setup**

Navigate into the backend folder.

Run:
npm install and
npm run server

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


**Frontend Setup**

Navigate into the frontend folder.
Run:
npm install and
npm run dev

The app runs at http://localhost:3000 by default.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


**Admin Panel Setup**

Navigate into the admin folder.

Run:
npm install and 
npm run dev

The admin runs at a different port, commonly http://localhost:3001.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**MongoDB Atlas Connection Setup**

Sign in to MongoDB Atlas
Create a cluster.
Create a database user and password. Avoid using @ in passwords to prevent issues.
Whitelist 0.0.0.0/0 or your IP address.
Copy the connection string and add it to your backend .env file:

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Stripe Setup**

Sign in to Stripe Dashboard
Go to Developers > API Keys.
Copy the Secret Key.
Add it to your backend .env file:

