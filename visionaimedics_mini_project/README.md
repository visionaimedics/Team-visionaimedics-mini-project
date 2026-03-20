[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/dNK7xGxu)
# SPARK Academy 2026 | Mini Capstone Project

**Submission Deadline:** 20th March 2026 · 11:59 PM GMT+1  
**Submission Method:** Push all files to this GitHub Classroom repo before the deadline

---

## 📌 Project Title

> BMI & Health Risk Calculator


## 👥 Team Name & Members

**Team Name:** `Visionaimedics`

| Full Name | Task Carried Out |
1. Gideon Ezekiel - gideonezekiel2017.com
2. Oladeji David Adegboyega - oladejidavid12@gmail.com
3. Glory Bagai - bagaiglory@gmail.com
4. Agunbiade Simbiat Mogbonjubola- mogbonjubola1999@gmail.com
5. Taiwo Yemisi - oluwayemisitaiwo62@gmail.com
6. Edah Alake - alakedah777@gmail.com
7. ⁠Ajanaku Opemipo - ajanakujeremiah@gmail.com
8. Afolabi doyinsola - doyinsolalove@gmail.com
9. Abayomi Abiodun - abiodunabayomi91@mail.com
10. Godwin Udo - basseyudo86@gmail.com
11. cojiako-hub, cojiako@unilag.edu.ng
12. Abdullah Salaudeen - salaudeenabdu@gmail.com

    Task assigned 
  - Gideon Ezekiel | Built the Patient class and RecordsManager class 
  -  Oladeji David Adegboyega| Handled data loading and cleaning with Pandas 
  -  ⁠Ajanaku Opemipo | Created all three visualisations using Matplotlib 
  - Afolabi doyinsola | Wrote standalone functions and the main program loop 
  -  Edah Alake| Wrote the README and assembled the PDF report 



## 📖 What This Project Does

**BMI & Health Risk Calculator**

This program calculates a user’s Body Mass Index (BMI) using their height and weight and classifies their health risk level based on standard medical guidelines. It helps identify individuals who may be underweight, overweight, or at risk of obesity-related conditions such as cardiovascular disease or diabetes. The tool can be used by healthcare professionals, fitness trainers, or patients in clinical and wellness settings for quick health assessment and monitoring.


## 🗂️ Repository Structure

```
├── data/
│   └── 07_patient_health.csv     # Dataset provided for this project
├── report/
│   └── Visionaimedics_report.pdf     # One-page project report (push PDF here)
├── main.py                       # Main program entry point (or main.ipynb)
├── README.md                     # This file
└── requirements.txt              # List of Python libraries used
```

---

## ⚙️ How to Run This Project

### 1. Clone the repository
```bash
git clone https://github.com/SPARK-Academy/Mini-Capstone-2026-Team-Name.git
cd Mini-Capstone-2026-Team-Name
```

### 2. Install required libraries
```bash
pip install -r requirements.txt
```

> If you don't have a `requirements.txt` yet, install manually:
> ```bash
> pip install pandas matplotlib seaborn
> ```

### 3. Run the program

**If using a Python script:**
```bash
python main.py
```

**If using a Jupyter Notebook:**
```bash
    explain
```

---

## 📦 Requirements

List all libraries your project uses. Add these to your `requirements.txt` file:

```
pandas
matplotlib
seaborn
```



## 📊 Visualisations

> Description of the 3 charts in the project:
> 1. **Chart 1** — This chart shows the **distribution of BMI values** in a population using a histogram with a smooth density curve. Most individuals fall within the **25–35 BMI range**, indicating a high proportion of overweight to moderately obese cases. The distribution is **right-skewed**, with fewer individuals at very high BMI values (above 40) and some lower values around 15–20.

> 2. **Chart 2** — This bar chart shows the **distribution of patients across risk categories**. The majority of patients fall into the **Moderate risk group**, followed by a significant number in the **High risk category**, while only a small proportion are classified as **Low risk**. This suggests that most individuals in the dataset require monitoring or medical attention.

> 3. **Chart 3** — This scatter plot shows the relationship between **age and BMI across different risk categories**. High-risk patients (green) generally have **higher BMI values across a wide age range**, while low-risk patients (blue) tend to cluster at **lower BMI levels**. Moderate-risk patients (red) are spread across the middle ranges, indicating that **BMI is a stronger indicator of risk than age alone**.


---

## 🧱 Classes & Functions

> The classes and standalone functions in the project:
### **Classes:**

* *No classes implemented* — The project is function-based and does not use object-oriented programming.

---

### **Standalone Functions:**

* `convert_cm_to_mm()` — Converts tumor sizes from centimeters to millimeters.
* `get_critical_tumors()` — Filters and returns tumor sizes above a critical threshold.
* `classify_tumor()` — Classifies tumor size into risk categories (Critical, Monitor, Stable).
* `patient_report()` — Generates a formatted report for a patient including tumor status.
* `get_critical_patient_names()` — Extracts names of patients with critical tumors.
* `array_statistics()` — Computes statistical measures (min, max, mean, std) from pixel data.
* `normalize_pixels()` — Normalizes pixel intensity values to a 0–1 range.
* `extract_roi()` — Extracts a region of interest (ROI) from an image array.
* `calculate_snr()` — Computes Signal-to-Noise Ratio for image quality assessment.
* `calculate_cnr()` — Computes Contrast-to-Noise Ratio between tissues.

---



---

## 📄 Report

The one-page PDF report is located in the `report/` folder.
It covers: project overview, technical summary, challenges faced, and team contributions.

---

## ⚠️ Academic Integrity

This project was built independently by our team.
We did not share code or collaborate with any other team assigned to the same project.

---

*SPARK Academy 2026 · Mini Capstone · Submitted via GitHub Classroom*
