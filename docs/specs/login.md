# Login Page

Status: draft · Owner: Mathi

## Goal

Provide a modern, responsive login interface using Tailwind CSS and Vite + TypeScript where users and administrators can enter credentials, view demo accounts, and authenticate into the Task List application.

## Out of scope

- Real backend authentication server or database integration (no backend yet).
- Registration and password recovery pages / workflows (only UI links provided).
- Third-party social logins (Google, GitHub, SSO).
- Two-factor authentication (2FA/MFA).
- Complex password reset mechanisms.

## Behavior

- [ ] Given the user opens the root URL in the browser, when the page renders, then they see the Task List login form styled with Tailwind CSS containing an email field, a password field, a "Remember me" checkbox, a "Log in" button, quick-fill buttons for demo accounts, and a link to "Register".
- [ ] Given the email or password field is empty, when the user clicks the "Log in" button, then inline validation messages appear in red indicating the required fields.
- [ ] Given an invalid email format (e.g. "invalid-email"), when the user submits, then an error message "Please enter a valid email address" is displayed.
- [ ] Given the user clicks the "Admin Demo" helper button, when clicked, then the email field is filled with "admin@example.com" and the password field is filled with demo credentials.
- [ ] Given the user clicks the "User Demo" helper button, when clicked, then the email field is filled with "user@example.com" and the password field is filled with demo credentials.
- [ ] Given valid credentials, when the user submits the form, then a success feedback alert or welcome screen is displayed indicating successful sign-in.

## Done when

- [ ] every behavior line has been checked
