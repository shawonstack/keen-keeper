# KeenKeeper

> Keep Your Friendships Alive

KeenKeeper is a personal relationship manager that helps you stay connected with
the people who matter most. Track your friendships, log interactions, and never
let important relationships fade away.

## Live Demo

[Deploy link here]

## Technologies Used

| Technology       | Purpose               |
| ---------------- | --------------------- |
| React.js (Vite)  | UI Framework          |
| React Router DOM | Client-side routing   |
| Tailwind CSS     | Utility-first styling |
| DaisyUI          | Component library     |
| Recharts         | Analytics charts      |
| React Hot Toast  | Toast notifications   |
| Lucide React     | Icons                 |

## Key Features

1. **Friend Dashboard** — View all your friends as cards with contact status (On
   Track / Almost Due / Overdue) at a glance
2. **Quick Check-In** — Log calls, texts, and video chats directly from a
   friend's detail page, which instantly appears on the Timeline
3. **Friendship Analytics** — Visual pie chart breakdown of your interaction
   types (Call / Text / Video) powered by Recharts

## Getting Started

```bash
# Install dependencies
npm install

# Run development server
npm run dev

# Build for production
npm run build
```

## Project Structure

```
src/
├── components/     # Navbar, Footer, FriendCard
├── context/        # TimelineContext (global state)
├── data/           # friends.json
├── pages/          # Home, FriendDetail, Timeline, Stats, NotFound
├── App.jsx
├── main.jsx
└── index.css
```

## Deployment

Deployed on Vercel. The `vercel.json` config ensures SPA routing works correctly
(no 404 on page refresh).
