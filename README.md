# ✉️Email-System-using-📁File-Handling
A simple console-based email system implemented in Java.

# Features
- Send emails between users
- View sent and received emails
- View inbox (only received emails)
- Delete emails

# How to Run
1. Clone the repository: git clone https://github.com/G-SHWETA55/Email-System-using-File-Handling.git
2. Navigate to the project directory: cd email-system
3. Compile the Java code: javac *.java
4. Run the application: java EmailSystem

# Usage

1. Launch the application and follow the menu prompts
2. Choose an option:
    -📤 Send Email: Compose and send an email to another user
    -📮 View Inbox: View emails in your inbox
    - 📨View Received Emails: View emails received by you
    - 🗑️Delete Email: Delete an email from your inbox
    - Exit: Quit the application

# 👩🏻‍💻Code Structure

The code is organized into four main classes:
- Email: Represents an email with sender, receiver, subject, and body.
- EmailDAO: Handles data access operations for emails, including saving, retrieving, and deleting emails.
- EmailService: Provides business logic for email operations, such as sending, viewing, and deleting emails.
- EmailSystem: The main class that runs the application and provides a menu-driven interface.
