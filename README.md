# Food Classification with Deep Learning in Pytorch
## Unlabeled Food Image based Nearby Restaurant Recommendation System

- image classification term project 2023-Second Semester
- [proposal](https://github.com/finallyupper/food_classficiation/blob/main/others/Group4_proposal.pdf) [proposal_ppt](https://github.com/finallyupper/food_classficiation/blob/main/others/Group4_proposal_presentation.pdf)
- [final presentation](https://github.com/finallyupper/food_classficiation/blob/main/others/Group4_presentation.pdf)
- [report](https://github.com/finallyupper/food_classficiation/blob/main/others/Group4_report.pdf) (CVPR format)
- [preprocessings](https://github.com/finallyupper/food_classficiation/tree/main/src/data_preprocessing)
- [model code (DenseNet161 ver.)](https://github.com/finallyupper/food_classficiation/tree/main/src/model)

### Used pre-trained models ###
1. VGG16
2. ResNet50
3. DenseNet161
4. InceptonV3
-> Transfer Learning

### Problem Definition ###
When you have a craving for a specific food and find nearby restaurants for it, 
you must know the name of food if you use Naver Map or Kakaomap.
This poses a clear limitation when you only have an image without knowing the name of food.
Therefore, we propose a service that can analyze the given image to identify the 
name or type of food and recommend nearby restaurants that serve that food.
  
### Pipeline ###
![pipeline](https://github.com/finallyupper/food_classficiation/blob/main/others/img1_pipeline.png)
  
### Results ###
![evaluation](https://github.com/finallyupper/food_classficiation/blob/main/others/img2_graphs.png)
![performance_table](https://github.com/finallyupper/food_classficiation/blob/main/others/img3_table.png)

### Info ###
- Yoojin Oh (Ewha Womans University, Dept of AI, Sophomore)
- Written in 2023-12-18
- tools : colab gpu, pytorch, wandb
