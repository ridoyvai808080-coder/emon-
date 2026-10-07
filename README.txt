EMON TOP UP — V2
=================

This version has a more polished mobile UI and is prepared for real customer accounts.

IMPORTANT — REAL LOGIN
----------------------
GitHub Pages is static hosting. It cannot safely create/manage customer accounts by itself.
This version therefore uses Firebase Authentication for:
- Google/Gmail login
- Bangladesh phone number + OTP login
- Returning customers can sign into the same account again, including on another device.

Before publishing:
1. Create a Firebase project.
2. Add a Web App.
3. Enable Authentication -> Google.
4. Enable Authentication -> Phone.
5. Add your GitHub Pages domain under Authentication -> Settings -> Authorized domains.
6. Copy the Firebase Web App config into app.js where the PASTE_... values are.
7. Upload index.html, style.css and app.js to the repository root.

Without the Firebase config, the page will NOT pretend that real login works.

PAYMENT
bKash: 01344839207
Nagad: 01960261023
WhatsApp order: 01960261023

WhatsApp does not auto-send. It opens WhatsApp with a pre-filled message and the customer presses Send.
