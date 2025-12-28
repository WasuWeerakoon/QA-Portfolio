# Registration Module – Test Scenarios

## 1. Overview
This document describes the high-level test scenarios identified for the **User Registration module** of the **Seagrass Sri Lanka Web Application**.  
These scenarios cover functional, validation, usability, and compatibility aspects of the registration feature.

---

## 2. Module Information
- **Project Name:** Seagrass Sri Lanka  
- **Module:** User Registration  
- **Application Type:** Web Application  

---

## 3. Test Scenarios

### TS-REG-01: Verify registration with valid user details
- Ensure that a new user can successfully register by providing valid inputs in all mandatory fields.

### TS-REG-02: Verify registration with empty mandatory fields
- Ensure appropriate validation messages are displayed when mandatory fields are left blank.

### TS-REG-03: Verify email field validation
- Ensure the system rejects invalid email formats and accepts valid ones.

### TS-REG-04: Verify password field validation
- Ensure password rules (minimum length, strength) are enforced.

### TS-REG-05: Verify confirm password mismatch validation
- Ensure the system displays an error when password and confirm password do not match.

### TS-REG-06: Verify duplicate email registration
- Ensure the system prevents registration with an already registered email.

### TS-REG-07: Verify registration button behavior
- Ensure the Register button is enabled only when required fields are correctly filled.

### TS-REG-08: Verify successful registration redirection
- Ensure the user is redirected to the login page or dashboard after successful registration.

### TS-REG-09: Verify error messages display correctly
- Ensure validation and error messages are clear and user-friendly.

### TS-REG-10: Verify registration page UI elements
- Ensure all input fields, labels, and buttons are visible and aligned properly.

### TS-REG-11: Verify registration functionality on different browsers
- Ensure registration works correctly on Chrome, Firefox, and Edge.

### TS-REG-12: Verify registration functionality on mobile devices
- Ensure the registration form is responsive and usable on mobile devices.

---

## 4. Conclusion
The above test scenarios ensure comprehensive coverage of the Registration module, helping identify functional, validation, and usability defects before release.
