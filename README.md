# Image Classification of Rocks, Papers, and Scissors

- Dataset : [Kaggle - Rockpaperscissors](https://www.kaggle.com/drgfreeman/rockpaperscissors)

In this project I created a model using TensorFlow to classify hand drawings and predict whether the hand represents a scissor, rock, or paper shape. TensorFlow(TF) is an end-to-end open source platform developed by Google Brain and is very popular for large-scale machine learning development.

Artificial neural network program using TensorFlowThis program will help identify the shape of the hand that makes up scissors, rock or paper.

## Modelling

The steps taken include:
1. Download the dataset and extract the file with the unzip method.
2. Store the directory of each class in the train directory and validate it into a variable.
3. Pre-processing data with image augmentation.
4. Prepare training data that will be studied by the model.
5. Build the model architecture with CNN.
6. Compile and train the model with model.compile and model.fit until you get the desired accuracy.
7. Predict the drawing of scissors, rock, or paper to test the model.

## Results

The model has an accuracy of up to 95% and can predict the hand that forms 'Paper'

![image](https://user-images.githubusercontent.com/87906938/127173056-adede5c8-6449-481f-b45a-ce493a983484.png)

![image](https://user-images.githubusercontent.com/87906938/127173001-d57eb1ed-1d7a-4dcf-96ea-d3f7a7c4bc05.png)

![image](https://user-images.githubusercontent.com/87906938/127173193-5077c6cc-258b-46b9-b36b-299dcd9f50bf.png)
