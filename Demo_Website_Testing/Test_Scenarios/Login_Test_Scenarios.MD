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
- Session management

---

## 3. Assumptions

- User registration is completed successfully
- Valid test credentials are available
- Application is accessible
- User has stable internet connectivity

---

## 4. Login Test Scenarios

### TS-LOGIN-01: Verify login with valid email and password

- Ensure a registered user can successfully log in using valid credentials.

### TS-LOGIN-02: Verify login with invalid email

- Ensure login fails when an unregistered email is entered.

### TS-LOGIN-03: Verify login with invalid password

- Ensure login fails when an incorrect password is entered.

### TS-LOGIN-04: Verify login with empty email and password

- Ensure validation messages are shown when both fields are empty.

### TS-LOGIN-05: Verify login with empty email field

- Ensure validation message is displayed when email is empty.

### TS-LOGIN-06: Verify login with empty password field

- Ensure validation message is displayed when password is empty.

### TS-LOGIN-07: Verify error message for invalid login

- Ensure error messages are clear and user-friendly.

### TS-LOGIN-08: Verify successful navigation after login

- Ensure user is redirected to the home page after successful login.

### TS-LOGIN-09: Verify logout functionality

- Ensure user can successfully log out from the application.

### TS-LOGIN-10: Verify session handling after logout

- Ensure user cannot access restricted pages after logout.

### TS-LOGIN-11: Verify login on different browsers

- Ensure login works correctly on Chrome, Firefox, and Edge.

### TS-LOGIN-12: Verify login on mobile devices

- Ensure login works correctly on mobile view.

---

## 5. Expected Outcome

- Login should succeed with valid credentials
- Invalid login attempts should be blocked
- Proper error messages should be displayed
- User session should be managed correctly

---

## 6. Prepared By

**QA Tester:** Wasana Weerakon  
**Date:** December 2025
