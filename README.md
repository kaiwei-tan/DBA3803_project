# DBA3803 Project
Project done for NUS module, <i>Predictive Analytics in Business</i>, in Spring 2019
<br> Done by: Kai Wei Tan, Daniel Lee, Eugene Ng, Tan Quan Hao, Rayner Tay, Kenny Chuen
<br> Supervised by: Professor He Long

Part of a natural language processing and classification project using latent Dirichlet allocation (LDA) for topic modelling ("LDA.ipynb") and logistic regression for text classification ("/flask/model.py"). This project aims to use machine learning to identify hate speech by classifying text under certain pre-defined categories e.g. 'racist', 'xenophobic', 'sexual', etc. Text data ("text.csv") was scraped from Singaporean forums and Facebook comments on Singaporean pages, and manually tagged by category.

I also created a Flask application ("/flask/main.py") which uses the trained logistic regression model to classify any new text input. If this input is classified under any of our pre-defined categories, the application identifies it as hate speech.
