# 📄 SwiftSum - CloudPDF

<div align="center">
  <img src="https://raw.githubusercontent.com/AdityaAjithKumar/CloudPDF/9fed9f4bcebef95f11f3f9c1c086432034c07f44/ScreenShot/swiftsum-logo.svg" alt="SwiftSum Logo" width="400">
  
  **Unlock Knowledge Instantly** ✨
  
  Transform lengthy PDFs into concise, accurate summaries in seconds with AI-powered intelligence.

  ---
  # Built with 

  <img src="https://github.com/AdityaAjithKumar/CloudPDF/blob/master/ScreenShot/Google-gemini-icon.svg.png?raw=true" alt="SwiftSum Logo" width="200">
   <img src="https://raw.githubusercontent.com/AdityaAjithKumar/CloudPDF/refs/heads/master/ScreenShot/bhashini.webp?raw=true" alt="SwiftSum Logo" width="200">
   
   ---

  [![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://python.org)
  [![Flask](https://img.shields.io/badge/Flask-2.0+-green.svg)](https://flask.palletsprojects.com/)
  [![Gemini AI](https://img.shields.io/badge/Gemini-AI-orange.svg)](https://ai.google.dev/)
  [![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
  
  ---
  
  ## 🚀 Try SwiftSum Now!
  
  [![Try SwiftSum](https://img.shields.io/badge/🚀_Try_SwiftSum_Live-Visit_App-success?style=for-the-badge&logo=rocket)](https://cloudpdf.onrender.com/)
  
  **👆 Click the button above to experience SwiftSum in action!**
  
  ---
  
  [📖 **Documentation**](#features) • [🐛 **Report Bug**](../../issues) • [💡 **Request Feature**](../../issues)
</div>

## 📸 Screenshots

<!-- Add your screenshots here -->
<div align="center">
  <h3>🏠 Homepage</h3>
  <img src="https://github.com/AdityaAjithKumar/CloudPDF/blob/master/ScreenShot/homepage1.png?raw=true" alt="SwiftSum Homepage" width="800">
  <img src="https://github.com/AdityaAjithKumar/CloudPDF/blob/master/ScreenShot/homepage2.png?raw=true" alt="SwiftSum Homepage" width="800">
  
  <h3>📊 PDF Summarization</h3>
  <img src="https://github.com/AdityaAjithKumar/CloudPDF/blob/master/ScreenShot/upload.png?raw=true" alt="PDF Summarization Interface" width="800">
    <img src="https://github.com/AdityaAjithKumar/CloudPDF/blob/master/ScreenShot/summary.png?raw=true" alt="PDF Summarization Interface" width="800">
  
  <h3>🌐 Translation Feature</h3>
  <img src="https://github.com/AdityaAjithKumar/CloudPDF/blob/master/ScreenShot/query.png?raw=true" alt="Translation Feature" width="800">
  <img src="https://github.com/AdityaAjithKumar/CloudPDF/blob/master/ScreenShot/query_hi.png?raw=true" alt="Translation Feature" width="800">
  <img src="https://github.com/AdityaAjithKumar/CloudPDF/blob/master/ScreenShot/kn.png?raw=true" alt="Translation Feature" width="800">
</div>

---

## ✨ Features

### 🔥 **Core Features**
- **📄 Smart PDF Summarization** - Extract key insights from any PDF using Google Gemini AI
- **🌍 Multi-Language Translation** - Translate summaries to 23+ Indian languages
- **💬 Interactive Q&A** - Ask questions about your uploaded PDFs
- **⚡ Lightning Fast** - Get summaries in seconds, not hours
- **🔒 Secure Processing** - Your documents are processed securely

### 🎯 **Supported Languages**

<summary>supported languages</summary>

| Language | Code | Language | Code |
|----------|------|----------|------|
| English | en | Hindi | hi |
| Konkani | gom | Kannada | kn |
| Dogri | doi | Bodo | brx |
| Urdu | ur | Tamil | ta |
| Kashmiri | ks | Assamese | as |
| Bengali | bn | Marathi | mr |
| Sindhi | sd | Maithili | mai |
| Punjabi | pa | Malayalam | ml |
| Manipuri | mni | Telugu | te |
| Sanskrit | sa | Nepali | ne |
| Santali | sat | Gujarati | gu |
| Odia | or | | |

### 🎨 **User Experience**
- **🎪 Beautiful UI** - Modern, responsive design with animations
- **📱 Mobile Friendly** - Works seamlessly on all devices  
- **🎯 Intuitive Interface** - Simple drag-and-drop file upload
- **💾 Download Results** - Save summaries as text files

---

## 🚀 Quick Start

### 📋 Prerequisites

- Python 3.8 or higher
- Google Gemini API Key
- ULCA API credentials (for translation)

### ⚡ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/AdityaAjithKumar/CloudPDF.git
   cd CloudPDF
   ```

2. **Install dependencies**
   ```bash
   pip install flask python-dotenv google-generativeai requests
   ```

3. **Set up environment variables**
   ```bash
   # Create a .env file in the root directory
   echo "GEMINI_API_KEY=your_gemini_api_key_here" > .env
   echo "ULCA_USER_ID=your_ulca_user_id" >> .env
   echo "ULCA_API_KEY=your_ulca_api_key" >> .env
   echo "FLASK_SECRET_KEY=your_secret_key_here" >> .env
   ```

4. **Run the application**
   ```bash
   python app.py
   ```

5. **Open your browser**
   Navigate to `http://localhost:5000` and start summarizing! 🎉

---

## 🛠️ Environment Setup

### 🔑 API Keys Required

| Service | Purpose | How to Get |
|---------|---------|------------|
| **Google Gemini API** | PDF Summarization & Q&A | [Get API Key](https://ai.google.dev/) |
| **ULCA API** | Translation Services | [ULCA Portal](https://bhashini.gov.in/ulca) |

### 📁 Project Structure

```
CloudPDF/
├── 📄 app.py                 # Main Flask application
├── 📁 static/               # CSS, JS, and assets
│   ├── 🎨 home_style.css    # Homepage styles
│   ├── ⚡ home_script.js    # Frontend interactions
│   └── 📁 assets/           # Images and icons
├── 📁 templates/            # HTML templates
│   ├── 🏠 homepage.html     # Landing page
│   └── 📊 index.html        # Main application
├── 📁 uploads/              # Uploaded PDF files
├── 📁 output/               # Generated summaries
└── 📄 README.md             # This file
```

---

## 🎮 Usage

### 📤 Upload & Summarize

1. **Upload PDF** - Drag and drop or select your PDF file (max 50MB)
2. **AI Processing** - Our AI reads and analyzes your document
3. **Get Summary** - Receive a comprehensive summary instantly
4. **Download** - Save your summary as a text file

### 💬 Interactive Q&A

1. After uploading a PDF, use the Q&A feature
2. Ask specific questions about your document
3. Get accurate, context-aware answers

### 🌐 Translation

1. Generate a summary in English
2. Select your target language from 23+ options
3. Get instant translation powered by ULCA

---

## 🔧 API Endpoints

| Endpoint | Method | Description |
|----------|--------|-------------|
| `/` | GET | Homepage redirect |
| `/home` | GET | Landing page |
| `/index` | GET/POST | Main application interface |
| `/ask` | POST | Q&A with uploaded PDF |
| `/translate` | POST | Translate content |
| `/languages` | GET | Get supported languages |
| `/download/<filename>` | GET | Download summary file |

---

## 🤝 Contributing

We love contributions! Here's how you can help:

<div align="center">

[![Contribute](https://img.shields.io/badge/Contribute-Welcome-brightgreen.svg?style=for-the-badge)](../../pulls)

</div>

### 🎯 Ways to Contribute

- 🐛 **Report Bugs** - Found an issue? Let us know!
- 💡 **Suggest Features** - Have ideas? We'd love to hear them!
- 🔧 **Submit PRs** - Fix bugs or add features
- 📖 **Improve Docs** - Help make our documentation better

### 🚀 Development Setup

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Make your changes
4. Commit: `git commit -m 'Add amazing feature'`
5. Push: `git push origin feature/amazing-feature`
6. Open a Pull Request



## 🔒 Security & Privacy

- 🛡️ **Secure Processing** - Files processed securely via Google's infrastructure
- 🗑️ **Auto Cleanup** - Uploaded files can be automatically removed
- 🔐 **API Security** - Environment variables for sensitive data
- 📱 **HTTPS Ready** - Production deployment with SSL support

---

## 🚀 Deployment

### 🌐 Deploy to Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

### 🐳 Docker Deployment

```bash
# Build the image
docker build -t swiftsum .

# Run the container
docker run -p 5000:5000 --env-file .env swiftsum
```

### ☁️ Cloud Platform Support

- ✅ **Heroku** - One-click deployment
- ✅ **AWS** - EC2, Elastic Beanstalk
- ✅ **Google Cloud** - App Engine, Cloud Run
- ✅ **Azure** - App Service
- ✅ **Digital Ocean** - App Platform

---

## 📞 Support

<div align="center">

Need help? We're here for you! 💪

[![Issues](https://img.shields.io/badge/Issues-GitHub-red.svg?style=for-the-badge)](../../issues)
[![Discussions](https://img.shields.io/badge/Discussions-GitHub-blue.svg?style=for-the-badge)](../../discussions)

</div>

---



## 🎖️ Acknowledgments

- 🤖 **Google Gemini** - For powerful AI summarization
- 🌐 **ULCA/Bhashini** - For comprehensive language translation
- 🎨 **Font Awesome** - For beautiful icons
- 🎯 **Google Fonts** - For typography
- 💡 **Flask Community** - For the amazing web framework

---



<div align="center">

**Made with ❤️ by [Aditya Ajith Kumar](https://github.com/AdityaAjithKumar)**

⭐ **If you found this project helpful, please give it a star!** ⭐

[![GitHub stars](https://img.shields.io/github/stars/AdityaAjithKumar/CloudPDF.svg?style=social&label=Star)](../../stargazers)
[![GitHub forks](https://img.shields.io/github/forks/AdityaAjithKumar/CloudPDF.svg?style=social&label=Fork)](../../network/members)

---

**[⬆ Back to Top](#-swiftsum---cloudpdf)**

</div>
