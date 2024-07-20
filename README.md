User Authentication System
Overview:
Developed as part of an assignment, this User Authentication System is a robust solution designed to efficiently manage user accounts, login sessions, password updates, and account deletion. The system comprises six key functions, ensuring a secure and user-friendly experience.

Features:

User Account Management:

Create new user accounts with unique usernames and secure passwords.
Validate and store user credentials securely.
Login Sessions:

Authenticate users with valid credentials.
Manage active login sessions to ensure security and user convenience.
Password Updates:

Allow users to securely update their passwords.
Implement validation checks to ensure password strength and integrity.
Account Deletion:

Provide a secure method for users to delete their accounts.
Ensure proper cleanup of user data upon account deletion.
Technical Details:

Programming Language: Python
Libraries Used: bcrypt for password hashing, sqlite3 for database management
Security Measures:
Passwords are hashed using bcrypt before storage.
Sessions are managed with unique tokens to prevent unauthorized access.
Documentation: Comprehensive documentation is provided for each function, including usage examples and security considerations.
Function Breakdown:

create_user(username, password): Registers a new user with a hashed password.
login_user(username, password): Authenticates a user and starts a session.
logout_user(username): Ends the user's current session.
update_password(username, old_password, new_password): Allows users to update their passwords after validating their old password.
delete_account(username, password): Deletes the user account after verifying credentials.
validate_session(username, token): Checks if a user's session is still valid.
