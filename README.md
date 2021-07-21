# Handwritng Prediction
The project is based on the hand writing dataset which can be found here https://www.kaggle.com/sachinpatel21/az-handwritten-alphabets-in-csv-format

This is my simple project which is based on my CNN model to predict handwritten letters, The purpose of this project is to work on my end to end development skills as I try take data and bring it through the data science pipeline to deployment, Hopefully I'll be able to improve on and expand this project over time.
 # Stage 1 
 First stage involved Exploratory Data Analysis and Featuring Engineering
 
 # Stage 2
 From here I developed my model and trained it, originally I performed the training using Google Colab, however trying to save the trained model and import it from Colab into Jupyter Notebook (due to continually maxing out the RAM allotment in Colab proved to be more of a headache than anticipated so I instead settled for a model with reduced Epochs that I could reliably run on my own machine without it crashing (which seemed to be the default outcome). Hopefully I'll be able to remedy this in future and implement the slightly more accurate Colab version. However the model I did employ is adequet for the current task. 
 
 # Stage 3 
 Here I attempted to move into the deployment of my model, As this was the main focus of my project I plan to experiment with different deployments as I look to expand my knowledge further and broaden my skill set. 
 My first deployment is a Tkinter GUI application which accepts photos uploaded from your device and predicts what the letter is, after prediction is complete, the models prediction along with the image are stored in a sqlite database.
 
 # Stage 4 
 The second deployment allows the user to write out letters in the GUI and have the model predict them, there is also the ability to save the image. From here I'd like to combine both deployments into one multi window GUI, where the functionality from both can be offered. I'd also like to try introduce another model which can perhaps predict words rather than just letters. If time allows I'd also like to branch into different pythonic web frameworks like flask to get some experience in the basics
 
 # Notes
 The main task was to bring data through the data science process and into deployment, as such things are a little rough around the edges but I will hopefully be able to improve all aspects and implement more features and deployments.
