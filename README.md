# Image_Captioning
##  Generate Description of a given image with Encoder Decoder architecture ##
### Data set ###
Image data is downloaded from (https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_Dataset.zip)
Text data is downloaded from(https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_text.zip)

### Libraries used ###
Tensor Flow, Keras, NLTK, Regex, Sklearn, Matplotlib, Numpy and Pandas.

### Text Preprocessing ###
Descriptions are processed using regex, sentences with suitable length are selected.

### Image Preprocessing ###
All the images are converted to vectors of suitable dimensions and passed into The Xception model to generate image vectors of dimension 2048 for each image.

### Model ###
Encoder Decoder architecture is used.

![alt text](https://raw.githubusercontent.com/yunjey/pytorch-tutorial/master/tutorials/03-advanced/image_captioning/png/model.png)
 
Image vector is passed as hidden state and cell state for the first LSTM cell in Decoder unit along with the text input.
Teacher forcing method is used to train the model. 

Example outputs are generated for evaluation





