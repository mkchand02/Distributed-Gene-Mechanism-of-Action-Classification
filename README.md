    Problem Statement: Predicting the mechanism of action (moa-fine) of drugs based on genomic, transcriptomic, and chemical data. Using features such as genes, expressions, drug information, sample characteristics, cell line data, canonical SMILES, and PubChem CID, the goal is to develop a classification model that accurately predicts the moa-fine for new, unseen drug samples.​
    Dataset: We use the following 95 million + rows dataset from Hugging Face:
       Link: https://huggingface.co/datasets/tahoebio/Tahoe-100M ​
    Goal: 
    1. To create a classification machine learning model that can accurately predict the mechanism of action (moa-fine) of drugs based on various features:​
    - Genes ​
    - Expressions​
    - Drug information​
    - Sample characteristics​
    - Chemical properties (e.g., canonical SMILES, PubChem CID)​
    2. Use GCP to do distributed computing by setting up a Spark (YARN) Cluster and get exposure of the same.
