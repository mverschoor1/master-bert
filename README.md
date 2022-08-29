# master-bert
Leaking information from pre-trained BERT models, a study for the completion of an Artificial Intelligence Master of Science degree from the Vrije Universiteit Amsterdam.

This repository contains code written for the Master Thesis: "The Fragmented Nature of Privacy: A Study on Data Leakage from a Post-Trained BERT Model". 

- Author: M.S. Verschoor
- Supervisor: E. Herrewijnen
- Supervisor VU: D. van den Bert 

The aim of this project was to find out how much data leaks from a post-trained BERT model. In order to find out, a BERT model was post-trained on the IMDB dataset. The five most common attributes in the dataset were determined via Spacy's NER. Five different test datasets were created for these five attributes, where 15% of the occurrence of these entities was masked. The post-trained BERT model predicted the masks. Accuracy was calculated by defining how many of the masks were correctly predicted. 

The file 'train_model.ipynb' in the dir 'code_mlm_bert' contains the code for post-training the model. 
The file 'predict_dataset.ipynb' in the dir 'predict_masks' contains the code for predicting the masks. 

The model itself is too big to upload, should you want access to this model, send an email to: m.s.verschoor1@gmail.com

Code written with help from Elize Herrewijnen (elize.herrewijnen@politie.nl).
