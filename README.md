# html-authentication-poc

A HTML authentication pages.

## Pages

- `login.html` -> Login form with email and password
- `register.html` -> Registration form for new users 
- `forgot-password.html` -> Form to request a password reset link 
- `reset-password.html` -> Form to set a new password 
- `dashboard.html` -> Landing page after login 

## How to Run

1. Clone or download this repository
2. Open `login.html` in any web browser
3. Click the links to navigate between pages

## Page Redirections

- **Login** -> Register, Forgot Password 
- **Register** -> Login 
- **Forgot Password** -> Login, Reset Password 
- **Reset Password** -> Login, Forgot Password 
- **Dashboard** -> Login and Logout

## Tech Stack

- HTML5