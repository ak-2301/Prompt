Build a React Native mobile application named "Paymint" that works on both Android and iOS, with a fully responsive design for all screen sizes.

📱 App Requirements
1. Splash Screen
Display a splash screen for 5 seconds
Show the text "Paymint" centered on the screen
After 5 seconds, automatically navigate to the Login Screen
2. Authentication Screens

Login Screen

Fields: Email, Password
Add proper validation:
Email must be valid format
Password must not be empty (min 6 characters)
Use dummy credentials for authentication
On successful login → Navigate to Home Screen
Add a button/link to navigate to Register Screen

Register Screen

Fields: Name, Email, Password, Confirm Password
Validation:
All fields required
Email format validation
Password & Confirm Password must match
On successful registration → Navigate to Login Screen
3. Home Screen
Add a top navigation bar
Include a toggle (hamburger) button on the left
On click → Open a sidebar (drawer navigation)
4. Sidebar (Drawer Menu)

Include the following menu items:

My Profile
Settings
Balance
Logout

Each item should:

Navigate to a separate screen when clicked
5. Screens to Implement
Home Screen
My Profile Screen
Settings Screen
Balance Screen
Login Screen
Register Screen
6. Logout Functionality
On clicking Logout, redirect user to Login Screen
7. Technical Requirements
Use React Native (CLI or Expo)
Use React Navigation (Stack + Drawer Navigation)
Ensure clean UI and responsive layout
Use functional components with React Hooks
Maintain proper folder structure (screens, components, navigation, etc.)
8. Bonus (Optional but Preferred)
Add basic styling for modern UI
Use reusable components
Add loading indicator during login
