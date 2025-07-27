# Test Case: User Login via Email and Password

**Test Case ID:** TC-005  
**Title:** Successful user login via email and password in the mobile application  

**Preconditions:**  
- Mobile application is installed and launched  
- User is registered and has valid credentials (email and password)  
- Device is connected to the internet

**Test Steps:**  
1. Open the mobile application  
2. On the login screen, enter a valid email (e.g., testuser@example.com)  
3. Enter the correct password  
4. Tap the "Login" button  
5. Wait for the server response and transition to the main screen of the application

**Expected Result:**  
- The main screen of the application (dashboard/home) is displayed  
- UI elements visible only to authorized users are present (e.g., username, logout button)  
- No errors or warnings are shown during login

**Postconditions:**  
- The user is successfully logged in and can use all features of the app that require authentication
