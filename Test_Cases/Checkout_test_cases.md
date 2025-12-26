# TC-016 – Proceed to checkout

**Preconditions:**  
- User has at least one product in the cart

**Test Steps:**  
1. Open the cart  
2. Click "Check Out"

**Expected Result:**  
- Checkout page opens successfully


# TC-017 – Required fields validation on checkout

**Preconditions:**  
- User is on the checkout page

**Test Steps:**  
1. Leave all required fields empty  
2. Click "Submit" or "Continue"

**Expected Result:**  
- Validation errors are displayed for each required field


# TC-018 – Successful checkout

**Preconditions:**  
- User is on the checkout page  
- User has at least one product in the cart

**Test Steps:**  
1. Fill in valid information (name, address, email, phone)  
2. Click "Submit" or "Continue"

**Expected Result:**  
- Order is successfully created  
- Confirmation message is displayed


# TC-019 – Invalid email validation

**Preconditions:**  
- User is on the checkout page

**Test Steps:**  
1. Enter email in invalid format (e.g., "useremail.com")  
2. Click "Submit" or "Continue"

**Expected Result:**  
- Error message about invalid email is displayed


# TC-020 – Checkout with empty cart

**Preconditions:**  
- User has no products in the cart

**Test Steps:**  
1. Click "Check Out"

**Expected Result:**  
- User cannot proceed to checkout  
- Message about empty cart is displayed