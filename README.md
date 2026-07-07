# NIH Topic Explorer

This project presents an interactive visualization of research topics derived from NIH-funded grant applications using AI-based topic modeling. It helps researchers, policymakers, and the public explore the scientific focus of NIH funding across different institutes and topic groupings.

## 🔍 What You Can Do

- Explore NIH research topics across multiple levels of granularity (K = 5, 10, 15, 20, 30)
- See which topics receive the most applications
- Understand which NIH Institutes and Centers (ICs) fund each topic
- Download the underlying dataset

## 📊 Visualizations

Visit the project site:  
👉 **[https://analyticsresearchinstitute.github.io/nih-topic-explorer](https://analyticsresearchinstitute.github.io/nih-topic-explorer)**

<!--
TODO: Replace the following with the actual citation.

## 📄 Citation

> Paula Fearon. *NIH Topic Explorer: Mapping Research Priorities in NIH-Funded Grants Using Topic Modeling.* arXiv preprint arXiv:xxxx.xxxxx, 2025.
> https://arxiv.org/abs/xxxx.xxxxx
-->

## 📁 Files

- `index.html`: Main web page with embedded charts
- `*_applications_by_topic_ic.html`: Interactive Plotly charts for different values of K
- `nih_topic_explorer_dataset_summary.csv`: Dataset containing topic labels and funding information

## 💡 Tech Stack

- Python (pandas, BERTopic, plotly)
- HTML/CSS
- GitHub Pages

---

This project is part of an effort to improve transparency and insight into how NIH allocates funding across biomedical research areas.
