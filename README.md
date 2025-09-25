# AgroSmart - Smart Crop Advisory System 🌱
An AI-powered, all-in-one platform to empower small and marginal farmers with data-driven agricultural advice.

This project is a fully-functional web application prototype developed for the Smart India Hackathon, based on the problem statement "Smart Crop Advisory System for Small and Marginal Farmers".

🎯 The Problem
Small and marginal farmers in India often rely on traditional knowledge, which can lead to guesswork in crop selection, pest control, and fertilization. This results in:

Poor crop yields and lower income.

High input costs due to inefficient use of resources.

Lack of personalized advice due to language barriers and low digital literacy.

Limited access to market data and government support schemes.

✨ The Solution: AgroSmart
AgroSmart is a multilingual, voice-enabled, and AI-powered web application that acts as a personal farming companion. It provides hyper-personalized, real-time guidance to farmers, helping them make informed decisions at every stage of the farming lifecycle.

The platform is designed to be an "All-in-One" solution, combining farm management, market services, and a community platform into a single, easy-to-use interface.

🚀 Key Features
The app includes a comprehensive suite of features to address every need of a modern farmer:

👤 1. Personalized Onboarding

Language Selection: Choose from 5 languages (English, Punjabi, Hindi, Marathi, Telugu) before starting.

User Registration: A simple form to capture the farmer's name, phone number, and location to personalize the experience.

User Profile: A clickable profile displays all registered user information and includes a "Log Out" function.

🌾 2. Farm Management

AI Crop Advisory: Get recommendations for the top 3 suitable crops by either uploading a soil lab report or manually entering N-P-K values.

AI Pest Detection: Upload an image of a crop leaf to identify pests/diseases and receive AI-generated treatment advice.

Field Monitoring: A real-time dashboard showing weather, soil moisture, and satellite-based crop health with an AI summary.

Weather Alerts: Timely warnings for critical weather events like heavy rain or heatwaves.

Crop Timeline: A sample schedule for all major farming activities from sowing to harvesting.

📈 3. Market & Services

Market Price Tracking: View real-time Mandi prices with trend indicators (up/down).

Agri-Marketplace: A platform for farmers to list their produce for sale and buy from other farmers directly.

Government Schemes: Information on relevant schemes with simple, step-by-step "How to Apply" guides.

SMS Alerts: Subscribe using a phone number to receive critical alerts even without internet access.

🤝 4. Knowledge & Community

Community Forum (Krishi Charcha): A platform for farmers to ask questions and share knowledge with each other.

Voice Assistant: A powerful, multilingual voice assistant accessible from the header to answer questions and navigate the app.

Feedback System: Allows users to submit feedback for the continuous improvement of the AI models.

💻 Technology Stack
Frontend: HTML5, TailwindCSS, Vanilla JavaScript

AI & Machine Learning: Google Gemini API (for crop advisory, pest detection, and AI summaries).

Icons: Lucide Icons

🛠️ Getting Started: How to Run Locally
You can easily run this application on your local machine using Visual Studio Code and the Live Server extension.

1. Save the Code

Save the complete code into a single file named index.html.

2. Get a Gemini API Key

This project requires a Google Gemini API key to power its AI features.

Visit the Google AI Studio to get your free API key.

3. Add the API Key to the Code

Open index.html in VS Code.

Find the following line in the <script> section at the bottom:

const apiKey = ""; 

Paste your API key inside the quotation marks:

const apiKey = "YOUR_OWN_API_KEY_HERE";

4. Install Live Server in VS Code

Go to the Extensions tab in VS Code.

Search for Live Server by Ritwick Dey and click Install.

5. Run the App

With the index.html file open, click the "Go Live" button in the bottom-right corner of the VS Code status bar.

Your browser will open, and the app will be fully functional.

👥 Team Information
Team Name: Error 404

Project: Smart India Hackathon 2025

📄 License
This project is licensed under the MIT License. See the LICENSE file for details.
