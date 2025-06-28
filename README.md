# Rehearsal Scheduler Web App

Automatically schedules band rehearsals, sends reminders, tracks attendance, and suggests optimal rehearsal times.

## Features
- Shared online calendar for rehearsals and gigs
- Member availability tracking
- Group chat/messaging
- Setlist creation and assignment
- Song library management
- Event notifications and reminders
- Member and role management
- Mobile-responsive design
- Integration with Spotify, SoundCloud, etc.

## Tech Stack
- Frontend: React
- Backend: Node.js/Express
- Database: PostgreSQL
- Auth: OAuth (Google/Facebook/email)
- Deployment: Docker, GitHub Actions, Vercel/Heroku

## Setup Instructions
1. `git clone https://github.com/dxaginfo/rehearsal-scheduler-app-auto.git`
2. `cd rehearsal-scheduler-app-auto`
3. Copy `.env.example` to `.env` and configure database/auth credentials
4. Run `docker-compose up` (or run backend and frontend separately)
5. Access the app at `http://localhost:3000`

## Security Notes
- Use secure environment variables for all API keys and DB credentials
- OAuth authentication recommended

## Deployment
- App is ready to deploy on Vercel or Heroku using provided Dockerfile and config

## References
- Project Plan: https://docs.google.com/document/d/1WmpzNS-zHsPz5t07wBSHioECHk8v1c2VqCJ_x_r0d6A
- Progress Sheet: https://docs.google.com/spreadsheets/d/1FkdJ4MpFGk5bA4JirPumrmS5Uee3UQ7j26YA99K9iHw

## Next Steps
- Generate/push initial front-end, backend, and migration code
- Configure deployment CI/CD
