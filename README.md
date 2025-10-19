# HalloMeme AI

> Democratize Halloween-themed meme creation through intelligent, user-friendly technology

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)](https://github.com/hallomeme/ai-generator)

## Overview

HalloMeme AI is the world's first AI-powered Halloween meme generator that transforms seasonal humor and creativity. Designed for social media content creators and Halloween enthusiasts, our platform makes meme creation quick, fun, and intelligent.

## Features

- ✨ AI-powered meme generation
- 🚀 Halloween-themed template library
- 💡 One-click social media sharing
- 🔒 Secure user authentication

## Tech Stack

**Frontend:**
- React 18 with TypeScript
- Tailwind CSS
- Zustand for state management
- Framer Motion for animations

**Backend:**
- Node.js 20 LTS
- Next.js API Routes
- PostgreSQL with Prisma ORM
- tRPC for type-safe APIs

**Deployment:**
- Vercel
- Supabase
- Cloudinary

## Quick Start

### Prerequisites

```bash
node >= 18.0.0
npm >= 9.0.0
```

### Installation

```bash
# Clone the repository
git clone https://github.com/hallomeme/ai-generator.git

# Install dependencies
cd hallomeme-ai
npm install

# Set up environment variables
cp .env.example .env
# Edit .env with your configuration

# Run development server
npm run dev
```

Visit `http://localhost:3000` to see the application.

## Project Structure

```
/
├── src/
│   ├── components/     # React UI components
│   ├── pages/          # Next.js pages
│   ├── utils/          # Utility functions
│   └── styles/         # Tailwind CSS
├── public/             # Static assets
├── tests/              # Test files
└── docs/               # Project documentation
```

## Development

### Available Scripts

```bash
npm run dev         # Start development server
npm run build       # Build for production
npm run test        # Run tests
npm run lint        # Lint code
```

### Environment Variables

Required environment variables:

```env
OPENAI_API_KEY=your_openai_api_key
CLOUDINARY_URL=your_cloudinary_url
DATABASE_URL=your_postgresql_connection_string
```

## Testing

```bash
# Run unit tests
npm run test

# Run with coverage
npm run test:coverage
```

## Deployment

### Vercel (Recommended)

```bash
npm run build
vercel --prod
```

## Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/spooky-meme-generator`)
3. Commit your changes (`git commit -m 'Add AI-powered meme templates'`)
4. Push to the branch (`git push origin feature/spooky-meme-generator`)
5. Open a Pull Request

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our development process.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Support

For support, email support@hallomemeai.com or open a GitHub issue.

---

**Generated with 🎃 by HalloMeme AI Team**