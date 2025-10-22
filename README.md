Question Answering with BERT, RoBERTa & DistilBERT

This project explores how transformer-based models like **BERT**, **RoBERTa**, and **DistilBERT** can understand language and answer questions based on given context.  
It demonstrates how modern NLP models process tokens, predict answer spans, and visualize model confidence.

=>Features

**Context based QA** using `BertForQuestionAnswering`  
**Token visualization** with Seaborn bar plots  
**Custom function (`faq_ask`)** that answers user questions from a given paragraph  
**Multiple model support** test BERT, RoBERTa, and DistilBERT  
**Human-readable output correction** for tokens like `##word`

=>Libraries Used
python
transformers
torch
matplotlib
