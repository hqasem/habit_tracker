User stories for the login/registration page
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

User stories for the homepage
User Story 1: View Welcome Message
Title: Personalized Welcome Message As a user, I want to see a personalized welcome message with my name on the homepage so that I feel recognized and can confirm I am logged into the correct account.
Acceptance Criteria:
1. The homepage should display a welcome message that includes the user's registered name.
2. The welcome message should be clearly visible at the top of the homepage.
3. If the user logs out and logs in again, the correct name should be displayed based on the current session.
Priority: Medium Story Points: 2 Notes:
 The welcome message should follow a friendly tone, e.g., "Welcome back, [User's Name]!".
 Since users log in with default credentials, their name should still be retained from registration.

User Story 2: Display Weekly Progress
Title: View Weekly Habit Progress As a user, I want to see my daily progress for each habit on the homepage so that I can easily monitor my progress.
Acceptance Criteria:
1. The homepage should display a progress section showing each habit and its completion status for the past 7 days.
2. Progress should be visually represented using a progress bar, checkmarks, or a calendar view.
3. The data should update dynamically based on habit completion.
Priority: High Story Points: 3 Notes:
 Users should be able to distinguish completed, in-progress, and missed habits.
 Consider accessibility features, such as colorblind-friendly indicators.

User Story 3: View Completed Habits
Title: Track Completed Habits As a user, I want to see a section for completed habits on the homepage so that I can track what I have already achieved.
Acceptance Criteria:
1. The homepage should display a separate section listing all completed habits.
2. Completed habits should be marked with a checkmark or visual confirmation.
3. The list should update dynamically when a habit is completed.
Priority: High Story Points: 2 Notes:
 The design should prevent clutter by limiting the list to recently completed habits or allowing users to filter them.
 Consider an option to mark habits as "archived" once completed.

User stories for the menu
User Story 1: Access Menu Options
Title: Access Main Menu As a user, I want to access a menu with options for configuring my habits, viewing reports, editing my profile, and signing out so that I can easily navigate to different parts of the app.
Acceptance Criteria:
1. The menu should be accessible from any screen via a visible button (e.g., a hamburger menu or bottom navigation bar).
2. The menu should display options for Profile, Habits, Reports, and Sign Out.
3. The menu should be easy to close (e.g., tapping outside the menu or using a close button).
Priority: High Story Points: 3 Notes:
 The menu should follow a simple and intuitive layout for ease of navigation.
 Consider adding icons alongside text labels for better usability.

User Story 2: Navigate to Profile
Title: Access Profile Page As a user, I want to access the profile page from the menu so that I can update my personal information.
Acceptance Criteria:
1. The menu should contain a "Profile" option that redirects users to the profile page.
2. Selecting "Profile" should load the profile page without delays or errors.
3. The user should be able to return to the previous screen after visiting the profile page.
Priority: High Story Points: 2 Notes:
 Consider adding a profile picture or initials as a visual cue in the menu.

User Story 3: Navigate to Habits Page
Title: Access Habits Page As a user, I want to access the habits page from the menu so that I can configure and manage my habits.
Acceptance Criteria:
1. The menu should have a "Habits" option that directs users to the habits management page.
2. Tapping on "Habits" should navigate to the correct screen without reloading the entire app.
3. The habits page should allow users to view, edit, and create habits.
Priority: High Story Points: 3 Notes:
 Ensure a smooth transition animation when navigating between pages.

User Story 4: Sign Out from Menu
Title: Log Out from Menu As a user, I want to sign out of my account using an option in the menu so that I can securely log out when I'm finished using the app.
Acceptance Criteria:
1. The menu should include a "Sign Out" option.
2. Selecting "Sign Out" should log the user out and return them to the login page.
3. Any session data should be cleared upon logout.
Priority: High Story Points: 2 Notes:
 Display a confirmation prompt before logging the user out to prevent accidental sign-outs.
 Ensure that cached user data is cleared for security reasons.

User stories for the profile page
User Story 1: View Personal Information
Title: View Profile Details As a user, I want to view my saved name, username, age, and country on my profile page so that I can see the details I provided during registration.
Acceptance Criteria:
1. The profile page should display the user's registered name, username, age, and country.
2. The displayed information should match the details entered during registration.
3. The profile information should be presented in a clear and structured format.
Priority: High Story Points: 2 Notes:
 Consider using a read-only mode with an "Edit" button for better user experience.
 Ensure proper text formatting and layout for accessibility.

User Story 2: Edit Personal Information
Title: Update Profile Information As a user, I want to update my name, username, age, and country on my profile page so that I can keep my information up to date.
Acceptance Criteria:
1. The profile page should provide an "Edit" button to enable modification of fields.
2. Users should be able to update their name, username, age, and country.
3. Invalid inputs (e.g., empty fields, non-numeric age) should be prevented with validation messages.
Priority: High Story Points: 3 Notes:
 Consider using a modal or inline editing for better usability.
 Ensure that the username remains unique if applicable.

User Story 3: Save Updated Information
Title: Save Profile Changes As a user, I want the changes I make to my profile to be saved so that my updated details are stored and reflected throughout the app.
Acceptance Criteria:
1. A "Save" button should be available after editing profile information.
2. Clicking "Save" should update the user’s information in the database.
3. The user should receive a confirmation message upon successful update.
Priority: High Story Points: 3 Notes:
 Ensure a smooth transition between edit and view modes.
 Consider adding an option to cancel changes before saving.

