# Golf Scorecard Tracker

## Overview
A mobile-first golf scorecard app built with **Supabase** backend and authentication. Tracks full golf rounds, practice sessions, club usage, and automatically calculates handicap — all with a clean, outdoor-friendly UI.

---

## Features
- Email + password login, plus guest mode  
- Track 9 or 18 hole rounds with strokes, club used, shot tags, and notes  
- Auto scoring: birdies, pars, bogeys with color-coded display  
- Practice mode separate from official rounds  
- Handicap calculation based on recent rounds  
- Stats dashboard: rounds played, average score, best round, birdie %, etc.  
- Offline support with auto-sync when online  
- Dark mode and large buttons for easy outdoor use  

---

## Tech Stack
- Frontend: React Native / React (web)  
- Backend: Supabase (Auth + Database)  
- AI-powered schema and backend logic generation (via Lovable AI)  

---

## Getting Started

### Prerequisites
- Supabase project (free tier works)  
- React Native environment or web browser  

### How to Use
1. Clone this repo  
2. Connect your Supabase project URL and anon key in the config  
3. Run the app locally with `npm start` or deploy as a web app  
4. Sign up or continue as guest to start tracking rounds  

---

## How to Read Your Data
- **Rounds:** Each round stores hole-by-hole details including strokes, clubs, and shot tags  
- **Stats:** Computed dynamically from saved rounds, showing performance trends  
- **Handicap:** Estimated from the average of your last 10-20 rounds  

---

## Contributing
Feel free to submit issues or pull requests. Let’s improve golf tracking for everyone!

---

## License
This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

