# Note-App  

A fully functional note-taking application built using the **MERN (MongoDB, Express, React, Node.js)** stack. This app allows users to create, edit, view, and delete notes with a clean and responsive user interface.  

## **Features**  

- **User-Friendly Interface**: A clean and intuitive design for easy note management.  
- **Create Notes**: Add new notes with a title and content.  
- **Edit Notes**: Modify existing notes anytime.  
- **Delete Notes**: Remove notes that are no longer needed.  
- **Responsive Design**: Optimized for devices of all screen sizes.  
- **Efficient Backend**: RESTful APIs built with Express.js and Node.js.  
- **Secure Data Storage**: Notes are stored securely in a MongoDB database.  

## **Technologies Used**  

### **Frontend**  
- **React.js**: For building the user interface.  
- **CSS**: For styling and layout.  

### **Backend**  
- **Node.js**: Runtime environment for server-side execution.  
- **Express.js**: Framework for building RESTful APIs.  

### **Database**  
- **MongoDB**: For storing user notes.  

## **Setup and Installation**  

### **Prerequisites**  
- Node.js installed on your machine.  
- MongoDB installed locally or access to a MongoDB Atlas cluster.  
- Git for version control.  

### **Steps to Run Locally**  

1. **Clone the repository**:  
   ```bash  
   git clone https://github.com/your-username/note-app.git  
   cd note-app  
   ```  

2. **Install dependencies**:  
   Navigate to both the `backend` and `frontend` directories and install the required dependencies.  

   **For backend**:  
   ```bash  
   cd backend  
   npm install  
   ```  

   **For frontend**:  
   ```bash  
   cd frontend  
   npm install  
   ```  

3. **Set up environment variables**:  
   Create a `.env` file in the `backend` directory with the following details:  
   ```env  
   MONGO_URI=<your-mongodb-connection-string>  
   PORT=5173  
   ```  

4. **Run the backend server**:  
   ```bash  
   cd backend  
   npm run dev  
   ```  

5. **Run the frontend development server**:  
   ```bash  
   cd frontend  
   npm run dev  
   ```  

6. Open your browser and navigate to `http://localhost:5173` to view the application.  
