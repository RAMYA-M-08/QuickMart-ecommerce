# 🛒QuickMart : Full-Stack E-Commerce Grocery Website

QuickMart is a dynamic and user-friendly online grocery shopping platform. It allows customers to explore products by category, manage their cart, proceed through a secure checkout and multi-mode payment process, and track their order history — all through a responsive and intuitive interface. An integrated admin portal empowers backend management of inventory and order delivery.

---

## 🔷 Project Description

QuickMart is a full-fledged eCommerce web application developed as part of a web programming project, aimed at replicating the core functions of an online supermarket. Designed to simulate a real-world grocery shopping experience, the platform streamlines the entire process from product browsing to order placement and management. It offers a secure, interactive, and responsive interface for both users and administrators, emphasizing usability, data validation, and modular backend control. This project demonstrates the practical application of web development skills in building a maintainable, fully-operable online retail system.

---

## 🔷 Features

### User Features
1. **User Signup and Login**
   - Users can create a new account or log in with existing credentials.
   - Validation is implemented for secure authentication.
   - OTP (mocked as any 4-digit number) is used for setting a new password.

2. **Home Page**
   - Browse multiple categories of grocery products.
   - Filter by category and sort by price.
   - Product search functionality available.

3. **Cart Page**
   - Add items to the cart.
   - Increase or decrease item quantities.
   - Remove products from the cart.
   - Dynamic pricing based on quantity.

4. **Checkout Page**
   - Collects delivery info: pincode and mobile number.
   - Validates:
     - Only Chennai pincodes.
     - 10-digit mobile numbers.
   - Proceeds to payment after successful validation.

5. **Payment Page**
   - Supports 4 payment modes:
     - Card
     - UPI
     - Net Banking
     - Cash on Delivery (COD)
   - Includes input validation for:
     - Card number format
     - CVV
     - UPI ID format
     - Mobile number

6. **My Orders Page**
   - Displays all past and current orders.
   - Order info includes:
     - Product details
     - Delivery status
     - Date/time
     - "Cancel Order" for orders with status Placed or Processing.

### Admin Features
- Admin login with verified credentials.
- Features:
  - Add new products.
  - Update stock, price, and description.
  - Update order delivery status.

---

## 🔷 Tech Stack

- **Frontend**: HTML, CSS, JavaScript  
- **JavaScript Library**: jQuery  
- **Backend**: Node.js with Express.js  
- **Database**: MongoDB  
- **Development Tools**: Visual Studio Code, Google Chrome  

---

## 🔷 System Configuration

To set up and run the system locally, please follow these steps:

- Install **Node.js** on your machine.
- Install **MongoDB** version 3.4 or above.
- Utilize **Visual Studio Code** as your code editor (recommended for optimal development experience).
- Install the necessary **Node Package Manager (NPM) packages**.

---

## 🔷 NPM Dependencies

The following essential NPM package are required

- express
- mongoose
- body-parser
- cookie-parser
- express-session
- path

---
## 🔷 Project Initialization

To initialize and run the project, execute the following commands:

### **1. Clone the repository**
```bash
git clone https://github.com/RAMYA-M-08/QuickMart-ecommerce-fullstack
```
### **2. Install dependencies**
``` bash
npm install
```
### **3. Start the server**
**Admin Portal**
``` bash
node adminserver.js
```
**User Pages**
```bash
node server1.js
```
---

## 🔷 Usage

1. Open [http://localhost:5000/homepage.html](http://localhost:5000/homepage.html) in your browser
2. Users must Sign up or Log in to explore the platform.
3. Admins can access the admin panel at [http://localhost:7000/login.html](http://localhost:7000/login.html)

    **Credentials for Admin login**
      - **Username -** `Admin#0x` **(where x is 1-9)**
      - **Password -** `Admin@0x` **(where x is 1-9)**
  
---


