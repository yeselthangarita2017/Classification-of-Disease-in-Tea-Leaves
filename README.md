# Classification-of-Tea-Leaves--NMA-DL-2022
Final project for the 2022 Neuromatch Academy-Deep Learning course

Computer Vision:
<br>
Building models to classify tea leaf diseases. Tea is one of the most popular drinks in the world, second only to water. Originating in China, contains medical properties and health care functions, and is quite effective in enhancing human immunity.

# Problematic

At present, the diagnosis of tea leaf diseases relies on the manual method, making results largely subjective and sometimes inaccurate.
Due to machine learning and image processing methods that do not require manual intervention have been widely used in the detection and identification of plant diseases.

# Dataset

This dataset is from Kaggle. There are a total of 886 images of tea leaves. 
<br>
It contains 7 classes of common tea leaf diseases and 1 class of healthy leaves.

# Contributions 

My contributions and responsabilities were 

* Organized topic ideas
* Guided project direction and topic selection
* Executed project design and logic 
* Investigated and assessed examples to use for transfer learning 
* Virtually presented results as part of a team to a medium size audience 

# Experiments

We performed experiments using VGG and Resnet18 neural networks with transfer learning and data augmentation on RGB and gray scale images with a split of 70% training, 15% validation, and 15% test. We used early stopping in all the experiments. 

# Results 

From some global metrics, we found out that the highest recall value was 0.92 for the resnet18(RGB) + DA + TL when using the test dataset. 
<br>
Also, we discovered that the Alga leaf disease class showed the highest accuracy among the 7 classes for the VGG RGB network whereas the gray light class showed the highest accuracy for the Resnet18(RGB) + DA + TL. 
<br>
Lastly, we found that 2 classes had the highest accuracy in both models

# Conclusions 

In conclusion, the best results were obtained using restnet18 RGB with data augmentation and transfer learning. 

# Acknowledgements 

We want to thank our mentors, Guillaume Etter(Research Associate at CHU Sainte-Justine Research Centre) and Farrokh Karimi(Researcher at Institute for Research in Fundamental Sciences (IPM)), our pod TA Israel Chaparro-Cruz(Research Assistant at Universidad Nacional Jorge Basadre Grohmann), and NMA organizers for this terrific experience!

# References 

1. Kaggle dataset: [Identifying Disease in Tea leaves | Kaggle](https://www.kaggle.com/datasets/shashwatwork/identifying-disease-in-tea-leafs)
2. Neuromatch Academy-DL 2022 course project example for transfer learning: [Learning about synapses from electron-microscopy data](https://deeplearning.neuromatch.io/projects/ComputerVision/slides.html)
3. Neuromatch Academy-DL 2022 course project Github: [Daily guide for projects](https://deeplearning.neuromatch.io/projects/docs/project_guidance.html)


**MUST CHECK GRAMMAR AND STRUCTURE**


