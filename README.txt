# The Ink Pulse Project

## 📌 Overview
The Ink Pulse Project applies topic modeling techniques—**Latent Dirichlet Allocation (LDA)** and **BERTopic**—to analyze 78 weeks of anonymous student reflections submitted via "The INK," a student-led Instagram platform at Ashesi University. The goal is to uncover the latent themes and concerns of students to inform and improve support services and engagement strategies on campus.

---

## 🧠 Motivation
Despite Ashesi University’s efforts to support students through various initiatives and help units (like CCAPS and ODIP), attendance and engagement levels remain low. Our hypothesis is that many events do not target the actual pain points students face. This project seeks to bridge that gap using **unsupervised machine learning** to extract recurring themes from student feedback.

---

## 📁 Project Files

| File | Description |
|------|-------------|
| `The Hill Speaks (Responses).xlsx` | Raw anonymized student submissions |
| `weekly_raw_text_sequential.csv` | Chronologically organized weekly reflections |
| `weekly_translated_text(2).csv` | Cleaned and translated version of the raw text |
| `Algorithm Implementation.pdf` | Technical implementation details for LDA and BERTopic |
| `AI REPORT ONE.pdf` | Full project report including ethical considerations |
| `DATA DOCUMENTATION REPORT.pdf` | Data sourcing, preprocessing, and visualization pipeline |
| `README.txt` | Setup and installation instructions |

---

## 🛠️ Installation & Requirements

```bash
Python 3.10+
pip install -r requirements.txt

---

## Key Libraries
sklearn – LDA modeling

bertopic – BERTopic modeling

umap-learn – Dimensionality reduction

hdbscan – Clustering

matplotlib, wordcloud – Visualization

nltk – Text preprocessing

pandas – Data handling

---

## 🚀 Usage Instructions
Upload the following files to your Google Colab environment:

The Hill Speaks (Responses).xlsx

weekly_raw_text_sequential.csv

weekly_translated_text(2).csv

Run the notebook in order:

Load and preprocess the data

Train the LDA and BERTopic models

Generate topic visualizations

Evaluate model outputs

---

⚠️ Skip the Pidgin Translator code section—it takes ~10 minutes to run and is already completed in weekly_translated_text(2).csv.

## 📊 Evaluation
Coherence Score (LDA): ~0.23 using custom logic due to library issues

Diversity Score (BERTopic): 72%

Document Alignment Score: 0.721 (BERTopic)

Human Evaluation: Performed via Google Forms and HTML interfaces.

---

## 🔐 Ethical Considerations
Permission was obtained from the INK page administrator before using the data.

All submissions were anonymous and de-identified.

Focused on surfacing collective themes—not individual critique.

Recommendations emphasize constructive institutional improvement.

---

## ✨ Key Insights
Common student concerns include academic pressure, mental health, and engagement fatigue.

Topic modeling enables scalable, repeatable analysis of student sentiment over time.

BERTopic performed better on informal texts due to semantic embeddings.

---

## 👥 Team Members
Agatha Suzie Sieyapnji Youyou

Ben Riak Changdar

Favour Amourzang Fri Fon

Josephine Forgive Doamekpor

---

## 📚 References & Tools
GeeksforGeeks, Medium, Zilliz Blog, Analytics Vidhya

BERTopic GitHub

Google Gemini API

---

## 🧩 Future Work
Automating feedback loops with new submissions

Integrating sentiment analysis alongside topic modeling

Enabling GPT-powered topic labeling and interpretation

