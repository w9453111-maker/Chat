# Gather — Community Chat Prototype

A Discord-inspired single-page chat prototype built with HTML, CSS, and JavaScript.

## Run it
Open `index.html` in a browser, or enable GitHub Pages in the repository settings to publish it.

## Features
- Create an account and sign in
- Member role is assigned automatically
- Server/channel layout and text messages
- Admin can create and delete servers
- Server managers can create roles and assign roles to members
- Channel settings include an “Everyone can chat” option and per-member chat permissions
- Profile bio, username, and uploaded avatar
- Responsive layout for smaller screens

## Important limitations before publishing
This is a **front-end demo**, not a secure, multi-user Discord replacement. Accounts, passwords, servers, and messages are stored in the browser's localStorage, so they do not sync between devices or different users' browsers. Passwords are not securely hashed. Anyone who can inspect the public source can see the demo admin password, and browser-only permissions can be bypassed. Do not use real/reused passwords or sensitive information.

For a real public chat service, add a trusted backend and database, secure authentication/password hashing, server-side role and channel permission checks, and image upload storage. Never rely on client-side code to protect admin access.
