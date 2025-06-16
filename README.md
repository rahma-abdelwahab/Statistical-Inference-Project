# 📊 Exploring Confidence Intervals & Sample Size Impact in R

This project explores the **statistical relationship between sample size and confidence interval width** using R. It demonstrates how **larger datasets reduce uncertainty and improve estimate precision**, using a real-world diabetes dataset.

---

## 📝 Project Summary

The notebook guides users through:

* Loading and preprocessing health data
* Visualizing dataset structure and basic statistics
* Demonstrating how **sample size affects the reliability of confidence intervals**
* Highlighting how **larger samples produce narrower, more stable intervals**, while **smaller samples introduce more variability**

---

## 🚀 Key Features

### 📦 Package Management

* Automatically installs and loads key R packages:

  * `quantmod`, `ff`, `foreign`, `R.matlab`, `readr`
  * `ggplot2`, `corrplot`, `caret`, `dplyr`, `tidyr`, `tidyverse`

### 📂 Data Loading

* Reads the `diabetes_dataset.csv` into an R DataFrame using `readr::read_csv()`

### 🔍 Data Exploration

* Provides structural overview and summary statistics using `summary()` and other descriptive tools

### 📐 Confidence Interval Analysis

* Demonstrates the theoretical and practical impact of **sample size** on confidence intervals

  * **Smaller sample sizes** → wider intervals → more uncertainty
  * **Larger sample sizes** → narrower intervals → more stable and accurate estimates

---

## 📊 Dataset Info

* **File:** `diabetes_dataset.csv`
* **Description:** Contains health-related features for individuals with/without diabetes, used here for statistical sampling and inference.

---

## 🧰 Technologies Used

* **Language:** R
* **Environment:** Jupyter Notebook with R kernel (or RStudio)
* **Libraries:**

  * Data Manipulation: `dplyr`, `tidyr`, `tidyverse`
  * Visualization: `ggplot2`, `corrplot`
  * I/O: `readr`, `foreign`, `R.matlab`
  * Statistical Modeling: `caret`, `quantmod`, `ff`

---

## ▶️ How to Run

1. **Install R** on your system ([https://cran.r-project.org/](https://cran.r-project.org/))
2. **Install Jupyter** with the R kernel OR use **RStudio**
3. **Install necessary R packages**:

   * The notebook auto-installs any missing libraries using `install.packages()`
4. **Download the dataset**: Ensure `diabetes_dataset.csv` is in the same folder as the notebook
5. **Open and execute the notebook** in your R environment


