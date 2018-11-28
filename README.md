# Dogs Vs Cats(CNN Experimentation)
--------------------------------------
**Dataset**

Link: https://www.kaggle.com/c/dogs-vs-cats/data

---------------------------------------
**Description**


The original dataset from Kaggle contains 25000 training images. For experimentation purposes I have extracted 2000 images from the original dataset out of which 1000 images(each of Cats & Dogs) consists of Training data and 500(each of Cats & Dogs) images consists of Validation data.

-----------------------------------------

**Inspiration**


High model accuracy can usually be achieved with big amounts of data. I personally believe that restricted constraints and less amount of data can foster great algorithmic creativity and derive better results. Therefore all the experiments in this repository is not done on the original 25000 images downloaded from kaggle. Instead I have taken 2000 images(1000 each of cats and dogs) for the training-set and 500 images each of validation-set and test-set



-----------------------------------------

**The Road-Map of the experimentation is as follows(Ongoing experiment):**

1. Constructing a basic Convolutional nework from scratch. Link: https://github.com/vishal-burman/Dogs_vs_Cats/tree/master/ConvNet%20from%20Scratch

2. Adding Data-Augmentaion and Dropout techniques to reduce overfitting. Link: https://github.com/vishal-burman/Dogs_vs_Cats-CNN-Experimentation-/tree/master/ConvNet%20with%20DA%20-%20Dropout

3. Training our split-small dataset on a pretrained network. Link:https://github.com/vishal-burman/Dogs_vs_Cats-CNN-Experimentation-/tree/master/ConvNet_Pretrained

4. Fine-tuning our pretrained network to improve accuracy. Link:https://github.com/vishal-burman/Dogs_vs_Cats-CNN-Experimentation-/tree/master/ConvNet_Pretrained_FineTuning

5. Visualizing the intermediate activations of VGG16 model. Link:https://github.com/vishal-burman/Dogs_vs_Cats-CNN-Experimentation-/tree/master/Visualize_Intermediate_Activations

------------------------------------------

**Requirements:**
1. keras
2. tensorflow-gpu
3. jupyter
4. numpy
5. matplotlib