User Story 4: Update Name in Header
Title: Display Updated Name in App Header As a user, I want my updated name to be displayed in the app’s header after I change it in the profile so that my changes are immediately visible.
Acceptance Criteria:
1. The app header should dynamically update the name after changes are saved.
2. The updated name should appear on the homepage and other relevant sections.
3. If the user logs out and logs in again, the new name should persist.
Priority: Medium Story Points: 2 Notes:
 Consider implementing real-time updates without requiring a page refresh.

User stories for the habits page
User Story 1: Add a New Habit
Title: Create a Habit As a user, I want to add new habits on the details configuration page so that I can manage and update my habits as needed.
Acceptance Criteria:
1. The habits page should have an "Add Habit" button that opens a habit creation form.
2. The form should include fields for habit name, frequency, reminders, and optional color selection.
3. After saving, the new habit should be added to the list and displayed on the homepage.
Priority: High Story Points: 3 Notes:
 Consider allowing users to set habit categories (e.g., health, productivity).
 Ensure a user-friendly interface with clear input fields and default values.

User Story 2: Delete a Habit
Title: Remove Unwanted Habits As a user, I want to delete existing habits so that I can keep my habits up to date.
Acceptance Criteria:
1. Each habit should have a "Delete" option (e.g., a trash icon or long press action).
2. A confirmation prompt should appear before permanently deleting a habit.
3. After deletion, the habit should be removed from the list and homepage.
Priority: High Story Points: 2 Notes:
 Consider allowing users to "archive" habits instead of permanent deletion.
 Ensure that deleted habits cannot be accidentally recovered without confirmation.

User Story 3: Personalize a Habit with Color
Title: Customize Habit Appearance As a user, I want to assign a specific color to each habit to make it personal to me.
Acceptance Criteria:
1. Users should have an option to choose a color when adding or editing a habit.
2. The selected color should be applied to the habit in the UI (e.g., background, icons, or progress bars).
3. Changes should be saved and persist after logging out and back in.
Priority: Medium Story Points: 2 Notes:
 Provide a color palette with a variety of options but avoid overly bright or unreadable colors.
 Consider accessibility features, such as contrast ratios for colorblind users.

User stories for the reports page
User Story 1: View Weekly Reports
Title: Track Weekly Progress As a user, I want to see a report of my weekly habit progress so that I can understand how well I am maintaining my habits.
Acceptance Criteria:
1. The reports page should display an overview of the user’s progress for the past 7 days.
2. The data should be presented in an easy-to-read format, such as a summary card or progress percentage.
3. The report should update dynamically as habits are completed or missed.
Priority: High Story Points: 3 Notes:
 Consider adding motivational messages based on progress (e.g., "Great job! Keep up the streak!").
 The report should clearly differentiate between completed and missed days.

User Story 2: Visualize Completed Habits
Title: View Completed Habits Chart As a user, I want to see a chart of my completed habits for each day of the week so that I can quickly identify trends in my progress.
Acceptance Criteria:
1. A visual representation (e.g., bar chart, line graph, or heatmap) should display the number of completed habits per day.
2. The chart should be interactive, allowing users to tap on a day to see details.
3. The colors should clearly distinguish between completed and uncompleted habits.
Priority: Medium Story Points: 3 Notes:
 Ensure the chart is accessible for users with visual impairments (e.g., text labels, high contrast).
 Consider allowing users to filter by specific habits.

User Story 3: View All Habits
Title: Comprehensive Habit Overview As a user, I want to see both completed and incomplete habits in my report so that I have a comprehensive view of my habit tracking performance.
Acceptance Criteria:
1. The report should include a section showing all habits, their statuses (completed/missed), and frequency.
2. The user should be able to sort or filter habits (e.g., "Show only completed" or "Show missed habits").
3. Habit data should persist and be accessible even after logging out and back in.
Priority: High Story Points: 3 Notes:
 Consider adding a streak counter to encourage consistency.
 The layout should avoid clutter, ensuring users can easily find key insights.

User stories for the notifications page
User Story 1: Enable/Disable Notifications
Title: Manage Notification Preferences As a user, I want to be able to enable or disable notifications for the app so that I can choose whether or not to receive reminders for my habits.
Acceptance Criteria:
1. The notifications page should have a toggle switch to enable or disable notifications globally.
2. If notifications are disabled, no habit reminders should be sent.
3. If notifications are enabled, users should be able to customize reminders for individual habits.
Priority: High Story Points: 2 Notes:
 Provide a confirmation message when enabling or disabling notifications.
 Consider integrating with system-level notification settings.

User Story 2: Add Habits for Notifications
Title: Select Habits for Notifications As a user, I want to select specific habits to receive notifications for so that I only get reminders for the habits I am actively working on.
Acceptance Criteria:
1. Users should see a list of their habits with checkboxes to enable or disable notifications for each habit.
2. Only selected habits should trigger notifications.
3. Changes should be saved and persist after logging out and back in.
Priority: High Story Points: 3 Notes:
 Consider adding a “Select All” option for convenience.
 Ensure that users can update their selections anytime.

User Story 3: Set Notification Times
Title: Configure Notification Schedule As a user, I want to have the option to receive notifications three times a day (morning, afternoon, evening) for all selected habits so that I get timely reminders throughout the day to complete my habits.
Acceptance Criteria:
1. Users should be able to set notification times for morning, afternoon, and evening.
2. Notifications should be sent only for selected habits at the specified times.
3. Users should receive a confirmation message when changes to notification times are saved.
Priority: Medium Story Points: 3 Notes:
 Provide default time suggestions (e.g., 8 AM, 2 PM, 7 PM) but allow users to customize them.
 Ensure that notifications respect the device’s "Do Not Disturb" settings.
