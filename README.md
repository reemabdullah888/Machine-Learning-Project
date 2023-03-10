# Machine-Learning-Project
While studying Machine learning for Data Science with Prof. Rajati at the University of Southern California, I worked on a project to explain and interpret the results of two pre-trained models EfficientNetB0 and VGG16. The main objective was to classify images of 20 bird species by applying transfer learning, which uses deep learning models that are trained on very large datasets such as ImageNet as feature extractors.
I performed several empirical regularizations on the training set which includes over 3600 images using OpenCV to increase the accuracy and decrease the error ratio. 


After completing the image augmentation phase, I used GlobalMaxPooling2D, ReLU and softmax activation functions as layers to my model along with batch normalization and a dropout rate of 20%. In addition, I used multinomial cross entropy loss and ADAM optimizer. Then I trained the networks for 70 epochs and performed an early stopping using the validation set. 

The visualization results showed that EfficientNetB0 produced more accurate results for classifying the bird species images. When I successfully finished this small project, I was inspired to increase and improve my analytical skills for future investigation.
