# PaTech Labs Website

This is the official website for PaTech Labs, a technology company specializing in AI solutions.

## Technologies Used

This project is built with the following technologies:
- Next.js 14 (App Router)
- React 18+
- TypeScript
- TailwindCSS
- Firebase (Authentication, Storage, and Database)
- Multiple AI endpoints using Vercel AI SDK:
  - OpenAI
  - Anthropic
  - Replicate (for image generation)
- Deepgram for audio transcription

## Getting Started

### Prerequisites
- Node.js 18+ 
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/rushnur88/PaTech-Labs-Website.git
cd PaTech-Labs-Website
```

2. Install dependencies:
```bash
npm install
# or
yarn
```

3. Create a `.env.local` file with the necessary environment variables (see `.env.example` for required variables)

4. Start the development server:
```bash
npm run dev
# or
yarn dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser to see the result.

## Project Structure

- `src/app`: Next.js App Router pages and layouts
- `src/app/api`: API routes
- `src/app/components`: React components
- `src/lib`: Helpers, hooks, and contexts
  - `src/lib/firebase`: Firebase configuration and utilities
  - `src/lib/contexts`: React context providers
  - `src/lib/hooks`: Custom React hooks

## License

All rights reserved © PaTech Labs