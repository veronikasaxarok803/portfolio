Veronika Haran — UI/UX Designer Portfolio

Problem first. Pixels second.

Personal portfolio of Veronika Haran, a Middle UI/UX designer. I start with the user's and the business's problem, not the mockup — and I can explain every decision on the screen.

🔗 Live site: portfolio-sigma-six-94.vercel.app

Open to full-time · Remote · Ukraine, UTC+2/+3 · Any time zone

About the project

The site is built in code (not a site builder), so case studies live on the site itself instead of only on Behance. Every case follows the same structure: problem → who it's for → my role → solution and why → result.

Selected work
Case	Type	What it shows
O3C	Web app · DevOps · 2025	Errors reach admins in minutes, not hours. Full design cycle from client brief to final UI. The tool is in use today.
RelationShift	Mobile app · 2025	A coaching app that helps couples talk. Lead designer for every screen, from sign-in to tests and mini-games. Live on Google Play.
Dashboard Student	Web · EdTech · 2024	A student dashboard that shows what matters first. Learning project with a brief and feedback from a course mentor.

Full presentations on Behance: O3C · RelationShift · Dashboard Student

Features

Done

Hero screen implemented from the Figma design: name, role, positioning, portrait card and calls to action
Navigation with anchor links to Work, About and Contact
Responsive layout

Planned

Main page sections: How I work, Selected work, client reviews, About, Contact
Separate pages for each of the three case studies and an About page
Bilingual site: English by default, Ukrainian via an EN/UA switch in the header
Contacts in the footer of every page
Tech stack
React 19 + TypeScript
Vite for development and builds
Oxlint for linting
Plain CSS, self-hosted fonts via Fontsource: Inter, Space Grotesk, IBM Plex Mono
Deployed on Vercel
Running locally

Requires Node.js 20 or newer.

bash
git clone https://github.com/veronikasaxarok803/portfolio.git
cd portfolio
npm install
npm run dev
Command	What it does
npm run dev	Start the dev server with hot reload
npm run build	Type-check and build for production into dist/
npm run preview	Preview the production build locally
npm run lint	Run Oxlint
Project structure
portfolio/
├── public/            # favicon and icons
├── src/
│   ├── assets/        # images (portrait)
│   ├── App.tsx        # page layout and sections
│   ├── App.css        # component styles
│   ├── index.css      # global styles and fonts
│   └── main.tsx       # entry point
├── index.html
└── vite.config.ts
Contact
Email: vrok.nik7@gmail.com
LinkedIn: veronika-morozenko
Upwork: profile and reviews — Top Rated Plus · 100% Job Success
