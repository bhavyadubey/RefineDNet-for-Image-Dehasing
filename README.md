# RefineDNet-for-Image-Dehasing

RefineDNet is a two-stage dehazing framework which can be weakly supervised using real-world unpaired images. That is, the training set
never requires paired hazy and haze-free images coming from the same scene. In the first stage, it adopts DCP to restore visibility of the 
input hazy image.In the second stage, it improves the realness of preliminary results from the first stage via CNNs.


I've developed an streamlit website(local-host) which removes the haze of an images on the web with option to tune the extent of dehazing.
Haze-free images of many vision systems and algorithms,and thus single image dehazing is of paramount importance in computer vision. In this 
field, prior-basedmethods have achieved initial success. However, they often introduce unneces artifacts to outputs because their priors can 
hardly fit all situations.


Dehazed and Haze image Example:

![image](https://user-images.githubusercontent.com/42567661/151776687-f23f5558-f16b-483a-9d19-f46b315f3ece.png)


Webpage preview for Dehazing an Image:

![image](https://user-images.githubusercontent.com/42567661/151776931-2e639da4-c83a-4c6c-8853-90ff364a2f57.png)

This takes an Image of 200kb , and format of .jpeg and .png , which then dehazes it , which also allows the transmission of an image between 0.1 to 0.9 , then 
return the modified image .

**Before and After Dehazing**


![image](https://user-images.githubusercontent.com/42567661/151780162-b527c3cf-6f19-4a55-9167-d3f01d93527a.png)


I Propose a simple yet effective two-stage weakly supervised dehazing framework RefineDNet for two purposes, i.e., merging the merits of 
prior-based and learning-based methods and addressing the lack of paired training images. To get more qualified results, I also added 
a perceptual fusion strategy to fuse different outputs of RefineDNet.











