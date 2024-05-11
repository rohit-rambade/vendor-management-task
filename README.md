
# Vendor-CRUD web app

This web application manages vendor information, offering features such as Google authentication, CRUD operations for vendors, pagination, and responsive UI design. 

## Technologies Used

- Node.js
- MongoDB
- Express.js 
- Redux Toolkit
- Tailwind CSS
- React Toastify
- Firebase Google Auth
- React Persist Storage

## Features
1. **Login with Google & Logout**
   - Allow users to log in using their Google accounts and log out when needed.

2. **Account Details**
   - Vendor Name*
   - Account No*
   - Bank Name* 
   - Address Line 1
   - Address Line 2*
   - City
   - Country
   - Zip Code

3. **Vendor Management**
   - Create Vendor
   - Display paginated list of vendors

4. **Edit Vendor**
   - vendor details to allow editing.

5. **Delete Vendor**
   - Delete vendor after confirmation.

## API Endpoints


`POST /api/auth/google-login`

`GET /api/vendors`

`POST /api/vendors`

`PUT /api/vendors/:id`

`DELETE /api/vendors/:id`
