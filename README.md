# Sentiment-Analysis-with-QReLU-and-mQReLU

Sentiment analysis using QReLU and mQReLU. Making use of the Sentiments 140 dataset.

- [Training Dataset](https://www.kaggle.com/kazanova/sentiment140)
- [QReLU & mQReLU GitHub](https://github.com/luca-parisi/QReLU_m-QReLU_TensorFlow_Keras)


## How to run:

The below steps apply to all notebooks. I recommend using Google Colab - these notebooks in particular were computed and ran using [Colab+](https://colab.research.google.com/signup). The free version of Colab should also work, but it will run slower.

Download the training dataset and the two .py files from the QReLU Github. My advice is to place the training dataset into a Google Drive, mount your drive and pull the folder in from here, this can be achieved with this line of code, noting that the path to the .csv file is respective to your Google Drive location:

```
from google.colab import drive
drive.mount('/content/drive')

df = pd.read_csv("./drive/MyDrive/QReLU/training.1600000.processed.noemoticon.csv", header=None, names =cols, engine='python')
```

Alternatively, you can just place the file into the local IDE or Colab itself, but particularly with Colab, it may have issues temporarily storing the file. 

Secondly, pull the two .py Acitivation Function files into the local IDE or Google Colab, from there, the code can be ran and mofified.
