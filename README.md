
## 📌 Project Title

> BMI & Health Risk Calculator


## 👥 Team Name & Members

**Team Name:** `Visionaimedics`

         Full Name 
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

      Task Carried Out
  - Gideon Ezekiel - Built the Patient class and RecordsManager class 
  -  Oladeji David Adegboyega - Handled data loading and cleaning with Pandas 
  -  ⁠Ajanaku Opemipo - Created Histogram of BMI distribution using Matplotlib 
  - Afolabi Doyinsola - Wrote standalone functions and the main program loop 
  -  Edah Alake - Wrote the README and assembled the PDF report
  -  Glory Bagai - Plot the Bar chart of risk categories using seaborn
  -  Agunbiade Simbiat Mogbonjubola- Created the assembled PDF report
  -  Taiwo Yemisi - Created the Scatter plot of BMI vs Age
  -  Abayomi Abiodun -Led the project by explaining some of the best approaches to solving the task
  - Godwin Udo - Assisted in building the Patient class and RecordsManager class
  -  cojiako-hub - Coordinate the team and the activities that enhance the success of the project 
  -  Abdullah Salaudeen - Assisted in handling data loading and cleaning with Pandas




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
git clone https://github.com/Team-visionaimedics-mini-project/visionaimedics_mini_project.git
cd visionaimedics_mini_project
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

The `BMI & Health Risk Calculator.pdf` one-page PDF report is located in the `visionaimedics_mini_project/` folder.
It covers: project overview, technical summary, challenges faced, and team contributions.

