# 📊 Probability & Statistics for AI, DS and DA

A structured summary and hands-on companion repo for the YouTube playlist:

> **[Master Probability and Statistics for Artificial Intelligence and Data Science (AI&DS) in 9 Days](https://www.youtube.com/playlist?list=PLJM7jJIw2GC2Ihr__bRSeMxzsiFMZEsx7)**
> Channel: *Artificial Intelligence & Data Science*
> **47 videos** total

---
YouTube's playlist are 47 videos in total; they're divided into two parts:
---

## 🎯 Part 1: Foundations (Videos 1–14).

### basic introduction to probability and statistics
| # (approx.) | Topic |
|---|---|
| 1 | Introduction to Data in AI/DS: Population vs. Sample |
| 2 | Data Types: Numerical (Discrete/Continuous) vs. Categorical (Nominal/Ordinal) |
| 3 | Sampling Techniques: Simple Random Sampling |
| 4 | Sampling Techniques: Stratified, Systematic & Cluster Sampling, and Sampling Bias |

### Descriptive Statistics
| # (approx.) | Topic |
|---|---|
| 5 | Descriptive Statistics: Mean, Median, Mode |
| 6 | Descriptive Statistics: Variance & Standard Deviation |
| 7 | Descriptive Statistics: Range, IQR & Coefficient of Variation |
| 8 | EDA: Quantiles & Percentiles |
| 9 | EDA: Outlier Detection (IQR Rule & Z-Score Rule) |
| 10 | Random Variables: Discrete vs. Continuous, Introduction to PMF/PDF |
| 11 | Random Variables: Cumulative Distribution Function (CDF) |

### Probability Distributions
| # (approx.) | Topic |
|---|---|
| 12 | Probability Distributions: Uniform & Binomial Distributions |
| 13 | Probability Distributions: Poisson Distribution |
| 14 | Probability Distributions: Normal/Gaussian, Standard Normal (Z), and the Empirical Rule (68-95-99.7); Skewness & Kurtosis |

📓 A fully executable Jupyter Notebook (`prob_stats_masterclass.ipynb`) implements every one of these topics with math, code, visualizations, and practice exercises — see below for details.

---

## 🎯 Part 2: Beyond the Basics (Videos 15–47)

> The topics below represent the **typical continuation** of a course at this stage — moving from single-variable descriptive/probability foundations into multivariate relationships, sampling theory, and inferential statistics. Treat this as a **best-guess roadmap**, not a confirmed transcript of the playlist.

### More Probability Distributions
| # (approx.) | Topic |
|---|---|
| 15 | Exponential Distribution |
| 16 | Geometric Distribution |
| 17 | Hypergeometric Distribution |
| 18 | Log-Normal Distribution |
| 19 | Multinomial Distribution |

### Joint Distributions & Relationships Between Variables
| # (approx.) | Topic |
|---|---|
| 20 | Joint Probability Distributions (Discrete & Continuous) |
| 21 | Marginal & Conditional Distributions |
| 22 | Covariance |
| 23 | Correlation (Pearson) & Correlation vs. Causation |
| 24 | Independence of Random Variables |

### Bayesian Foundations
| # (approx.) | Topic |
|---|---|
| 25 | Conditional Probability |
| 26 | Bayes' Theorem & Applications (e.g., medical testing, spam filtering) |
| 27 | Law of Total Probability |

### Sampling Distributions & the Core of Inference
| # (approx.) | Topic |
|---|---|
| 28 | Sampling Distribution of the Mean |
| 29 | The Central Limit Theorem (CLT) — theory & simulation |
| 30 | Standard Error vs. Standard Deviation |
| 31 | Law of Large Numbers |

### Estimation
| # (approx.) | Topic |
|---|---|
| 32 | Point Estimation & Estimator Properties (bias, consistency, efficiency) |
| 33 | Confidence Intervals for the Mean (Known/Unknown Variance) |
| 34 | Confidence Intervals for Proportions |
| 35 | t-Distribution & When to Use It Instead of Normal |

### Hypothesis Testing
| # (approx.) | Topic |
|---|---|
| 36 | Introduction to Hypothesis Testing: Null vs. Alternative Hypotheses |
| 37 | Type I & Type II Errors, Significance Level, p-values |
| 38 | One-Sample Z-Test / T-Test |
| 39 | Two-Sample T-Test (Independent & Paired) |
| 40 | Chi-Square Test for Independence / Goodness-of-Fit |
| 41 | One-Way ANOVA |

### Regression & Applied Topics
| # (approx.) | Topic |
|---|---|
| 42 | Simple Linear Regression & Least Squares |
| 43 | Assumptions of Linear Regression & Residual Analysis |
| 44 | Multiple Linear Regression (intro) |
| 45 | A/B Testing Fundamentals for Data-Driven Decisions |
| 46 | Statistics in Machine Learning Pipelines (feature scaling, distributions, assumptions) |
| 47 | Course Wrap-Up / Capstone Case Study |

---

## 📓 What's in This Repo

| File | Description |
|---|---|
| `prob_stats_masterclass.ipynb` | Fully executable notebook covering **Videos 1–14** (Part 1 above) with LaTeX math, runnable Python (NumPy/Pandas/SciPy/Matplotlib/Seaborn), synthetic datasets, annotated plots, interpretations, and practice challenges with hidden solutions. |
| `README.md` | This file. |

> Part 2 (Videos 15–47) is **not yet implemented** as a notebook in this repo. Contributions extending the notebook series to cover inferential statistics, regression, and hypothesis testing are welcome.

## 🛠️ Tech Stack

- Python 3.11+
- [NumPy](https://numpy.org/) · [Pandas](https://pandas.pydata.org/) · [SciPy](https://scipy.org/) (`scipy.stats`) · [Matplotlib](https://matplotlib.org/) · [Seaborn](https://seaborn.pydata.org/)

## 🚀 Getting Started

```bash
git clone <your-repo-url>
cd <your-repo-name>

python3 -m venv venv
source venv/bin/activate      # Windows: venv\Scripts\activate

pip install numpy pandas scipy matplotlib seaborn jupyter
jupyter notebook prob_stats_masterclass.ipynb
```

The notebook sets `np.random.seed(42)` for full reproducibility.

## 📚 Source Playlist

- **Playlist:** [Master Probability and Statistics for AI&DS in 9 Days](https://www.youtube.com/playlist?list=PLJM7jJIw2GC2Ihr__bRSeMxzsiFMZEsx7)
- **Total videos:** 47
- **Videos implemented in this repo's notebook:** 1–14

This project is an independent, original educational resource created for hands-on practice alongside the playlist — it does not reproduce or redistribute any video content directly.

## 🤝 Contributing

- Have the real titles for Videos 15–47? Open a PR replacing the inferred outline in Part 2.
- Want to extend the notebook to cover inferential statistics (Part 2 topics)? Contributions welcome.

## 📄 License

Open for educational use — fork, adapt, and extend for your own learning or teaching.
