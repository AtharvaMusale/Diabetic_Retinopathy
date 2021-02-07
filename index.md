# Diabetic_Retinopathy
![image](https://user-images.githubusercontent.com/46114095/107138730-11a65600-693c-11eb-9b37-f3ac3c1753cf.png)

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
<img width="711" alt="Screenshot 2021-01-27 at 10 13 59 AM" src="https://user-images.githubusercontent.com/46114095/105944054-8e0d7f00-6088-11eb-964b-d4e947a593d0.png">
<img width="343" alt="Screenshot 2021-01-27 at 10 14 11 AM" src="https://user-images.githubusercontent.com/46114095/105944064-936ac980-6088-11eb-8a14-a8d23b100c68.png">


## Results - 
<img width="438" alt="Screenshot 2021-01-27 at 9 35 35 AM" src="https://user-images.githubusercontent.com/46114095/105941975-919f0700-6084-11eb-9f5a-5a27ef5b7009.png">
