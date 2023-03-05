# VoiceDesensitizer

This is a project aimed to desensitize voice data to keep our privacy safe. The structure of this project is like transform the voice data to text data first and use NLP model to detect the sensitive keywords in the text data then use computer audio to read the text data.

## Files Introduction:
- V2T2V.ipynb: demo to transform voice data to text data and use computer audio to read the text data.
- NLPEntityDetection: a demo to detect the keywords in the text data.
- labelText.ipynb: a script to label text data and generate corresponding labeled speech voice data.
- CNN.ipynb: CNN classifier based on Pytorch in the notebook to predict the sensitive sentences in the speech.
- torchLSTM.ipynb: There is a LSTM classifier in the notebook based on Pytorch to predict the sensitive sentences in the speech.
