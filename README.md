# AskMedGraph - Healthcare Knowledge Graph Q&A

A React app for querying healthcare knowledge graphs with AI-powered language models.

## Features

- Interactive Knowledge Graph visualization (D3.js)
- AI-powered search with multiple LLM options
- Responsive design for desktop & mobile
- Collapsible sidebar & keyboard shortcuts
- Copy-to-clipboard & sample questions

## Tech Stack

React 18, Tailwind CSS, D3.js, Lucide React, ES6+

## Installation

Clone the repo and install dependencies:

```bash
git clone https://github.com/mohammadalsobbahidsra2025-ai/askmedgraph.git
cd askmedgraph
npm install
```

## Usage

1. Open the sidebar using the menu button or Ctrl+B
2. Select your preferences:
   - Data Source (Knowledge Graph/SQL Server)
   - Language Model (GPT-4o Mini/Claude/DeepSeek)
3. Enter your query or click a sample question
4. Press Search or use Ctrl+Enter
5. Explore results:
   - Read the AI-generated answer
   - Interact with the knowledge graph
   - View insights and entities

## Backend Integration

The app expects a Flask backend with this endpoint:

- `POST /api/search` - Main search functionality

## Running the App

**Development:**
```bash
npm start
```

**Production Build:**
```bash
npm run build
```

## Deployment

**Netlify/Vercel:**
1. Build the project: `npm run build`
2. Upload `build/` folder
3. Set environment variables in hosting dashboard

## Components

- `Sidebar.js` - Settings and preferences
- `SearchBox.js` - Query interface
- `AnswerBox.js` - Response formatting
- `KnowledgeGraph.js` - D3.js visualization

## Responsive Features

- Mobile-first design with touch-friendly interface
- Collapsible sidebar with overlay on mobile
- Adaptive layouts for different screen sizes
- Keyboard shortcuts for power users

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Authors

Mohammad Al Sobbahi - Lebanese University
