# Sentiment-analysis-model-GLUE-SST2

<img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fventurebeat.com%2Fwp-content%2Fuploads%2F2019%2F09%2Fhugging-face.png%3Fw%3D1200%26strip%3Dall&f=1&nofb=1&ipt=6f1337f8236317ae4029976cb7206cc9e96d3f546c0e591096cb6bed7fcbd87e&ipo=images"></img>

This fine-tuned model is tuned with Standford Sentiment Treebank (SST-2) datasets, and the pre-trained model that i consider to use in this case is DistilBERT base uncased finetuned SST-2 which was trained on SST-2 dataset before. The fine-tuned version acheives 90% accuracy on the SST-2 validation set. However, SST-2 labels of test dataset on huggingface was hidden so that our prediction on the test set cannot be computed. By the way, after try on many review cases, the model can predict customers' sentiment as POSITIVE and NEGATIVE effectively.

### Link of the pre-trained model of DistilBERT on huggingface 
<a> https://huggingface.co/distilbert-base-uncased-finetuned-sst-2-english </a>
