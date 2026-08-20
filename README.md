# LocalSkill Match - AI Local Employment

LocalSkill Match is an offline-first React + TypeScript web app for connecting local job seekers with community employment opportunities.

The skill-matching engine runs locally in the browser using deterministic text and skill-similarity logic.

## Run locally

### Prerequisites

- Node.js 18+ (Node.js 20+ recommended)
- npm

### Install dependencies

```bash
npm install
```

### Start the development server

```bash
npm run dev
```

Open the local URL shown by Vite, normally:

`http://localhost:3000`

### Build for production

```bash
npm run build
```

### Preview the production build

```bash
npm run preview
```

## Notes

- No external AI account or API key is needed.
- User profiles, jobs, applications, and settings are stored locally in the browser using `localStorage`.
- The project also includes a Capacitor Android wrapper under `android/`.
