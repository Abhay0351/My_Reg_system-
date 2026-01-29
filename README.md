# DocuMind - Retrieval-Augmented Generation Chat Application

A production-grade Chat-with-your-Data application built with React, TypeScript, and Tailwind CSS. DocuMind enables seamless interaction with PDF and text documents using advanced RAG (Retrieval-Augmented Generation) techniques.

## Features

- 📄 **Multi-Document Support**: Upload and process PDF and text files
- 🔍 **Vector Search**: Semantic similarity search with custom embeddings
- 💬 **Conversational AI**: Memory-aware responses with source citations
- 🎨 **Modern UI**: Dark-mode optimized interface with Tailwind CSS
- ⚡ **Type-Safe**: Full TypeScript implementation
- 🔧 **Configurable**: Adjustable model settings and processing parameters

## Project Structure

```
retrieval-augmented-generation/
├── public/                 # Static assets
├── src/
│   ├── assets/            # Images, icons, and media
│   ├── components/        # Reusable React components
│   │   ├── ChatArea.tsx
│   │   ├── ChatInput.tsx
│   │   ├── ChatMessage.tsx
│   │   ├── EmptyState.tsx
│   │   └── Sidebar.tsx
│   ├── config/            # Configuration files
│   ├── context/           # React Context providers
│   ├── hooks/             # Custom React hooks
│   │   └── useDocuMind.ts
│   ├── pages/             # Page components
│   ├── services/          # Business logic and API calls
│   ├── styles/            # Global and component styles
│   ├── types/             # TypeScript type definitions
│   │   └── index.ts
│   ├── utils/             # Utility functions
│   │   ├── cn.ts
│   │   └── ragPipeline.ts
│   ├── App.tsx
│   ├── index.css
│   └── main.tsx
├── tests/                 # Test files
├── scripts/               # Build and automation scripts
├── docs/                  # Documentation
├── .env.example           # Environment variables template
├── index.html
├── package.json
├── requirements.txt       # Python dependencies
├── tsconfig.json
├── vite.config.ts
└── README.md
```

## Getting Started

### Prerequisites

- Node.js 18+
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone <repository-url>
cd retrieval-augmented-generation
```

2. Install dependencies
```bash
npm install
```

3. Create environment file
```bash
cp .env.example .env.local
```

4. Configure your API keys in `.env.local`

### Development

Start the development server:
```bash
npm run dev
```

The application will be available at `http://localhost:5173`

### Build

Build for production:
```bash
npm run build
```

Preview production build:
```bash
npm run preview
```

## Technology Stack

### Frontend
- **React 19** - UI library
- **TypeScript** - Type safety
- **Tailwind CSS** - Styling
- **Vite** - Build tool
- **Lucide React** - Icons

### Backend Logic (Client-side)
- **RAG Pipeline** - Custom implementation
- **Vector Storage** - In-memory vector store
- **Text Processing** - Document chunking and parsing

## Configuration

Edit `src/config/` to customize:
- API providers and credentials
- Model parameters
- RAG pipeline settings
- UI themes

## Environment Variables

See `.env.example` for available configuration options.

## Documentation

Detailed documentation is available in the `docs/` directory:
- Architecture overview
- API reference
- Component documentation
- RAG pipeline guide

## Testing

Run tests with:
```bash
npm test
```

## Contributing

1. Create a feature branch
2. Make your changes
3. Submit a pull request

## License

[Your License Here]

## Author

Built with ❤️ for RAG enthusiasts
