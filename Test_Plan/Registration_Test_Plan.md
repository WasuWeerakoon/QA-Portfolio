# Registration Module – Test Plan

## 1. Introduction
This Test Plan outlines the strategy, scope, resources, schedule, and approach for testing the **User Registration module** of the **Seagrass Sri Lanka Web Application**.  
The purpose is to ensure that new users can register successfully with valid details and that validations work correctly.

---

## 2. Project Information
- **Project Name:** Seagrass Sri Lanka  
- **Application Type:** Web Application  
- **Module Under Test:** User Registration  
- **Test Environment:** Hosted (Production / QA)  
- **Application URL:**  
  - https://polite-desert-02a5b7610.2.azurestaticapps.net/

---

## 3. Objectives
- Verify that users can register with valid information.
- Ensure mandatory field validations are enforced.
- Validate error messages for invalid inputs.
- Prevent duplicate user registrations.
- Verify successful registration confirmation.
- Check registration functionality across browsers and devices.

---

## 4. Scope of Testing

### In Scope
- Registration form UI testing  
- Functional testing (positive & negative)  
- Field validation testing  
- Password rules validation  
- Duplicate registration handling  
- Compatibility testing (desktop & mobile)  
- Usability testing  

### Out of Scope
- Backend API load testing  
- Email/SMS service performance  
- Social login (Google/Facebook)  
- Password reset functionality  

---

## 5. Test Approach

### 5.1 Testing Types
- Functional Testing  
- UI / UX Testing  
- Boundary Value Testing  
- Error Handling Testing  
- Security Behavior Checks (basic only)  
- Browser Compatibility Testing  
- Regression Testing  

### 5.2 Testing Levels
- Component Testing (Registration page)  
- Integration Testing (Registration → Login)  
- System Testing  

---

## 6. Entry & Exit Criteria

### Entry Criteria
- Registration requirements are finalized.
- Application build is deployed.
- Test data is available.
- Test environment is stable.

### Exit Criteria
- All high & medium priority test cases executed.
- No critical or high severity defects open.
- Test summary report prepared.

---

## 7. Test Deliverables
- Registration Test Plan  
- Registration Test Scenarios  
- Registration Test Cases  
- Bug Reports  
- Test Summary Report  
- Screenshots / Test Artifacts  

---

## 8. Test Environment
- **Environment:** Localhost / QA / Hosted  
- **Browsers:** Chrome, Firefox, Edge  
- **Devices:** Laptop, Mobile  

### Tools Used
- Microsoft Excel – Test Cases & Bug Reports  
- GitHub – QA Portfolio hosting  
- VS Code – Documentation  

---

## 9. Test Schedule

| Task | Estimated Time |
|------|----------------|
| Test Planning | 1 day |
| Test Scenario Design | 1 day |
| Test Case Writing | 1–2 days |
| Test Execution | 2–3 days |
| Bug Reporting | Ongoing |
| Report Preparation | 1 day |

---

## 10. Risks & Mitigation

| Risk | Mitigation |
|------|------------|
| Unclear requirements | Communicate early with team |
| Environment instability | Keep backup test time |
| Delayed build delivery | Adjust schedule |

---

## 11. Approval

| Role | Name | Signature |
|------|------|-----------|
| QA Engineer | Wasana | |
| Project Lead | | |
