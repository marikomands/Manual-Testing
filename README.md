# Login Feature Test Design

## 1. Overview
This document outlines the test design for the login functionality.  
It covers both successful (happy path) and failure scenarios to ensure reliable and user-friendly behaviour.

---

## 2. Test Approach
The testing approach is based on user behaviour and common usage patterns.

The following aspects were considered:
- Normal user flow (happy path)
- Error handling for invalid inputs
- Basic edge cases

The goal is to verify that the login feature works correctly and provides clear feedback to users in both success and failure situations.

---

## 3. Test Scenarios

### ✅ Happy Path
- Login with valid email and password  
  → User successfully logs in and is redirected to the dashboard

---

### ❌ Failure Cases

- Incorrect password  
  → Error message displayed and login fails  

- Empty email or password  
  → Validation message displayed  

- Invalid email format  
  → Error message displayed  

---

## 4. Notes
Additional scenarios that could be tested for more comprehensive coverage include:
- Long input values  
- Special characters in input fields  
- UI behaviour (error message position, layout issues)  
- Performance (response time during login)

---

## 5. Summary
This test design focuses on ensuring that the login functionality behaves correctly under normal and error conditions, while maintaining a clear and consistent user experience.
