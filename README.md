Please before reeviewing the website first go through README.md
link to open the site :  https://thegreatpratyush.github.io/splitwise/
Splitwise-like Expense Sharing App

A front-end implementation of an expense sharing application inspired by Splitwise.
This project focuses on core expense logic, balance calculation, and settlement flow, with backend integration planned next.

🚀 Features Implemented

Create groups and add members

Add, edit, and delete expenses

Split expenses equally or among selected members

Automatic balance calculation for each member

Optimized settlement logic (who pays whom and how much)

Pending member status support

Group-wise expense history

Clean and readable UI with real-time updates

⚠️ Important Notes & Current Limitations

Page refresh required after creating a group
Group creation updates LocalStorage, but UI refresh is required to reflect changes.

Hover-based navigation (desktop only)
Group dropdown uses hover effects, so it works best on desktop/laptop (Windows/Mac).

Static logged-in user
Currently, the inviter is always set as:

John (john@gmail.com)


This is intentional and will become dynamic after backend authentication.

Pending members are visible but not verified
Invited members appear as pending but can still participate for now due to lack of backend validation.

LocalStorage-based data
All data is stored in browser LocalStorage, so:

Data is device-specific

No multi-user sync

Clearing browser data removes everything

🛠️ Why Backend Is Needed (Next Phase)

Backend integration will solve:

Real user authentication (login/signup)

Email-based invitations with secure invite links

Joining groups via invite or code

Role-based permissions (admin / member)

Persistent data using MySQL

Multi-device and multi-user access

Secure expense ownership and history tracking

🔮 Planned Improvements

Backend using Node.js + Express

MySQL database for groups, users, expenses

Email authentication and invite flow

Join group via invite link or group code

Mobile-friendly UI (remove hover dependency)

Activity feed and notifications

🧠 Tech Stack

Frontend

HTML

CSS

JavaScript (Vanilla)

Storage (Current)

Browser LocalStorage

Backend (Planned)

Node.js

Express

MySQL

Email authentication

📌 How to Run

Open index.html in a desktop browser (Chrome recommended)

Create a group

Refresh the page once to see the group

Start adding members and expenses

This README honestly shows:

what works ✅
