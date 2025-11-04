# Personal AI Chat Bot

Hey there! This is a friendly AI chat bot I built to help people with their needs. It's like having a personal assistant that learns about you through a quick onboarding process and then provides tailored help.

## What does it do?

The bot starts by asking for some basic info like your name, email, and what you're looking for help with. Once it knows a bit about you, it can give more personalized responses. It remembers your chat history and can even pull in content from your website if you provide a URL.

## Key Features

- **Smart Onboarding**: Collects your details to provide better assistance
- **Personalized Responses**: Uses your info to tailor conversations
- **Chat History**: Saves your conversations locally
- **Website Integration**: Can reference your website content for more relevant help
- **Clean UI**: Built with modern React components and smooth animations

## Tech Stack

This project uses some cool modern web technologies:
- **Vite** - Fast build tool and dev server
- **TypeScript** - Type-safe JavaScript
- **React** - UI library with hooks
- **shadcn/ui** - Beautiful, accessible components
- **Tailwind CSS** - Utility-first styling
- **Groq API** - For the AI chat functionality

## Getting Started

### Prerequisites

You'll need Node.js and npm installed. If you don't have them, check out [nvm](https://github.com/nvm-sh/nvm#installing-and-updating) for an easy way to install Node.

### Installation

1. Clone this repo:
```sh
git clone <YOUR_GIT_URL>
```

2. Go into the project directory:
```sh
cd your-personal-pal-main
```

3. Install the dependencies:
```sh
npm install
```

4. Get a Groq API key from [groq.com](https://groq.com) and add it to the code (look in `src/hooks/useGroqChat.ts` for the API key constant)

5. Start the development server:
```sh
npm run dev
```

That's it! The app should open in your browser at `http://localhost:5173`.

## How to Use

1. When you first open the app, it'll ask for your Groq API key if you haven't set it up yet
2. The bot will guide you through a quick onboarding process to learn about you
3. Start chatting! The bot will remember your details and provide personalized help
4. Use the "Reset" button to start fresh or "Clear" to wipe your chat history

## Building for Production

When you're ready to deploy:

```sh
npm run build
```

This creates an optimized build in the `dist` folder that you can deploy to any static hosting service.

## Contributing

Feel free to open issues or submit pull requests if you have ideas for improvements!

## License

This project is open source - do whatever you want with it!
