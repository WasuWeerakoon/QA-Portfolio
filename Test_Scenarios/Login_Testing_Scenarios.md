# Login Module – Test Scenarios
## Project: Seagrass Sri Lanka Web Application

---

## 1. Overview
This document describes the high-level **test scenarios** identified for testing the **Login module** of the Seagrass Sri Lanka web application.  
These scenarios ensure that the login functionality works correctly under various conditions, including positive, negative, and edge cases.

---

## 2. Test Scenarios – Positive Scenarios

### TS-01: Login with valid credentials
Verify that a registered user can successfully log in using a valid email/username and password.

### TS-02: Redirect after successful login
Verify that the user is redirected to the correct page (Home/Dashboard) after successful login.

### TS-03: Login using keyboard actions
Verify that the user can log in using the **Enter** key instead of clicking the Login button.

### TS-04: Remember session after login
Verify that the user session remains active until logout or session timeout.

---

## 3. Test Scenarios – Negative Scenarios

### TS-05: Login with invalid email/username
Verify that an appropriate error message is displayed when an invalid email/username is entered.

### TS-06: Login with invalid password
Verify that an appropriate error message is displayed when an incorrect password is entered.

### TS-07: Login with both fields invalid
Verify that login fails and an error message is shown when both email/username and password are invalid.

### TS-08: Login with empty email/username field
Verify that validation messages are displayed when the email/username field is left empty.

### TS-09: Login with empty password field
Verify that validation messages are displayed when the password field is left empty.

### TS-10: Login with both fields empty
Verify that login is prevented and validation messages are shown when both fields are empty.

---

## 4. Test Scenarios – Validation & UI Scenarios

### TS-11: Password field masking
Verify that the password entered is masked (hidden) by default.

### TS-12: Show/Hide password functionality
Verify that the password visibility toggle works correctly (if available).

### TS-13: Mandatory field indication
Verify that mandatory fields are clearly indicated in the UI.

### TS-14: Error message clarity
Verify that error messages are user-friendly, readable, and meaningful.

### TS-15: Login button state
Verify that the Login button behavior is correct (enabled/disabled) based on input fields.

---

## 5. Test Scenarios – Edge & Boundary Scenarios

### TS-16: Login with minimum allowed password length
Verify login behavior when the password length is at the minimum boundary.

### TS-17: Login with maximum allowed password length
Verify login behavior when the password length is at the maximum boundary.

### TS-18: Login with special characters in password
Verify that passwords containing special characters are handled correctly.

### TS-19: Login with leading/trailing spaces
Verify that leading and trailing spaces in input fields are handled correctly.

---

## 6. Test Scenarios – Security & Session Scenarios

### TS-20: Multiple failed login attempts
Verify system behavior after multiple consecutive failed login attempts.

### TS-21: Direct access without login
Verify that protected pages cannot be accessed without logging in.

### TS-22: Logout functionality
Verify that the user is logged out successfully and redirected appropriately.

### TS-23: Session expiration
Verify that the user is logged out after session timeout.

---

## 7. Test Scenarios – Compatibility Scenarios

### TS-24: Login on different browsers
Verify login functionality on Chrome, Firefox, and Edge browsers.

### TS-25: Login on mobile devices
Verify login functionality on mobile devices and different screen sizes.

---

## 8. Conclusion
These test scenarios ensure that the Login module of the Seagrass Sri Lanka web application is functionally correct, user-friendly, secure, and compatible across different environments.
