# 1. Introduction
This Test Plan outlines the strategy, scope, resources, schedule, and approach for testing the Login module of the application.  
The purpose is to ensure that the login functionality is secure, reliable, and performs as expected before release.

---

# 2. Objectives
- Verify that valid users can successfully log in.  
- Ensure invalid login attempts are handled securely.  
- Validate form input, UI behavior, and error messages.  
- Ensure proper session handling and redirection.  
- Check login functionality across different devices and browsers.

---

# 3. Scope of Testing

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

# 4. Test Approach

## **4.1 Testing Types**
- Functional Testing  
- UI/UX Testing  
- Boundary Value Testing  
- Error Handling Testing  
- Security Behavior Checks (basic only)  
- Browser Compatibility Testing  
- Regression Testing  

## **4.2 Testing Levels**
- Component Testing (login page)  
- Integration Testing (login + dashboard)  
- System Testing  

---

# 5. Entry & Exit Criteria

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

# 6. Test Deliverables
- Test Plan  
- Test Scenarios  
- Test Cases  
- Bug Reports  
- Test Summary Report  
- Screenshots / Artifacts  

---

# 7. Test Environment
**Environment:** Staging / QA  
**Browsers:** Chrome, Firefox, Edge  
**Devices:** Laptop + Mobile  

**Tools:**  
- Excel (for Test Cases & Bug Reports)  
- GitHub (for project hosting)  

---

# 8. Test Schedule

| Task                 | Estimated Time |
| -------------------- | -------------- |
| Test Planning        | 1 day          |
| Test Scenario Design | 1 day          |
| Test Case Writing    | 1–2 days       |
| Test Execution       | 2–3 days       |
| Bug Reporting        | Ongoing        |
| Report Preparation   | 1 day          |

---

# 9. Risks & Mitigation

| Risk                   | Mitigation                  |
| ---------------------- | --------------------------- |
| Unclear requirements   | Communicate early with team |
| Environment not stable | Keep backup test time       |
| Delayed build delivery | Adjust schedule             |

---

# 10. Approval

| Role         | Name   | Signature |
| ------------ |--------|---------- |
| QA Engineer  | Wasana |          |
| Project Lead |        |          |
