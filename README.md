**📊 TOPSIS-Based Model Ranking for Text Classification**

This project implements the TOPSIS (Technique for Order Preference by Similarity to Ideal Solution) multi-criteria decision-making method to rank transformer-based NLP models across different text classification domains.

The goal is to objectively compare models based on multiple performance and efficiency metrics, rather than relying on a single score.

**🚀 Project Overview**

In real-world machine learning systems, model selection is not based only on accuracy. Factors like precision, recall, inference time, and model size are equally important.

This project:

Applies the TOPSIS algorithm from scratch using NumPy

Ranks popular NLP models domain-wise

Visualizes model rankings using bar charts

Saves final rankings and plots automatically

**🧠 Models Compared**

BERT

RoBERTa

DistilBERT

ALBERT

📂 Domains Analyzed

Politics

Sports

Medicine

**📌 Evaluation Criteria**
Criterion	Type
Accuracy	Benefit
Precision	Benefit
Recall	Benefit
F1-Score	Benefit
Inference Time	Cost
Model Size	Cost

All criteria are assigned equal weights.

**🛠️ Technologies Used**

Python

NumPy

Pandas

Matplotlib

📁 Project Structure
├── results/
│   ├── Politics_topsis_graph.png
│   ├── Sports_topsis_graph.png
│   ├── Medicine_topsis_graph.png
│   └── text_classification_topsis_results.csv
├── topsis_text_classification.py
└── README.md

⚙️ How TOPSIS Is Implemented

Normalize the decision matrix

Apply equal weights to all criteria

Identify ideal best and ideal worst solutions

Compute distances from ideal solutions

Calculate TOPSIS scores

Rank models based on scores

**📊 Output**

CSV file containing domain-wise model rankings

Bar plots showing TOPSIS scores for each domain

Sample output columns:

Domain

Model

TOPSIS Score

Rank

<img width="495" height="329" alt="image" src="https://github.com/user-attachments/assets/79e9f5dc-7864-476e-8615-c109f8d80a8f" />


**▶️ How to Run**

Clone the repository:

git clone https://github.com/your-username/topsis-text-classification.git


Install required libraries:

pip install numpy pandas matplotlib


Run the script:

python topsis_text_classification.py


Results will be saved inside the results/ folder.

**📈 Use Cases**

Model selection in NLP systems

Multi-criteria decision-making problems

Academic projects and research

Comparative analysis of ML models

**📚 Key Learning Outcomes**

Practical understanding of TOPSIS

Hands-on experience with multi-criteria model evaluation

Domain-wise comparison of transformer models

Data visualization for decision analysis

**🤝 Contributions**

Contributions, suggestions, and improvements are welcome.

**📬 Contact**

Swayam Gupta
Feel free to connect on LinkedIn or GitHub for discussions and collaborations.
