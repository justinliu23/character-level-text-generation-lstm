# character-level-text-generation-lstm

 ## Dependencies

The following Python libraries are required for the project:

- `numpy`: For numerical computations.
- `random`: For generating random values, particularly for sampling.
- `copy`: To create deep copies of objects.
- `pprint`: For pretty-printing Python data structures.
- `utils`: Custom utility functions (this should be available in the project repository).

## Configuration

The project includes several configurable parameters, which can be adjusted in the notebook to optimize performance or alter the model's behavior:

- **Gradient Clipping**: To prevent exploding gradients, the project includes a mechanism to clip gradients during backpropagation. The maximum value for gradient clipping can be adjusted in the corresponding function.
  
- **Model Parameters**: The learning rate, number of iterations, and hidden units in the RNN can be configured to explore different training outcomes.

- **Sampling**: The sampling process involves generating text by predicting one character at a time. The sampling function can be adjusted to change the diversity of the generated text.

These configurations are primarily managed within the Jupyter notebook, where you can modify and experiment with different settings to achieve the desired results.
