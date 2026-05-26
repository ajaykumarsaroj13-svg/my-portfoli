# Premium EdTech Ecosystem

A complete, local-first EdTech platform prototype for JEE Main, JEE Advanced, NDA, IISER, Class 11 and Class 12.

## What is included

- Premium public landing page with dynamic CMS-backed content.
- Student mobile app UI preview with onboarding, dashboard, lectures, tests, PYQs, notes, analytics, profile and dark mode.
- Full admin control panel for lectures, assignments, DPPs, questions, subjects, chapters, mock tests, banners, homepage sections, media, students, subscriptions, notifications, teachers, roles and theme controls.
- Local persistence using browser storage so admin edits immediately update the platform.
- Firebase/Supabase-ready service boundary in `src/services/backend-adapter.js`.
- Cloud storage folder plan in `docs/cloud-storage.md`.
- Navigation and data architecture in `docs/architecture.md`.

## Run locally

```bash
npm start
```

Open `http://localhost:4173`.

## Production path

Use this prototype as the product shell, then connect the adapter layer to Firebase or Supabase:

- Auth: email/password, mobile OTP, Google Sign-In.
- Database: Firestore or PostgreSQL.
- Storage: Firebase Cloud Storage or Supabase Storage.
- Rules: role-based access for owner, admin, teacher, support and student.
