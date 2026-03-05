# :test_tube: Test Cases
## Project: E-Commerce Web Application

---

## Test Case 1

**Test Case ID:** TC_001  
**Test Scenario:** Verify user registration with valid details  

**Steps:**
1. Open the registration page
2. Enter valid name, email, and password
3. Click Register

**Expected Result:**
User account should be created successfully.

---

## Test Case 2

**Test Case ID:** TC_002  
**Test Scenario:** Verify user cannot register with existing email  

**Steps:**
1. Open registration page
2. Enter an already registered email
3. Click Register

**Expected Result:**
System should show error message "Email already exists".

---

## Test Case 3

**Test Case ID:** TC_003  
**Test Scenario:** Verify user login with valid credentials  

**Steps:**
1. Navigate to login page
2. Enter valid username and password
3. Click login

**Expected Result:**
User should be logged into the system.

---

## Test Case 4

**Test Case ID:** TC_004  
**Test Scenario:** Verify login with invalid credentials  

**Steps:**
1. Navigate to login page
2. Enter incorrect username/password
3. Click login

**Expected Result:**
System should display "Invalid credentials".

---

## Test Case 5

**Test Case ID:** TC_005  
**Test Scenario:** Verify product search functionality  

**Steps:**
1. Enter product name in search bar
2. Click search

**Expected Result:**
Relevant products should be displayed.

---

## Test Case 6

**Test Case ID:** TC_006  
**Test Scenario:** Verify user can add product to cart  

**Steps:**
1. Open product page
2. Click "Add to Cart"

**Expected Result:**
Product should be added to cart successfully.

---

## Test Case 7

**Test Case ID:** TC_007  
**Test Scenario:** Verify user can remove product from cart  

**Steps:**
1. Open cart
2. Click remove product

**Expected Result:**
Product should be removed from cart.

---

## Test Case 8

**Test Case ID:** TC_008  
**Test Scenario:** Verify checkout process  

**Steps:**
1. Add product to cart
2. Click checkout
3. Enter shipping details
4. Place order

**Expected Result:**
Order should be placed successfully.

---

## Test Case 9

**Test Case ID:** TC_009  
**Test Scenario:** Verify cart updates quantity correctly  

**Steps:**
1. Add product to cart
2. Increase quantity

**Expected Result:**
Total price should update accordingly.

---

## Test Case 10

**Test Case ID:** TC_010  
**Test Scenario:** Verify logout functionality  

**Steps:**
1. Login to application
2. Click logout

**Expected Result:**
User should be logged out successfully.
