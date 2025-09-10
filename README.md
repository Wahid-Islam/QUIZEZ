# 📚 Slide→Quiz Generator

A modern, AI-powered quiz generator that converts PDF slides into interactive multiple-choice quizzes with an integrated AI tutor.

![Quiz Generator Preview](https://img.shields.io/badge/Status-Active-brightgreen) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) ![PDF.js](https://img.shields.io/badge/PDF.js-FF6B35?style=flat&logo=adobe&logoColor=white)

## ✨ Features

### 🎯 **Core Functionality**
- **PDF Upload**: Extract text from multiple PDF files simultaneously
- **AI-Powered Questions**: Generate high-quality MCQs using Google's Gemini AI
- **Smart Fallback**: Intelligent question generation even without API key
- **Multiple Quiz Sets**: Create 1-10 different quiz sets with 5-60 questions each
- **Random Sets**: Get a different quiz experience each time

### 🤖 **AI Tutor Integration**
- **Interactive Chat**: Get hints and explanations from Gemini AI
- **Context-Aware**: Tutor is grounded on your uploaded slide content
- **No Spoilers**: AI provides helpful guidance without revealing quiz answers
- **Session Storage**: API key persists through browser session for convenience

### 🎨 **Modern UI/UX**
- **Beautiful Design**: Clean, professional interface with subtle animations
- **Alternating Card Colors**: Light lavender-gray and peach-beige theme
- **Responsive Layout**: Works perfectly on desktop, tablet, and mobile
- **Accessibility**: Full keyboard navigation and screen reader support
- **Dark/Light Contrast**: Optimized for readability and eye comfort

### 📊 **Advanced Features**
- **Detailed Feedback**: See full questions, your answers, correct answers, and explanations
- **Progress Tracking**: Real-time timer and comprehensive scoring
- **Expandable Results**: Collapsible feedback section for better navigation
- **Session Persistence**: API key automatically saved for browser session

## 🚀 Getting Started

### Quick Start
1. **Open the HTML file** in any modern web browser
2. **Upload PDF slides** using the file picker
3. **Configure settings** (number of sets, questions per set)
4. **Add Gemini API key** for AI-powered questions (optional but recommended)
5. **Generate quizzes** and start learning!

### Getting a Gemini API Key
1. Visit [Google AI Studio](https://aistudio.google.com/apikey)
2. Sign in with your Google account
3. Click "Create API key"
4. Select "Create project" or use existing project
5. Copy your API key and paste it into the application

## 🛠️ Technical Details

### Technologies Used
- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **PDF Processing**: PDF.js library for client-side text extraction
- **AI Integration**: Google Gemini 2.0 Flash API
- **Typography**: Inter font family for modern aesthetics
- **Storage**: Session Storage for secure API key management

### Browser Compatibility
- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+

### File Structure
```
📁 Slide→Quiz Generator/
├── 📄 Slide→Quiz Generator (PDF).html    # Main application file
└── 📄 README.md                          # This documentation
```

## 🎛️ Configuration Options

### Quiz Settings
- **Number of Sets**: 1-10 different quiz variations
- **Questions per Set**: 5-60 questions each
- **Random Seed**: Optional seed for reproducible randomness
- **AI Generation**: Toggle between AI and fallback question generation

### Smart Question Generation
- **With API Key**: Uses Gemini AI for context-aware, high-quality questions
- **Without API Key**: Falls back to intelligent heuristic generation
- **Image-Heavy PDFs**: Automatically detects and provides generic academic questions

## 📖 Usage Guide

### Basic Workflow
1. **Upload**: Select one or more PDF files containing your slides
2. **Configure**: Set your preferred number of quiz sets and questions
3. **Generate**: Click "Generate quizzes" to create your assessments
4. **Study**: Take quizzes and use the AI tutor for additional help
5. **Review**: Analyze detailed feedback to improve understanding

### AI Tutor Tips
- Ask for **conceptual explanations** rather than direct answers
- Request **examples** and **analogies** for complex topics
- Use it for **clarification** on slide content
- Get **study tips** and **memory aids**

### Best Practices
- Upload PDFs with substantial text content for best results
- Use descriptive filenames for easier organization
- Take advantage of multiple quiz sets for varied practice
- Leverage the AI tutor for deeper understanding

## 🔒 Privacy & Security

### Data Handling
- **Local Processing**: All PDF text extraction happens in your browser
- **No File Upload**: PDFs never leave your device
- **Session-Only Storage**: API keys stored locally and cleared when browser closes
- **No Data Collection**: No personal information is collected or transmitted

### API Key Security
- **Session Storage**: Keys automatically deleted when browser is closed
- **Local Only**: API keys never sent to any server except Google's official API
- **Clear Function**: Manual clear button for immediate key removal
- **Visual Status**: Real-time indication of key storage status

## 🎨 Design System

### Color Palette
- **Light Lavender-Gray**: `#e0dce7` (Card backgrounds - odd)
- **Light Peach-Beige**: `#f0e3db` (Card backgrounds - even)
- **Brand Blue**: `#3b82f6` (Primary actions and accents)
- **Success Green**: `#059669` (Correct answers and confirmations)
- **Error Red**: `#dc2626` (Incorrect answers and warnings)

### Typography
- **Primary Font**: Inter (Modern, clean, highly readable)
- **Fallback**: System fonts for maximum compatibility
- **Responsive Sizing**: Scales appropriately across all devices

## 🤝 Contributing

This project welcomes contributions! Here are some ways you can help:

### Potential Improvements
- **Additional AI Providers**: Support for other AI services
- **Question Types**: True/false, fill-in-the-blank, essay questions
- **Export Features**: PDF reports, study guides
- **Themes**: Dark mode, color customization
- **Analytics**: Learning progress tracking

### Development Guidelines
- Follow existing code style and structure
- Test across multiple browsers and devices
- Ensure accessibility compliance
- Maintain responsive design principles

## 📄 License

© 2025 MD Wahid Islam Arefin. All rights reserved.

This project is created for educational purposes. PDF.js library is used under Apache License 2.0.

## 🙏 Acknowledgments

- **PDF.js Team** - For the excellent PDF processing library
- **Google AI** - For the powerful Gemini API
- **Inter Font** - For the beautiful typography
- **Checklist Design** - For design inspiration and best practices

---

**Made with ❤️ for better learning experiences**

*Transform your slides into interactive learning adventures!*
