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
  - [Milestone 13: Edit Product Functionality](#milestone-13-edit-product-functionality)
  - [Milestone 14: Delete Product Functionality](#milestone-14-delete-product-functionality)
  - [Milestone 15: Navbar Component & Navigation](#milestone-15-navbar-component--navigation)
  - [Milestone 16: Product Info Page](#milestone-16-Product-Info-Page)
  - [Milestone 17: Add to Cart Functionality](#milestone-17-Add-to-Cart-Functionality)
  - [Milestone 18: Cart Page & Checkout Functionality](#milestone-18-Cart-Page-and-Checkout-Functionality)
  - [Milestone 19: Cart Quantity Management](#milestone-19-Cart-Quantity-Management)
  - [Milestone 20: Profile Page](#milestone-20-Profile-Page)
  - [Milestone 21: Address Form Page](#milestone-21-Address-Form-Page)
  - [Milestone 22: Address Storage Endpoint](#milestone-22-Address-Storage-Endpoint)
  - [Milestone 23: Product Image Upload Feature](#milestone-23-Product-Image-Upload-Feature)
  - [Milestone 24: Order Confirmation Page](#milestone-24-Order-Confirmation-Page)
  - [Milestone 25: Place Order Endpoint](#milestone-25-Place-Order-Endpoint)
  - [Milestone 26: Get User Orders Endpoint](#milestone-26-Get-User-Orders-Endpoint)
  - [Milestone 27: My Orders Page ](#milestone-27-My-Orders-Page)
  - [Milestone 28: Cancel Order Functionality ](#milestone-28-Cancel-Order-Functionality)
  - [Milestone 29: PayPal Payment Integration](#milestone-29-PayPal-Payment-Integration)
  - [Milestone 30: Integrating Online Payments with PayPal](#milestone-30-Integrating-Online-Payments-with-PayPal)
  - [Milestone 31: Global State Management with Redux](#milestone-31-Global-State-Management-with-Redux)
  - [Milestone 32: Storing and Accessing Mail in Global State with Redux](#milestone-32-Storing-and-Accessing-Mail-in-Global-State-with-Redux)
  - [Milestone 33: Creating and Storing JWT Token in Cookies](#milestone-33-Creating-and-Storing-JWT-Token-in-Cookies)
  - [Milestone 34: Validating JWT Token Stored in Cookies](#milestone-34-Validating-JWT-Token-Stored-in-Cookies)
  - [Milestone 35: Deploying Your Project](#milestone-35-Deploying-Your-Project)
- [How to Run the Project](#-how-to-run-the-project) 
---

## 🛠 Tech Stack  
- Frontend: React.js, Tailwind CSS  
- Backend: Node.js, Express.js  
- Database: MongoDB  
- File Uploads: Multer  
- Password Encryption: bcrypt  
- Version Control: Git, GitHub  

---

## 📌 Milestones  

### Milestone 1: Project Setup  
*✅ Goals:*  
- Created and updated README.md file.  
- Initialized GitHub repository for version control.  

---

### Milestone 2: Frontend & Backend Initialization  
*✅ Goals:*  
1. *Project Folder Structure:* Organized files into separate frontend and backend directories.  
2. *React Frontend Setup:* Initialized a React application for building the user interface.  
3. *Node.js Backend Setup:* Set up a simple Node.js server for API integration in future milestones.  
4. *Tailwind CSS Configuration:* Integrated and configured Tailwind CSS for modern, responsive styling.  
5. *Login Page Development:* Created a login page with functionality and styling.  

---

### Milestone 3: Backend Structure & Server Setup  
*✅ Goals:*  
1. *Backend Folder Structure:* Created a structured hierarchy for organizing routes, controllers, models, and middleware.  
2. *Server Setup:*  
   - Used Node.js and Express.js to create a backend server.  
   - Configured the server to listen on a designated port.  
3. *Database Connection:*  
   - Integrated MongoDB for efficient data storage.  
   - Confirmed the connection between the server and MongoDB.  
4. *Error Handling:*  
   - Provided clear error messages for better debugging and user feedback.  

---

### Milestone 4: Creating User Model and Controller  
*✅ Goals:*  
1. *User Model:* Defined the structure of user data with attributes like name, email, password, and profile picture.  
2. *User Controller:* Handled user-related actions such as registration and data retrieval.  
3. *Multer Integration:* Enabled file uploads for storing user profile pictures.  
4. *API Routes:* Created endpoints for user creation and fetching user details.  
5. *README Update:* Documented progress and updated repository.  

---

### Milestone 5: Sign-Up Page & Form Validation  
*✅ Goals:*  
1. *Sign-Up Page UI:* Designed a clean and user-friendly sign-up form with fields for name, email, and password.  
2. *Form Validation:*  
   - Ensured the email follows the correct format.  
   - Implemented password security criteria (minimum length, special characters, etc.).  
3. *User Registration Flow:* Integrated frontend form submission with the backend API.  
4. *Error Handling:* Displayed validation errors to users in real-time.  
5. *README Update:* Documented progress and updated repository.  

---

### Milestone 6: Secure User Registration  
*✅ Goals:*  
1. *Password Encryption:*  
   - Used bcrypt to hash passwords before storing them in the database.  
   - Ensured no plaintext passwords are stored.  
2. *Secure Data Storage:*  
   - Stored the user's encrypted password along with other necessary details in MongoDB.  
3. *Updated API Endpoints:*  
   - Modified the user registration endpoint to handle password hashing securely.  
4. *Security Compliance:*  
   - Followed best practices for protecting user credentials.  
5. *README Update:*  
   - Documented progress for Milestone 6 and updated the repository.  

---

### Milestone 7: User Login & Authentication  
*✅ Goals:*  
1. *Login Endpoint:* Created a backend endpoint for user login and verified user credentials.  
2. *Password Validation:* Utilized bcrypt for secure password comparison.  
3. *Authentication Flow:* Authenticated users based on matching hashed passwords.  
4. *Security Considerations:* Ensured secure handling of user credentials.  
5. *README Update:* Updated with details about the user login functionality.  

---

### Milestone 8: Product Card Component & Homepage Layout  
*✅ Goals:*  
1. *Card Component Creation:* Designed a reusable card component for displaying product details.  
2. *Homepage Layout Design:* Created a responsive grid layout for displaying multiple product cards.  
3. *Dynamic Data Display:* Implemented dynamic rendering of product cards using mapping.  
4. *Consistency & Responsiveness:* Ensured consistent styling and responsive design.  
5. *README Update:* Documented progress and learning outcomes for Milestone 8.  

---

### Milestone 9: Product Input Form  
*✅ Goals:*  
1. *Product Form Creation:*  
   - Designed a form for inputting product details such as name, description, price, and category.  
   - Included fields for uploading multiple product images.  
2. *Image Upload Functionality:*  
   - Implemented file input to accept multiple images.  
   - Configured frontend to preview selected images before submission.  
3. *Form Validation & Error Handling:*  
   - Ensured all required fields are filled out.  
   - Displayed validation errors for incomplete or incorrect inputs.  
4. *Integration with Backend:*  
   - Connected the form to the backend API for product creation.  
   - Stored product details and images in MongoDB.  
5. *User Experience Enhancements:*  
   - Provided a clean and user-friendly UI for the product input form.  
   - Added real-time feedback for image uploads and form validation.  
6. *README Update:*  
   - Documented the progress and learning outcomes for Milestone 9.  
   - Updated the repository with details about the product input form.  

---

### Milestone 10: Product Schema & Endpoint Creation  
*✅ Goals:*  
1. *Product Schema Creation:*  
   - Designed a Mongoose schema for product details including name, description, price, and image URL.  
   - Ensured each field has proper validation (e.g., required fields, correct data types).  
2. *Endpoint Creation:*  
   - Built a POST endpoint to receive product data.  
   - Validated and saved the product details to MongoDB.  
3. *Why Validation?*  
   - Ensures that only valid data is saved in the database, maintaining data integrity and preventing errors.  
4. *Security Enhancements:*  
   - Implemented additional validation and data integrity measures to ensure accurate and secure data storage.  
5. *Next Steps (Optional):*  
   - Experiment with adding features such as admin access control to allow only admins to upload products or creating user profiles with roles for managing the shop.  

---
### Milestone 11: Dynamic Homepage with Product Data  

✅ *Goals:*  

#### ⿡ Backend - Fetch All Products  
- Created an API endpoint to retrieve all product data stored in MongoDB.  
- Used *Express.js* and *Mongoose* to fetch and send product details as JSON.  

#### ⿢ Frontend - Fetch & Display Data Dynamically  
- Created a function to *fetch product data* from the backend.  
- Passed the received data to the existing *Product Card Component*.  
- Used .map() to dynamically *render each product* on the homepage.  

#### ⿣ Why This Matters?  
- Enables *dynamic content loading* from the database instead of hardcoded values.  
- Improves *scalability and flexibility* as new products are added.  

#### ⿤ Submission Steps  
- ✅ Pushed the updated code to the *GitHub repository*.  
- ✅ Updated the *README.md* file with Milestone 11 details.  
- ✅ Shared the repository link for submission.

---

### Milestone 12: My Products Page - Filtering by User Email  

✅ *Goals:*  

#### 1️⃣ Backend - Fetch Products by User Email  
- Created an API endpoint to *retrieve only the products* added by the logged-in user.  
- Used *Express.js* and *Mongoose* to *filter products based on the user's email* stored in MongoDB.  
- Ensured *secure and efficient querying* to fetch only relevant data.  

#### 2️⃣ Frontend - Fetch & Display User-Specific Products  
- Created a function to *fetch products linked to the logged-in user's email*.  
- Passed the received data to the existing *Product Card Component*.  
- Used .map() to dynamically *render only the user's products* on the *"My Products"* page.  

#### 3️⃣ Why This Matters?  
- Enables *personalized product listings* based on the logged-in user's email.  
- Improves *data filtering skills*, ensuring only relevant data is sent to the client.  
- Enhances user experience by displaying only their *added products* instead of all products.

---

### Milestone 13: Edit Product Functionality

✅ Goals:  

#### 1️⃣ Backend - Update Product Endpoint
- Write an endpoint that will receive new data and update the existing data inside MongoDB.
- Utilized Express.js and Mongoose to handle update operations securely and efficiently.

#### 2️⃣ Frontend - Edit Button & Auto-Filled Form
- Added an Edit button to each product card to enable product modification.
- On clicking Edit, the form auto-fills with the existing product data, allowing updates to name, description, price, and images.
- Implemented real-time form validation and preview of changes before submission.

#### 3️⃣ User Experience Enhancement
- Provided a smooth transition between the product list and the edit form.
- Ensured validation checks are in place to maintain data integrity during updates.

#### 4️⃣ Submission Steps
- ✅ Pushed the updated code to the GitHub repository.
- ✅ Updated the README.md file with Milestone 13 details.
- ✅ Shared the repository link for submission.

---

### Milestone 14: Delete Product Functionality

✅ *Goals:*

#### 1️⃣ Backend - Delete Product Endpoint
- Created an endpoint that allows deletion of a product using its specific ID.
- Utilized Express.js and Mongoose to handle delete operations securely and efficiently.

#### 2️⃣ Frontend - Delete Button Integration
- Added a Delete button to each product card.
- When clicked, the product ID is sent to the server endpoint to trigger the deletion.

#### 3️⃣ User Experience Enhancement
- Provided confirmation prompts to avoid accidental deletions.
- Implemented smooth transitions and updates to the UI when a product is deleted.

#### 4️⃣ Submission Steps
- ✅ Pushed the updated code to the GitHub repository.
- ✅ Updated the README.md file with Milestone 14 details.
- ✅ Shared the repository link for submission.

---


### Milestone 15: Navbar Component & Navigation

✅ *Goals:*

#### 1️⃣ Creating the Navbar Component
- Designed a **responsive Navbar** with navigation links for:
  - Home
  - My Products
  - Add Product
  - Cart
- Ensured **consistency across all pages** for a seamless experience.

#### 2️⃣ Implementing Reusability
- Used the Navbar **across all screens** to maintain a uniform layout.
- Optimized **component structure** for easy scalability.

#### 3️⃣ Enhancing Responsiveness
- Used **CSS Flexbox/Grid** & **Tailwind CSS** to make the Navbar adaptable to different screen sizes.
- Implemented **hamburger menu** for mobile users.

#### 4️⃣ Submission Steps
- ✅ Pushed the updated code to the GitHub repository.
- ✅ Updated the README.md file with Milestone 15 details.
- ✅ Shared the repository link for submission.

---
=======


### Milestone 16: Product Info Page  

✅ *Goals:*  

#### 1️⃣ Creating the Product Info Page  
- Designed a **dedicated page** to display detailed product information, including:  
  - Product Name  
  - Description  
  - Price  
  - Image(s)  

#### 2️⃣ Adding Quantity Selection & "Add to Cart" Button  
- Implemented a **quantity selector** to allow users to choose the desired quantity.  
- Added an **"Add to Cart"** button to store selected items in the cart.  

#### 3️⃣ Dynamic Routing for Product Details  
- Utilized **React Router** to create dynamic routes for each product.  
- Fetched product details based on the **product ID** from the URL.  

#### 4️⃣ Enhancing User Experience  
- Ensured **mobile responsiveness** for smooth browsing on all devices.  
- Implemented **loading indicators** for better user experience.  

#### 5️⃣ Submission Steps  
- ✅ Pushed the updated code to the GitHub repository.  
- ✅ Updated the README.md file with Milestone 16 details.  
- ✅ Shared the repository link for submission.  

---

### Milestone 17: Add to Cart Functionality  

✅ *Goals:*  

#### 1️⃣ Update User Schema for Cart Functionality  
- Modified the **user schema** to include a `cart` field.  
- Structured the cart field to store an array of product objects containing:  
  - Product ID  
  - Name  
  - Price  
  - Quantity  

#### 2️⃣ Backend - Add to Cart Endpoint  
- Created an endpoint to **receive product details** and store them in the user's cart.  
- Ensured secure handling of requests and efficient database updates using **MongoDB & Mongoose**.  

#### 3️⃣ Frontend - Add to Cart Integration  
- Connected the **"Add to Cart"** button from the Product Info Page to the backend API.  
- Stored **cart data in the database** and updated the UI dynamically.  

#### 4️⃣ User Experience Enhancements  
- Implemented a **notification system** to confirm when a product is added to the cart.  
- Ensured **real-time cart updates** without needing to refresh the page.  

#### 5️⃣ Submission Steps  
- ✅ Pushed the updated code to the GitHub repository.  
- ✅ Updated the README.md file with Milestone 17 details.  
- ✅ Shared the repository link for submission.  

---
### Milestone 18: Cart Page and Checkout Functionality  

✅ *Goals:*  

#### 1️⃣ Creating the Cart Page  
- Designed a **Cart Page** to display:  
  - List of added products  
  - Product images, names, prices, and quantities  
  - Total cart value  
- Implemented a **Remove from Cart** button for each item.  

#### 2️⃣ Backend - Fetch & Update Cart  
- Created an endpoint to **retrieve cart items** from the database.  
- Implemented an API to **update product quantities** in the cart.  
- Ensured secure **cart data management** for logged-in users.  

#### 3️⃣ Checkout Functionality  
- Added a **Checkout button** that:  
  - Confirms the order  
  - Clears the cart after a successful purchase  
  - Redirects users to an order confirmation page  
- Integrated a **payment gateway placeholder** for future improvements.  

#### 4️⃣ User Experience Enhancements  
- Provided **real-time cart updates** when quantities change.  
- Displayed **subtotal and total price** dynamically.  
- Ensured a **mobile-friendly UI** for a seamless experience.  

#### 5️⃣ Submission Steps  
- ✅ Pushed the updated code to the GitHub repository.  
- ✅ Updated the README.md file with Milestone 18 details.  
- ✅ Shared the repository link for submission.  

---

### Milestone 19: Cart Quantity Management

✅ *Goals:*

### 1️⃣ Frontend - Cart Page UI Enhancements

- Added + and - buttons next to each product to modify its quantity.

- Ensured real-time updates for accurate pricing adjustments.

### 2️⃣ Backend - Quantity Management Endpoint

- Created two API endpoints to increase and decrease product quantity in the cart.

- Integrated logic to prevent negative quantities and handle item removal automatically when reduced to zero.

### 3️⃣ Enhancing User Experience

- Ensured instant feedback when quantity adjustments are made.

- Maintained a clean UI design with clear quantity controls.

### 4️⃣ Submission Steps

- ✅ Pushed the updated code to the GitHub repository.

- ✅ Updated the README.md file with Milestone 19 details.

- ✅ Shared the repository link for submission.

--- 
### Milestone 20: Profile Page

✅ *Goals:*

### 1️⃣ Backend - User Data Endpoint

- Created an API endpoint to send all user data including profile details and addresses.

- Ensured the endpoint is secure and accessible only to authenticated users.

### 2️⃣ Frontend - Profile Page UI

- Designed a Profile Page that displays:

   - Profile Photo

   - Name

   - Email

   - List of Addresses

- Added a clear "Add Address" button for adding new addresses.

- Displayed "No address found" when no addresses are available.

### 3️⃣ Enhancing User Experience

- Ensured the profile page design is clean and easy to navigate.

4️⃣ Submission Steps

- ✅ Pushed the updated code to the GitHub repository.

- ✅ Updated the README.md file with Milestone 20 details.

- ✅ Shared the repository link for submission.

---

# Milestone 21: Address Form Page

✅ **Goals:**

### 1️⃣ Frontend - Address Form Page

- Created an address form page that collects the following details:
  - **Country**
  - **City**
  - **Address Line 1**
  - **Address Line 2**
  - **ZIP Code**
  - **Address Type** (e.g., Home, Office, etc.)

- Implemented a state that stores the address input data for better management.

- Ensured that when users click the "Add Address" button on the Profile Page, they are navigated to this form page.

### 2️⃣ Enhancing User Experience

- Designed the address form to be user-friendly and intuitive.
- Ensured clear input labels and proper validation for required fields.

### 3️⃣ Submission Steps

- ✅ Pushed the updated code to the GitHub repository.
- ✅ Updated the README.md file with Milestone 21 details.
- ✅ Shared the repository link for submission.

---
# Milestone 22: Address Storage Endpoint

✅ **Goals:**

### 1️⃣ Backend - Address Storage Endpoint

- Created an API endpoint that receives address data from the frontend address form.
- Added logic to store the received address inside the `address` array within the user's profile collection in the database.
- Ensured endpoint security by restricting access to authenticated users only.

### 2️⃣ Enhancing User Experience

- Ensured proper error handling to manage invalid data entries.
- Implemented success and error response messages for clear user feedback.

### 3️⃣ Submission Steps

- ✅ Pushed the updated code to the GitHub repository.
- ✅ Updated the README.md file with Milestone 22 details.
- ✅ Shared the repository link for submission.

---
# Milestone 23: Product Image Upload Feature

✅ **Goals:**

### 1️⃣ Backend - Product Image Upload Endpoint

- Created an API endpoint for uploading product images using **Multer**.
- Integrated image storage logic to save uploaded images in a designated folder and store their paths in the database.
- Ensured endpoint security by restricting access to admin users only.

### 2️⃣ Enhancing User Experience

- Implemented clear success and error response messages for better feedback.
- Added file type validation to allow only image formats (e.g., `.jpg`, `.png`, `.jpeg`).
- Set a file size limit to prevent large uploads from slowing down the system.

### 3️⃣ Submission Steps

- ✅ Pushed the updated code to the GitHub repository.
- ✅ Updated the README.md file with Milestone 23 details.
- ✅ Shared the repository link for submission.

---
# Milestone 24: Order Confirmation Page

✅ **Goals:**

### 1️⃣ Frontend - Order Confirmation Page

- Developed an **Order Confirmation Page** that displays the following details:
  - ✅ List of all products in the order with relevant details.
  - ✅ The selected **delivery address** for clear reference.
  - ✅ The **total cart value** calculated dynamically.
  - ✅ A prominent **"Place Order"** button for finalizing the purchase.

### 2️⃣ Enhancing User Experience

- Ensured the layout is clean and user-friendly.
- Added visual cues for better clarity, such as product images and clear section headings.
- Provided feedback for successful order placement or any potential errors.

### 3️⃣ Learning Outcome

- Gained insights into implementing order functionality, including displaying order details and handling user selections.

### 4️⃣ Submission Steps

- ✅ Pushed the updated code to the GitHub repository.
- ✅ Updated the README.md file with Milestone 24 details.
- ✅ Shared the repository link for submission.

---

# Milestone 25: Place Order Endpoint

✅ **Goals:**

### 1️⃣ Backend - Place Order Endpoint

- Created a secure **Place Order** endpoint that:
  - ✅ Receives product details, user information, and selected address from the frontend.
  - ✅ Extracts the user's email to retrieve their `_id` from the database.
  - ✅ Creates a **separate order** entry for each product while maintaining the same delivery address.
  - ✅ Stores the order details in the **MongoDB orders collection** using the previously created order schema.

### 2️⃣ Enhancing Functionality

- Implemented proper error handling to manage invalid data or failed order creation.
- Ensured only authenticated users can access the endpoint for added security.
- Included clear success and error response messages for better frontend integration.

### 3️⃣ Learning Outcome

- Learned how to:
  - Structure an effective **Place Order** endpoint.
  - Manage and store order data efficiently in MongoDB.

### 4️⃣ Submission Steps

- ✅ Pushed the updated code to the GitHub repository.
- ✅ Updated the README.md file with Milestone 25 details.
- ✅ Shared the repository link for submission.

---

### Milestone 26: Get User Orders Endpoint 

✅ **Goals:**  

### 1️⃣ Backend - User Orders Endpoint  

- Created an API endpoint that retrieves all orders for a specific user.  
- Implemented logic to receive the user's email and retrieve the corresponding `_id`.  
- Used the retrieved `_id` to query and fetch all orders associated with that user from the database.  

### 2️⃣ Enhancing User Experience  

- Ensured proper error handling for cases such as invalid email, missing orders, or database issues.  
- Implemented clear success and error response messages for better user feedback.  

### 3️⃣ Submission Steps  

- ✅ Pushed the updated code to the GitHub repository.  
- ✅ Updated the README.md file with Milestone 26 details.  
- ✅ Shared the repository link for submission.  
---
### Milestone 27: My Orders Page  

✅ **Goals:**  

### 1️⃣ Frontend - My Orders Page  

- Created a dedicated `My Orders` page to display all user orders.  
- Implemented a `GET` request to the `/my-orders` endpoint to fetch the user's orders.  
- Sent the user's email in the request to retrieve relevant orders from the database.  

### 2️⃣ Enhancing User Experience  

- Displayed order details in a structured format for better readability.  
- Added error handling for cases such as missing orders or failed requests.  
- Integrated the `My Orders` page into the navigation bar for easy access.  

### 3️⃣ Submission Steps  

- ✅ Pushed the updated code to the GitHub repository.  
- ✅ Updated the README.md file with Milestone 27 details.  
- ✅ Shared the repository link for submission.  
---
### Milestone 28: Cancel Order Functionality  

✅ **Goals:**  

### 1️⃣ Backend - Cancel Order Endpoint  

- Created a new API endpoint to handle order cancellations.  
- Implemented logic to receive the `orderId` from the request.  
- Retrieved the order using the provided `orderId` and updated its status to `"canceled"`.  
- Saved the updated order back to the database.  

### 2️⃣ Frontend - My Orders Page Update  

- Added a **Cancel Order** button for each order in the `My Orders` page.  
- Ensured that the cancel button is **not displayed** for already canceled orders.  
- Sent a request to the cancel order endpoint when the button is clicked.  
- Updated the UI to reflect the canceled status after a successful cancellation.  

### 3️⃣ Enhancing User Experience  

- Handled potential errors, such as invalid order IDs or already canceled orders.  
- Provided feedback to the user on the cancellation status.  

### 4️⃣ Submission Steps  

- ✅ Pushed the updated code to the GitHub repository.  
- ✅ Updated the README.md file with Milestone 28 details.  
- ✅ Shared the repository link for submission.  
---

### **Milestone 29: PayPal Payment Integration**  

✅ **Goals:**  

### 1️⃣ **Setting Up PayPal Sandbox Account**  

- Created a **PayPal Developer Account** and accessed the **Sandbox Accounts** section.  
- Copied and saved the **Sandbox UserID** for testing transactions.  
- Retrieved the **Client ID** from the PayPal Developer Dashboard for API integration.  

### 2️⃣ **Adding Payment Options to the Order Confirmation Page**  

- Implemented **two payment options**:  
  - **Cash on Delivery (COD)**  
  - **Online Payment (via PayPal)**  
- Used radio buttons to allow users to select their preferred payment method.  

### 3️⃣ **Displaying PayPal Button**  

- Configured logic to **display the PayPal payment button** only when "Online Payment" is selected.  
- Ensured that selecting **COD** hides the PayPal payment option.  

### 4️⃣ **Next Steps for Milestone 30**  

- In the next milestone, we will implement the actual PayPal payment functionality.  

### 5️⃣ **Submission Steps**  

- ✅ Pushed the updated code to the GitHub repository.  
- ✅ Updated the **README.md** file with Milestone 29 details.  
- ✅ Shared the repository link for submission.  

---

# Milestone 30: Integrating Online Payments with PayPal  

✅ **Goals:**  

### 1️⃣ Backend - PayPal Integration  

- Created a PayPal Developer account and registered a sandbox account.  
- Retrieved the Client ID for API authentication.  
- Configured PayPal API settings to enable online transactions.  

### 2️⃣ Frontend - Implementing PayPal Payment Gateway  

- Installed `react-paypal-js` package using:  
  ```sh
  npm install @paypal/react-paypal-js
  ```
- Imported `PayPalScriptProvider` and `PayPalButtons` components.  
- Wrapped the application with `PayPalScriptProvider` and passed the `clientId`.  
- Configured the PayPal button to handle transactions and capture payments.  

### 3️⃣ Enhancing User Experience  

- Handled payment success and failure scenarios.  
- Provided feedback to users on transaction status.  
- Ensured security measures for processing payments.  

### 4️⃣ Submission Steps  

- ✅ Pushed the updated code to the GitHub repository.  
- ✅ Updated the README.md file with Milestone 30 details.  
- ✅ Shared the repository link for submission.  

---

# Milestone 31: Global State Management with Redux

## ✅ Goals:

### 1️⃣ Backend - Redux Store Setup
- Created a Redux store to manage global state for the application.
- Configured the Redux store with a user reducer to handle the user email state.
- Added actions for updating and accessing the global email state.

### 2️⃣ Frontend - Implementing Redux
- Installed the `react-redux` package using:
  ```bash
  npm install react-redux
  ```
- Created a folder structure with `store.js` and `userActions.js`.
- Wrapped the `App` component with the `Provider` component to pass the Redux store to the rest of the application.
  
### 3️⃣ Enhancing User Experience with Redux
- Handled the global state of the user email and ensured it's accessible across all components.
- Allowed for easy management and updating of the email state via Redux actions and reducers.

### 4️⃣ Submission Steps
- ✅ Pushed the updated code to the GitHub repository.
- ✅ Updated the README.md file with Milestone 31 details.
- ✅ Shared the repository link for submission.

Good luck, Kalvians! ✨

---

# Milestone 32: Storing and Accessing Mail in Global State with Redux

## ✅ Goals:

### 1️⃣ Backend - Redux Integration with Mail
- Updated the Redux store to store the user's mail in the global state.
- Used the `dispatch` method to store the email in the global state upon login.

### 2️⃣ Frontend - Accessing Mail Across Pages
- Used the `useSelector` hook to access the user's email in all pages.
- Ensured that the global email state is available across different components and pages.

### 3️⃣ Enhancing User Experience with Redux
- Provided consistent access to the user's email across the application.
- Ensured the application responds to the state updates in a seamless manner.

### 4️⃣ Submission Steps
- ✅ Pushed the updated code to the GitHub repository.
- ✅ Updated the README.md file with Milestone 32 details.
- ✅ Shared the repository link for submission.

Good luck, Kalvians! ✨

---


# Milestone 33: Creating and Storing JWT Token in Cookies

## ✅ Goals:

### 1️⃣ Backend - JWT Token Creation
- Installed the `jsonwebtoken` package using:
  ```bash
  npm install jsonwebtoken
  ```
- Used the `sign` method to create a JWT token, including the user's email and ID.

### 2️⃣ Storing JWT Token in Cookies
- Set an expiration time for the JWT token using `maxAge`.
- Added the JWT token to the response as a cookie to store it in the browser.

### 3️⃣ Enhancing Security
- Ensured that the JWT token is stored securely inside a cookie, facilitating seamless authentication.
- Implemented the cookie-based token storage to manage user sessions.

### 4️⃣ Submission Steps
- ✅ Pushed the updated code to the GitHub repository.
- ✅ Updated the README.md file with Milestone 33 details.
- ✅ Shared the repository link for submission.

Good luck, Kalvians! ✨

---

# Milestone 34: Validating JWT Token Stored in Cookies

## ✅ Goals:

### 1️⃣ Backend - JWT Token Validation
- Extracted the JWT token from the browser’s cookie and sent it to the server.
- Created a middleware function on the backend to validate the JWT token received from the client.
- Ensured the server checks if the token is valid before granting access to protected routes.

### 2️⃣ Frontend - Token Handling
- Ensured that every page checks for the JWT token, preventing unauthorized access without login.
- Implemented token validation across the application to ensure users are logged in before accessing protected resources.

### 3️⃣ Enhancing Security and Authentication
- Added robust token validation to secure the application and prevent unauthorized access.
- Implemented the necessary steps to protect routes using JWT token validation on the server side.

### 4️⃣ Submission Steps
- ✅ Pushed the updated code to the GitHub repository.
- ✅ Updated the README.md file with Milestone 34 details.
- ✅ Shared the repository link for submission.

Good luck, Kalvians! ✨

---

# Milestone 35: Deploying Your Project

## ✅ Goals:

### 1️⃣ Deploying the Backend
- Deployed the backend on a cloud service (e.g., Heroku, AWS, DigitalOcean, etc.).
- Retrieved the backend deployment link and ensured it was accessible.

### 2️⃣ Deploying the Frontend
- Replaced the local backend URLs in the frontend code with the backend deployment link.
- Deployed the frontend to a hosting service (e.g., Netlify, Vercel, or any other platform).
- Verified that the frontend was connected to the deployed backend and functioning properly.

### 3️⃣ Full Deployment Verification
- Ensured that both the frontend and backend were correctly deployed and were working as expected.
- Conducted final tests to confirm that the website was fully functional with deployed backend and frontend.

### 4️⃣ Submission Steps
- ✅ Pushed the updated code to the GitHub repository.
- ✅ Deployed both the frontend and backend.
- ✅ Shared the deployment link in the assignment submission section.

Good luck, Kalvians! ✨

---

## ▶ How to Run the Project  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/your-username/E_Commerce_Follow_Along.git  
   cd E_Commerce_Follow_Along  
   ```  
   
2. Install dependencies for both frontend and backend:  
   ```bash  
   cd frontend && npm install  
   cd ../backend && npm install  
   ```  
   
3. Run the backend server:  
   ```bash  
   npm start  
   ```  
   
4. Run the frontend application:  
   ```bash  
   cd frontend  
   npm start  
   ```  
   
5. Open [http://localhost:3000/](http://localhost:3000/) in your browser.  

