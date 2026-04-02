# Introduction to Intelligent Systems - Assignment



## Q1 — Fuzzy Logic System: Washing Machine Cycle Time



### Problem Statement

Design a fuzzy logic system to determine the **washing machine cycle time** based on two inputs: **Dirt Level** and **Load Size**.



### Inputs \& Outputs

|Variable|Type|Range|Fuzzy Sets|
|-|-|-|-|
|Dirt Level|Input|0 – 10|Low, Medium, High|
|Load Size|Input|0 – 10|Small, Medium, Large|
|Cycle Time|Output|0 – 90|Short, Medium, Long|

### 

### Fuzzy Rules (9 Rules)

|Rule|Dirt Level|Load Size|Cycle Time|
|-|-|-|-|
|1|Low|Small|Short|
|2|Low|Medium|Short|
|3|Low|Large|Medium|
|4|Medium|Small|Short|
|5|Medium|Medium|Medium|
|6|Medium|Large|Medium|
|7|High|Small|Medium|
|8|High|Medium|Long|
|9|High|Large|Long|

### 

### Methodology

* **Inference Method:** Mamdani
* **Defuzzification:** Centroid method
* **Library Used:** scikit-fuzzy

### 

### How to Run

1. Open [Google Colab](https://colab.research.google.com)
2. Upload `Q1\\\\\\\_Fuzzy\\\\\\\_Washing\\\\\\\_Machine.ipynb`
3. Click **Runtime → Run All**

### 

### Outputs

* Membership function plots for Dirt Level, Load Size and Cycle Time
* Test results table showing cycle time for 5 sample inputs
* Heatmap (Rule Viewer) showing cycle time for every combination of Dirt Level and Load Size



## Dependencies

All dependencies are installed automatically inside the notebook using `!pip install`.

|Library|Purpose|
|-|-|
|`scikit-fuzzy`|Fuzzy logic inference system|
|`numpy`|Numerical computation|
|`matplotlib`|Plotting membership functions and graphs|
|`seaborn`|Heatmap (Rule Viewer)|



## Credits

**Developed by: Vibhuti Malik
Course Project:** Introduction to Intelligent Systems
**Institution:** Manipal University Jaipur

\---

## License

This project is open-source for learning and portfolio use. No commercial usage allowed without permission.

