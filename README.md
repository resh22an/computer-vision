
## Image Classification

- This repo contains preparation material for [TensorFlow Developer Certification](https://www.tensorflow.org/certificate) (Content as in Coursera's [DeepLearning.AI TensorFlow Developer](https://coursera.org/professional-certificates/tensorflow-in-practice) course)
- ```tf.keras.utils.image_dataset_from_directory```is used instead of the deprecated ```preprocessing.image.ImageDataGenerator``` in the below projects
- Tensorboard is used to visualize model's loss and accuracy metrics during hyperparameter tuning
- Image corruption is checked in DogsVsCats, RockPaperScissors datasets using JPEG's JFIF header check and libraries (```PIL.Image```, ```cv2```, ```wand```)

### Binary image classification :

- [Dogs or Cats](https://github.com/resh22an/computer-vision/blob/add42633516764693e8bbe8eea0ba1a912bd0929/binary-image-classification/DogsVsCats.ipynb) - Classify images as Cats or Dogs
- [Transfer Learning - Dogs or Cats](https://github.com/resh22an/computer-vision/blob/3fd3d2ed617dc09b044e26c82a1be98e5faa7ad2/binary-image-classification/DogsCats_TransferLearning.ipynb) - Using InceptionV3
- [Horses or Humans](https://github.com/resh22an/computer-vision/blob/add42633516764693e8bbe8eea0ba1a912bd0929/binary-image-classification/HorsesHumans.ipynb) - Classify images as Horses or Humans
- [Happy or Sad](https://github.com/resh22an/computer-vision/blob/add42633516764693e8bbe8eea0ba1a912bd0929/binary-image-classification/HappySad.ipynb) - Classify the emoji-like faces as Happy or Sad
    

### Multi class image classification :

- [Rock Paper Scissors](https://github.com/resh22an/computer-vision/blob/43995b695cf161e15e6f6e53157c22a01cfe3319/multiclass-image-classification/RockPaperScissors.ipynb) - Recognize if the hand image is in rock or paper or scissors pose
- [Sign language MNIST](https://github.com/resh22an/computer-vision/blob/1114e369647df6bb34cc03d8fab759b3a46f85d4/multiclass-image-classification/SignLanguageMNIST.ipynb) - Classify each image as the letter it represents
- [Fashion MNIST](https://github.com/resh22an/computer-vision/blob/43995b695cf161e15e6f6e53157c22a01cfe3319/multiclass-image-classification/FashionMNIST.ipynb) - Recognize different items of clothing, trained from a dataset containing 10 different types
