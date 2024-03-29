## Malaria Parasite Detection

This is a flask app which predicts whether the given image(blood sample) contains a malaria parasite or not. I have used the concept of transfer learning in this project. I used the pre-trained [VGG-16 model architecture](https://neurohive.io/en/popular-networks/vgg16/) which was trained with ImageNet dataset. I trained this model (by freezing the in-between convolutional layers having previously trained weights) on [Malaria Cell Images Dataset](https://www.kaggle.com/datasets/iarunava/cell-images-for-detecting-malaria) from Kaggle competition. I am able to achieve around 92% accuracy on the validation dataset.

---
### A Glimpse of the app 😎
Homepage
![home](https://github.com/dayosalam/stuff-done/blob/main/Malria-Detector/Screenshot%20from%20app/1.png)
<br>

Upload page
![upload](https://github.com/dayosalam/stuff-done/blob/main/Malria-Detector/Screenshot%20from%20app/2.png)
<br>

Prediction Page
![prediction](https://github.com/dayosalam/stuff-done/blob/main/Malria-Detector/Screenshot%20from%20app/3.png)

