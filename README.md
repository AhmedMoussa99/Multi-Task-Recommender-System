# Recommender System: Entire Space Multi-Task Model (ESMM)

## Four A’s Data Dudes

### Motivation and Problem Statement

Our project focuses on "Multi-task Learning for Recommendation" using the Tenrec dataset. The goal is to create a model that can perform multiple recommendation tasks simultaneously, such as item recommendation and click-through rate (CTR) prediction. By jointly optimizing these tasks, our aim is to improve the accuracy and performance of recommendation systems compared to single-task models.

### Background and Objectives

Recommender systems play a crucial role in enhancing user experience on online platforms by providing personalized recommendations. Multi-task learning has emerged as a promising approach for recommendation systems, enabling models to leverage shared information between tasks and improve accuracy.

We chose to investigate multi-task learning for recommendation systems using the Tenrec dataset to enhance the effectiveness of recommendation algorithms. By incorporating multiple tasks into a single model, we aim to capture complex user-item interactions and preferences, leading to more accurate and personalized recommendations.

Our objectives are to:
1. Explore and implement state-of-the-art models for multi-task learning in recommendation systems.
2. Evaluate and compare the performance of these models on the Tenrec dataset.
3. Contribute to the research community by providing insights into multi-task learning for recommender systems.

### Related Work

We have reviewed several relevant papers, including:
1. "Collaborative Filtering for Implicit Feedback Datasets" by Hu et al.
2. "Factorization Machines" by Rendle.
3. "Session-based Recommendations with Recurrent Neural Networks" by Hidasi et al.
4. "Deep Neural Networks for YouTube Recommendations" by Covington et al.

### Basic Data Exploration

The Tenrec dataset consists of around 5 million users and 140 million interactions from two real-world recommendation platforms. It includes user-item interaction data, user features (e.g., age, gender), item features (e.g., title, category), and interaction types (e.g., click, like, share).

The dataset is divided into training, validation, and test sets, along with a features file containing user and item features. We will use this dataset to train, evaluate, and compare different recommender systems.

### Experiment Design and Work Distribution

To achieve our goals, we have outlined a systematic approach:

1. Data Exploration and Preprocessing: Member 1 will analyze and preprocess the Tenrec dataset.
2. Algorithm Selection: Each member will choose a model from the leaderboard. Member 2 will explore LightGCN, Member 3 will investigate NGCF, and Member 4 will consider ESMM.
3. Model Implementation and Training: Based on their selections, each member will implement and train their model on the Tenrec dataset.
4. Model Evaluation and Comparison: Each member will evaluate their model using precision, recall, and AUC-ROC metrics and compare them against baseline models and other team members' models.
5. Integration and Ensemble: The team will integrate individual models into a unified ensemble model, leveraging the strengths of each algorithm to enhance recommendation performance.

Throughout the project, close collaboration, regular meetings, and knowledge sharing will ensure comprehensive understanding and successful implementation.

### Team Members

1. Ahmed Moussa - Model Implementation and Training
2. Adel Abdelfatah - Algorithm Selection (LightGCN)
3. Ali Aboelela - Algorithm Selection (NGCF)
4. AbdAllah Ibrahim - Algorithm Selection (ESMM)

### References

[1] P. Covington, J. Adams, and E. Sargin. Deep Neural Networks for YouTube Recommendations. In Proceedings of the 22nd ACM SIGKDD International Conference on Knowledge Discovery and Data Mining, 2016.

[2] B. Hidasi, A. Karatzoglou, L. Baltrunas, and D. Tikk. Session-based Recommendations with Recurrent Neural Networks. arXiv preprint arXiv:1511.06939, 2015.

[3] Y. Hu, Y. Koren, and C. Volinsky. Collaborative Filtering for Implicit Feedback Datasets. In 2008 Eighth IEEE International Conference on Data Mining, 2008.

[4] S. Rendle. Factorization Machines. In 2010 IEEE International Conference on Data Mining, 2010.
