# BERT-Japanese-Formality-Classifier

This is a reduced version of the source code for my final project from MSc in Computer Science at University of York.

The project unites my interest in NLP and ML with my background in foreign languages, specifically in Japanese. 

This work intended to use the property of Japanese verbs that contain formality markers, therefore allowing creation of supervised data without the need of manually labelling the dataset. The heuristic based on this information allowed creation of a custom Japanese dataset automatically labelled for formality and distinguishing between informal and polite sentences. 

The dataset was then used for pre-training and fine-tuning BERT model capable of inferring the label of the sentence and classifying Japanese sentences based on their formality level.

The project consists of the following files:
1. Dataset-Analysis
2. BERT Fine-tuning
3. Final Model

