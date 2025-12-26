## NFR-001 – Page Load Performance

**Description:**  
- Verify that the homepage and product pages load quickly under normal conditions

**Test Steps:**  
1. Open the homepage in a browser  
2. Measure page load time  
3. Repeat for product pages

**Expected Result:**  
- Pages load within 3 seconds on a standard internet connection


## NFR-002 – Responsive Design

**Description:**  
- Verify that the website is fully responsive on desktop, tablet, and mobile devices

**Test Steps:**  
1. Open the site on desktop, tablet, and mobile  
2. Navigate through main pages, catalog, and checkout

**Expected Result:**  
- Layout and elements adjust correctly to screen size  
- No overlapping or hidden elements

## NFR-003 – Cross-browser compatibility

**Description:**  
- Verify that the website works correctly across popular browsers (Chrome, Firefox, Edge, Safari)

**Test Steps:**  
1. Open the website in **Google Chrome** and navigate through:  
   - Homepage  
   - Product catalog  
   - Product details page  
   - Cart  
   - Checkout page  
2. Repeat the same steps in **Mozilla Firefox**  
3. Repeat the same steps in **Microsoft Edge**  
4. Repeat the same steps in **Safari**  
5. Check all interactive elements: buttons, links, dropdowns, forms, add to cart, checkout

**Expected Result:**  
- Pages render correctly in all browsers  
- Layout, styles, and fonts display consistently  
- All buttons, links, and forms work as expected  
- No visual or functional issues specific to a browser

## NFR-004 – Security

**Description:**  
- Verify that sensitive user data (login, email, payment info) is protected

**Test Steps:**  
1. Attempt to access user account data without logging in  
2. Inspect network requests for sensitive data exposure  
3. Check password field masking

**Expected Result:**  
- Unauthorized access is prevented  
- Sensitive data is encrypted or not exposed  
- Password field masks input

---

## NFR-005 – Accessibility

**Description:**  
- Verify that the website is accessible for users with disabilities

**Test Steps:**  
1. Navigate the site using keyboard only  
2. Test screen reader support on key pages (home, products, cart, checkout)  
3. Check color contrast ratios

**Expected Result:**  
- All interactive elements are reachable via keyboard  
- Screen readers can read content correctly  
- Color contrast meets WCAG standards

---

## NFR-006 – Scalability / Load handling

**Description:**  
- Verify that the website can handle multiple users simultaneously

**Test Steps:**  
1. Simulate 50-100 concurrent users browsing products and adding items to cart  
2. Observe performance and response times

**Expected Result:**  
- Website remains functional  
- Page load and interactions remain within acceptable time limits

---

## NFR-007 – Reliability / Availability

**Description:**  
- Verify that the website is available and does not crash under normal usage

**Test Steps:**  
1. Navigate through main pages repeatedly  
2. Add/remove products from cart multiple times  
3. Attempt checkout

**Expected Result:**  
- No crashes or unexpected errors occur  
- Website remains accessible during testing