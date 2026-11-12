# Winvian Design Intelligence — Prototype 01

A browser-based clickable prototype for Winvian Design Firm's client discovery experience.

## Run it
1. Extract the ZIP (if downloaded).
2. Open `index.html` in a modern browser.
3. Click **Begin your design journey** and complete the six steps.
4. The generated brief can be printed/saved as PDF or copied.
5. Open **Studio Dashboard** to view submissions saved in that browser.

## Included
- Responsive client landing page
- Six-step discovery journey
- Visual style and material selection
- Lifestyle, project and budget questions
- Guided conversation UI (scripted prototype, not connected to an AI model)
- Room/project brief generation
- Print-to-PDF and copy brief
- Local browser demo dashboard using localStorage

## Important prototype limitations
- Data is stored only in the browser that was used; it is not a secure shared database.
- No real user login, cloud sync, AI API, image upload, payment or SketchUp/Enscape integration.
- Image references load from Unsplash and require an internet connection.
- Before using with real clients, add authentication, a secure backend/database, privacy notice/consent, access controls, backups and production testing.

## Suggested next build
Deploy the frontend, connect Supabase for secure project storage and authentication, then add an AI service that converts approved client answers into editable design briefs. Keep architectural decisions and final specifications under designer review.
