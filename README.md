# Emotion Detection 
This project provides a user-friendly web interface for real-time emotion detection using a machine learning model trained on a custom dataset.
Powered by Gradio, it allows users to input text, images, or audio and instantly receive predictions about the emotions expressed in the input.
With its intuitive design and customizable features, this interface makes emotion detection accessible to a wide range of users.

# Objectives 
* Accuracy: Aim to achieve high accuracy in detecting emotions from input data. This could involve accurately identifying various emotions such as happiness, sadness, anger, etc.
* User Experience Improvement: Ultimately, the goal of emotion detection is to enhance user experience. Measure the impact of the model on user satisfaction, engagement, or other relevant metrics.

# Technology 
* I have used a dataset from kaggle you can also use it. We have made a model from scratch , then used VGG16 model which is used to classify and detect which type images are,
  the we used RESNET50 model which function is same like VGG16.
* For the websiter interface we used gradio to run the model where you can upload the image and submit it to find the result.

# Thoughts 
* By working on this project one can get idea how to build cnn model from scratch and calculate its 
efficiency, talking of efficiency I am talking about canfusionn matrix one can get idea what how the model is performming since the accuracy is good but the the model is able to predict
that properly by looking at the confusion matrix
* Since Our previous model was not working then we used VGG16 model which is used to classiy images , you can learn more about VGG16 by looking online and reading articles. we trained the model and accuracy is
  also good but the confusion matrix is not that good again. So we cannnot use that model againn.
* Now we other model RESNET50 which fucntion is same like VGG16 now wee train the model and get the accuracy good and confusion matrix is showing also good numbers. So we can use this model and save the model
* I have talked about also other parts of the model you can search it online and read research paper about it.

# How to run 
* To run this project use kaggle API function to import the dataset
* Now run the RESNET50 model part.
* Now run the Gradio part code it will generate the localhost link.
