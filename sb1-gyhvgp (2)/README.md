# Lab to Lab Platform

A professional network platform connecting laboratories across the United States.

## Project Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/haleyreinhard/labtolabplatform.git
   cd labtolabplatform
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file with your Supabase credentials:
   ```
   VITE_SUPABASE_URL=your_supabase_url
   VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

## Build and Deploy

To build the project for production:
```bash
npm run build
```

The project is configured for deployment on Netlify with the following settings:
- Build command: `npm run build`
- Publish directory: `dist`

## Features
- Lab Directory
- Professional Community
- Marketplace for Lab Services
- Contact System
- User Authentication
- Lab Registration

## Tech Stack
- React
- TypeScript
- Vite
- Tailwind CSS
- Supabase
- React Router
- Lucide Icons