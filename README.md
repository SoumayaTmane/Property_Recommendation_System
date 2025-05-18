🏡 Property Recommendation System
✨ A machine learning–powered tool to assist appraisers by recommending the top 3 most comparable properties in seconds.

📌 Overview
This project leverages XGBoost to predict and recommend the best comparable properties for a given subject property. It reduces the time and subjectivity in manual property comparisons.

🚀 Key Features
⚙️ Developed a robust ML model using XGBoost
📊 Trained on real-world appraisal data
🧠 Automatically identifies top 3 comparable properties for each subject property
🕒 Saves time and increases consistency compared to manual appraisal
📍 Incorporates address similarity using cosine similarity
🧼 Standardizes and encodes property features for accurate predictions

How It Works
-Load appraisal data, including both subject properties and comparable properties (comps).
-Extract and clean features from all properties, ensuring consistency between comps and subjects.
-Use cosine similarity with TF-IDF to compare and score address similarity between properties.
-Train an XGBoost classifier to predict whether a given property is a valid comp for a subject property.
-For each subject property, rank all potential comps and recommend the top 3 based on predicted relevance.
