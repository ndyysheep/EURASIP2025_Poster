# Inter-Departmental Ticket Processing Time Prediction using Multi-Task Learning

📄 Official repository for the paper:  
**"Inter-Departmental Ticket Processing Time Prediction using Multi-Task Learning"**  
Authors: Dongdong Zhang, Xinyu Yang, Yuanbo Tang, Naifan Zhang, Yiwen Liu, Feifan He, Shuhan Huang, Yang Li  

---

## 📘 Paper
- [PDF Download]([./paper.pdf](https://github.com/ndyysheep/EURASIP2025_Poster/blob/main/Inter-Departmental%20Ticket%20Processing%20Time%20Prediction%20using%20Multi-Task%20Learning.pdf))  <!-- 这里可以放本地路径，也可以替换成 arXiv / 会议链接 -->
- To appear in *EURASIP 2025*.  

---

## 🔍 Abstract
High-quality community service depends on the **timely resolution of tickets**. However, tickets often transfer across multiple departments, introducing uncertainty into the overall resolution time.  
We propose **MT-TLM**, a hybrid encoder combining **Transformer self-attention** and **LSTM**, trained with a **multi-task learning** framework to jointly predict:  

1. The next responsible department  
2. The processing time of the next department  
3. The total resolution time  

Experiments on large-scale real-world community ticket data show significant improvements over strong baselines, achieving **87.04% accuracy** for node prediction and reducing RMSE to **125.82** for total-time prediction.

---

## 📊 Key Results
| Model            | Node Acc. | RMSE / MAE |
|------------------|-----------|------------|
| Transformer      | 85.28%    | 142.88 / 72.37 |
| Seq2Seq-LSTM     | 86.66%    | 135.22 / 78.04 |
| **MT-TLM (Ours)** | **87.04%** | **125.82 / 66.16** |

---

## 📌 Citation
