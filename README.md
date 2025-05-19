# GENERATIVE_TEXT_MODEL
COMPANY: CODETECH IT SOLUTIONS

NAME: SRAVAN JANGAM

INTERN ID: CODF209

DOMAIN: Artificial Intelligence Markup Language

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH

In this project, I explored text generation using two deep learning-based language models: a Long Short-Term Memory (LSTM) model and the pre-trained GPT-2 model. The objective was to understand and compare how traditional sequence-based models and modern transformer-based models can generate human-like text given a prompt. This project combines the principles of deep learning, natural language processing (NLP), and sequence modeling to create coherent and contextually relevant text. The first part of the project involved implementing an LSTM-based text generator. LSTM is a type of recurrent neural network (RNN) that excels at learning long-term dependencies in sequences. I used Python with TensorFlow/Keras to build the model. The dataset used for training consisted of a text corpus that was preprocessed by converting all characters to lowercase, removing unnecessary characters, and generating input-output pairs. The text was then tokenized and divided into sequences of a fixed length. The LSTM model consisted of an embedding layer, one or more LSTM layers, and a dense output layer with softmax activation to predict the next word. The model was trained using categorical cross-entropy loss and the Adam optimizer. After training, the model was capable of generating new text by predicting one word at a time based on previous inputs. The generation process used a sliding window approach, where the output from each prediction was fed back as input for the next step. Temperature scaling was also used to control the randomness of predictions and generate more diverse outputs. In the second part of the project, I implemented text generation using the GPT-2 model, a transformer-based architecture developed by OpenAI. Unlike LSTMs, GPT-2 processes entire sequences in parallel using attention mechanisms and is pre-trained on a massive dataset, enabling it to generate much more fluent and contextually accurate text. I used the Hugging Face transformers library for easy access to GPT-2. By working with both models, I gained insights into the strengths and limitations of sequential RNN-based models and transformer architectures. The LSTM model required training from scratch and struggled with long-range dependencies, while GPT-2 leveraged transfer learning to produce impressive results with minimal setup.





OUTPUT:
