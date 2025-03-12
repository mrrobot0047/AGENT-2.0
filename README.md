# AGENT 2.0 - AI-Powered Genomic Analysis Platform

![License](https://img.shields.io/badge/license-Apache-blue.svg)
![Next.js](https://img.shields.io/badge/Next.js-14.0.0-black)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0.0-blue)
![AI SDK](https://img.shields.io/badge/AI_SDK-2.2.31-purple)

AGENT 2.0 is an advanced AI-powered platform designed specifically for genomic data analysis and oncology research. It provides researchers and healthcare professionals with a sophisticated interface to analyze genomic data, interpret results, and access relevant oncology information.

## ✨ Features

- **AI-Powered Analysis**: Utilizes GPT-4o for advanced genomic data interpretation
- **File Analysis**: Upload and analyze genomic files (CSV, FASTA, TXT, PDF)
- **Voice Input**: Speak queries directly using the built-in voice recognition
- **Dark/Light Mode**: Toggle between themes for comfortable viewing
- **Real-time AI Status**: Visual indicators of AI processing state
- **Enhanced Markdown Rendering**: Beautifully formatted responses with tables and code blocks
- **AI-Powered Quick Replies**: Context-aware suggested follow-up questions
- **HIPAA Compliance**: Built-in sanitization for sensitive health information
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **FHIR Integration**: Connect with EPIC and other healthcare systems
- **OAuth 2.0 Authentication**: Secure user authentication and authorization
- **Audit Trails**: Comprehensive logging for compliance requirements

## 🚀 Technologies

- **Frontend**: Next.js 14, React 18, TypeScript
- **Styling**: Tailwind CSS, Framer Motion for animations
- **AI Integration**: Vercel AI SDK, OpenAI API
- **Storage**: Supabase for secure file storage
- **State Management**: Zustand
- **Security**: JWT-based authentication, HIPAA compliance tools
- **Healthcare Standards**: FHIR API integration for EPIC systems

## 📋 Prerequisites

- Node.js 18.x or higher
- npm or yarn
- OpenAI API key
- Supabase account
- FHIR API credentials (for healthcare system integration)


## 🔧 Installation

1. Clone the repository:
      git clone https://github.com/mrrobot0047/AGENT-2.0.git
   cd agent-2-chat
Thought for 2 seconds```markdown project="AGENT 2.0" file="README.md"
...

2. Install dependencies:

npm install
# or
yarn


3. Set up environment variables:
Create a .env.local file in the root directory with the following variables:

NEXT_PUBLIC_AI_API_KEY=your_openai_api_key
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key


4. Run the development server:

npm run dev
# or
yarn dev


5. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.


## 💻 Usage

### Chat Interface

The main chat interface allows you to:

- Type questions about genomic data and oncology research
- Use voice input by clicking the microphone button
- Upload genomic files for analysis
- Toggle between light and dark themes
- View AI-suggested follow-up questions


### File Analysis

AGENT 2.0 supports analysis of various genomic file formats:

- CSV: Gene expression data, mutation tables, etc.
- FASTA: DNA/RNA sequence files
- TXT: Clinical reports, sequence data
- PDF: Research papers, pathology reports


Upload a file by clicking the "Upload genomic file" button or by dragging and dropping files into the designated area.

### Voice Input

To use voice input:

1. Click the microphone icon in the chat input
2. Speak your query clearly
3. Click the icon again to stop recording and send your query


## 📁 Project Structure

agent-2-chat/
├── app/                  # Next.js App Router
│   ├── api/              # API routes
│   │   └── chat/         # Chat API endpoint
│   ├── chat/             # Chat page
│   ├── globals.css       # Global styles
│   ├── layout.tsx        # Root layout
│   └── page.tsx          # Root page (redirects to /chat)
├── components/           # React components
│   ├── ChatBox.tsx       # Main chat interface
│   ├── ChatHeader.tsx    # Chat header with status
│   ├── FileUpload.tsx    # File upload component
│   ├── InputField.tsx    # Chat input field
│   ├── Loader.tsx        # Loading indicator
│   ├── MessageBubble.tsx # Chat message component
│   ├── QuickReply.tsx    # AI suggestion buttons
│   ├── ThemeToggle.tsx   # Theme switcher
│   ├── VoiceInput.tsx    # Voice input component
│   └── theme-provider.tsx # Theme provider
├── store/                # State management
│   └── chat-store.ts     # Zustand store
├── utils/                # Utility functions
│   ├── chatbotApi.ts     # Chat API utilities
│   └── fileUploadApi.ts  # File processing utilities
├── public/               # Static assets
├── .env.local            # Environment variables (not in repo)
├── next.config.js        # Next.js configuration
├── package.json          # Dependencies
├── tailwind.config.js    # Tailwind configuration
└── tsconfig.json         # TypeScript configuration

## 🔒 Security Considerations

AGENT 2.0 includes several security features:

- Sanitization of potentially sensitive health information
- Secure handling of API keys via environment variables
- Optional Supabase integration for secure file storage
- Client-side validation of file types and sizes


## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (git checkout -b feature/amazing-feature)
3. Commit your changes (git commit -m 'Add some amazing feature')
4. Push to the branch (git push origin feature/amazing-feature)
5. Open a Pull Request


## 📄 License

This project is licensed under the  Apache License - see the LICENSE file for details.

## 🙏 Acknowledgements

- [OpenAI](https://openai.com/) for the GPT-4o model
- [Supabase](https://supabase.com/) for storage solutions
- [Tabler Icons](https://tabler-icons.io/) for the beautiful icons
- [shadcn/ui](https://ui.shadcn.com/) for UI components


---

Built with ❤️ for advancing genomic research and oncology
