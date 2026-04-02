# 🤖 AI Webpage Generator

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![Streamlit](https://img.shields.io/badge/Streamlit-1.0+-FF4B4B.svg)](https://streamlit.io/)
[![LangChain](https://img.shields.io/badge/LangChain-Latest-green.svg)](https://python.langchain.com/)
[![Google Gemini](https://img.shields.io/badge/Google-Gemini%202.5%20Flash-4285F4.svg)](https://ai.google.dev/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

> Transform your ideas into fully functional websites with the power of AI! This Streamlit application leverages Google's Gemini 2.5 Flash model through LangChain to generate production-ready HTML, CSS, and JavaScript files from simple text descriptions.

## ✨ Features

- 🎨 **AI-Powered Generation** - Utilizes Google Gemini 2.5 Flash for intelligent webpage creation
- 📝 **Natural Language Input** - Describe your webpage in plain English
- 🎯 **Complete Frontend Stack** - Generates HTML5, CSS3, and modern JavaScript (ES6+)
- 📦 **One-Click Download** - Get all files packaged in a convenient ZIP file
- 🚀 **Production-Ready Code** - Generated code follows industry best practices
- 💻 **User-Friendly Interface** - Clean, intuitive Streamlit UI

## 🎥 Demo

*Describe your webpage → AI generates code → Download and deploy!*

## 📋 Prerequisites

Before you begin, ensure you have the following installed:

- **Python 3.9 or higher** - [Download Python](https://www.python.org/downloads/)
- **Google Gemini API Key** - [Get your API key](https://makersuite.google.com/app/apikey)

## 🚀 Quick Start

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/AI-Webpage-Generator.git
cd AI-Webpage-Generator
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Set Up Environment Variables

Create a `.env` file in the project root directory:

```bash
touch .env
```

Add your Gemini API key to the `.env` file:

```env
gemini_key=YOUR_GEMINI_API_KEY_HERE
```

**⚠️ Important:** Never commit your `.env` file to version control. Make sure it's listed in your `.gitignore`.

### 4. Run the Application

```bash
streamlit run webpage_app.py
```

The app will open in your default web browser at `http://localhost:8501`

## 📖 How to Use

1. **Describe Your Webpage**  
   Enter a description of the type of webpage you want to create. Be specific about the style, layout, and features.
   
   *Example:* "A modern landing page for a tech startup with a hero section, features grid, and contact form"

2. **Provide Content**  
   Enter the actual content you want to appear on the webpage (text, headings, button labels, etc.)
   
   *Example:* 
   ```
   Company Name: TechVision AI
   Tagline: Innovating Tomorrow's Solutions Today
   Features: Fast Performance, Secure Infrastructure, 24/7 Support
   CTA: Get Started Free
   ```

3. **Generate**  
   Click the "Generate" button and wait a few seconds while the AI creates your webpage.

4. **Download**  
   Click the download button to get your `website.zip` file containing:
   - `index.html` - Your webpage structure
   - `style.css` - Styling and layout
   - `script.js` - Interactive functionality

5. **Deploy**  
   Extract the ZIP file and open `index.html` in your browser, or deploy to any web hosting service!

## 🏗️ Project Structure

```
AI-Webpage-Generator/
│
├── webpage_app.py          # Main Streamlit application
├── requirements.txt        # Python dependencies
├── README.md              # Project documentation
├── .env                   # Environment variables (create this)
└── .gitignore            # Git ignore file (recommended)
```

## 🛠️ Technical Details

### Dependencies

- **streamlit** - Web application framework
- **python-dotenv** - Environment variable management
- **langchain** - LLM application framework
- **langchain-core** - Core LangChain functionality
- **langchain-google-genai** - Google Gemini integration

### AI Model

This project uses **Google Gemini 2.5 Flash**, a fast and efficient large language model optimized for:
- Quick response times
- High-quality code generation
- Understanding natural language descriptions
- Producing structured output

## 💡 Usage Examples

### Example 1: Portfolio Website

**Description:**
```
A minimalist portfolio website with a dark theme, showcasing projects in a grid layout
```

**Content:**
```
Name: John Doe
Title: Full Stack Developer
Projects: E-commerce Platform, Weather App, Task Manager
Contact: john@example.com
```

### Example 2: Restaurant Landing Page

**Description:**
```
An elegant restaurant landing page with a warm color scheme, menu section, and reservation form
```

**Content:**
```
Restaurant: La Bella Cucina
Tagline: Authentic Italian Cuisine
Menu Items: Pasta Carbonara, Margherita Pizza, Tiramisu
Hours: Mon-Sat 5PM-10PM
```

### Example 3: Product Showcase

**Description:**
```
A modern product showcase page with image carousel, feature highlights, and pricing table
```

**Content:**
```
Product: SmartWatch Pro
Features: Heart Rate Monitor, GPS Tracking, 7-Day Battery
Price: $299
```

## 🔧 Troubleshooting

### Common Issues

**Issue:** `ModuleNotFoundError: No module named 'streamlit'`  
**Solution:** Make sure you've installed all dependencies: `pip install -r requirements.txt`

**Issue:** `API key not found`  
**Solution:** Verify your `.env` file exists and contains `gemini_key=YOUR_ACTUAL_API_KEY`

**Issue:** Generated files are empty  
**Solution:** Check your internet connection and ensure your Gemini API key is valid and has available quota

**Issue:** App doesn't open in browser  
**Solution:** Manually navigate to `http://localhost:8501` or check if port 8501 is already in use

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Ideas for Contribution

- Add support for additional AI models (Claude, GPT-4, etc.)
- Implement webpage previews before download
- Add template selection (blog, e-commerce, portfolio, etc.)
- Include responsive design testing
- Add code syntax highlighting in the UI
- Implement version history for generated webpages

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Google Gemini](https://ai.google.dev/) - For powering the AI generation
- [Streamlit](https://streamlit.io/) - For the amazing web framework
- [LangChain](https://python.langchain.com/) - For LLM orchestration

## 📞 Contact & Support

- **Issues:** [GitHub Issues](https://github.com/yourusername/AI-Webpage-Generator/issues)
- **Discussions:** [GitHub Discussions](https://github.com/yourusername/AI-Webpage-Generator/discussions)

## 🌟 Star This Repository

If you find this project useful, please consider giving it a star ⭐ to show your support!

---

**Made with ❤️ and AI**
