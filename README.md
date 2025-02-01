
# Simple Chatbot using Python and TensorFlow

This project is a simple chatbot implemented using Python and TensorFlow. The chatbot is trained to recognize various intents and respond accordingly. The intents and responses are defined in a JSON file, and the model is trained using a neural network.

## Project Structure
```
.gitignore         # Specifies files and directories to be ignored by Git
launch.json        # Configuration for debugging in Visual Studio Code
cb.py             # Main script to run the chatbot
chatbot_model.h5  # Trained model file
classes.pkl       # Pickle file containing the classes (intents)
intents.json      # JSON file defining the intents and responses
training.ipynb    # Jupyter notebook used for training the model
words.pkl         # Pickle file containing the words
```

## Requirements
- Python 3.12.5
- TensorFlow
- NLTK
- NumPy

## Setup
### Clone the repository:
```sh
git clone https://github.com/your-repository/chatbot.git
cd chatbot
```
### Install the required packages:
```sh
pip install -r requirements.txt
```
### Download the NLTK data:
```python
import nltk
nltk.download('punkt')
nltk.download('wordnet')
```

## Training the Model
To train the model, open the `training.ipynb` notebook and run all the cells. This will preprocess the data, create the neural network, and train it. The trained model will be saved as `chatbot_model.h5`.

## Running the Chatbot
To run the chatbot, execute the `cb.py` script:
```sh
python cb.py
```
Type your messages to the chatbot in the console. To exit, type `exit`.

## Intents
The intents and responses are defined in the `intents.json` file. You can modify this file to add new intents or update existing ones.

## Acknowledgements
- TensorFlow
- NLTK
- NumPy


