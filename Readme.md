# 📊 Mental Health & International Students 

> **Challenge**: Investigate whether international students are at higher risk of mental health difficulties, and explore how length of stay affects depression, social connectedness, and acculturative stress.

## 🌍 Context

A Japanese international university surveyed students in 2018 and published findings in 2019, approved by multiple ethical boards. The study revealed:

- International students face **higher mental health risks** than the general population.
- **Social connectedness** and **acculturative stress** are strong predictors of depression.

---

## 🧪 Methodology 

- ✅ Filtered international students (`inter_dom == "Inter"`)
- 📊 Aggregated scores by **length of stay** (`stay`)
- 🔍 Analyzed three key metrics:
  - `todep`: Depression score (PHQ-9)
  - `tosc`: Social connectedness score (SCS)
  - `toas`: Acculturative stress score (ASISS)

---

## 📈 Visualizations

Three line charts show how mental health indicators vary with time spent in the host country:

- **Depression vs. Stay**
- **Social Connectedness vs. Stay**
- **Acculturative Stress vs. Stay**
---

## 💡 Insights

- 📉 Depression scores fluctuate but tend to **decrease** with longer stays.
- 🤝 Social connectedness improves slightly over time.
- 🌍 Acculturative stress is **highest early on**, then declines supporting the original study.

---

## 🛠️ Tools Used / Outils Utilisés

- Python 3.x
- Pandas
- Matplotlib
- Jupyter Notebook
---


