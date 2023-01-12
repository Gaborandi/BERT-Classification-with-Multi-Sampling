# BERT-Classification-with-Multi-Sampling

comparing the performance of BERT model with different sample sizes 

this code will help in measuring the performance of BERT model with different sample sizes using the same dataframe

this code is updated version of the code from this tutorial (https://mccormickml.com/2019/07/22/BERT-fine-tuning/) by Chris McCormick 

Testing is done against positive labels only 

the purpose of multisampling is to see how powerful is the model against small sample size

usually when you sample from the data randomly, you get different probabilities. then you have to take the average of these probabilities to make sure you have a robust result

this could help in knowing which model could be good for domains with limited amount of samples such as rare diseases in medical domain

domain adaptation could help in overcoming the problem of limited sample size but more experiements are needed 
