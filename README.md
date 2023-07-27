# Scam_detection
**Detecting Scam/Fraud messages, emails, job posting, and recruitment posting messages using pre-trained BERT Model**

It's a **Scam(fraud) classification** Project in which we have different types of datasets to integrate and then classify a specific message or an email as a fraud(scam) or real message.
The Datasets are first pre-processed and then integrated to form a single file containing nearly 40000 instances(observations) and their corresponding labels. The text input columns are first preprocessed and then passed from a pipeline to get the embedding and tokenizations of the input text features before passing them to the input model for the training process. 

The preprocessed Dataset is then split into train, validation, and testing datasets with a 70:10:20 ratio. (Keep in mind the Class balance splitting of the dataset).

A pretrained Transformer model named **BERT**( (Bidirectional Encoder Representations from Transformers) is a popular natural language processing (NLP) model, is used to train the model and it can classify the preprocessed splitted training dataset into Real/ Fake classes. 

The model is evaluated on the testing dataset as well as the unseen dataset to visualize the model performance in the form of confusion matric and heatmap. 

The main code .pyfile and notebook both are uploaded to this repository.
