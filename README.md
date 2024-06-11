# Abstractive_Text_Summarisation_Using_LSTM

The project is based on text summarization technique using abstractive approach to provide the summary of the given input text file. Different Deep Learning techniques like LSTM, Attention models, ROUGE-N values and encoding decoding are used in this project.The amzon food review dataset is used. 

# Steps
1. Import necessary libraries
2. Fetch the dataset
3. Text preprocessing
4. Defining layers for model
5. Train the model
6. Test the model
7. Results

# Block Diagram
![image](https://github.com/kasturimandlik/Abstractive_Text_Summarisation_Using_LSTM/assets/104767049/ed0d3648-755a-4e24-8fce-ad096a586c16)

# Dataset
https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews

# Deep Learning Techniques used
1. Long Short Term Memory (LSTM)
2. Attention model
3. ROUGE-n values

# Results
![image](https://github.com/kasturimandlik/Abstractive_Text_Summarisation_Using_LSTM/assets/104767049/3a9db52e-96cd-4901-bb09-1ed489547b1a)
![image](https://github.com/kasturimandlik/Abstractive_Text_Summarisation_Using_LSTM/assets/104767049/4238c8fa-8cd1-42f1-8569-2c4f528d608d)

# Evaluation of model
ROUGE (Recall-Oriented Understudy for Gisting Evaluation) is a set of metrics used for automatically evaluating the quality of summaries by comparing them to reference (human-created) summaries. It is widely used in natural language processing tasks, particularly in text summarization, to assess the effectiveness of summarization algorithms and systems. ROUGE scores measure the similarity between the generated summary (hypothesis) and the reference summary (ground truth). The scores are based on various criteria, such as overlapping n-grams (ROUGE-N), the longest common subsequence (ROUGE-L), and the weighted longest common subsequence (ROUGE-W).
ROUGE-1: is a metric used to evaluate the quality of summaries by measuring the overlap of unigrams (single words) between the generated summary (hypothesis) and the reference summary (ground truth).
ROUGE-L: Measures the longest common subsequence (LCS) between the hypothesis and the reference summary. The LCS is the longest sequence of words that appear in both summaries in the same order.


