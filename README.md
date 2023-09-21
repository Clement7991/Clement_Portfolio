# CLEMENT'S PORTFOLIO

## Data Science projects : 

### [YWL : You Write Like](https://github.com/Clement7991/ywl)
<a href="https://www.youtube.com/watch?v=5VZa8K2afMg&t=336s&ab_channel=PouetPouet">
  <img align="right" src="ywl.png" alt="YWL" width="200" style="margin-left: 40px;" />
</a>

* Group project with [Nico404](https://github.com/Nico404) and [lxmuresan](https://github.com/lxmuresan)
* Created a tool capable of indicating which classic author's style a text resembles.
* Used the Gutenberg API to collect raw texts from 40 different authors.
* Tested and gridsearched the following models : CNN Conv1D, RNN GRU, RNN LSTM, BERT and distilBERT.
* Opted for Hugging Face's distilBert which had a val accuracy of 0.7.

Watch our [presentation](https://www.youtube.com/watch?v=5VZa8K2afMg&ab_channel=PouetPouet) (only in French...) and try our [app](https://youwritelike.streamlit.app) out!


### [A Titanic Mistake (DS)](https://github.com/Clement7991/Titanic-hw)
<img align="right" src="https://images.rawpixel.com/image_800/cHJpdmF0ZS9sci9pbWFnZXMvd2Vic2l0ZS8yMDIzLTAzL3drMjk5MDc4OS1pbWFnZS5qcGc.jpg" alt="A-Titanic-Mistake" width="200" height="200" style="margin-left: 40px;" />

* Created an app that can predict the survival of a passenger of the Titanic.
* Used and preprocessed Kaggle's Titanic dataset.
* Tested a Random Forest Classifier, an Adaboost, a KNN and an ensemble method using all three models.
* Chose the Random Forest Classifier, gridsearched parameters and obtained an accuracy of 0.88.

[Check](https://titanic-mistake.streamlit.app/) whether you would have survived. 


## Data Analysis projects : 

### [Olist : analysing a Brazilian e-commerce platform](https://olist.com/pt-br/)

* <ins>Hypothesis :</ins> Delay in delivery has an impact on Olist's churn.
* <ins>Methodology :</ins> collected data from [**Kaggle**](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce), explored, cleaned the data and feature-engineered using **Python**, used **Tableau** to create a dashboard.
* <ins>Results :</ins> Delay in delivery mostly affects states with low order volumes and has limited customer satisfaction.
* <ins>Recommendations :</ins> Audit freight services of states with the highest average delay and sellers with recurrent delays in delivery.

<img src="Olist Dashboard (7).png" alt="Olist Dashboard" width="500" height="400">
