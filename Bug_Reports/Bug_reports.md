## BR-001 – Cart count does not update correctly

**Steps to reproduce:**  
1. Go to the products page  
2. Click "Add to Cart" for any product  
3. Observe the cart icon

**Expected Result:**  
- Cart icon immediately updates with the correct quantity

**Actual Result:**  
- Cart icon sometimes does not update until the page is refreshed

**Severity:** Medium  
**Status:** Open  


## BR-002 – Checkout button enabled on empty cart

**Steps to reproduce:**  
1. Ensure the cart is empty  
2. Click "Check Out"

**Expected Result:**  
- Checkout should be disabled or show a message that the cart is empty

**Actual Result:**  
- Checkout page opens even when there are no products in the cart

**Severity:** Medium  
**Status:** Open  


## BR-003 – Product images missing alt text

**Steps to reproduce:**  
1. Open the products page  
2. Inspect product images

**Expected Result:**  
- Each product image should have descriptive alt text for accessibility

**Actual Result:**  
- Product images do not have alt text, reducing accessibility

**Severity:** Low  
**Status:** Open  


## BR-004 – Login form accepts invalid email format

**Steps to reproduce:**  
1. Go to the Login page  
2. Enter an invalid email (e.g., "useremail.com")  
3. Enter any password and click "Submit"

**Expected Result:**  
- Validation error should be shown for incorrect email format

**Actual Result:**  
- Form accepts invalid email, but login fails with a generic error

**Severity:** Medium  
**Status:** Open  


## BR-005 – Footer links lead to blank pages

**Steps to reproduce:**  
1. Scroll to the footer  
2. Click on "About Us" or "Blog" links

**Expected Result:**  
- Corresponding pages should open correctly

**Actual Result:**  
- Some links open blank pages or do not redirect correctly

**Severity:** Low  
**Status:** Open  