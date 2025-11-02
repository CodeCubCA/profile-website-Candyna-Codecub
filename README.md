# 🎵 AI Chat Assistant - Music Adviser

> An intelligent AI-powered chatbot designed to provide personalized music recommendations and engage in meaningful conversations about music, artists, and genres.

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://ai-chatbox-Candyna-codecub.streamlit.app)
[![Python](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![Groq API](https://img.shields.io/badge/Groq-API-purple.svg)](https://groq.com/)

---

## 🎯 About

**Music Adviser** is an intelligent AI chatbot built with cutting-edge technology to help music enthusiasts discover new songs, artists, and genres. Powered by the Groq API (Llama 3.3 70B model), this chatbot offers real-time, context-aware conversations that feel natural and engaging.

Whether you're looking for song recommendations based on your mood, want to learn about music history, or need help discovering new artists, Music Adviser is here to help! The chatbot leverages advanced natural language processing to understand your preferences and provide personalized suggestions.

Perfect for students, music lovers, and anyone seeking intelligent assistance with their musical journey!

---

## ✨ Features

- 🤖 **AI-Powered Conversations** - Utilizes Groq's Llama 3.3 70B model for intelligent, human-like responses
- 🎵 **Music Recommendations** - Get personalized song and artist suggestions based on your preferences
- 💬 **Real-Time Chat** - Instant responses with smooth, interactive conversation flow
- 🧠 **Context Awareness** - Remembers conversation history for coherent, contextual responses
- 🎨 **Beautiful UI** - Clean, modern interface built with Streamlit
- ☁️ **Cloud Deployment** - Accessible anywhere via Streamlit Cloud
- 🔒 **Secure API Integration** - Environment variable management for API key security
- 📱 **Responsive Design** - Works seamlessly on desktop and mobile devices

---

## 🛠️ Technologies Used

### Core Technologies
- **Python 3.9+** - Programming language
- **Streamlit** - Web application framework
- **Groq API** - AI model provider (Llama 3.3 70B Versatile)

### Libraries & Dependencies
- `streamlit` - Interactive web interface
- `groq` - Groq API client
- `python-dotenv` - Environment variable management
- `requests` - HTTP library for API calls

### Deployment
- **Streamlit Cloud** - Cloud hosting platform
- **Git/GitHub** - Version control and CI/CD

---

## 🚀 How to Run Locally

### Prerequisites
- Python 3.9 or higher installed
- Git installed
- A Groq API key ([Get one here](https://console.groq.com/))

### Step 1: Clone the Repository
```bash
git clone https://github.com/candyna/ai-chatbox.git
cd ai-chatbox
```

### Step 2: Install Dependencies
```bash
pip install -r requirements.txt
```

If you don't have a `requirements.txt`, create one with:
```txt
streamlit
groq
python-dotenv
```

Then run:
```bash
pip install -r requirements.txt
```

### Step 3: Configure Environment Variables
Create a `.env` file in the project root:
```bash
touch .env
```

Add your Groq API key:
```env
GROQ_API_KEY=your_groq_api_key_here
```

**Important:** Never commit your `.env` file to GitHub! Make sure `.env` is in your `.gitignore`.

### Step 4: Run the Application
```bash
streamlit run app.py
```

The app will open in your browser at `http://localhost:8501`

---

## ☁️ Deployment to Streamlit Cloud

### Step 1: Push to GitHub
Make sure your code is pushed to a GitHub repository.

### Step 2: Deploy on Streamlit Cloud
1. Go to [Streamlit Cloud](https://streamlit.io/cloud)
2. Click "New app"
3. Connect your GitHub repository
4. Select your repository and main file (e.g., `app.py`)
5. Click "Deploy"

### Step 3: Add Secrets
In Streamlit Cloud dashboard:
1. Go to your app settings
2. Click "Secrets"
3. Add your API key:
```toml
GROQ_API_KEY = "your_groq_api_key_here"
```

Your app will be live at: `https://ai-chatbox-[your-name]-codecub.streamlit.app`

---

## 🌐 Live Demo

Try the live version here:
**[Music Adviser - Live Demo](https://ai-chatbox-Candyna-codecub.streamlit.app)**

Experience the AI chatbot in action and get personalized music recommendations!

---

## 📸 Screenshots

> **Note:** Add screenshots of your application here to showcase the user interface and features.

### Main Chat Interface
![Chat Interface](screenshots/chat-interface.png)

### Music Recommendations
![Recommendations](screenshots/recommendations.png)

---

## 🔑 API Key Setup

### How to Get a Groq API Key

1. **Visit Groq Console**
   Go to [https://console.groq.com/](https://console.groq.com/)

2. **Sign Up / Log In**
   Create a free account or log in with your existing credentials

3. **Navigate to API Keys**
   Click on "API Keys" in the sidebar

4. **Create New Key**
   Click "Create API Key" and give it a name (e.g., "Music Adviser")

5. **Copy Your Key**
   Copy the generated API key immediately (you won't be able to see it again!)

6. **Add to Your Project**
   - For local development: Add to `.env` file
   - For Streamlit Cloud: Add to Secrets in app settings

### Free Tier Limits
- Groq offers generous free tier limits
- Perfect for development and small-scale projects
- Check [Groq Pricing](https://groq.com/pricing/) for current limits

---

## 🔮 Future Improvements

Here are some exciting features planned for future releases:

- [ ] **Playlist Generation** - Create custom playlists based on user preferences
- [ ] **Spotify Integration** - Connect with Spotify API for direct playlist creation
- [ ] **User Accounts** - Save conversation history and preferences
- [ ] **Voice Input** - Add speech-to-text functionality
- [ ] **Multi-language Support** - Support conversations in multiple languages
- [ ] **Music Genre Explorer** - Interactive genre discovery and learning
- [ ] **Mood-Based Recommendations** - Suggest music based on detected user mood
- [ ] **Artist Comparisons** - Compare artists and find similar musicians

---

## 👨‍💻 Author

**Candyna**
12-year-old Developer | AI Enthusiast | Music Lover

- 🌐 Portfolio: [https://Candyna.codecub.org](https://Candyna.codecub.org)
- 💼 GitHub: [@candyna](https://github.com/candyna)
- 🎵 Favorite Artists: ENHYPEN, Stray Kids

---

## 📝 License

This project is created for educational purposes as part of CodeCub's programming curriculum.

---

## 🙏 Acknowledgments

- **Groq** - For providing the amazing Llama 3.3 70B API
- **Streamlit** - For the excellent web framework
- **CodeCub** - For mentorship and learning support
- **ENHYPEN & Stray Kids** - For the musical inspiration! 🎵

---

## 🤝 Contributing

This is a personal learning project, but feedback and suggestions are always welcome! Feel free to open an issue or submit a pull request.

---

## ⭐ Star This Project

If you found this project helpful or interesting, please consider giving it a star on GitHub! It helps others discover the project and motivates continued development.

---

<div align="center">

**Made with ❤️ and 🎵 by Candyna**

*Where creativity meets code meets music!*

</div>
