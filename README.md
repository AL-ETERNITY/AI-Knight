# AI-Knight
This competition was Organised by IIT Jodhpur on kaggle. We secured 15th rank with a F1-Score of 0.93.

## How to Run the Repo for Inference

This repo contains three `.ipynb` notebooks that are designed to run on Kaggle with T4 GPU support. Below are the steps to run each notebook:

### 1. XceptionNET Finetuning
- Open the `xceptionNET_Finetuning.ipynb` file in Kaggle.
- Make sure you're using the T4 GPU in Kaggle.
- If you encounter any errors, restarting the Colab session usually resolves them.
- Ensure you have installed all the neccessary libraries(mentioned in the `requirements.txt`) also add the CIFAKE dataset in input(since we had competition so we were following their dataset, but both are same just the number of images 
  are different in the dataset and also the labels, in original CIFAKE dataset images are marked as 'FAKE' or 'REAL').
- Simply run the entire notebook.

### 2. EfficientNET Finetuning
- Open the `EfficientNET_Finetuning.ipynb` file in Kaggle.
- Make sure you're using the T4 GPU in Kaggle.
- If you encounter any errors, restarting the Kaggle session usually resolves them.
- Ensure you have installed all the neccessary libraries(mentioned in the `requirements.txt`) also add the CIFAKE dataset in input(since we had competition so we were following their dataset, but both are same just the number of images 
  are different in the dataset and also the labels, in original CIFAKE dataset images are marked as 'FAKE' or 'REAL').
- Simply run the entire notebook.

### 3. CLIP finetuned model
- we tried to finetne the CLIP model on our own, But since it was very time intensive. we picked the clip model which was already finetuned on this CIFAKE dataset.
- simply run the entire notebook(before ensuring that everything is installed).


### Important Note:
- Make sure that you change the dataset directory (since we were using data according to this competition).

 ## Requirements
- tensorflow>=2.10.0
- numpy>=1.19.0
- pandas>=1.1.0
- scikit-learn>=0.24.0
- logging
- warnings
- random
