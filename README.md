## Malaria Parasite Detection

This is a flask app which predicts whether the given image(blood sample) contains a malaria parasite or not. I have used the concept of transfer learning in this project. I used the pre-trained [VGG-16 model architecture](https://neurohive.io/en/popular-networks/vgg16/) which was trained with ImageNet dataset. I trained this model (by freezing the in-between convolutional layers having previously trained weights) on [Cat-vs-Dog dataset](https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition) from Kaggle competition. I am able to achieve around 92% accuracy on the validation dataset.

---
### A Glimpse of the app 😎
Homepage
![home](https://github.com/sudeeep885/Cat-vs-Dog-Flask-web-app/blob/master/screenshots/home.jpg?raw=true)
<br>

Upload page
![upload](https://github.com/sudeeep885/Cat-vs-Dog-Flask-web-app/blob/master/screenshots/upload.jpg?raw=true)
<br>

Prediction Page
![prediction](https://github.com/sudeeep885/Cat-vs-Dog-Flask-web-app/blob/master/screenshots/prediction.jpg?raw=true)
