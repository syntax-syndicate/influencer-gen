# FantazyPro - AI Influencer Generator

![FantazyPro](https://img.shields.io/badge/Next.js-15-black?style=flat&logo=next.js)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?style=flat&logo=typescript)
![License](https://img.shields.io/badge/license-MIT-green)

> Create stunning AI-generated virtual influencers with cutting-edge diffusion technology

[Live Demo](https://influencer-gen.vercel.app) | [Documentation](#getting-started) | [Community](https://t.me/FantazyPro)

## 🌟 Overview

FantazyPro is an AI-powered platform that enables creators to generate high-quality virtual influencer characters. Build your fanbase and monetize your AI-generated personas with our intuitive character creation tools.

### ✨ Key Features

- 🎨 **Advanced Character Builder** - Create unique virtual influencers with customizable traits and attributes
- 🖼️ **High-Quality Image Generation** - Powered by state-of-the-art diffusion models for stunning visuals
- 📋 **Pre-built Templates** - Quick-start with professional templates (Fashion Model, Fitness Coach, Tech Reviewer, Chef, DJ, and more)
- 🎭 **Dynamic Poses** - Generate engaging poses that bring your characters to life
- 💰 **Monetization Ready** - Tools designed to help you build and grow your virtual influencer business
- 🔒 **Secure Authentication** - Firebase-powered user management
- 📱 **Responsive Design** - Seamless experience across all devices

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ or Bun
- npm, yarn, pnpm, or bun package manager
- Firebase account (for authentication and database)

### Installation

1. Clone the repository
```bash
git clone https://github.com/gehirudm/influencer-gen.git
cd influencer-gen
```

2. Install dependencies
```bash
npm install
# or
yarn install
# or
pnpm install
# or
bun install
```

3. Set up environment variables

Create a `.env.local` file in the root directory:

```env
NEXT_PUBLIC_FIREBASE_API_KEY=your_api_key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_auth_domain
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_storage_bucket
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
NEXT_PUBLIC_FIREBASE_APP_ID=your_app_id
```

4. Run the development server
```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser

## 🏗️ Project Structure

```
influencer-gen/
├── app/                    # Next.js app directory
├── components/             # React components
├── contexts/               # React context providers
├── hooks/                  # Custom React hooks
├── lib/                    # Utility functions and configurations
├── public/                 # Static assets
├── theme/                  # Theme configuration
├── types/                  # TypeScript type definitions
├── workflows/              # Workflow configurations
└── firestore-structure.md  # Database schema documentation
```

## 🛠️ Tech Stack

- **Framework**: [Next.js 15](https://nextjs.org/)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Styling**: CSS Modules / Tailwind CSS
- **Authentication**: [Firebase Auth](https://firebase.google.com/docs/auth)
- **Database**: [Cloud Firestore](https://firebase.google.com/docs/firestore)
- **Storage**: [Firebase Storage](https://firebase.google.com/docs/storage)
- **Deployment**: [Vercel](https://vercel.com)
- **Font Optimization**: [next/font](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) with Geist

## 📖 Usage

### Creating Your First Character

1. **Sign Up / Login** - Create an account or sign in to get started
2. **Choose a Template** - Select from pre-built character templates or start from scratch
3. **Customize Traits** - Adjust appearance, style, and personality traits
4. **Generate Images** - Create high-quality images with various poses
5. **Share & Monetize** - Build your audience and start earning

### Character Templates

- 👗 Fashion Model
- 💪 Fitness Model
- 🧘 Wellness Coach
- ✈️ Travel Blogger
- 💻 Tech Reviewer
- 👨‍🍳 Chef
- 🎧 Musician/DJ
- 🔞 NSFW Model (age-restricted)

## 🌐 Deployment

### Deploy on Vercel

The easiest way to deploy your FantazyPro instance is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme):

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/gehirudm/influencer-gen)

Check out the [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.

## 📚 Documentation

- [Firestore Structure](./firestore-structure.md) - Database schema and structure
- [AI Configuration](./ai.md) - AI model settings and configurations
- [CORS Setup](./cors.json) - CORS configuration for Firebase Storage

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Community

- 📱 [Telegram Community](https://t.me/FantazyPro)
- 💬 [Discord Server](https://discord.gg/yRSTYdzyzb)
- 📧 [Email Support](mailto:hello@fantazy.pro)

## 🙏 Acknowledgments

- Built with [Next.js](https://nextjs.org/) by Vercel
- Powered by [Firebase](https://firebase.google.com/)
- Fonts by [Geist](https://vercel.com/font)

## 📊 Stats

- 500k+ Creations per Month
- Growing community of creators
- Continuous updates and improvements

---

**Made with ❤️ by [Gehiru Damnidu](https://github.com/gehirudm) and [Nimsith Senevirathne](https://github.com/Nimsith79)**

Copyright © FantazyPro AI 2025 | All rights reserved
