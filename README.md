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

| ⚙️ Feature         | 🧰 Technology                         |
|--------------------|--------------------------------------|
| Frontend UI         | React + Vite ⚡                     |
| Styling             | Tailwind CSS 🎨                    |
| Routing             | React Router 🔁                    |
| Voice Features      | Web Speech API 🎤🗣️               |
| NLP                 | Compromise.js / Natural.js 🧠      |
| AI / LLM            | OpenAI API or HuggingFace 🤖       |
| State Management    | useState / useContext 🧩           |
| Data Storage        | LocalStorage 💾                    |

---

## 📦 Getting Started

```bash
# 📥 Clone the repo
git clone https://github.com/yourusername/phantom-pals.git
cd phantom-pals

# 📦 Install dependencies
npm install

# 🔐 Add your LLM API key
echo "VITE_OPENAI_API_KEY=your_api_key_here" > .env

# 🚀 Start development server
npm run dev```

