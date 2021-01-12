# Fruits classification
* Perform in [google colab](https://colab.research.google.com/drive/1bR4GuIwe8abl4YRvf3uX8VcOw5Ecb4Xu?usp=sharing) and you can download my results in [here](https://drive.google.com/drive/folders/1--ur2dQm4vzfVWxVGwXwKlR0Xb2ZMwxh?usp=sharing).
* Dataset [fruits](https://www.kaggle.com/moltean/fruits) in kaggle 
  - Dataset have 131 class with 360 degrees
* I perform campares transfer learning and training from scratch with model VGG16.
  - The results of training from scratch had high performance with Accuracy 99% in validation set and 98% in test set (Cause the layers extract feature of pre-train model vgg not suitable our data).
  - Some fruits have quite similar color and shapes, which has caused slight confusion. 
  ex: ![results-inference](link)


  
