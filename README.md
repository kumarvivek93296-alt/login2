Tricolor Trends — Mini Marketplace (Client ↔ Worker) — Static (GitHub Pages ready)
==============================================================================

What this is:
- A ready-to-host static web app using Firebase (Auth + Firestore).
- Clients can post projects.
- Workers can browse projects by skill/category and apply.
- Clients can view applicants and assign a worker.

How to use:
1) Create a Firebase project → Web App → copy config.
2) In `scripts/firebase.js`, paste your Firebase config in the placeholder.
3) In Firebase Console:
   - Enable Authentication → Email/Password.
   - Create Cloud Firestore (in test mode for quick start).
4) (Recommended) Set Firestore Rules (copy this into Rules tab).

5) Host the folder on GitHub Pages (root contains index.html).
6) Open index.html → Register as Client or Worker.
7) Enjoy!
