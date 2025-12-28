# 1. Introduction
This Test Plan outlines the strategy, scope, resources, schedule, and approach for testing the **Login module** of the **Seagrass Sri Lanka Web Application**.  
The purpose is to ensure that the login functionality is secure, reliable, and performs as expected before release.

---

# 2. Project Information
- **Project Name:** Seagrass Sri Lanka  
- **Application Type:** Web Application  
- **Module Under Test:** User Login  
- **Test Environment:** Production (Hosted)  
- **Application URL:**  
  - Hosted (if available): https://polite-desert-02a5b7610.2.azurestaticapps.net/
---

# 3. Objectives
- Verify that valid users can successfully log in.  
- Ensure invalid login attempts are handled securely.  
- Validate form input, UI behavior, and error messages.  
- Ensure proper session handling and redirection.  
- Check login functionality across different devices and browsers.

---

# 4. Scope of Testing

## **In Scope**
- Login form UI testing  
- Functional testing (positive & negative)  
- Validation message testing  
- Security-related behavior (basic checks)  
- Session management testing  
- Compatibility testing (mobile/desktop)  
- Usability testing  

## **Out of Scope**
- Backend API load testing  
- Password reset module  
- User registration module  
- OAuth/Google login (if not included)  

---

# 5. Test Approach

## **5.1 Testing Types**
- Functional Testing  
- UI/UX Testing  
- Boundary Value Testing  
- Error Handling Testing  
- Security Behavior Checks (basic only)  
- Browser Compatibility Testing  
- Regression Testing  

## **5.2 Testing Levels**
- Component Testing (login page)  
- Integration Testing (login → home/dashboard)  
- System Testing  

---

# 6. Entry & Exit Criteria

## **Entry Criteria**
- Login feature requirements shared.  
- Build is deployed to the test environment.  
- Test data is prepared.  
- Test environment is stable.  

## **Exit Criteria**
- All high & medium priority test cases executed.  
- No critical or high-severity bugs open.  
- Test summary report prepared.  

---

# 7. Test Deliverables
- Test Plan  
- Test Scenarios  
- Test Cases  
- Bug Reports  
- Test Summary Report  
- Screenshots / Artifacts  

---

# 8. Test Environment
**Environment:** Localhost / QA  
**Browsers:** Chrome, Firefox, Edge  
**Devices:** Laptop + Mobile  

**Tools Used:**  
- Microsoft Excel – Test Cases & Bug Reports  
- GitHub – QA Portfolio hosting  
- VS Code – Documentation  

---

# 9. Test Schedule

| Task                 | Estimated Time |
| -------------------- | -------------- |
| Test Planning        | 1 day          |
| Test Scenario Design | 1 day          |
| Test Case Writing    | 1–2 days       |
| Test Execution       | 2–3 days       |
| Bug Reporting        | Ongoing        |
| Report Preparation   | 1 day          |

---

# 10. Risks & Mitigation

| Risk                   | Mitigation                  |
| ---------------------- | --------------------------- |
| Unclear requirements   | Communicate early with team |
| Environment not stable | Keep backup test time       |
| Delayed build delivery | Adjust schedule             |

---

# 11. Approval

| Role         | Name   | Signature |
| ------------ |--------|---------- |
| QA Engineer  | Wasana |          |
| Project Lead |        |          |
