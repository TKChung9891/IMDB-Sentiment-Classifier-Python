# IMDB-Sentiment-Classifier-Python

This is a binary sentiment classifier for the IMDB movie dataset.  IMDB dataset has 50K samples of reviews with labels of either positive or negative sentiments.  The dataset is then pre-processed and trained with traditional machine learning and neural net deep learning algorithms, and results are analysed and compared with each other.  The code is written in Python and executed on Jupyter Notebook.

All three traditional machine learning algorithms of Naïve Bayes, Logistics Regression and SVM perform well with Accuracy, Precision and Recall at around 0.9.  For deep learning, a CNN architecture is used with about 500,000 trainable parameters. Best results reached at 2 epochs with Accuracy, Precision and Recall at 0.86. 

CNN architecture took longer to run and did not give improved results for this IMDB dataset. The neural network design can be further tweaked, using other types of layers, changing dropout, more complex designs like LSTM. However, given the small dataset size of 50K samples, any improvement is likely limited.  Neural networks should work better for much larger dataset. 

![image](https://user-images.githubusercontent.com/88481617/145678804-698eb4aa-a938-4b57-9ffd-df6737ecabb7.png)
![image](https://user-images.githubusercontent.com/88481617/145678812-fd824589-53c8-4053-b843-06aaf69b89d6.png)
![image](https://user-images.githubusercontent.com/88481617/145678823-f26a3624-db10-455b-be6d-90232a3aa802.png)
![image](https://user-images.githubusercontent.com/88481617/145678835-2fea36e4-9042-4f92-a737-270b4ee986cb.png)
![image](https://user-images.githubusercontent.com/88481617/145678870-f256a067-6c13-40e4-a2cb-afab604695e8.png)
