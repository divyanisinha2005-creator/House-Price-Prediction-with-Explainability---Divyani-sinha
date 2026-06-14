# House-Price-Prediction-with-Explainability-Divyani sinha
A deep learning regression model built with Keras to predict house prices, featuring SHAP values for model explainability and feature importance.
# House Price Prediction (with SHAP Explainability) 🏡

Hey! Thanks for checking out my project. 

I built this deep learning model using the classic Kaggle Ames House Prices dataset. But instead of just throwing a neural network at the data and stopping at the final prediction, I wanted to focus on a skill that is actually used in the industry: model explainability. 

It’s one thing to get a low error rate, but in the real world, people want to know why a model priced a house a certain way. To solve this, I integrated SHAP to open up the "black box" of the neural network.

# What I Did
Data Prep: I used `pandas` and `scikit-learn` to clean up missing values and encode the messy categorical data. I also scaled the numerical features to make sure the neural network trained smoothly.
The Model: I built and trained a 3-layer Dense Neural Network using `TensorFlow/Keras`. 
The "Why": I used `SHAP` values to break down the predictions. The plots in my notebook show exactly which features (like Living Area or Overall Quality) pushed a specific home's price up or down.

# Tech Stack
* Python (`pandas`, `numpy`)
* Deep Learning: `TensorFlow` / `Keras`
* Preprocessing:`scikit-learn`
* Explainability & Visuals: `SHAP`, `matplotlib`

# Next Steps
The model's current R^2 score is solid, but I plan to keep experimenting with tuning the hidden layers and adjusting the preprocessing steps to push the accuracy even further. 
Feel free to open the `.ipynb` notebook above to check out the code, the data engineering steps, and the SHAP visualizations in action.
