# BERT-for-Q-A :interrobang::
This is a project which test the efficiency of machine learning pre-trained model BERT. In the project we ask BERT a few questions which answer can be found from within a context. 
## Technologies and techniques used for this project
* **Python 3**
* **[Simple Transofrmers](https://simpletransformers.ai/)**: A library which simplifies the use of the Tranforming library by [Huggingface](https://huggingface.co/transformers/v2.2.0/index.html/).
* **[SQuAD](https://rajpurkar.github.io/SQuAD-explorer/)** A dataset by crowdworkers which allows for the training, testing and benchmark leaderboard for Q&A models.
* **Google Colab**: A online Python compiler that allows for the use of Google GPU resources to make the training of these models .faster.


## Conext, questions and answers in the project
* **About COVID-19 :** Coronavirus disease 2019 (COVID-19) is an infectious disease caused by severe acute respiratory syndrome coronavirus 2 (SARS-CoV-2). It was first identified in December 2019 in Wuhan, China, and has resulted in an ongoing pandemic. The first case may be traced back to 17 November 2019. As of 13 June 2020, more than 7.69 million cases have been reported across 188 countries and territories, resulting in more than 426,000 deaths. More than 3.65 million people have recovered.

	| Question  | BERT answer |
	| ------------- | ------------- |
	| What is COVID-19?  | Coronavirus disease 2019  |
	| What are the symptoms of coronavirus?  | Severe acute respiratory syndrome  |
	| Where was the first case of COVID-19? | December 2019 in Wuhan, China  |
	| How many people have died from COVID-19?  | 426,000 |
	| How many people did coronavirus infected?  | 7.69 million  |

* **About supermarket enviroment:** 5 bananas cost one dollar, 10 bananas cost 2 dollars, small milk is 50 cents, large milk costs one dollar and orange juice is three dollars.
	| Question  | BERT answer |
	| ------------- | ------------- |
	| How many bananas can I buy with one dollar?  | 5  |
	| And if I wanted 10 bananas how much will that be? | 2 dollars  |
	| I'll take 5 bananas thank you. Excuse me one more question, how much does the orange juice costs? | Three dollars  |
	| Oh my god that is so expensive, I think I'll just get milk, how expensive is the large one?  | One dollar |
	| Oh! No I've forgotten my money at home again, I've only got spare change, what size of milk could I buy with 58 cents?  | small  |
