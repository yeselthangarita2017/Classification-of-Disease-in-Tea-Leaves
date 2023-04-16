# Classification-of-Tea-Leaves--NMA-Deep-Learning-2022
This analysis was done as the final project for the [2022 Neuromatch Academy-Deep Learning worlwide summer course](https://deeplearning.neuromatch.io/tutorials/intro.html).

## Our Task 
Tea is one of the most popular drinks in the world, second only to water. Originating in China contains medical properties and health care functions, and is quite effective in enhancing human immunity. 

We performed experiments using VGG and Resnet18 neural networks with transfer learning(TL) and data augmentation(DA) on RGB and gray scale images with a split of 70% training, 15% validation, and 15% test to classify tea leaf diseases. 

## Main Question to Answer
Can we discover what model helps the most to identify diseases in tea leaves based on color and shape of 7 classes of tea leaves?

## Dataset
This [disease in tea leaves dataset](https://www.kaggle.com/datasets/shashwatwork/identifying-disease-in-tea-leafs) is from Kaggle. There are a total of 886 images of tea leaves. 
<br>
It contains 7 classes of common tea leaf diseases and 1 class of healthy leaves.

## Methodology

* Led a team of 7 where we exchanged ideas using the [Neuromatch Academy-DL 2022 course project Github: Daily guide for projects](https://deeplearning.neuromatch.io/projects/docs/project_guidance.html) as a guide. 
* Each member shared an idea of a dataset and model
* We compared options
* Selected the most voted project

## Computer Vision Model Methodology

* Transfer learning using Neuromatch Academy-DL 2022 course [project example for transfer learning: Learning about synapses from electron-microscopy data](https://deeplearning.neuromatch.io/projects/ComputerVision/slides.html).
* Data Augmentation
* Modeling and experimentation
* Determined the variables and hyperparameters
* Planning/drafting the model
* Implementing the model
* Testing and evaluating the model
* Publishing the model

## Insight 1

From some global metrics, we found out that the highest recall value was 0.92 for the resnet18(RGB) + DA + TL when using the test dataset.

## Insight 2

Also, we discovered that the Alga leaf disease class showed the highest accuracy among the 7 classes for the VGG RGB network whereas the gray light class showed the highest accuracy for the Resnet18(RGB) + DA + TL.

## Insight 3

Lastly, we found that 2 classes had the highest accuracy in both models.

The best results were obtained using restnet18 RGB with data augmentation and transfer learning. The hardest challenge I had was to persuade the team of 4 engineers and scientists to get to the goal in such a short period of time.


## Conclusions 

In conclusion, the best results were obtained using restnet18 RGB with data augmentation and transfer learning. 

# Acknowledgements 

We want to thank our mentors, Guillaume Etter(Research Associate at CHU Sainte-Justine Research Centre) and Farrokh Karimi(Researcher at Institute for Research in Fundamental Sciences (IPM)), our pod TA Israel Chaparro-Cruz(Research Assistant at Universidad Nacional Jorge Basadre Grohmann), and NMA organizers for this terrific experience!
