# TC-01: Login with invalid password (Mobile App)
## Priotity: Medium

## Requirement
When a user enters an incorrect password during login in a mobile application, an appropriate error message should be displayed.

---

## Preconditions
- The mobile application is installed
- The user is registered in the system
  
---
## Test Data
- Login: test123
- Password: wrong_password34
---

## Steps

### Step 1
**Action:** Open the application  
**Expected result:** Login (authorization) screen is displayed

---

### Step 2
**Action:** Enter valid login in the "Login" field  
**Expected result:** Login is displayed in the input field

---

### Step 3
**Action:** Enter incorrect password in the "Password" field  
**Expected result:** Password is masked (displayed as hidden characters)

---

### Step 4
**Action:** Click the "Login" button  
**Expected result:** Error message appears:  
"Please check the correctness of login and password"
