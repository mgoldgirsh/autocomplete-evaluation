# Query Autocompletion Model Evaluation
This project was created to determine what query autocompletion models work best. 
It evaluates 3 seperate embedding methods to create 3 seperate language models to determine which model is better 
at predicting the best full query to generate from the provided partial query.

## The 3 Language Models
- Bag of Words Model (with tf-idf scores)
- One Hot Vector Model 
- Word2Vec Neural Network Model 

## Datasets and Resources
SIGIR 2017 Dataset
> @inproceedings{park2017neural,   
>                title={A neural language model for query auto-completion},
>                author={Park, Dae Hoon and Chiba, Rikio},
>                booktitle={Proceedings of the 40th International ACM SIGIR Conference on Research and Development in Information Retrieval},
>                pages={1189--1192},
>                year={2017},
>                organization={ACM} }
> https://sites.google.com/site/daehpark/Resources/data-set-for-query-auto-completion-sigir-2017 

Word2Vec Documentation
https://radimrehurek.com/gensim/models/word2vec.html#gensim.models.word2vec.Word2Vec.predict_output_word 

