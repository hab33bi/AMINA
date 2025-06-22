# AMINA 🤖

**Artificial Machine Intelligence Neural Architecture**

A beautiful, modern AI chat application built with React and TypeScript that connects to LM Studio for intelligent conversations with advanced features like streaming responses, conversation management, and multimodal support.

![AMINA Screenshot](https://img.shields.io/badge/React-18+-blue?logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5+-blue?logo=typescript)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-3+-blue?logo=tailwindcss)
![LM Studio](https://img.shields.io/badge/LM%20Studio-Compatible-green)

## ✨ Features

### 🎨 **Beautiful UI/UX**
- **Dark Mode Default**: Professional dark theme with light mode toggle
- **Gradient Branding**: Beautiful AMINA logo with animated loading screen
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile
- **Smooth Animations**: Professional transitions and micro-interactions

### 💬 **Advanced Chat Experience**
- **Streaming Responses**: Real-time text streaming with live markdown rendering
- **Conversation Management**: Collapsible sidebar with persistent chat history
- **Multimodal Support**: Text + image input capabilities
- **Auto-scrolling**: Smart chat window that follows the conversation

### 🤖 **AI Integration**
- **LM Studio Connection**: Seamless integration with LM Studio
- **Gemma 3 12b Support**: Optimized for Google's Gemma 3 12b model
- **OpenAI-Compatible API**: Standard chat completions format
- **Error Handling**: Graceful error management and user feedback

### 💾 **Data Persistence**
- **Local Storage**: Conversations and preferences saved locally
- **Session Management**: Automatic conversation creation and switching
- **Settings Persistence**: Theme preferences and chat history

## 🚀 Quick Start

### Prerequisites

- **Node.js** 16+ and npm
- **LM Studio** with Gemma 3 12b model loaded
- **Modern web browser** with ES6+ support

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/hab33bi/AMINA.git
   cd AMINA
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the development server:**
   ```bash
   npm start
   ```

4. **Open your browser:**
   Visit `http://localhost:3000`

## ⚙️ Configuration

### LM Studio Setup

1. **Install LM Studio** from [lmstudio.ai](https://lmstudio.ai)

2. **Download Gemma 3 12b model** or your preferred model

3. **Start the local server:**
   - In LM Studio, go to the "Local Server" tab
   - Load your Gemma 3 12b model
   - Start the server (default: `http://localhost:1234`)

4. **Update API endpoint** (if needed):
   ```typescript
   // In src/App.tsx, line ~150
   const response = await fetch(
     "http://192.168.1.174:1234/v1/chat/completions", // Update this URL
     // ...
   );
   ```

### Environment Variables

Create a `.env` file in the root directory:

```env
REACT_APP_LM_STUDIO_URL=http://192.168.1.174:1234/v1
REACT_APP_MODEL_NAME=gemma-3-12b
```

## 🎮 Usage

### Starting a Conversation
1. **Launch AMINA** - Enjoy the loading animation
2. **Type your message** in the input field
3. **Upload images** (optional) using the camera icon
4. **Send your message** and watch the streaming response

### Managing Conversations
- **New Chat**: Click the hamburger menu → "New Chat"
- **Switch Chats**: Click any conversation in the sidebar
- **Delete Chats**: Hover over a conversation and click the trash icon

### Customization
- **Toggle Dark/Light Mode**: Click the sun/moon icon in the header
- **Responsive Sidebar**: Auto-collapses on mobile devices

## 🛠️ Technologies Used

- **Frontend Framework**: React 18+ with TypeScript
- **Styling**: Tailwind CSS 3+ with custom animations
- **Markdown Rendering**: react-markdown
- **Build Tool**: Create React App
- **AI Integration**: LM Studio with OpenAI-compatible API
- **Storage**: Browser localStorage for persistence

## 📁 Project Structure

```
AMINA/
├── public/                 # Static assets
├── src/
│   ├── App.tsx            # Main application component
│   ├── index.css          # Global styles and Tailwind
│   ├── index.tsx          # Application entry point
│   └── ...
├── package.json           # Dependencies and scripts
├── tailwind.config.js     # Tailwind configuration
├── postcss.config.js      # PostCSS configuration
└── README.md             # This file
```

## 🔧 Development

### Available Scripts

- `npm start` - Start development server
- `npm build` - Build for production
- `npm test` - Run test suite
- `npm run eject` - Eject from Create React App

### Code Style

- **TypeScript**: Strict type checking enabled
- **ESLint**: Configured with React rules
- **Prettier**: Code formatting (recommended)

## 📱 Browser Support

- **Chrome**: 90+
- **Firefox**: 88+
- **Safari**: 14+
- **Edge**: 90+

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **LM Studio** for the excellent local AI server
- **Google** for the Gemma model family
- **Tailwind CSS** for the beautiful styling system
- **React** and **TypeScript** communities

## 📞 Support

If you encounter any issues or have questions:

1. Check the [Issues](https://github.com/hab33bi/AMINA/issues) page
2. Create a new issue with detailed information
3. Join the discussions in the repository

---

**Made with ❤️ by [hab33bi](https://github.com/hab33bi)**

*AMINA - Your Intelligent Conversation Partner*