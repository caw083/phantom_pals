# Phantom Pals

**Phantom Pals** is an interactive React application that lets you explore, collect, and chat with imaginary friends from fantastical universes — from phantoms 👻 and mythical beasts 🐉 to anime heroes 🎌 and more!

Built as a fun and creative MVP to showcase imagination 🧠, AI power 🤖, and smooth user experience 🎨.

---

## 🚀 MVP Features

### 🌌 Explore Universes
- Browse characters from different worlds: **Phantom**, **Mythical**, **Anime**, and beyond 🌍
- Each character appears as a beautiful card with name, image, and story 📇

### 🔍 Smart Search (NLP-enhanced)
- Use natural language to search:
  - "anime fire" 🔥
  - "phantom water" 💧
  - "mythical dragon" 🐲

### 🎙️ Voice Interaction
- 🎤 Voice-to-text for hands-free searching
- 🔊 Listen to characters speak via text-to-speech

### 🤖 LLM-Powered Assistant *(NEW!)*
- Integrated with **GPT/LLM APIs** for:
  - ✨ Auto-generating character backstories
  - 💬 Chat with your favorite phantom
  - 📘 Create a new character with just a prompt
- Example prompts:
  - `"Make a water guardian from the forest 🌳"`
  - `"Design a ghost warrior with fire powers 🔥👻"`

### ⭐ Favorites Collection
- Save your favorite pals 💖
- Data stored locally using LocalStorage 💾

---

## 🛠️ Tech Stack

| Feature         | Technology                         |
|----------------|------------------------------------|
| Frontend UI    | React + Vite ⚡                   |
| Styling        | Tailwind CSS 🎨                  |
| Routing        | React Router 🔁                  |
| Voice Features | Web Speech API 🎤🗣️             |
| NLP            | Compromise.js / Natural.js 🧠    |
| AI / LLM       | OpenAI API or HuggingFace 🤖     |
| State Management | useState / useContext 🧩        |
| Data Storage   | LocalStorage 💾                  |

---

## 🧭 Project Structure

```
phantom-pals/
├── src/
│   ├── components/       # UI Components 🧩
│   ├── pages/            # Pages (Home, Favorites, etc.) 📄
│   ├── ai/               # LLM interaction logic 🤖
│   ├── nlp/              # Search intelligence (NLP) 🧠
│   ├── assets/           # Images, sounds, etc. 🖼️🔊
│   └── App.jsx
├── public/
└── README.md
```

---

## 📦 Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn package manager

### Installation

```bash
# 📥 Clone the repository
git clone https://github.com/yourusername/phantom-pals.git
cd phantom-pals

# 📦 Install dependencies
npm install

# 🔐 Set up environment variables
# Create a .env file in the root directory
echo "VITE_OPENAI_API_KEY=your_api_key_here" > .env

# 🚀 Start development server
npm run dev
```

### Build for Production

```bash
# 🏗️ Build the project
npm run build

# 🌐 Preview production build
npm run preview
```

---

## 🎯 Usage

1. **Explore Characters**: Browse through different universe categories
2. **Search**: Use natural language to find specific character types
3. **Voice Commands**: Click the microphone icon for voice search
4. **Chat with AI**: Generate new characters or chat with existing ones
5. **Save Favorites**: Click the heart icon to save your favorite pals

---

## ✨ Coming Soon

- 🧠 User-authored character creator
- 🌐 Cloud sync with Firebase
- 🎮 Mini-games with your phantom pals
- 🌈 More universe categories
- 📱 Mobile app version

---

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Ideas for Contributions
- 💡 New character ideas and universes
- 🎨 UI/UX improvements
- 🐛 Bug fixes and optimizations
- 📚 Documentation improvements

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 📫 Contact & Support

**Built with ❤️ by Christopher Ade Wiyanto**

- 🌐 GitHub: [@yourusername](https://github.com/yourusername)
- 📧 Email: your.email@example.com
- 💼 LinkedIn: [Your Profile](https://linkedin.com/in/yourprofile)

Open for collaboration, creativity, and coffee chats ☕✨

---

## 🙏 Acknowledgments

- Thanks to the open-source community for the amazing tools
- Inspired by the creativity of anime, fantasy, and gaming communities
- Special thanks to all contributors and testers

---

*Ready to meet your new phantom pals? Start exploring! 👻✨*
