
TODO: 

- Add Part 1 and Part 2 references.
- Make Assignment Description neater.

# Assignment 07 - Computer Vision

## Assignment Description

Part 1 - supervised contrastive learning  - Using new loss 

Write a colab to demonstrate supervised contrastive learning loss based supervised classification versus regular softmax based one

Hint : Check colab links at https://docs.google.com/presentation/d/1UxtHDwjViC7VpSb0zB-kajGQ-TwznQmc-7LsbHRfO3s/edit#slide=id.gcdc5f16e5b_20_5Links to an external site. and https://towardsdatascience.com/contrastive-loss-for-supervised-classification-224ae35692e7Links to an external site. - Also check https://keras.io/examples/vision/supervised-contrastive-learning/Links to an external site. 

Please provide necessary visualizations

Part 2 - Transfer learning on various modalities : 
Write simple colabs to transfer learn on images, videos, audios -  - with both as a feature extractor as well as a fine tuning usecases


Example hints : 

Audio : https://blog.tensorflow.org/2021/03/transfer-learning-for-audio-data-with-yamnet.htmlLinks to an external site.

Video : https://www.tensorflow.org/hub/tutorials/action_recognition_with_tf_hubLinks to an external site.

NLP : https://www.tensorflow.org/hub/tutorials/tf2_text_classificationLinks to an external site.  or https://amitness.com/2020/02/tensorflow-hub-for-transfer-learning/Links to an external site. or pick 

Image :

Showcase basic transfer learning for a classification task (either cats/dogs or breeds of dogs) in a colab - with both as a feature extractor as well as a fine tuning usecase

Hint : https://www.tensorflow.org/tutorials/images/transfer_learningLinks to an external site. or https://towardsdatascience.com/dog-breed-classification-using-cnns-and-transfer-learning-e36259b29925Links to an external site.

or

use the below usecases : 

https://github.com/mrdbourke/tensorflow-deep-learning/blob/main/04_transfer_learning_in_tensorflow_part_1_feature_extraction.ipynbLinks to an external site.

https://github.com/mrdbourke/tensorflow-deep-learning/blob/main/05_transfer_learning_in_tensorflow_part_2_fine_tuning.ipynbLinks to an external site.

https://github.com/mrdbourke/tensorflow-deep-learning/blob/main/06_transfer_learning_in_tensorflow_part_3_scaling_up.ipynb

 

 

Part 3 - Zero shot transfer learning in colab

Showcase zero shot transfer learning with CLIP model 

Hint : https://towardsdatascience.com/how-to-try-clip-openais-zero-shot-image-classifier-439d75a34d6b (and associated colab)Links to an external site.

Showcase transfer learning using state of art models from tfhub (Eg: use bigtransfer for example) using tfhub

Hint : https://keras.io/examples/vision/bit/Links to an external site. or flowers data set eg : https://www.tensorflow.org/tutorials/images/transfer_learning_with_hub

### Part 01 Description

Write simple colabs to illustrate various data augmentation and generalization techniques (with A/B tests).
Write in tensorflow.

a. l1 l2

b. dropout

c. earlystop

d. montecarlo dropout

e. various initializations and when to use what

f. batch norm

g. custsom dropout, custom regularization

h. using callbacks and tensorboard

i. Using keras tuner

j. use keras cv data augmentation

k. Data Augmentation and Classification for Image

L. FastAI Data Augmentation Capabilities

### Part 02

Write a colab/colabs where you use advanced Keras deep learning constructs and concepts.

Please ensure you use the links provided for hints as examples. Use your own creativity. Properly annotate your colab/colabs appropriately and write proper explanation and description. Properly demonstrate each of these aspects with either individual colabs or one colab having all these.

A. User custom learning rate scheduler (one cycler scheduler example)

B. Use custom dropout (MCAlphaDropout section)

C. Use custom normalization (MaxNormDense section)

D. Use tensorboard (see links)

E. Use custom loss function (HuberLoss section)

F. Use custom activation function, initializer regularizer and kernel weight constraint (sections leaky_relu, my_glorot_initializer, MyL1Regularizer, my_positive_weights)

G. Use custom metric (HuberMetric section)

H. Use custom layers (Sections: exponential_layer, MyDense, AddGaussianNoise, LayerNormalization)

I. Use custom model (ResidualRegressor and ResidualBlock sections)

J. Custom optimizer (MyMomentumOptimizer sections)

K. Custom Training Loop  

## Assignment Deliverables

Please see below for the list of deliverables that have been submitted for this assignment.
Please note that all deliverables are under the `assignment_07` folder.

1. `assignment_07/CMPE258_Assignment07_Part01.ipynb`: Google Colab for Part 01 portion of assignment.
2. `assignment_07/CMPE258_Assignment07_Part02.ipynb`: Google Colab for Part 02 portion of assignment.
3. `assignment_07/CMPE258_Assignment07_Part03.ipynb`: Google Colab for Part 03 portion of assignment.
4. `assignment_07/README.md`: Markdown file that contains the following:
   - Assignment Description
   - Assignment Deliverables
   - References Used

## References Used

Part 1 References:
1. [Deep Vision with CNN](https://docs.google.com/presentation/d/1UxtHDwjViC7VpSb0zB-kajGQ-TwznQmc-7LsbHRfO3s/edit#slide=id.p)
2. [Contrastive loss for supervised classification](https://towardsdatascience.com/contrastive-loss-for-supervised-classification-224ae35692e7)
3. [Supervised Contrastive Learning](https://keras.io/examples/vision/supervised-contrastive-learning/)

Part 2 References:
TODO

Part 3 References:
TODO
