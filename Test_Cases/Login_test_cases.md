# Login Form – Test Cases

## TC-001 – Login with valid credentials (Positive)

**Preconditions:**  
- User is on the login page

**Test Steps:**
1. Enter a valid email
2. Enter a valid password
3. Click the **Login** button

**Expected Result:**
- User is logged in successfully
- User is redirected to the product list page
- No error messages are displayed


## TC-002 – Login with invalid password (Negative)

**Preconditions:**  
- User is on the login page

**Test Steps:**
1. Enter a valid email
2. Enter an invalid password
3. Click the **Login** button

**Expected Result:**
- Login is not successful
- Error message is displayed
- User remains on the login page


## TC-003 – Login with invalid email (Negative)

**Preconditions:**  
- User is on the login page

**Test Steps:**
1. Enter an invalid email
2. Enter a valid password
3. Click the **Login** button

**Expected Result:**
- Login fails
- Error message is displayed


## TC-004 – Login with empty fields (Negative)

**Preconditions:**  
- User is on the login page

**Test Steps:**
1. Leave the username field empty
2. Leave the password field empty
3. Click the **Login** button

**Expected Result:**
- Login is not performed
- Validation error messages are shown


## TC-005 – Password field masking

**Preconditions:**  
- User is on the login page

**Test Steps:**
1. Enter any value into the password field

**Expected Result:**
- Password characters are hidden (masked)


## TC-006 – Error message clarity

**Preconditions:**  
- User is on the login page

**Test Steps:**
1. Enter invalid login credentials
2. Click the **Login** button

**Expected Result:**
- Error message is clearly visible
- Error message text is user-friendly


## TC-007 – Logout after successful login

**Preconditions:**  
- User is logged in successfully

**Test Steps:**
1. Click the **Logout** button

**Expected Result:**
- User is logged out
- User is redirected to the login page
