
## Image Classification

- This repo contains preparation material for TensorFlow Developer Certification
- ```tf.keras.utils.image_dataset_from_directory```is used instead of the deprecated ```preprocessing.image.ImageDataGenerator``` in the below examples
- Tensorboard is used to visualize model's loss and accuracy metrics during hyperparameter tuning
- Image corruption is checked in DogsVsCats dataset using JPEG's JFIF header check and libraries (```PIL.Image```, ```cv2```, ```wand```)

### Binary image classification :

- [Dogs or Cats](https://github.com/resh22an/computer-vision/blob/add42633516764693e8bbe8eea0ba1a912bd0929/binary-image-classification/DogsVsCats.ipynb) - Classify images as Cats or Dogs
- [Horses or Humans](https://github.com/resh22an/computer-vision/blob/add42633516764693e8bbe8eea0ba1a912bd0929/binary-image-classification/HorsesHumans.ipynb) - Classify images as Horses or Humans
- [Happy or Sad](https://github.com/resh22an/computer-vision/blob/add42633516764693e8bbe8eea0ba1a912bd0929/binary-image-classification/HappySad.ipynb) - Classify the emoji-like faces as Happy or Sad
    

### Multi class image classification :

  - [Fashion MNIST](ImageClassification/MultiClass/FashionMNIST.py) - Recognize different items of clothing, trained from a dataset containing 10 different types
