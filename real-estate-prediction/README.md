Real Estate Price Prediction App

Predict real estate prices using AI

This React.js app leverages Brain.js (a JavaScript neural network library) to estimate property prices based on various factors.

Features

AI-Powered Predictions – Uses Brain.js for price estimation.

Data Visualization – Chart.js displays price comparisons.

Similar Listings – Suggests matching properties from dataset.json.

Persistent Model Storage – Saves trained model in localStorage.

User Feedback System – Users can rate the accuracy of predictions.

Responsive UI – Styled with Bootstrap for a clean, modern look.

Technologies Used

Frontend: React.js, Bootstrap

AI Model: Brain.js

Visualization: Chart.js

Storage: LocalStorage

Folder Structure

real-estate-prediction/
│── src/
│   ├── components/       # React components
│   │   ├── Chart.js      # Chart visualization
│   │   ├── Form.js       # User input form
│   │   ├── Prediction.js # Display predictions & similar listings
│   │
│   ├── data/             # Dataset (dataset.json)
│   ├── model/            # Neural network logic (Brain.js)
│   │   ├── brainModel.js # Handles AI model & training
│   │
│   ├── styles/           # CSS styles
│   ├── App.js            # Main app component
│   ├── index.js          # Entry point
│   ├── index.css         # Global styles
│
│── public/
│   ├── favicon.ico       # Custom favicon
│   ├── index.html        # Root HTML file
│
│── package.json          # Dependencies & scripts
│── README.md             # Documentation

How to Run Locally

1. Clone the Repository

git clone https://github.com/Prabh345/real-estate-price-prediction.git
cd real-estate-price-prediction

2. Install Dependencies

npm install

3. Start the Development Server

npm start

The app will be available at http://localhost:3000.

4. Build for Production

npm run build

5. Deploy to GitHub Pages

npm run deploy

How It Works

Users enter property details (area, bedrooms, bathrooms, location, age).

The AI model (Brain.js) predicts the price based on trained real estate data.

Users get a predicted price along with similar property listings.

Charts visualize actual vs. predicted prices for better comparison.

Feedback system allows users to mark predictions as accurate or inaccurate.

Deployed site: https://prabh345.github.io/real-estate-price-prediction/
