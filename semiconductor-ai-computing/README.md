## 💡 Semiconductor Industry | AI Computation & Hardware Trends

This project explores the evolution of computation in large AI models, analyzing how hardware capabilities and compute scaling have accelerated across organizations and model architectures.

#### 🔗 [Tableau Dashborad](https://public.tableau.com/views/BriefoverviewofAIcomputegrowth/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
---

## 🧭 Project Overview

- **Industry**: Semiconductor / AI Research & Development  
- **Focus**: Compute scaling trends, model performance vs. hardware investment, organizational contributions  
- **Goal**: To analyze and visualize the growing demand for compute in large-scale AI models and the performance returns from that investment.

---

## 🧰 Tools Used

- **Jupyter Notebook** – Data cleaning, feature engineering, and visualizations
- **Tableau** – Interactive dashboard to visualize compute growth and performance
- **Google Sheets** – Lightweight EDA and exploratory metrics

---

## 📊 Key Questions Answered

1. How has training computation scaled over time for top AI models?
2. What is the relationship between training compute and model performance (MMLU score)?
3. Which organizations are leading in compute-intensive AI development?
4. Are we seeing diminishing returns in performance per unit of compute?

---

## 📂 Dataset Overview

| Column | Description |
|--------|-------------|
| `Entity` | Name of the model |
| `Code` | Placeholder (can be used for unique ID if needed) |
| `Year` | Year of model release |
| `MMLU avg` | Average performance on Massive Multitask Language Understanding benchmark |
| `Training computation (petaFLOP)` | Compute used to train the model |
| `Organization` | Research group or company behind the model |

---

## 📈 Sample Insights

- **Exponential Growth**: Training compute has increased from ~36,000 petaFLOPs (GPT-2) to 80 billion (Gemini Ultra) in just four years.
- **Diminishing Returns**: After a certain compute threshold (~2.5B petaFLOPs), performance gains (MMLU) show signs of plateauing.
- **Org Spotlight**: Google DeepMind and OpenAI dominate high-compute, high-performance model development.

---

## 🧠 Visualization Previews

Include:
- **Line chart**: Training compute over time by organization
- **Scatter plot**: Compute vs. MMLU Score (log scale)
- **Bar chart**: Top 5 most compute-intensive models
- **Box plot**: Compute efficiency (MMLU per petaFLOP) by organization

---

## 🚀 Future Work

- Include **inference compute** and energy usage if available
- Add **parameter count** and **training duration**
- Integrate semiconductor hardware info (e.g. TPU, GPU type used)



## Data Pulled from Kaggle
