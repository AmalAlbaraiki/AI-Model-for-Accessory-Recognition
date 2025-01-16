# AI-Model-for-Accessory-Recognition
________________________________________
AI Model for Accessory Recognition: Report
Objective:
The goal of this project was to train an image recognition model using Google Teachable Machine to classify images into four categories: glasses, earrings, hats, and no accessories. After training the model, the objective was to export it in TensorFlow format and build a Python script to load the model and make predictions on new images.
Process:
1. Data Collection and Labeling:
I used a set of images labeled with four categories:
•	Glasses
•	Earrings
•	Hats
•	No Accessories
Each category contained multiple images to ensure the model could learn to differentiate between them effectively. These images were uploaded to Teachable Machine for training.
2. Model Training:
Using the labeled data, I trained a custom image recognition model through Teachable Machine. The model was trained on the four categories and optimized to classify images based on the accessories they contained.
3. Exporting the Model:
After the model was trained, I exported it in TensorFlow SavedModel format. The exported model includes the weights and the configuration necessary to use it for making predictions.
4. Model Evaluation:
The model was evaluated by testing it with images from each category. The accuracy of the model was sufficient to make accurate predictions for most images in the dataset.
5. Python Script Development:
I developed a Python script that loads the exported TensorFlow model. The script takes an input image, processes it, and passes it through the model to predict which category it belongs to. The predictions are returned in the form of probabilities, and the script determines the most likely category.
6. Testing the Model:
I tested the Python script with various images to ensure that the model could classify them accurately. The results confirmed that the model performs well on images it has seen during training.
Conclusion:
The project successfully trained an image recognition model with four categories of accessories. The model was exported in TensorFlow format and integrated into a Python script to make predictions. The model performed well, demonstrating its ability to classify images into the correct categories.
________________________________________
GitHub Repository:
https://github.com/AmalAlbaraiki/AI-Model-for-Accessory-Recognition________________________________________
	 
   
