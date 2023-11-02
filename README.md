# Next-Word-Generator


## Overview

- This project focuses on training a deep learning model, specifically an LSTM (Long Short-Term Memory) neural network.
- The model's primary function is to predict the next word in a sequence based on a three-word input.
- It utilizes a substantial amount of text data for training and leverages the inherent context and patterns within the text to provide accurate and correct word predictions.

## Training Set

- Our training set consists of the text from the renowned book ["Pride and Prejudice" by Jane Austen](https://www.gutenberg.org/ebooks/1342). This classic work of literature offers a diverse and captivating source of textual data for model training.

## Getting Started

To run this project in Google Colab and train the LSTM model, follow these steps:

1. Open Google Colab and upload the ["NWP"](NWP.ipynb) file to access more significant GPU resources.

2. Change the runtime type to either TPU or T4 GPU for enhanced performance.

3. Start running the cells in the provided notebook.

4. In the second cell, the code prompts for input, and you need to upload the ["pap.txt"](pap.txt) file, which serves as the training dataset for the model.

5. Execute the code, which includes training the LSTM model. The training duration may vary based on your system and network capabilities.

6. If you find that the model's accuracy is not sufficient, consider adjusting the number of training epochs and batch size.

7. After training, the model can generate predictions based on a three-word input, providing a predicted word as output.

8. To exit the code, simply set the exit condition to 0.

## Note

- The execution time for training the LSTM model can vary depending on the system and network resources available.

## Conclusion

This project demonstrates the potential of Natural Language Processing (NLP) in language modeling and text generation. The LSTM neural network is a valuable tool for tasks such as auto-suggestion and predictive text generation in various applications, leveraging the power of deep learning and neural networks to enhance text-based capabilities.

Feel free to adapt and expand upon this readme file to provide more context and details about your project.
