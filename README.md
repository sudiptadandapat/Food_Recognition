# Food_Recognition
Food Recognition &amp; Nutrition Estimation using Deep Learning

In this project, we came with an approach to alleviate the user to enter all such details and have the same result  with just a food image. 

We propose a deep-learning based approach to calculate the calories from the food image through classification of type of food and estimating the weight of the food. Here, we use a pipeline approach by doing few steps. First, we identify the type of food in the image. Second, we generate an estimated size of food item in grams. Then, by taking the first two intermediate results, we estimate different nutritional content from data-set.

All our prediction tasks were performed using deep learning with some standard pre-trained model like InceptionV3 for object classification and YOLOv3 for object detection in fast food images. 

We compared our pipelined approach to a baseline approach that directly predicts the amount of calories based only on the image, and showed a reduction in prediction accuracy.

