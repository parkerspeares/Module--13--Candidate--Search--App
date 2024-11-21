Module 13 Cadidate Search App

License: MIT | TypeScript
This application allows you to view a list of GitHub users and manage them with ease.

Table of Contents
Introduction
Required Technologies
Installation
Usage
Features
License
Technologies Used
Credits
Contact Me

Introduction
Candidate Search is a TypeScript-based app designed to streamline viewing and managing GitHub users. It provides tools to save or reject users and track saved candidates.

Required Technologies
This project requires:
Node.js 
TypeScript

Installation
Clone or download the project files.
Open the terminal in the /develop directory of the project folder.
Install dependencies by running:
bash
Copy code
npm install
Navigate to the .env.EXAMPLE file in the develop/environment directory:
Add your GitHub fine-grained personal access token.
Rename the file to .env.
Start the application by running:
bash
Copy code
npm run dev

Usage
Once launched, you’ll see the Candidate Search Homepage:

If your GitHub token is configured, a list of GitHub users will be displayed.
Each user card includes:
Profile picture
Username
"Accept" and "Decline" buttons
Additional details such as bio, name, email, location, and company (if available).
Key Interactions:
Accepting Users:
Clicking "Accept" saves the user's data to local storage and removes them from the homepage.
Declining Users:
Clicking "Decline" removes the user from the homepage without saving.
Saved Candidates Page:
Accessible via the "Saved Candidates" link at the top.
View detailed information for all accepted users.
Decline saved users from this page to remove them from local storage.
Clear Local Storage Button:
Located at the bottom of the homepage, this clears all saved data.

Features
Display GitHub user information.
Accept/Decline functionality for managing users.
Saved Candidates page for accepted users.
Clear Local Storage button for quick data management.

License
This project is licensed under the MIT License.

Technologies Used
VS Code
TypeScript
Node.js
Vite
Stack Overflow
W3 Schools

Credits
Author - Parker Speares

Contact Me
For any questions or feedback, please feel free to reach out.