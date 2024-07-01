# Password Manager

🔒 Manage Your Passwords with Ease

## Key Features:

### Individual Password Storage
Securely store separate passwords for different accounts, ensuring that each password is kept safe and accessible only to you.

### User Authentication
Users can sign up or sign in using their email. Various sign-in and sign-up cases are handled to provide a seamless user experience:
- **Sign-in cases handled**:
  - Account not found
  - Incorrect password
  - Mandatory fields
  - Invalid email id (email id that doesn’t exist)
- **Sign-up cases handled**:
  - Existing account
  - Password mismatch
  - Mandatory fields
  - Invalid email id (email id that doesn’t exist)

### User Notifications
Receive notifications via React Toastify to stay informed about important actions and events.

### Email Validation
Utilizes the API of emailvalidation.io to check if an email id is valid, ensuring that users provide a correct and functional email address.

## Main Functionalities:

### Save Passwords
Store passwords by specifying the site, username, and password. This feature allows you to keep all your login credentials in one secure place.

### Edit Passwords
Modify any saved password with ease. Keep your credentials up to date without hassle.

### Delete Passwords
Remove any password from your account. Manage your stored passwords and keep your list clean and organized.

### User Session Management
Easily log out from your account to ensure that your session remains secure.

### Database
All passwords are stored in a MongoDB database. Upon signing in, users can view all passwords associated with their account, making it easy to manage multiple credentials.

## Tech Stack:

- **Frontend**: React.js
- **Backend**: Express.js
- **Database**: MongoDB
- **Notifications**: React Toastify
- **Email Validation**: emailvalidation.io API key
- **Animations**: GSAP library for smooth transitions between sign-in and sign-up

## Installation and Setup Instructions:

### Prerequisites
- Node.js and npm installed on your machine
- MongoDB instance running
- An API key from emailvalidation.io

### Steps to Setup:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/password-manager.git
2. **Navigate to the backend directory:**
   ```bash
   cd backend
3. **Install backend dependencies:**
   ```bash
   npm install
4. **Start the backend server:**
   ```bash
   npm start
5. **Navigate to the frontend:**
   ```bash
   cd ..
6. **Install frontend dependencies:**
   ```bash
   npm install
7. **Start the frontend development server:**
   ```bash
   npm run dev
