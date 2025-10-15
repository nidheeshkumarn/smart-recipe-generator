# 🍳 Smart Recipe Generator

**AI-Powered Smart Cooking Assistant**

The **Smart Recipe Generator** is a modern, AI-driven web application that helps users decide *“What can I cook with what I have?”*  
Simply input your ingredients — or upload a photo — and let the app recognize your ingredients, suggest suitable recipes, and guide you step-by-step through cooking.

---

## 🚀 About The Project

The **Smart Recipe Generator** combines artificial intelligence, intuitive UI, and cloud-backed data persistence to deliver a personalized and interactive cooking experience.  

Users can discover recipes based on available ingredients, rate their favorites, and even get tailored recipe recommendations powered by AI.

### ✨ Key Features

- 🧠 **AI Ingredient Recognition** — Upload a photo and let the AI automatically detect ingredients.  
- 🍽️ **Smart Recipe Matching** — Instantly get recipes that match your available ingredients.  
- 💡 **Personalized Suggestions** — AI-powered recommendations that learn from your saved and rated recipes.  
- ⚖️ **Adjustable Serving Sizes** — Dynamically update ingredient quantities based on your serving preferences.  
- 🧑‍🍳 **Live Cooking Assistant** — Ask the AI for substitutions, cooking tips, or clarifications right on the recipe page.  
- 📚 **Comprehensive Recipe Database** — 36 curated, beginner-friendly recipes with step-by-step guidance and nutrition info.  
- 🔍 **Advanced Filtering** — Filter recipes by cooking time, difficulty, or dietary needs.  
- 🔒 **User Accounts & Data Persistence** — Securely store favorite recipes and ratings with Firebase Authentication & Firestore.  
- 📱 **Mobile-Responsive Design** — Beautiful, modern interface that adapts perfectly across all devices.

---

## 🧩 Architecture Overview

The application follows a clean **Single-Page Application (SPA)** architecture, rendered client-side with React.

### **Frontend (React + Tailwind CSS)**
- Built with **React.js** for a modular and reactive UI.
- Styled with **Tailwind CSS** for a sleek and responsive layout.
- Includes integrated **AI chat assistant** for live help and personalization.

### **Backend-as-a-Service (Firebase)**
- 🔐 **Authentication:** Anonymous user sign-in for private, unique sessions.
- ☁️ **Firestore:** NoSQL database for storing user data (saved recipes, ratings, preferences).

### **AI Integration (Google Gemini API)**
The Gemini API powers the app’s intelligence:
- Ingredient recognition from uploaded images.
- Smart recipe recommendations using user history and preferences.
- Conversational assistance for real-time cooking help.

---

## 🛠️ Technology Stack

| Layer | Technology |
|-------|-------------|
| **Frontend** | React.js, Tailwind CSS |
| **Backend & Database** | Firebase Authentication, Firebase Firestore |
| **AI / ML Integration** | Google Gemini API |
| **Deployment** | Vercel |

---

## ⚙️ Project Setup & Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/smart-recipe-generator.git
   cd smart-recipe-generator
