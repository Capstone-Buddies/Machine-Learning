# Machine Learning Repository

We are developing two models within the QFlare application. The first model is a recommender system that suggests questions to users based on their performance in previous quizzes. It aims to enhance their understanding in weaker categories by generating quizzes tailored to their needs. This system selects questions using calculated proportions and similarity scores, ensuring a personalized learning experience through content-based filtering. The goal is to help users improve in areas where they are weakest.

Additionally, we are implementing gamification to track users' learning progress, featuring a leaderboard that ranks users based on their EXP (Experience Points). To support this gamification feature, we have developed an EXP Point prediction model using TensorFlow's Deep Neural Network (DNN). This model predicts users' EXP based on their accuracy and duration in answering each question.

## ML Task
1. Data Collection and Preprocessing
2. Model Development
   - TPS & Literasi Recommender System using Cosine Similarity
   - EXP leveling system using TF Deep Neural Network
4. Model Testing and Evaluation
5. Save and Convert model into HDF5

## Tools
1. Code Platform: Google Colab
2. Programming Language: Python
3. Libraries: Pandas, TensorFlow, NumPy, Matplotlib, scikit-learn
4. Datasets: 
   - Questions sourced from various UTBK Preparation books [access here](https://drive.google.com/drive/folders/1AcEinBDjYzxP4g2nVyau5ZgWqzsK9o49)
   - Datasets for EXP Predictions and the recommender system are generated using Google Spreadsheets [access here](https://github.com/Capstone-Buddies/Machine-Learning/tree/main/Dataset)

## Datasets
1. The source of questions comes from various UTBK preparation books [access here](https://drive.google.com/drive/folders/1AcEinBDjYzxP4g2nVyau5ZgWqzsK9o49)
2. For datasets used in EXP Predictions and the recommender system, we generate dummy data using Google Spreadsheets [access here](https://github.com/Capstone-Buddies/Machine-Learning/tree/main/Dataset)
