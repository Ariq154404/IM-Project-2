# Description:
This is the second project for upskill on Natural language processing on a Kernel only competition on kagggle with a Auc score private score of 0.82439
The competion description is here:
https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification

##Implementation:
A pretrained of Delibert from huggingface is being used as the base later which is fine tuned on a feed forword neural network and only less the 10% of the training data is used due to resource complexity
# Dependencies:
python >3.7
Gpu:Tesla T4 for Bert training
Tpu: collab Tpu cluster for feed forward neural network
