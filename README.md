<h1> QnA-using-Transformers </h1>
Question Answering Pipeline using BERT

Question-Answering Systems are generally categorized into two types - Open Domain QnA (ODQA) and Closed Domain QnA (CDQA). 

While ODQA generally deals with almost all types of questions based on all world's knowledge in form of generalized data, CDQA is more precise and deals with questions under a particular domain that we train the system on.

- Here we implement CDQA using pretrained BERT (Bidirectional Encoder Representations from Transformers). 
- We provide files for the model to train on, here in this case - a pdf containing five stories by Alphonse Daudet and another pdf file of a Deep Learning Research Paper.
- Then we query the model and extract answers.
