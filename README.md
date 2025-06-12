# Taal Tutor - AI-Powered Language Learning Platform

Een moderne webapplicatie voor het leren van talen met AI-gestuurde tools, interactieve oefeningen en gepersonaliseerde leerervaringen.

## Features

- **Spraak Tutor**: Verbeter je uitspraak met AI-gestuurde spraakanalyse
- **Visuele Leermiddelen**: Upload afbeeldingen om woordenschat in context te leren
- **Persoonlijk Woordenboek**: Bouw je eigen woordenschat collectie
- **Interactieve Vertaling**: Realtime vertaling met culturele inzichten
- **Multi-language Support**: Nederlands, English, Deutsch, Français, العربية, سوري

## Tech Stack

- React + TypeScript
- Tailwind CSS
- Supabase (Authentication & Database)
- Vite
- Netlify (Deployment)

## Database Schema

- **users**: User profiles and authentication data
- **user_settings**: User preferences and settings

## Getting Started

1. Clone the repository
2. Install dependencies: `npm install`
3. Set up environment variables (see .env.example)
4. Run development server: `npm run dev`

## Deployment

The application is automatically deployed to Netlify when changes are pushed to the main branch.

Environment variables required:
- `VITE_SUPABASE_URL`
- `VITE_SUPABASE_ANON_KEY`

---

*Last updated: $(date)*