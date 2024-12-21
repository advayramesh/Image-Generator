# Pentagram

A web application that generates images using AI. Built with Next.js, Modal.ai, and Supabase.

## Features
- Text-to-image generation using Stable Diffusion XL Turbo
- Image storage with Vercel Blob
- User authentication (coming soon)

## Tech Stack
- **Frontend**: Next.js 14 (App Router)
- **Image Generation**: Modal.ai with SDXL Turbo
- **Storage**: Vercel Blob
- **Authentication**: Supabase (in progress)
- **Styling**: Tailwind CSS

## Getting Started

### Prerequisites
- Node.js 18+
- Modal.ai account
- Supabase account
- Vercel account (for Blob storage)

### Installation

1. Clone the repository:
```bash
git clone <your-repo-url>
cd pentagram
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env.local` file with the following variables:
```env
NEXT_PUBLIC_SUPABASE_URL="your-supabase-url"
NEXT_PUBLIC_SUPABASE_ANON_KEY="your-supabase-anon-key"
MODAL_URL="your-modal-endpoint"
API_KEY="your-api-key"
```

4. Run the development server:
```bash
npm run dev
```

5. Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Project Structure
```
pentagram/
├── src/
│   ├── app/
│   │   ├── api/
│   │   │   └── generate-image/
│   │   │       └── route.ts
│   │   ├── components/
│   │   │   └── ImageGenerator.tsx
│   │   ├── actions/
│   │   │   └── generateImage.ts
│   │   ├── layout.tsx
│   │   └── page.tsx
│   └── lib/
│       └── supabase.ts
└── pentagram-modal/
    └── main.py
```

## Features in Development
- User authentication and profiles
- Image history and management
- Social features (likes, comments)
- Image search and discovery

## Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License
This project is licensed under the MIT License - see the LICENSE file for details


