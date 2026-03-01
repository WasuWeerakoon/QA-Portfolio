# Cart Management – Test Scenarios

---

## 1. Module Information

- **Module Name:** Cart Management
- **Application:** Automation Exercise
- **Application URL:** https://automationexercise.com/
- **Testing Type:** Manual Testing

---

## 2. Objective

To verify that the **Cart Management module** allows users to add, view, update, and remove products from the cart correctly, and ensures accurate calculations and validations.

---

## 3. Assumptions

- Product listing page is accessible
- Products are available for adding to cart
- User has stable internet connectivity
- Cart functionality is enabled
- User may or may not be logged in (based on application behavior)

---

## 4. Cart Management Test Scenarios

### TS-CM-01: Verify user can add product to cart

- Verify that a user can successfully add a product to the cart and the cart icon updates with the correct item count.

### TS-CM-02: Verify viewing cart page

- Verify that the cart page displays all added products with correct product details including name, image, price, and quantity.

### TS-CM-03: Verify cart subtotal calculation

- Verify that the subtotal for each product is calculated correctly based on quantity and unit price.

### TS-CM-04: Verify cart total amount calculation

- Verify that the total cart amount reflects the correct sum of all product subtotals.

### TS-CM-05: Verify updating product quantity

- Verify that modifying the product quantity updates the subtotal and total amount correctly.

### TS-CM-06: Verify removing product from cart

- Verify that a user can remove a product from the cart and the cart updates immediately.

### TS-CM-07: Verify empty cart functionality

- Verify that the system displays an appropriate message when the cart is empty and restricts checkout access.

### TS-CM-08: Verify invalid quantity handling

- Verify that the system prevents invalid quantity inputs such as negative numbers or non-numeric values.

### TS-CM-09: Verify cart persistence after refresh

- Verify that cart items remain intact after refreshing the page.

### TS-CM-10: Verify cart persistence during navigation

- Verify that cart items remain available when navigating between different pages of the application.

### TS-CM-11: Verify checkout button functionality

- Verify that clicking the checkout button redirects the user to the checkout process page.

### TS-CM-12: Verify cart page UI consistency

- Verify that the cart page layout, buttons, and alignment are consistent and responsive across different devices.

### TS-CM-13: Verify cross-browser compatibility

- Verify that cart functionality works correctly across different browsers such as Chrome, Firefox, and Edge.

### TS-CM-14: Verify cart performance

- Verify that the cart page loads within an acceptable time under normal network conditions.

---

## 5. Expected Outcome

- Users should be able to add, update, and remove products without errors.
- Cart calculations should be accurate.
- Proper validation messages should appear when required.
- Cart UI should be consistent and responsive across browsers and devices.

---

## 6. Prepared By

**QA Tester:** Wasana Weerakon  
**Date:** December 2025
