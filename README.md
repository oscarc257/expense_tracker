# React-Node Expense Tracker Web App 

Welcome to the React-Node Budget Tracker Web App! This application allows users to view, add, and manage their everyday expenses. It's built using React for the frontend and Node.js with Prisma and Postgres(Thru Suppabase) for the backend. In more formal words, this stack combines modern frontend and backend technologies with a cloud-hosted database and selfmade/external API integration to create a full-stack budgeting application.

## Getting Started 🚀

### Prerequisites:

- Node.js and npm installed on your machine.
- An account on [Render](https://www.render.com/) for the deployment.
- Can use [Render] or [Suppabase] for database and migrate using prisma.  
- A [ExchangeRate-API](https://app.exchangerate-api.com/) for the CURRENCY API.

### Setting Up:


1. **Setting up the Backend**:

   - Navigate to the backend directory:
     ```bash
     cd backend
     ```

   - Install the necessary packages:
     ```bash
     npm install
     ```

   - **EXCHANGERATE API**:
     - Added the api key to the API_KEY variable in the .env file   

   - **Render or Supabase Setup**:
     - Create a new database instance on Render or Supabase.
     - Copy the connection string provided by Render or Supabase.

   - **Prisma Setup**:
     - Replace the `DATABASE_URL` in the `.env` file with your Postgresql connection string.
     - Initialize Prisma and generate the Prisma client:
       ```bash
       npx prisma init
       npx prisma generate
       ```

   - Start the backend server:
     ```bash
     npm run server or nodemon
     ```

2. **Setting up the Frontend**:

   - Navigate to the frontend directory:
     ```bash
     cd frontend
     ```

   - Install the necessary packages:
     ```bash
     npm install
     ```

   - Start the frontend development server:
     ```bash
     npm run dev or npm start
     ```

3. **Deployment on Render**: 

   - To test app directly from render, please use the following link:  https://budgetly-0ige.onrender.com 

4. **Technology Stack Used** 
   
   - Frontend: 
      React: A JavaScript library for building user interfaces.
      Build React App
      React Icons: For adding icons to the UI.
      SCSS: For styling the application.
  
   - Backend:
      Node.js: A JavaScript runtime for building the backend server.
      Express: A web framework for Node.js to handle API routes.
      Prisma: An ORM (Object-Relational Mapping) tool for interacting with the PostgreSQL database.
      dotenv: For managing environment variables.
      CORS: Middleware to handle Cross-Origin Resource Sharing.
      node-fetch: For making HTTP requests to the API.
   
   - Database
      PostgreSQL: A relational database used to store user data and favorite recipes.
      Render or Supabase: Cloud platforms for hosting the PostgreSQL database.
   
   - External API:
      Spoonacular API: A third-party API for fetching recipe data.
   
   - Development Tools: 
      Nodemon: For automatically restarting the server during development.
      Prisma CLI: For database migrations and generating the Prisma client. 
   
   - Deployment: 
      Render: For deploying the backend and database.
      Render Frontend Hosting: For hosting the React frontend.     