# SolarIQ
SolarIQ: Predictive Energy Chat is a web-based chatbot that analyzes and predicts household electricity consumption and solar generation. Built with TailwindCSS, Chart.js, and a custom JS regression model, it simulates Belagavi’s seasonal patterns and provides AI-powered energy-saving tips via Gemini API.

SolarIQ is a smart, chat-based web app that helps households track, analyze, and predict their energy usage and solar power generation.
It combines AI-powered insights, real-time charts, and weather-based simulation to provide personalized energy-saving recommendations for households in Belagavi, Karnataka.

Users can chat with SolarIQ using natural language queries like:

“Show me last month’s solar generation”

“Predict my energy consumption for next week”

“Give me tips to save energy this summer”

🚀 Features

💬 Conversational Chatbot – Simple chat interface for energy queries.

🌦️ Weather Simulation – Seasonal patterns & animated icons (sun, cloud, rain).

📊 Dynamic Charts – Energy trends visualized with Chart.js.

🤖 Custom AI Models – Linear regression (JS) for predictions.

💡 Smart Energy Tips – Personalized advice via Gemini API.

🎨 Modern UI/UX – Dark mode, TailwindCSS styling, and smooth chat design.

🛠️ Tech Stack

Frontend: HTML5, CSS3, TailwindCSS

Data Visualization: Chart.js, Moment.js

AI/ML: Custom Linear Regression (JavaScript), Gemini API

Simulation: Synthetic household dataset (Belagavi climate)

📂 Project Structure
📦 SolarIQ
 ┣ 📜 index.html      # Main app UI with chatbot and charts
 ┣ 📜 style.css       # Tailwind + custom styles
 ┣ 📜 script.js       # Chat logic, ML models, data simulation, API calls
 ┗ 📜 README.md       # Documentation

⚙️ Setup & Installation

Clone the repository:

git clone https://github.com/your-username/SolarIQ.git


Open the folder:

cd SolarIQ


Open index.html in your browser.

(Optional, for tips feature) Add your Gemini API key in script.js:

const apiKey = "YOUR_GEMINI_API_KEY";

📖 Usage

Type a query in the chat box, e.g.:

“Show me last month’s usage”

“Predict solar generation for next week”

“Compare consumption in summer vs winter”

Get:
✅ Interactive charts
✅ AI-powered predictions
✅ Personalized energy-saving tips

🔮 Future Scope

Integration with real smart meter IoT data

Support for multiple regions & tariff plans

Advanced forecasting with LSTM/Transformers

Mobile-first PWA version

📜 License

This project is licensed under the MIT License.
