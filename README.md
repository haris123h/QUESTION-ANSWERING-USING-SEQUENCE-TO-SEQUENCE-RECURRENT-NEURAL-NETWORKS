# QUESTION-ANSWERING-USING-SEQUENCE-TO-SEQUENCE-RECURRENT-NEURAL-NETWORKS
# NLP_Term_Project
NLP_Term_Project_QUESTION ANSWERING USING SEQUENCE-TO-SEQUENCE RECURRENT NEURAL NETWORKS.


# QUESTION ANSWERING USING SEQUENCE-TO-SEQUENCE RECURRENT NEURAL NETWORKS


Question Answering a task in NLP that takes input as a questions of different types and outputs answers for these questions. The questions can be of various types such as Open domain vs closed domain. In open domain, factual and non-factual etc., The answers can also be of different types such as one word answers, selecting answers from a text inputted, yes or no questions, etc.  The open domain question answering has two parts. The first part is the Retriever module that gets documents from the web to answer the questions. The reader module is then used to answer the questions based on the retrieved documents. Both of the these tasks have to be trained.



## Algorithms Used:
#In our project, we have considered answering the Open domain question answering using sequence to sequence encoders and decoders. We have used Bidirectional LSTMS in both encoders and decoders.
  

## Instructions to Run code:

- Open the dog_vision.ipynb file in Google colab, As we have taken huge dataset it cannot be processed in Local jupyter notebooks,
 We are using googlecolob as it has the servers with High GPU.

- Load the Data sets in to the model, Which can be obtained from Kaggle

- Once the above steps are performed follow the instructions in dog_vision.ipynb file and execute all the cells.
  we will get the required model predictions at the end with the prediction probabilities for each dog breed of each test image.

 
## Evaluation metrics:
  
  - The evaluation is a file with prediction probabilities for each dog breed of each test image.
