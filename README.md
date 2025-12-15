# chandushree-1CD22AI008
#1. CNN – Lily vs Rose Flower Classification
 Original Code
   Faculty provided a CNN program to classify flowers from the tf_flowers dataset.
 Changes Made
  1. Reduced convolution filters to lower model complexity.
  2. Added image normalization for better training stability.
  3. Removed unnecessary print statements.
  4. Improved code readability with comments.
  5. Ensured compatibility with Google Colab.
 Reason for Changes
 - Reduce overfitting
 - Improve training speed
 - Make the code easier to understand
 - 
#2. Reinforcement Learning – Graph Navigation

 Original Code
   Basic reinforcement learning implementation on a graph was provided.
Changes Made
   1. Added comments to explain each step.
   2. Improved variable naming for clarity.
   3. Optimized reward matrix initialization.
   4. Removed unused imports.
 Reason for Changes
  - Better readability
  - Easier debugging
  - Improved learning efficienc
  - 
#3. LSTM

 i.Reduced Number of LSTM Units
 model.add(LSTM(4, input_shape=(1, time_step)))
 Reduced LSTM neurons from 10 → 4

 ii.Decreases trainable parameters
 1.Speeds up training on small time-series datasets
 2.Added Dropout for Regularization
 3.model.add(Dropout(0.2))
 4.Dropout rate of 0.2
 5. Helps prevent overfitting
 6. mproves model generalization

 iii.Reduced Training Epochs
 model.fit(trainX, trainY, epochs=20, batch_size=1)
 Epochs reduced from 50 → 20
 Faster convergence
 Avoids overtraining

 iv. Final Modified LSTM Architecture
 model = Sequential()
 model.add(LSTM(4, input_shape=(1, time_step)))
 model.add(Dropout(0.2))
 model.add(Dense(1))

#4. Tic-Tac-Toe Reinforcement Learning

  i. Objective
  To train an AI agent that learns to play Tic-Tac-Toe optimally using reinforcement learning and later play against a human.

  ii. Updates Made
  1.Fixed incorrect player symbol initialization.
  2. Improved reward strategy for win, loss, and draw.
  3. Prevented infinite loops during gameplay.
  4. Limited output moves for controlled testing.
  5. Added clean ASCII board visualization.
  6. Implemented policy saving and loading using pickle.

  iii. Technologies Used
  Python
  NumPy
  Reinforcement Learning

#5. AlexNet CNN (Image Classification)
   
  i. Objective
  To implement the AlexNet architecture for image classification and optimize it by reducing layers and parameters.

  ii. Updates Made
 1. Reduced convolutional layers to lower complexity.
 2. Reduced number of filters to decrease total parameters.
 3. Simplified fully connected layers.
 4.  Maintained AlexNet core architecture.
 5.  Improved TensorFlow 2.x compatibility.
 
  iii. Technologies Used
  Python
  TensorFlow / Keras
  CNN (Convolutional Neural Networks)





Total params: 149




Executed notebook in googlecolab -https://colab.research.google.com/drive/1O-NX_7ONSzQS9omXvbdzqzEz9cl3UrW8?usp=sharing
