** About The Project
The Smart Recipe Generator is a modern, AI-powered web application designed to solve the common problem of "what can I cook with what I have?". This app allows users to input ingredients either by text or by simply uploading a photo. It intelligently recognizes ingredients, suggests a variety of suitable recipes, and provides detailed, beginner-friendly cooking instructions.
Built with React and Firebase, the application offers a personalized experience by allowing users to save and rate their favorite recipes. These ratings then fuel an AI-powered suggestion engine that provides tailored recipe recommendations, turning a simple recipe browser into a smart cooking assistant.

** Key Features
AI Ingredient Recognition: Upload a photo of your ingredients and let the AI identify them for you.
Smart Recipe Matching: Get recipe suggestions based on the ingredients you have on hand.
Personalized Suggestions: Rate your saved recipes to receive AI-powered recommendations tailored to your taste.
Adjustable Serving Sizes: Dynamically update ingredient quantities based on the number of servings.
Live Cooking Assistant: Ask for substitutions, techniques, or advice with an integrated AI chat assistant on every recipe page.
Comprehensive Recipe Database: Includes 36 diverse, curated recipes with detailed, beginner-friendly instructions and nutritional information.
Advanced Filtering: Filter recipes by cooking time, difficulty, and dietary restrictions.
User Accounts & Data Persistence: Securely saves your favorite recipes and ratings using Firebase Authentication and Firestore.
Mobile-Responsive Design: A clean and intuitive UI that works beautifully on any device.

** Project Implementation & Technical Details
Architecture Overview
The application is built as a single-page application (SPA) using React, rendered entirely client-side. It follows a simple, robust architecture:
Frontend (React & Tailwind CSS): The user interacts with the React UI. All components, state management, and logic are contained within a single file for easy deployment.
Backend-as-a-Service (Firebase):
Authentication: Handles unique, anonymous user sessions to keep data private.
Firestore: A NoSQL cloud database used to store user-specific data like saved recipes and personal ratings.
Artificial Intelligence (Google Gemini API):
The application makes secure, server-less calls to the Gemini API for three core "smart" features: recognizing ingredients from images, generating personalized recipe suggestions based on user ratings, and powering the live cooking assistant.

** Technology Stack
Frontend: React.js, Tailwind CSS
Backend & Database: Firebase (Authentication & Firestore)
AI & Machine Learning: Google Gemini API
Deployment: Vercel
