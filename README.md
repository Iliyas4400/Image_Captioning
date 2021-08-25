# Image_Captioning
##  Generate Description of a given image with encoder decoder architecture ##
### Data set ###
Image data is downloaded from (https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_Dataset.zip)
Text data is downloaded from(https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_text.zip)

### Libraries used ###
Tensor Flow, Keras, NLTK, Regex, Sklearn, Matplotlib, Numpy and Pandas.

### Text Preprocessing ###
Descriptions are processed using regex, sentences with suitable length are selected.

### Image Preprocessing ###
All the images are converted to vectors of suitable dimensions and passed into The Xception model to generate image vectors for each image.

### Model ###
Encoder Decoder model is used with teacher forcing technique.
![alt text](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/11/working-of-Deep-CNN-Python-project.png)
 








