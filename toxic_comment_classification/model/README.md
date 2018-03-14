# Notebook Description
The ipython notebooks are run on Google Colaboratory instead of Kaggle kernel, becuase my model need a larger training time in the range of 3-4 hours, and extremely fast computation using gpu. Google Colaboratory fortunately now provides gpu backend.

# File Descrition
1. [clean_text_data.ipynb](https://drive.google.com/open?id=1gIRzxNALV28ueIlHfl0UHa8OHqoX9zsx) - this notebook cleans the raw text data in the train and test using regular expression and nltk library, and saves the cleaned data in google drive
2. [Word2VecGenerator.ipynb](https://drive.google.com/open?id=1N2IieFh7Cm7zFXr_iwPaCOCNFEx0WMKX) - this notebook generates word2vec model using gensim library and save the model.
3. [single_classifier_gpu](https://drive.google.com/open?id=1i75pPSgnOio4b5YZWPPuv-eC4-3b0xmS) - creates a multilayered lstm model with gpu computation
4. [multiple_classifiers_gpu](https://drive.google.com/open?id=11dONs-V0NO6yxzRv2QTEDz9bJ0RwXHAO) - creates six different multilayered lstm classifier for each sentiment with gpu computation

# CAUTION!
It looks like the github ipython notebook renderer has problems opening the entire jupyter notebook prepared in Google Colaboratory. If you face a problem in viewing the notebooks just view the notebooks in the embedded links in a colab enviroment or just download them.
