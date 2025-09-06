# Inter-Departmental Ticket Processing Time Prediction using Multi-Task Learning

📄 Official repository for the paper:  
**"Inter-Departmental Ticket Processing Time Prediction using Multi-Task Learning"**  
Authors: Dongdong Zhang†, Xinyu Yang†, Yuanbo Tang, Naifan Zhang, Yiwen Liu, Feifan He, Shuhan Huang, Yang Li*  
† Equal contribution · * Corresponding author

---

## 📘 Paper
- [Download PDF](./Inter-Departmental%20Ticket%20Processing%20Time%20Prediction%20using%20Multi-Task%20Learning.pdf)
- (To appear in *EURASIP 2025*)

---

## 🔍 Abstract
When customers submit problem tickets to customer-service departments, these requests enter standardized workflows.  
Ensuring **real-time visibility** of progress and accurate **resolution-time estimation** is critical for positive customer experience.  

We propose a novel **Multi-Task Transformer-LSTM (MT-TLM)** model that jointly optimizes three tasks:
1. Predicting the next responsible department  
2. Estimating department-specific processing duration  
3. Estimating total resolution time  

Experiments on ~92k real-world community service tickets (Shenzhen, 2022–2024) demonstrate that MT-TLM outperforms classic ML, ensemble models, and single-task deep learning approaches, achieving **87.04% node prediction accuracy** and reducing RMSE to **125.82** for total-time prediction:contentReference[oaicite:1]{index=1}.

---

## 📊 Key Results

| Model            | Node Acc. | RMSE / MAE |
|------------------|-----------|------------|
| Transformer      | 85.28%    | 142.88 / 72.37 |
| Seq2Seq-LSTM     | 86.66%    | 135.22 / 78.04 |
| LSTM             | 86.47%    | 131.39 / 73.43 |
| **MT-TLM (Ours)** | **87.04%** | **125.82 / 66.16** |

---

## 📌 Citation
