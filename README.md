# Classify-Radio-Signals-in-Space-using-Keras
Designed a convolutional neural network with 2 convolution layers and 1 fully connected layer to predict four radio signal types in space using Keras on the SETI(The Search for ExtraTerrestrial Intelligence) dataset.

The various tasks completed in this project include:
- Task 1: Import Libaries<br>
- Import essential modules and helper functions from NumPy, Matplotlib, and Keras.<br>

- Task 2: Load and Preprocess SETI Data<br>
- Display 2D spectrograms using Matplotlib.<br>
- Reshape the input data with NumPy.<br>

- Task 3: Create Training and Validation Data Generators<br>
Generate batches of tensor image data with real-time data augmentation.<br>
Specify paths to training and validation image directories and generates batches of augmented data.<br>

- Task 4: Create a Convolutional Neural Network (CNN) Model<br>
Design a convolutional neural network with 2 convolution layers and 1 fully connected layers to predict four signal types.<br>
Use Adam as the optimizer, categorical crossentropy as the loss function, and accuracy as the evaluation metric.<br>

- Task 5: Learning Rate Scheduling and Compile the Model<br>
When training a model, it is often recommended to lower the learning rate as the training progresses.<br>
Apply an exponential decay function to the provided initial learning rate.<br>

- Task 6: Train the Model<br>
Train the CNN by invoking the model.fit() method.<br>
Use ModelCheckpoint() to save the weights associated with the higher validation accuracy after every epoch<br>
Display live training loss and accuracy plots in Jupyter Notebook using livelossplot.<br>

- Task 7: Evaluate the Model<br>
Evaluate the CNN by invoking the model.fit() method.<br>
Obtain the classification report to note the precision and recall of your classifier.<br>
