# Token Classification / Entity Recognition Experiments
A series of notebooks to carry experiments on the token classification task with different datasets, finetuning techniques, and pre-trained models. 


### Description:

1. Preparing a dataset for training a model in token classification task.

    <a href=https://github.com/JorgeCantillo/token-classification-experiments/blob/main/cord_ner_token_classification_data_preprocessing.ipynb>cord_ner_token_classification_data_preprocessing</a>

2. Full-finetuning a BERT model on the token classification task.

    <a href=https://github.com/JorgeCantillo/token-classification-experiments/blob/main/cord_ner_token_classification_training.ipynb>cord_ner_token_classification_training</a>

3. <b>Upcoming:</b> PEFT-Finetuning same BERT model on the token classsification task but using LORA. 

### Prerequisites:
- Python 3.11
- Create virtual environment (<code>.venv</code>) and activate.
- Install libraries in virtual environment (<code>pip install -r requirements.txt</code>). 


### Pre-trained model:
<a href=https://huggingface.co/medicalai/ClinicalBERT>ClinicalBERT</a> is trained on a large multicenter dataset with a large corpus of 1.2B words of diverse diseases using a large-scale corpus of EHRs from over 3 million patient records.

### Data:
<a href=https://www.kaggle.com/datasets/sushilkumarinfo/covid-ner-data-set>Covid NER Data Set</a> is processed for NER recognition for covid-19. This data set contains 64 entity specific for covid-19 and every article breaks into 512 length. 
