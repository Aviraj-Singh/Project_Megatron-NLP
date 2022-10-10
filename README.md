# Project_Megatron_NLP

MegatronBot is a fully fleged chatbot with easy to update feature and can integrate with website. It is easy to deploy in any cloud services like AWS, GCP and Azure and comes with a capibility to work in production enviorment. Megatron accepts various formats of inputs like text input and also you can also give a Speech as a input.

##Install requirements.txt


## What is the need of ChatBot?

Megatron was built by the team of iNeuron.ai where I have worked upon a task of Intent Classification and State Tracking. The need of the MegatronBot came as iNeuron.ai has a overwhemling responses and queries asked by the student over their newly released courses, as their is a Skype Support team to clarify their queries always but they cant be available 24x7. Due to this iNeuron.ai wanted to build such a great solution where the user can clarify most of their queries at any point of time.

## How I have apporached to such Solution?

Building a Megatron like ChatBot requires a huge amount of data and various state of the art components. So, the first task was to get a large set of data. The dataset was creatd by scaraping the questions asked by students over a year to their Skype support team as well as their respective answers, the dataset include of 2 Million sentences which were transformed and added to CSV and json format and then they were labelled manually.

We tried many State of the art language models from BERT-large to DialoGPT to RoBERTa but got an awesome results over Distilled BERT Models with ELMO embeddings. The model then trained over the next set of queries after preprocessing then adding tokens like [SEP], [START], [END] and [EOS].
  
The Architecture of MegatronBot: -

<p align="center">
  <img width="1010" height="700" src="utils/Megatron-ChatBot@2x (1).png">
</p>


Below are some results: 

<p align = "center"><img align = "center" src = "utils/NewGIF.gif" /></p>
