# Recommender System: Multi-Task Learning for Recommendation

## General Requirements

Welcome to our project on "Multi-Task Learning for Recommendation." In this group-based project, we aim to explore and implement multi-task learning techniques for recommendation systems using the Tenrec dataset. Each team member will be responsible for working on one model or pipeline, ensuring that we collectively benefit from the task. This project proposal outlines our approach to achieve the following goals:

1. Familiarize ourselves with experiment design and dataset preparation for deep-learning tasks.
2. Understand state-of-the-art models for recommendation tasks.
3. Replicate SOTA models and apply them to new datasets.
4. Compare and conclude on the performance of SOTA models.
5. Collaborate with each other to enhance our knowledge on the specific task.
6. Present our findings through a recorded presentation and a replicate package for all experiments.
7. Create a neat replication package in a notebook file (ipynb) for final evaluation.

In the following sections, we will detail our motivation, problem statement, related work, data exploration, experiment design, and work distribution.

## Motivation and Problem Statement

**Problem Statement:**  
Our objective is to develop a multi-task learning model that can simultaneously perform multiple recommendation tasks, including item recommendation and click-through rate (CTR) prediction, using the Tenrec dataset. We want to improve recommendation accuracy and CTR prediction compared to single-task models. The success of our project will be measured through appropriate evaluation metrics for recommendation accuracy and CTR prediction.

**Motivation and Background:**  
Recommender systems are crucial for online platforms, helping users discover relevant content and enhancing their experience. Multi-task learning has emerged as a promising approach for recommendation systems. By jointly learning multiple related tasks, such as item recommendation and CTR prediction, multi-task models can leverage shared information and improve recommendation accuracy.

We are motivated to explore multi-task learning for recommendation systems using the Tenrec dataset to enhance the effectiveness of recommendation algorithms. This will provide users with more personalized and accurate recommendations, leading to increased user engagement, conversion rates, and customer satisfaction. Moreover, our investigation and implementation of multi-task learning techniques will contribute to the research community and industry practitioners, driving further advancements in the field of recommender systems.

**User Groups Benefitting from the Outcome:**  
1. Online Platform Providers: E-commerce websites and streaming services can benefit from improved recommendation accuracy and CTR prediction, leading to increased user engagement and satisfaction.
2. Users: Online platform users will receive more personalized and relevant recommendations aligned with their preferences and needs.
3. Researchers and Practitioners: Our project's findings and insights will advance the understanding of multi-task learning techniques in recommendation systems, serving as a benchmark for evaluating different approaches and driving further research and development in the field.

## Related Work

In our exploration of multi-task learning for recommendation systems, we found the following related work:

1. **Collaborative Filtering for Implicit Feedback Datasets**  
   - Paper by Hu, Yifan, et al.
   - Description: Proposes a collaborative filtering approach for implicit feedback datasets, demonstrating its effectiveness on the Amazon Product Reviews dataset.

2. **Factorization Machines**  
   - Paper by Rendle, Steffen.
   - Description: Introduces factorization machines, a generic model for predicting user-item preferences in recommender systems, with evaluations on the MovieLens dataset.

3. **Session-based Recommendations with Recurrent Neural Networks**  
   - Paper by Hidasi, Balazs, et al.
   - Description: Proposes a session-based recommendation model based on recurrent neural networks (RNNs), achieving state-of-the-art performance on the Last.fm dataset.

4. **Deep Neural Networks for YouTube Recommendations**  
   - Paper by Covington, Paul, et al.
   - Description: Presents a deep learning architecture for personalized video recommendations on YouTube, showing the effectiveness of deep neural networks in improving user engagement.

## Basic Data Exploration

The Tenrec dataset, curated by Tencent AI Lab, contains data from two real-world recommendation platforms: a news feed platform and a video feed platform. It comprises around 5 million users and 140 million interactions and includes user IDs, item IDs, interaction types, timestamps, user features, and item features. The dataset is a valuable resource for training and evaluating new recommender systems and comparing different models' performance.

## Experiment Design and Work Distribution

To achieve our goals, we have designed a systematic approach to address the multi-task learning for recommendation systems. Each team member will focus on a specific aspect:

1. **Data Exploration and Preprocessing (Member 1)**: This member will analyze the Tenrec dataset, handle missing values, and preprocess the data for further analysis.

2. **Algorithm Selection (All Members)**: Each member will review and select an algorithm from the leaderboard. Member 2 will explore the LightGCN algorithm, Member 3 will investigate NGCF, and Member 4 will focus on ESMM.

3. **Model Implementation and Training (Members 2, 3, and 4)**: Each member will implement their selected algorithm and train it on the Tenrec dataset, optimizing for recommendation accuracy and CTR prediction.

4. **Model Evaluation and Comparison (All Members)**: Each member will evaluate their implemented model using metrics like precision, recall, and AUC-ROC. Comparisons will be made against baseline models and other team members' models.

5. **Integration and Ensemble (

Member 1)**: The team will integrate individual models into a unified ensemble model that leverages the strengths of each algorithm to improve overall recommendation performance.

Throughout the project, regular meetings and discussions will facilitate collaboration, knowledge sharing, and addressing challenges collectively.

## Experiment Results
After extensive experimentation, we obtained the following results for our models:

LightGCN Model:

Test Loss: 1.2731
NGCF Model:

Test Loss: [To be updated]
ESMM Model:

Click Accuracy: 0.604858
Like Accuracy: 0.718606

## References

[1] P. Covington, J. Adams, and E. Sargin. Deep neural networks for YouTube recommendations. In Proceedings of the 22nd ACM SIGKDD international conference on Knowledge discovery and data mining, 2016.

[2] B. Hidasi, A. Karatzoglou, L. Baltrunas, and D. Tikk. Session-based recommendations with recurrent neural networks. arXiv preprint arXiv:1511.06939, 2015.

[3] Y. Hu, Y. Koren, and C. Volinsky. Collaborative filtering for implicit feedback datasets. In 2008 Eighth IEEE International Conference on Data Mining, 2008.

[4] S. Rendle. Factorization machines. In 2010 IEEE International Conference on Data Mining, 2010.

---


**The Leader: Ahmed Moussa 20398549**  
**Member 2: Adel Abdelfatah 20398047**  
**Member 3: Ali Aboelela 20398556**  
**Member 4: AbdAllah Ibrahim 20398554**
