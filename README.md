# ConvoManage 🎥

A modern, full-stack video conferencing and meeting management platform built with Next.js, featuring real-time video calls, meeting scheduling, and comprehensive call management.

## ✨ Features

- **🔐 Authentication**: Secure user authentication powered by Clerk
- **📹 Video Conferencing**: High-quality video calls using Stream.io
- **📅 Meeting Management**: Schedule, join, and manage meetings effortlessly
- **📱 Responsive Design**: Modern UI that works on all devices
- **🎨 Beautiful UI**: Built with Tailwind CSS and Radix UI components
- **📊 Call History**: Track and review previous meetings and recordings
- **🚀 Real-time**: Live updates and notifications for meeting events

## 🛠️ Tech Stack

- **Frontend**: Next.js 14, React 18, TypeScript
- **Styling**: Tailwind CSS, Radix UI
- **Authentication**: Clerk
- **Video**: Stream.io Video SDK
- **State Management**: React Hooks
- **Development**: ESLint, PostCSS

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ 
- npm, yarn, pnpm, or bun

### Installation

1. **Clone the repository**
   ```bash
   git clone git@github.com:vmcse/convomanage.git
   cd convomanage
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   # or
   bun install
   ```

3. **Set up environment variables**
   
   Create a `.env.local` file in the root directory:
   ```env
   # Clerk Authentication
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
   CLERK_SECRET_KEY=your_clerk_secret_key
   
   # Stream.io Video
   NEXT_PUBLIC_STREAM_API_KEY=your_stream_api_key
   STREAM_API_SECRET=your_stream_api_secret
   ```

4. **Run the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   # or
   bun dev
   ```

5. **Open your browser**
   
   Navigate to [http://localhost:3000](http://localhost:3000) to see your application.

## 📁 Project Structure

```
convomanage/
├── actions/              # Server actions
├── app/                  # Next.js app directory
│   ├── (auth)/          # Authentication routes
│   ├── (root)/          # Main application routes
│   └── meeting/         # Meeting management
├── components/           # Reusable UI components
│   └── ui/              # Base UI components
├── constants/            # Application constants
├── hooks/                # Custom React hooks
├── lib/                  # Utility functions
├── providers/            # Context providers
└── public/               # Static assets
```

## 🎯 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## 🔧 Configuration

### Next.js
The project uses Next.js 14 with the app directory structure for modern React development.

### Tailwind CSS
Custom styling is configured with Tailwind CSS and includes custom animations and components.

### TypeScript
Full TypeScript support for better development experience and type safety.


## 🙏 Acknowledgments

- [Next.js](https://nextjs.org/) - The React framework
- [Clerk](https://clerk.com/) - Authentication
- [Stream.io](https://stream.io/) - Video SDK
- [Tailwind CSS](https://tailwindcss.com/) - CSS framework
- [Shadcn UI](https://ui.shadcn.com/) - UI Components


