# FìNT₹AX - MERN Stack Expense Tracker 📊💰

FìNT₹AX is a robust expense tracker developed using the MERN (MongoDB, Express.js, React.js, Node.js) stack with JWT authentication. It enhances financial awareness by sending email reminders when expense limits are approaching or exceeded. Users can efficiently manage their expenses and income for specific date ranges, gaining insights through comprehensive graphs and analyses powered by Chart.js.

## About the Project 📊💡

FìNT₹AX offers a dynamic and user-friendly MERN Stack solution for managing personal finances. The application provides a seamless experience with a wide range of features designed to offer a holistic approach to expense tracking.

Users can log, edit, and delete expenses and income entries with ease, organizing them by specific date and time ranges. The intuitive interface includes a sortable table for easy navigation through financial data. Filtering options allow users to focus on specific categories, and the search functionality simplifies the process of locating transactions. Email reminders keep users informed about their spending, promoting financial mindfulness and accountability.

With Chart.js, FìNT₹AX provides interactive graphs and analyses that reveal spending patterns and financial trends. Users can define custom date ranges for analysis, further enhancing the platform's utility and empowering informed financial decisions.

Secure JWT authentication ensures user privacy and data integrity, making FìNT₹AX a comprehensive solution for individuals aiming to take control of their finances and achieve their financial goals. 💰🚀

## Features
- ✅ **Authentication**: Secure JWT authentication for user accounts.
- ✅ **Expense and Income Management**: Add, edit, and delete expenses and income entries for specific dates and times.
- ✅ **Sortable Table**: Sort data based on various parameters for better organization.
- ✅ **Filtering**: Filter data to view specific categories of expenses and income.
- ✅ **Search Functionality**: Search for transactions by title, amount, or description.
- ✅ **Graphical Analysis**: Visualize transactions with dynamic graphs and charts generated with Chart.js.
- ✅ **Custom Date Range Analysis**: Define date ranges to analyze financial data effectively.
- ✅ **Email Reminders**: Receive email reminders when expense limits are approaching or exceeded, enhancing financial awareness.

## Technologies Used
- MongoDB
- Express.js
- React.js
- Node.js
- JWT Authentication
- Chart.js
- Primereact
- Nodemailer

### Starting the Backend

1. **Setup Environment Variables**:
   - Create a `.env` file in backend folder with the following parameters:
     - `MONGO_URI`: URL for MongoDB
     - `JWT_SECRET`: Any string for JWT secret
     - `GOOGLE_ID`: Email ID from which reminder emails are sent
     - `GOOGLE_PASS`: 12-Digit Password for the email ID (For generating refer-https://support.google.com/accounts/answer/185833?hl=en#:~:text=To%20help%20keep%20your%20account,2%2DStep%20Verification%20turned%20on)
   - Example:
     ```
     MONGO_URI="mongodb://127.0.0.1:27017/notesapp"
     JWT_SECRET="secretcode"
     GOOGLE_ID="youremailid@example.com"
     GOOGLE_PASS="xxxxxxxxxxxx"
     ```

2. **Navigate to the Backend Directory**:
   - Open the main folder in the command prompt.
   - Type `cd backend` to navigate to the backend directory.

3. **Install Dependencies**:
   - Run `npm install` to install all required node modules.

4. **Start the Server**:
   - Run `node ./server.mjs` to start the server-side application.

### Starting the Frontend

1. **Navigate to the Frontend Directory**:
   - Open the main folder in the command prompt.
   - Type `cd frontend` to navigate to the frontend directory.

2. **Install Dependencies**:
   - Run `npm install` to install all required node modules.

3. **Start the Client**:
   - Run `npm start` to start the client-side application.

4. **Access the Application**:
   - Visit `http://localhost:3000` in your web browser to access the application.
