Real Estate Price Prediction App                               

A React.js app that leverages AI to predict real estate prices based on various property factors using Brain.js, a JavaScript neural network library.                     

Features:                                          
AI-Powered Predictions: Uses Brain.js for accurate price estimation.                     
Data Visualization: Visualize price comparisons with Chart.js.                         
Similar Listings: Suggests properties similar to the one entered by the user, based on the dataset.                    
Persistent Model Storage: The trained model is saved in localStorage for reuse.                                    
User Feedback System: Users can rate the accuracy of predictions.           
Responsive UI: Clean, modern design styled with Bootstrap.          

Technologies Used:            
Frontend: React.js, Bootstrap              
AI Model: Brain.js (Neural network for price prediction)           
Visualization: Chart.js              
Storage: LocalStorage (for storing the trained model)                

Key Components:                                      
src/components/: Contains all React components like the chart, input form, and the prediction display.         
src/data/: Holds the dataset (dataset.json) containing real estate details for training the model.                           
src/model/: Contains the AI model's logic using Brain.js. The brainModel.js file handles the neural network training and predictions.                     
src/styles/: Custom CSS styles to give the app its look and feel.                                
public/: Stores static assets like the favicon and the root HTML template.                  
package.json: Includes all dependencies and scripts required to build and run the app.               

How to Run Locally:               
Clone the Repository                   
git clone https://github.com/Prabh345/real-estate-price-prediction.git                     
cd real-estate-price-prediction               

Install Dependencies            
npm install                                 

Start the Development Server                               
npm start                     

The app will be available at http://localhost:3000                              

Build for Production                 
npm run build                

Deploy to GitHub Pages                          
npm run deploy               

How It Works:                        

Users enter property details (area, bedrooms, bathrooms, location, age).                                     
The AI model (Brain.js) processes the input and predicts the price.                          
Users see the predicted price along with a list of similar properties.                    
A chart displays a comparison between the actual and predicted prices.                                
Users can provide feedback on the accuracy of the predictions.                            

Deployed Site:                       
https://prabh345.github.io/real-estate-price-prediction/           
