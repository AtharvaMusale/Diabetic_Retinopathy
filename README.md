# Diabetic_Retinopathy
# Problem definition - 
The images of retina fundus are provided. We are given the corresponding labels with respect to each image. Each label defines the stage of diabetic retinopathy for an retina image. The stages are as follows
0- No DR
1- Mild
2- Moderate
3- Severe
4- Proliferate
We can think of this project as multiclass classification. 
## Dataset - 
The data which was used was from APTOS 2019 Blindness Detection Challenge on Kaggle
### https://www.kaggle.com/c/aptos2019-blindness-detection/data 

## Model Used-
For solving this problem I have used Densenet 121 as a transfer learning baseline.
Learning Rate used was 0.005.
Optimizer used is Adam
Loss Function which was used is categorical crossentropy
We are also keeping the Kappa Score as a metric

## Results - 
<img width="438" alt="Screenshot 2021-01-27 at 9 35 35 AM" src="https://user-images.githubusercontent.com/46114095/105941975-919f0700-6084-11eb-9f5a-5a27ef5b7009.png">
