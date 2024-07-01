# Password Manager

🔒 Manage Your Passwords with Ease
## Key Features:

- **Individual Password Storage**: Securely store separate passwords for different accounts.
- **User Authentication**: Sign up or sign in using your email.
  - Sign-in cases handled: Account not found, incorrect password, mandatory fields, and invalid email id (email id that doesn’t exist).
  - Sign-up cases handled: Existing account, password mismatch, mandatory fields, and invalid email id (email id that doesn’t exist).
- **User Notifications**: Notifications via React Toastify.
- **Email Validation**: API of emailvalidation.io for checking if an email id is valid.

## Main Functionalities:

- **Save Passwords**: Store passwords by specifying the site, username, and password.
- **Edit Passwords**: Modify any saved password.
- **Delete Passwords**: Remove any password from your account.
- **User Session Management**: Easily log out from your account.
- **Database**: All passwords are stored in a MongoDB database. Upon signing in, users can view all passwords associated with their account.

## Tech Stack:

- **Frontend**: React.js
- **Backend**: Express.js
- **Database**: MongoDB
- **Notifications**: React Toastify
- **Email Validation**: emailvalidation.io API key
- **Animations**: GSAP library for smooth transitions between sign in and sign up

## Installation and Setup Instructions:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/password-manager.git
   cd password-manager
