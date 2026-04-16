# Negative Test Cases: Login Failure Scenarios

## Test ID
TC-LOGIN-002 to TC-LOGIN-006

---

## ❌ TC-LOGIN-002: Invalid Password

### Purpose
Verify that login fails when the password is incorrect.

### Test Data
- Email: testuser@example.com
- Password: WrongPassword

### Preconditions
- Browser is open
- User is on the login page
- Test account exists 

### Steps
1. Navigate to the login page  
2. Enter a valid email  
3. Enter an invalid password  
4. Click "Login"  

### Expected Result
- Login fails  
- Error message appears: "Invalid email or password"  
- User stays on login page

### Actual Result
(To be filled during execution)

---

## ❌ TC-LOGIN-003: Invalid Email Format

### Test Data
- Email: testuserexample.com
- Password: Password123

### Preconditions
- Browser is open
- User is on the login page
- Test account exists 

### Steps
1. Navigate to the login page  
2. Enter an invalid email  
3. Enter an invalid password  
4. Click "Login"

### Expected Result
- Validation error appears: "Please enter a valid email address"  
- Login request is not sent  

### Actual Result
(To be filled during execution)

---

## ❌ TC-LOGIN-004: Empty Email Field

### Test Data
- Email: (empty)
- Password: Password123

### Preconditions
- Browser is open
- User is on the login page
- Test account exists 

### Steps
1. Open login page  
2. Leave the Email field empty  
3. Enter a valid password  
4. Click "Login"

### Expected Result
- Error message: "Email is required"

### Actual Result
(To be filled during execution) 

---

## ❌ TC-LOGIN-005: Empty Password Field

### Test Data
- Email: mariko_tajima@hotmail.com
- Password: (empty field)

### Preconditions
- Browser is open
- User is on the login page
- Test account exists 

### Steps
1. Open login page  
2. Enter a valid email 
3. Leave the Password field empty
4. Click "Login"


### Expected Result
- Error message: "Password is required"


### Actual Result
(To be filled during execution)


---

## ❌ TC-LOGIN-006: Both Fields Empty

### Test Data
- Email: (empty field)
- Password: (empty field)

### Preconditions
- Browser is open
- User is on the login page
- Test account exists 


### Steps
1. Open login page  
2. Leave a Email field empty
3. Leave the Password field empty
4. Click "Login"

### Expected Result
- Error message: "Email and password are required"

### Actual Result
(To be filled during execution)
