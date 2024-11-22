# **CS 613: NLP - Assignment 3**  
## **Fine Tuning & Evaluation**

### **Assignment Overview**
This assignment involves fine-tuning a pre-trained language model (Llama3.2-1B/Gemma) for two tasks:  
1. Sentiment Classification (SST-2 dataset).  
2. Question Answering (SQuAD dataset).  

Performance before and after fine-tuning is reported for relevant metrics.  

---

### **Team Contributions**

| Team Member         | Contributions                                                                 |
|----------------------|------------------------------------------------------------------------------|
| Suriya, Vedant        | Calculated parameters for the Llama3.2-1B model and verified them with the paper. |
| Abhyudaya, Vinayak     | Fine-tuned the model for SST-2 classification and implemented metric evaluation. |
| Suriya, Vedant       | Fine-tuned the model for SQuAD Question Answering and performed post-evaluation analysis. |
| Shiva, Vinayak         | Analyzed performance differences between zero-shot and fine-tuned models and wrote rationale. |
| Shiva        | Organized final report, managed repository, and handled the model push to 🤗 Hub.  |

---


### **Tasks Overview**
#### **Model Details**  
- **Model Name**: Llama3.2-1B  
- **Pre-trained Parameters**: 1.2 billion  
- **Fine-tuning Parameters**: Entire model (1.2 billion)  

#### **Tasks Performed**
1. **Parameter Validation**  
   Verified reported parameters with calculated parameters.  
2. **Fine-Tuning Tasks**  
   - **Task 1**: Sentiment Classification (SST-2 Dataset).  
   - **Task 2**: Question Answering (SQuAD Dataset).  
3. **Evaluation Metrics**  
   - **SST-2**: Accuracy, Precision, Recall, F1 Score.  
   - **SQuAD**: squad_v2, F1, METEOR, BLEU, ROUGE, and Exact-Match.  

4. **Analysis**  
   - Discussed rationale behind performance differences.  
   - Examined parameter differences before and after fine-tuning.  

5. **Model Deployment**  
   - Fine-tuned model uploaded to 🤗 Hub.  
