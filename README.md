# Project Name: Landsafe
Landsafe is an innovative solution addressing the recurring threat of landslides in Sri Lanka, particularly in mountainous regions. With over 30% of the country's land area highly susceptible to landslides and floods, it's imperative to empower communities with timely information and decision-making tools. Landsafe+ goes beyond traditional approaches by integrating state-of-the-art technologies like Weight of Evidence (WoE) models, Earth observations from satellite data, and crowdsourced information to create a comprehensive Landslide Susceptibility Map. This map serves as a vital resource for hazard managers, planners, and the general public, enabling informed decision-making and proactive measures to mitigate the impact of landslides.

## Objectives:

### Community Awareness: 
Develop awareness among communities about their level of risk and the importance of preparedness measures.
Landslide Susceptibility Mapping: Utilize WoE models to create a detailed Landslide Susceptibility Map, incorporating Earth observations and local open data.
Decision Support Tool: Provide hazard managers and planners with an advanced decision support tool that integrates satellite data and local information for effective risk management.
Crowdsourced Data Contribution: Engage the general public in data collection efforts to enhance the precision of landslide risk analysis and improve the accuracy of the Landslide Susceptibility Map.
Features:

### Real-time Alerts:
Receive timely notifications about landslide threats in your area, helping you stay informed and prepared.
Interactive Maps: Explore the Landslide Susceptibility Map to understand the risk levels in different regions and plan accordingly.
Decision Support Tools: Access advanced tools for hazard managers and planners to analyze data and make informed decisions.
Crowdsourced Data Collection: Contribute to the improvement of landslide risk analysis by sharing data from your territory through the app.
Community Engagement: Connect with other users, share experiences, and collaborate in disaster preparedness efforts.
Technologies Used:

### WoE Models: 
Utilize Weight of Evidence models for Landslide Susceptibility Mapping.
Earth Observations: Integrate satellite data for enhanced analysis and mapping.
Crowdsourcing Platform: Develop a user-friendly interface for crowdsourced data collection and contribution.
Mobile App Development: Employ Flutter framework for cross-platform mobile app development.
Data Security: Implement encryption protocols and adhere to data protection regulations to ensure user privacy and security.

## Technologies Used: 
Machine learning for landslide prediction, GIS for spatial data analysis, TensorFlow for model development, Flutter for mobile app development.
New Components: Integrating machine learning model with GIS for landslide susceptibility mapping, developing a mobile application for real-time alerts and risk assessment.
Technologies for Implementation: Python for machine learning model development, ArcGIS for GIS analysis, TensorFlow for model conversion to TFLite, Flutter for mobile app development.
Scaling Parameters: Data sizes include GIS raster data (e.g., DEM, rainfall maps) and landslide inventory datasets. QPS estimates depend on the frequency of user requests for risk assessment and alerts.
Rollout Strategy: Initial rollout to targeted regions prone to landslides, followed by expansion based on user feedback and effectiveness evaluation.
Information Security/Privacy Concerns: Secure handling of user location data and personal information, encryption of data transmission, compliance with data protection regulations such as GDPR and HIPAA

### The approach used to generate the algorithm:

The algorithm follows a U-Net architecture for semantic sutilizesion, designed to segment landslide areas from satellite images. It preprocesses the input data, including RGB channels, NDVI, slope, and elevation, and constructs a U-Net model with convolutional and transposed convolutional layers. The model is trained using binary cross-entropy loss and metrics such as accuracy, F1 score, precision, and recall. A checkpoint callback is employed to save the best model based on the validation F1 score. The approach uses TensorFlow for implementation and utilizes GPU acceleration for faster training.


Together, let's create a safer tomorrow with Landsafe!
