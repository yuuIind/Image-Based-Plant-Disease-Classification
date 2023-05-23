# Image-Based-Plant-Disease-Classification
Inception V3 Based Plant Disease Classification Model

Course Project for EE468 Spring 2023

Hakan Taştan, Eray Kuru, Yaseming Köse

Model:

- 39 Classes
- input_shape = (256, 256, 3)
- Total params: 47,520,711
- Trainable params: 38,545,447
- Non-trainable params: 8,975,264
- loss = 'categorical_crossentropy'
- Adam Optimizer
- Learning rate = 0.0001 for first 81 epochs
- Learning rate = 0.00001 after epoch 81
- batch_size = 32
- Trained for 111 epochs
- Data is randomly splitted into train/validation/test
- train/validation/test => 60/20/20
- train: 31231 images belonging to 39 classes.
- validation: 10407 images belonging to 39 classes.
- test: 10444 images belonging to 39 classes.
- Train Set -> 99.16% accuracy
- Validation Set -> 98.32% accuracy
- Test Set -> 98.15% accuracy
- Seperate Test for evaluation 97.82% accuracy on 3352 images

