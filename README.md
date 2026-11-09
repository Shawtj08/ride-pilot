# Ride Pilot v1
This is a functional single-browser prototype, not a deployed service.

Features: local passenger access requests, admin approve/decline/suspend, ride requests, 9 PM Eastern late-request classification, shift-change flag, driver ride approvals, simple capacity check for matching time groups, JSON export, PWA manifest.

Limitations: No secure login, real invitations, shared database, payments, notifications, mapping, route feasibility, or backend authorization. Driver and passenger tabs are visible on the same device. Do not use with real passenger personal data or real paid rides.

To preview: unzip and run `python -m http.server 8000` in this folder; visit http://localhost:8000. To install on Android, upload all files together to an HTTPS host, then use Chrome's Install/Add to Home Screen option.

Next phase: secure Firebase Auth + Firestore, server-enforced driver role and passenger approvals, invitation links, transactional booking capacity, and notifications.
