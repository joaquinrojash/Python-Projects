# NYC SAT Performance Analysis

![New York City schoolbus](schoolbus.jpg)

Photo by [Jannis Lucas](https://unsplash.com/@jannis_lucas) on [Unsplash](https://unsplash.com).

## Overview

This project analyzes SAT performance across New York City public high schools. SAT scores include three sections: Reading, Math, and Writing, each scored out of 800. Using a dataset of NYC schools, we explore which schools and boroughs perform best — and with the most variation — on the SAT.

## Objectives

- Identify top-performing NYC schools in Math.
- Determine the top 10 schools based on combined SAT scores.
- Find which NYC borough shows the largest variability in SAT results.

## Dataset

- **File**: `schools.csv`
- **Columns**: 
  - `school_name`
  - `average_math`
  - `average_reading`
  - `average_writing`
  - `borough`

## Tools Used

- Python 🐍
- pandas 🧮
- Jupyter Notebook 📓

---

## ✅ Results Summary
The notebook produces sorted tables of:

- `NYC schools with math scores ≥ 640.`
- `The top 10 total SAT scoring schools.`
- `Borough statistics with average and standard deviation of SAT scores.`

---

📜 License
This project is open source under the MIT License.

---

### 📦 `requirements.txt`

```txt
pandas
matplotlib
seaborn
numpy
jupyter