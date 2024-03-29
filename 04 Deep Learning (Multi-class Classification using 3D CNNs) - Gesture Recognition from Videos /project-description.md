  - In this project, a manufacturer of Smart TVs wishes to introduce a new product feature whereby a TV sensor captures and processes its user's hand gestures in real time for certain remote control tasks. Given a labelled training dataset consisting of over 650 videos (each video consisting of a sequence of 30 images) of human hand gestures, my task was to develop a model that learns to predict the correct label corresponding to a new hand gesture video
  - I was able to train a model delivering 67% accuracy on a validation dataset consisting of 100 videos using a 3D-Convolutional Neural Network (3D-CNN)
  - The files inside this folder include:
    - A sub-folder consisting of both training and validation videos and labels,
    - A Jupyter notebook covering data (image) pre-processing steps, batch generation steps, model (3D-CNN) construction and fitting steps (Keras),
    - A copy of the model with best hyperparameters I encountered (best_model.h5), and
    - Some notes on architectural decisions (some_notes.pdf)