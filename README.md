# NeuroForge

NeuroForge is a personalized learning application that helps users understand their study preferences and develop structured learning plans. It uses questionnaire-based assessments to generate learning profiles, recommend study techniques, and create weekly schedules.

## Features

- **Learning Assessment:** Evaluates study preferences through a structured questionnaire.
- **Learning Profile:** Identifies dominant learning preferences, strengths, and areas for improvement.
- **Personalized Recommendations:** Suggests study techniques, learning resources, and suitable study environments.
- **Goal Setting:** Allows users to define learning goals, subjects, and target timelines.
- **Study Plan Generator:** Creates a weekly schedule based on the learning profile.
- **Local Persistence:** Saves assessment responses, profiles, and goals in browser storage.

## Technology Stack

- React and TypeScript
- Vite
- Tailwind CSS
- React Router
- Lucide React
- Browser Local Storage

## Project Structure

- `src/components/`: Assessment, results, goal-setting, landing, and study-plan interfaces.
- `src/contexts/`: Shared learning state and application context.
- `src/data/`: Assessment questions and scoring weights.
- `src/types/`: TypeScript interfaces and data structures.
- `src/utils/scoring.ts`: Learning-profile scoring and recommendation logic.
- `src/utils/studyPlans.ts`: Study techniques, resources, tips, and schedule generation.
- `src/utils/storage.ts`: Browser storage utilities.
- `src/App.tsx`: Application routes and context provider.
- `src/index.css`: Global styles.
- `package.json`: Dependencies and development scripts.

## How It Works

Users complete an assessment, review their learning profile, set study goals, and generate a structured study plan. Recommendations are produced through predefined scoring rules and mappings.

## Project Status

The main assessment, profiling, goal-setting, and study-planning workflows are implemented. Future improvements include more flexible scheduling, improved recommendation logic, and broader evaluation of the assessment methodology.

## Getting Started

```bash
npm install
npm run dev
```

To create a production build:

```bash
npm run build
```

## Note

NeuroForge is an educational project. Its learning profiles are based on predefined rules and self-reported preferences, not a validated psychological assessment or machine learning model.
