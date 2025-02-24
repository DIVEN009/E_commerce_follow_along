# 📌 Project Name: E_Commerce_Follow_Along  

## 🚀 Overview  
This project is an e-commerce website developed through a series of milestones, progressively adding features to build a complete and functional application.  

## 📚 Table of Contents  
- [Overview](#-overview)  
- [Tech Stack](#-tech-stack)  
- [Milestones](#-milestones)  
  - [Milestone 1: Project Setup](#milestone-1-project-setup)  
  - [Milestone 2: Frontend & Backend Initialization](#milestone-2-frontend--backend-initialization)  
  - [Milestone 3: Backend Structure & Server Setup](#milestone-3-backend-structure--server-setup)  
  - [Milestone 4: Creating User Model and Controller](#milestone-4-creating-user-model-and-controller)  
  - [Milestone 5: Sign-Up Page & Form Validation](#milestone-5-sign-up-page--form-validation)  
  - [Milestone 6: Secure User Registration](#milestone-6-secure-user-registration)  
  - [Milestone 7: User Login & Authentication](#milestone-7-user-login--authentication)  
  - [Milestone 8: Product Card Component & Homepage Layout](#milestone-8-product-card-component--homepage-layout)  
  - [Milestone 9: Product Input Form](#milestone-9-product-input-form)  
  - [Milestone 10: Product Schema & Endpoint Creation](#milestone-10-product-schema--endpoint-creation)  
  - [Milestone 11: Dynamic Homepage with Product Data](#milestone-11-dynamic-homepage-with-product-data)  
  - [Milestone 12: My Products Page - Filtering by User Email](#milestone-12-my-products-page---filtering-by-user-email)  
  - [Milestone 13: Complete Project Documentation & Code Refactoring](#milestone-13-complete-project-documentation--code-refactoring)  
- [How to Run the Project](#-how-to-run-the-project)  
- [Next Steps](#-next-steps)  
- [Contributing](#-contributing)  
- [License](#-license)  

---

## 🛠 Tech Stack  
- **Frontend:** React.js, Tailwind CSS  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **File Uploads:** Multer  
- **Password Encryption:** bcrypt  
- **Version Control:** Git, GitHub  

---

## 📌 Milestones  

### Milestone 1: Project Setup  
✅ **Goals:**  
- Created and updated `README.md` file.  
- Initialized GitHub repository for version control.  

---

### Milestone 2: Frontend & Backend Initialization  
✅ **Goals:**  
1. **Project Folder Structure:** Organized files into separate frontend and backend directories.  
2. **React Frontend Setup:** Initialized a React application for building the user interface.  
3. **Node.js Backend Setup:** Set up a simple Node.js server for API integration in future milestones.  
4. **Tailwind CSS Configuration:** Integrated and configured Tailwind CSS for modern, responsive styling.  
5. **Login Page Development:** Created a login page with functionality and styling.  

---

### Milestone 3: Backend Structure & Server Setup  
✅ **Goals:**  
1. **Backend Folder Structure:** Created a structured hierarchy for organizing routes, controllers, models, and middleware.  
2. **Server Setup:**  
   - Used Node.js and Express.js to create a backend server.  
   - Configured the server to listen on a designated port.  
3. **Database Connection:**  
   - Integrated MongoDB for efficient data storage.  
   - Confirmed the connection between the server and MongoDB.  
4. **Error Handling:**  
   - Provided clear error messages for better debugging and user feedback.  

---

### Milestone 4: Creating User Model and Controller  
✅ **Goals:**  
1. **User Model:** Defined the structure of user data with attributes like name, email, password, and profile picture.  
2. **User Controller:** Handled user-related actions such as registration and data retrieval.  
3. **Multer Integration:** Enabled file uploads for storing user profile pictures.  
4. **API Routes:** Created endpoints for user creation and fetching user details.  
5. **README Update:** Documented progress and updated repository.  

---

### Milestone 5: Sign-Up Page & Form Validation  
✅ **Goals:**  
1. **Sign-Up Page UI:** Designed a clean and user-friendly sign-up form with fields for name, email, and password.  
2. **Form Validation:**  
   - Ensured the email follows the correct format.  
   - Implemented password security criteria (minimum length, special characters, etc.).  
3. **User Registration Flow:** Integrated frontend form submission with the backend API.  
4. **Error Handling:** Displayed validation errors to users in real-time.  
5. **README Update:** Documented progress and updated repository.  

---

### Milestone 7: User Login & Authentication  
✅ Goals:  
1. Login Endpoint: Created a backend endpoint for user login and verified user credentials.  
2. Password Validation: Utilized bcrypt for secure password comparison.  
3. Authentication Flow: Authenticated users based on matching hashed passwords.  
4. Security Considerations: Ensured secure handling of user credentials.  
5. README Update: Updated with details about the user login functionality.  

---

### Milestone 8: Product Card Component & Homepage Layout  
✅ Goals:  
1. Card Component Creation: Designed a reusable card component for displaying product details.  
2. Homepage Layout Design: Created a responsive grid layout for displaying multiple product cards.  
3. Dynamic Data Display: Implemented dynamic rendering of product cards using mapping.  
4. Consistency & Responsiveness: Ensured consistent styling and responsive design.  
5. README Update: Documented progress and learning outcomes for Milestone 8.  

---

### Milestone 9: Product Input Form  
✅ Goals:  
1. Product Form Creation:  
   - Designed a form for inputting product details such as name, description, price, and category.  
   - Included fields for uploading multiple product images.  
2. Image Upload Functionality:  
   - Implemented file input to accept multiple images.  
   - Configured frontend to preview selected images before submission.  
3. Form Validation & Error Handling:  
   - Ensured all required fields are filled out.  
   - Displayed validation errors for incomplete or incorrect inputs.  
4. Integration with Backend:  
   - Connected the form to the backend API for product creation.  
   - Stored product details and images in MongoDB.  
5. User Experience Enhancements:  
   - Provided a clean and user-friendly UI for the product input form.  
   - Added real-time feedback for image uploads and form validation.  
6. README Update:  
   - Documented the progress and learning outcomes for Milestone 9.  
   - Updated the repository with details about the product input form.  

---

### Milestone 10: Product Schema & Endpoint Creation  
✅ Goals:  
1. Product Schema Creation:  
   - Designed a Mongoose schema for product details including name, description, price, and image URL.  
   - Ensured each field has proper validation (e.g., required fields, correct data types).  
2. Endpoint Creation:  
   - Built a POST endpoint to receive product data.  
   - Validated and saved the product details to MongoDB.  
3. Why Validation?  
   - Ensures that only valid data is saved in the database, maintaining data integrity and preventing errors.  
4. Security Enhancements:  
   - Implemented additional validation and data integrity measures to ensure accurate and secure data storage.  
5. Next Steps (Optional):  
   - Experiment with adding features such as admin access control to allow only admins to upload products or creating user profiles with roles for managing the shop.
  
---

### Milestone 11: Dynamic Homepage with Product Data  

✅ **Goals:**  

#### 1️⃣ Backend - Fetch All Products  
- Created an API endpoint to retrieve all product data stored in MongoDB.  
- Used **Express.js** and **Mongoose** to fetch and send product details as JSON.  

#### 2️⃣ Frontend - Fetch & Display Data Dynamically  
- Created a function to **fetch product data** from the backend.  
- Passed the received data to the existing **Product Card Component**.  
- Used `.map()` to dynamically **render each product** on the homepage.  

#### 3️⃣ Why This Matters?  
- Enables **dynamic content loading** from the database instead of hardcoded values.  
- Improves **scalability and flexibility** as new products are added.  

#### 4️⃣ Submission Steps  
- ✅ Pushed the updated code to the **GitHub repository**.  
- ✅ Updated the **README.md** file with Milestone 11 details.  
- ✅ Shared the repository link for submission.

---

### Milestone 12: My Products Page - Filtering by User Email  

>>>>>>
✅ **Goals:**  
1. **Code Refactoring:**  
   - Improved code structure, ensuring modular and maintainable components.  
   - Removed unnecessary files and optimized logic.  
2. **Comprehensive README Update:**  
   - Documented all features and milestones clearly.  
   - Added setup instructions and usage details for new contributors.  
3. **Bug Fixes:**  
   - Fixed known issues related to authentication and data fetching.  
   - Enhanced error handling for better debugging.  
4. **Deployment Preparation (Optional):**  
   - Structured code for potential deployment on platforms like **Vercel** or **Heroku**.  
5. **Final Submission:**  
   - Pushed the updated code to **GitHub**.  
   - Ensured project documentation is complete and easy to understand.  

---

### Milestone 13: Complete Project Documentation & Code Refactoring  
✅ *Goals:*  
1. *Code Refactoring:*  
   - Improved code structure, ensuring modular and maintainable components.  
   - Removed unnecessary files and optimized logic.  
2. *Comprehensive README Update:*  
   - Documented all features and milestones clearly.  
   - Added setup instructions and usage details for new contributors.  
3. *Bug Fixes:*  
   - Fixed known issues related to authentication and data fetching.  
   - Enhanced error handling for better debugging.  
4. *Deployment Preparation (Optional):*  
   - Structured code for potential deployment on platforms like *Vercel* or *Heroku*.  
5. *Final Submission:*  
   - Pushed the updated code to *GitHub*.  
   - Ensured project documentation is complete and easy to understand.  

---


## ▶ How to Run the Project 

1. **Clone the repository:**  
   ```bash
   git clone https://github.com/your-username/E_Commerce_Follow_Along.git
   cd E_Commerce_Follow_Along
=======
1. Clone the repository:  
   bash  
   git clone https://github.com/your-username/E_Commerce_Follow_Along.git  
   cd E_Commerce_Follow_Along  
     
   
2. Install dependencies for both frontend and backend:  
   bash  
   cd frontend && npm install  
   cd ../backend && npm install  
     
   
3. Run the backend server:  
   bash  
   npm start  
     
   
4. Run the frontend application:  
   bash  
   cd frontend  
   npm start  
     
   
5. Open [http://localhost:3000/](http://localhost:3000/) in your browser.  

---
