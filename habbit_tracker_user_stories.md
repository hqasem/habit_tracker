User Story 1: Account Registration
Title: Account Registration As a user, I want to register with my name, username, age, and country so that I can create an account and access the habit tracking features.
Acceptance Criteria:
1. The registration form must include fields for name, username, age, and country.
2. The system should validate all required fields before allowing submission.
3. Upon successful registration, the user should see a confirmation message and be redirected to the login page.
Priority: High Story Points: 3 Notes:
 Users should not be able to register with a duplicate username.
 No password is required at registration since login is restricted to default credentials.

User Story 2: Account Login
Title: Account Login As a user, I want to log in using the default username and password so that I can access my account and track my habits.
Acceptance Criteria:
1. The login page must have fields for username and password.
2. Users can only log in using the predefined default credentials.
3. After successful login, the user is redirected to the homepage.
Priority: High Story Points: 2 Notes:
 User-entered credentials are not stored in the browser cache and are cleared after logout.
 Users should not be able to log in with their own registered credentials.

User Story 3: Error Feedback on Login
Title: Error Feedback on Login As a user, I want to receive a message if I enter the wrong username or password so that I know my login attempt was unsuccessful.
Acceptance Criteria:
1. If the user enters incorrect credentials, an error message should be displayed.
2. The error message should clearly state that the username or password is incorrect.
3. The login form should not clear entered credentials upon error but should allow the user to correct them and try again.
Priority: High Story Points: 2 Notes:
 The error message should not reveal whether the username or password is incorrect for security reasons.
