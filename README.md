# Cognitive Aging Brain Analysis

> Analyzing the relationship between brain structure and cognitive function across aging using R.

---

## 🔍 Research Question

How do structural brain changes (e.g., cortical thickness, regional volume) relate to cognitive decline in aging populations?

---

## 📁 Data

- **Source**: [OpenNeuro](https://openneuro.org) — Dataset: `[데이터셋 이름/ID 추후 기입]`
- **Participants**: [N명] adults aged [범위] years
- **Key variables**:
  - Brain: regional gray matter volume / cortical thickness (preprocessed)
  - Cognition: [사용한 인지검사 이름 기입]
  - Demographics: age, sex, education

---

## 🛠️ Methods

All analyses were conducted in **R (version 4.x)**.

| Step | Method | R Package |
|---|---|---|
| Data cleaning | Outlier removal, missing data handling | `tidyverse` |
| Descriptive stats | Mean, SD, distribution | `psych` |
| Main analysis | Linear regression / mixed-effects model | `lm()` / `lme4` |
| Visualization | Scatter plots, brain-cognition plots | `ggplot2` |

---

## 📊 Key Results

> *(추후 분석 완료 후 작성)*

- Finding 1: ...
- Finding 2: ...

---

## 📂 File Structure

```
├── data/           # Raw & preprocessed data (not uploaded due to size)
├── scripts/
│   ├── 01_data_cleaning.R
│   ├── 02_descriptive_stats.R
│   └── 03_main_analysis.R
├── figures/        # Output plots
└── README.md
```

---

## 👩‍💻 Author

**Hyesoo Kwon**  
B.A. Psychology & Brain Science, Ewha Womans University  
Research Assistant, Cognitive Aging Lab, Seoul National University  
📧 [이메일 주소]  
🔗 [LinkedIn 또는 기타 링크]
