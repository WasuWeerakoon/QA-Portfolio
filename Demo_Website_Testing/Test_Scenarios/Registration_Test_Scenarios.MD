# Demo Website – Registration Test Scenarios

## 1. Module Information

- **Module Name:** User Registration
- **Application:** Automation Exercise
- **Application URL:** https://automationexercise.com/
- **Testing Type:** Manual Testing

---

## 2. Objective

To verify that the **Registration functionality** works correctly by validating:

- New user account creation
- Input field validation
- Error handling
- Mandatory field checks
- Successful registration flow

---

## 3. Assumptions

- Registration feature is available and accessible
- User is not already registered with the same email
- Valid test data is available
- User has stable internet connectivity

---

## 4. Registration Test Scenarios

### TS-REG-01: Verify registration with valid details

- Ensure that a new user can successfully register using valid inputs.

### TS-REG-02: Verify registration with empty name and email

- Ensure the system prevents registration empty name and email

### TS-REG-03: Verify registration with empty name

- Ensure validation messages are displayed when mandatory fields are left blank.

### TS-REG-04: Verify registration with empty email

- Ensure validation messages are displayed when mandatory fields are left blank.

### TS-REG-05: Verify registration with invalid email format

- Ensure error messages are displayed.

### TS-REG-06: Verify registration with already registered email

- Ensure an error message is shown.

### TS-REG-07: Verify navigation after successful signup

- Ensure navigation goes to Acount information.

### TS-REG-08: Verify signup form UI

- Ensure the UI properly aligned and readable.

### TS-REG-09: Verify registration on different browsers

- Ensure registration works correctly on Chrome, Firefox, and Edge.

### TS-REG-10: Verify registration on mobile devices

- Ensure registration works correctly on mobile view.

---

## 5. Expected Outcome

- Registration should succeed with valid data
- Duplicate registrations should be blocked
- Validation messages should be clear and user-friendly
- Successful users should proceed to login or dashboard

---

## 6. Prepared By

**QA Tester:** Wasana Weerakon  
**Date:** December 2025
