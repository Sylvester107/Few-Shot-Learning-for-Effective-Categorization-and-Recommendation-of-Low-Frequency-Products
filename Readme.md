# Few-shot learning for Effective Product Categorization and Recommendation 🔍

📚 **Overview**
=========================
  
This repository contains the implementation of a session-aware product recommendation system that integrates session data with product metadata. Using a few-shot learning approach with SetFit, the model predicts and ranks the top 100 products a user is likely to interact with. The approach addresses the cold-start problem for low-frequency products by leveraging enriched embeddings and contrastive learning. Experimental results demonstrate superior performance, particularly for low-frequency items, achieving an MRR@100 of 0.3198.

🔧 **Installation|running**
===========================
**Google colab:** This is the recommended way to run the code. 
- download the dataset from kaggle using this  [link](https://www.kaggle.com/datasets/marquis03/amazon-m2)
- Replace links to our google drive with your personal link to load and write data and embeddings
- install or requirements in the requirements.txt file
- there are four notebooks, dedicated to different parts of the pipline
- the stages, are defined in our paper
- However, each notebook contains the exact descriptions of what is being done


** To run the code locally **
- set up the environment 
```bash
# setup the environment on windows by running the following code.
python -m venv venv; venv\Scripts\activate; python -m pip install -q --upgrade pip; python -m pip install -r requirements.txt  

#On Linux
python3 -m venv venv; source venv/bin/activate; python -m pip install -q --upgrade pip; python -m pip install -r requirements.txt 

```
The Two commands are of the same structure
- Activate the python environment
- Upgrade pip to it current version
-  install the requirements located in requirements.txt: You should be at the root of your env

👥 **Authors**
===
- Sylvester Ampomah
- Sai Sowmya 

🌟 **Acknowledgment**
===
We express our profound gratitude to Professor Qu of GWU for his profound support in handling this project
