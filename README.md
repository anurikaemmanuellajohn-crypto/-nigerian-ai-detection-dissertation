# A Data-Driven Framework for Differentiating AI-Generated Content and Promoting Responsible Use: A Case Study of the Nigerian Digital Ecosystem

**University of the West of Scotland**
School of Computing, Engineering and Physical Sciences
MSc Information Technology with Data Analytics — 2026
**Student:** Anurika Emmanuella John

---

##  Project Overview

This project investigates how to distinguish between AI-generated and human-written text using stylometric features within the Nigerian digital ecosystem. It addresses the linguistic bias of existing detection tools against Nigerian English and Pidgin-influenced writing, and proposes a data-driven Responsible Use framework for Nigerian institutions.

---

##  Objectives

- Build a Nigerian-specific corpus of 704 text samples (354 human, 350 AI)
- Extract stylometric features: Perplexity, Burstiness and Lexical Density
- Train machine learning classifiers: SVM and Random Forest
- Evaluate AI detection tools: GPTZero and ZeroGPT against Nigerian texts
- Propose a Responsible Use framework for Nigerian academic and professional institutions

---

##  Tools and Technologies

- Python 3.12
- Google Colab
- Pandas, NLTK, spaCy
- Scikit-learn
- Matplotlib, Seaborn
- Hugging Face Transformers (GPT-2 for perplexity)
- GPTZero and ZeroGPT (external detection tools)

---

##  Stylometric Feature Results

| Feature | Human Mean | AI Mean |
|---|---|---|
| Burstiness (σ) | 12.54 | 7.01 |
| Perplexity | 36.13 | 32.22 |
| Lexical Density | 0.4418 | 0.4395 |

---

##  Machine Learning Results

| Classifier | Accuracy | Precision | Recall |
|---|---|---|---|
| Support Vector Machine (SVM) | 68.8% | 56.5% | 92.9% |
| Random Forest | 73.0% | 62.5% | 80.4% |

**Key finding:** Burstiness was the strongest discriminating feature. Random Forest achieved the most balanced performance.

---

##  Detection Tool Evaluation

| Tool | Human Accuracy | AI Accuracy | False Positive Rate |
|---|---|---|---|
| GPTZero | 75% | 95% | 15% |
| ZeroGPT | 70% | 70% | 20% |

---

## Files Included

- `analysis.ipynb` — Main Python implementation notebook
- `Master_Dataset_700.xlsx` — Full corpus of 704 anonymised text samples
- `Dataset_With_Features.xlsx` — Dataset with all extracted stylometric features
- `figures/` — All visualisations including boxplots, scatterplot and heatmaps

---

## Ethical Statement

This project is conducted for academic research purposes only, in compliance with the Nigeria Data Protection Act (NDPA) and University of the West of Scotland ethical research standards. All human-authored texts are fully anonymised. The detection framework is designed as a supportive tool and not a punitive instrument.

---

 ## Contact

For academic enquiries please contact through the University of the West of Scotland.
