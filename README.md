# Simple Chatbot using Python and TensorFlow

This project is a simple chatbot implemented using Python and TensorFlow. The chatbot is trained to recognize various intents and respond accordingly. The intents and responses are defined in a JSON file, and the model is trained using a neural network.

## Project Structure
```
.gitignore         
cb.py             
chatbot_model.h5  
intents.json     
training.ipynb    

```

## Requirements
- Python
- TensorFlow
- NLTK
- NumPy

## Setup
### Clone the repository:
```sh
git clone https://github.com/Abdullah-Masood-5/ChatBot.git
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

---
