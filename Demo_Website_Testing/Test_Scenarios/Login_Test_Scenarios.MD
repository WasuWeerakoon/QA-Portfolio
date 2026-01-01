# Demo Website – Login Test Scenarios

## 1. Module Information

- **Module Name:** User Login
- **Application:** Automation Exercise
- **Application URL:** https://automationexercise.com/
- **Testing Type:** Manual Testing

---

## 2. Objective

To verify that the **Login functionality** works correctly by validating:

- User authentication
- Input field validation
- Error handling
- Navigation after login
- Session handling

---

## 3. Assumptions

- User registration is available and functional
- Valid user credentials exist
- User has internet connectivity
- Application is accessible

---

## 4. Login Test Scenarios

### TS-LOGIN-01: Verify login with valid credentials

- Ensure that a registered user can successfully log in using valid email and password.

### TS-LOGIN-02: Verify login with invalid email

- Ensure the system prevents login when an invalid email is entered.

### TS-LOGIN-03: Verify login with invalid password

- Ensure the system displays an appropriate error message when an incorrect password is entered.

### TS-LOGIN-04: Verify login with empty email and password fields

- Ensure validation messages are displayed when mandatory fields are left empty.

### TS-LOGIN-05: Verify login with empty email field

- Ensure the system prompts the user when the email field is left blank.

### TS-LOGIN-06: Verify login with empty password field

- Ensure the system prompts the user when the password field is left blank.

### TS-LOGIN-07: Verify password field masking

- Ensure the password entered is masked by default.

### TS-LOGIN-08: Verify login button behavior

- Ensure the login button behaves correctly based on input fields.

### TS-LOGIN-09: Verify error message content

- Ensure error messages are user-friendly and informative.

### TS-LOGIN-10: Verify successful redirection after login

- Ensure the user is redirected to the home/dashboard page after successful login.

### TS-LOGIN-11: Verify logout functionality

- Ensure the user can successfully log out after logging in.

### TS-LOGIN-12: Verify session handling after logout

- Ensure the user cannot access protected pages after logging out.

### TS-LOGIN-13: Verify login across different browsers

- Ensure login works correctly on Chrome, Firefox, and Edge.

### TS-LOGIN-14: Verify login on mobile devices

- Ensure login works correctly on mobile view.

---

## 5. Expected Outcome

- Login functionality should authenticate valid users
- Invalid login attempts should be handled securely
- Proper error messages should be displayed
- User sessions should be managed correctly

---

## 6. Prepared By

**QA Engineer:** Wasana Weerakon  
**Date:** December 2025
