This project demonstrates how to securely hash and validate passwords in python using the bcrypt library.
It includes two implementations:
**Console Based Version** - Passwords are entered through the terminal and validated against a stored hash
**GUI-Based Version(Tkinter)** - A simple login window where users can enter a password,which is checked against a pre stored hash.
This ensures that passwords are never stored in plain text , improving application security.
**Features** - 
Secure password hashing with bcrypt and automatic salt generation.
Password verification using bcrypt.checkpw().
Tkinter GUI for user-friendly login validation.
Console version for command-line demonstrations.
