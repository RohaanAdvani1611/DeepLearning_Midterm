# DeepLearning_Midterm

For the deeplearning midterm project, we used multiple notebooks to speed up and parallelize our workflow. Each notebooks function is given below. Multiple parameters and prompts were used to get results. We used ensemble techniques at the end from the best models to get the final results.


## Baseline
This was the sample notebook used to generate models from base Llama 3.1. Its work was continued on by the Resume training notebook to add on samples to the existing models.


## Resume Training
This notebook was used after baseline has given samples to the model and more samples needed to be added to the model. We tried changing the batch sizes, learning rates to check performance on iterative learning steps. We created this notebook to have the abilitiy to save work in checkpoints and load from it again to continue the work to handle computational limits.


## Load And Inference:
The notebook used to load the trained models and get the final test results. We added a small section of inference from validation set to check and compare models internally. A validation accuracy score of greate than 0.85 was considered as good model. We also generated confusion metrics, ROC_AUC score and F1 scores.

## EDA
Used for simple EDA

## Dataset Unbiasness
Notebook to create custom dataset from original dataset and upload on hugging face. Created dataset which allows equal spread of true and false samples. Has 10% validation set.

## Ensemble
Use the test results from different mdoels and respective Kaggle scores for weighted ensembling technique.

## Hugging Face
We created few hugging face models and dataset to be easily accessed by the team. 
Links: 
 - [Dataset](https://huggingface.co/datasets/LinNY-DLM/train_dataset)
 - [Models](https://huggingface.co/LinNY-DLM/mixedprompting-88200)
