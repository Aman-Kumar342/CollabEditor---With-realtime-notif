# CollabEditor — With Realtime Notifications

A modern collaborative document editor built with Next.js, Liveblocks, Clerk authentication, and Sentry error monitoring. Supports real-time editing, notifications, comments, and user presence.

## Features
- **Realtime Collaboration:** Multiple users can edit documents simultaneously.
- **User Authentication:** Secure sign-in/sign-up via Clerk.
- **Live Notifications:** Get notified of changes and comments in real time.
- **Comments & Sharing:** Add comments and share documents with others.
- **Rich Text Editing:** Powered by Lexical and JSM Editor.
- **User Presence:** See active collaborators and their avatars/colors.
- **Error Monitoring:** Integrated with Sentry for robust error tracking.
- **Beautiful UI:** Built with Radix UI and Tailwind CSS.

## Tech Stack
- **Frontend:** Next.js, React, Tailwind CSS
- **Realtime:** Liveblocks
- **Auth:** Clerk
- **Editor:** Lexical, JSM Editor
- **UI:** Radix UI, Lucide Icons
- **Error Tracking:** Sentry

## Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/Aman-Kumar342/CollabEditor---With-realtime-notif.git
cd CollabEditor---With-realtime-notif
```

### 2. Install dependencies
```bash
npm install
```

### 3. Configure environment variables
Create a `.env.local` file in the root directory and add:
```
LIVEBLOCKS_SECRET_KEY=your_liveblocks_secret_key
CLERK_SECRET_KEY=your_clerk_secret_key
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
SENTRY_DSN=your_sentry_dsn
```

### 4. Run the development server
```bash
npm run dev
```
Visit [http://localhost:3000](http://localhost:3000) to use the app.

## Project Structure
- `app/` — Next.js app directory (routes, pages, API)
- `components/` — UI and editor components
- `lib/` — Utility functions and Liveblocks integration
- `public/` — Static assets (icons, images)
- `styles/` — CSS themes
- `types/` — TypeScript types

## Scripts
- `npm run dev` — Start development server
- `npm run build` — Build for production
- `npm run start` — Start production server
- `npm run lint` — Lint code

## License
ISC

---

Made with ❤️ by Aman Kumar and contributors.
