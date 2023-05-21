1. If X is the standard notation for the input to an RNN, what are the standard notations for the outputs?

    - [ ] Y
    - [ ] H
    - [x] Y(hat) and H
    - [ ] H(hat) and Y

2. What is a sequence to vector if an RNN has 30 cells numbered 0 to 29

    - [ ] The total Y(hat) for all cells
    - [ ] The average Y(hat) for all 30 cells
    - [x] The Y(hat) for the last cell
    - [ ] The Y(hat) for the first cell

3. What does a Lambda layer in a neural network do?

    - [ ] Pauses training without a callback
    - [x] Allows you to execute arbitrary code while training
    - [ ] There are no Lambda layers in a neural network
    - [ ] Changes the shape of the input or output data

4. What does the axis parameter of tf.expand_dims do?

    - [ ] Defines if the tensor is X or Y
    - [ ] Defines the axis around which to expand the dimensions
    - [ ] Defines the dimension index to remove when you expand the tensor
    - [x] Defines the dimension index at which you will expand the shape of the tensor

5. A new loss function was introduced in this module, named after a famous statistician. What is it called?

    - [ ] Hawking loss
    - [x] Huber loss
    - [ ] Hyatt loss
    - [ ] Hubble loss

6. What’s the primary difference between a simple RNN and an LSTM

    - [x] In addition to the H output, LSTMs have a cell state that runs across all cells
    - [ ] LSTMs have multiple outputs, RNNs have a single one
    - [ ] LSTMs have a single output, RNNs have multiple
    - [ ] In addition to the H output, RNNs have a cell state that runs across all cells

7. If you want to clear out all temporary variables that tensorflow might have from previous sessions, what code do you run?

    - [ ] tf.cache.backend.clear_session()
    - [ ] tf.cache.clear_session()
    - [ ] tf.keras.clear_session
    - [x] tf.keras.backend.clear_session() 
   
8. What happens if you define a neural network with these two layers?
tf.keras.layers.Bidirectional(tf.keras.layers.LSTM(32)),
tf.keras.layers.Bidirectional(tf.keras.layers.LSTM(32)),
tf.keras.layers.Dense(1),

    - [x] Your model will fail because you need return_sequences=True after the first LSTM layer
    - [ ] Your model will fail because you need return_sequences=True after each LSTM layer
    - [ ] Your model will compile and run correctly
    - [ ] Your model will fail because you have the same number of cells in each LSTM
