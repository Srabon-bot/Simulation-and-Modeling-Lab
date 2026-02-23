# 📊 Customer Service Wait Time Simulation

## 👤 Student Information
* **Name:** Md. Shahriar Hossain Srabon
* **ID:** 0432310005101056
* **Section:** B1
* **Batch:** 53

---

## 🧮 Assignment Overview
This project simulates and analyzes customer wait times in a service center under two different conditions — regular days and busy days — using Python. It applies core concepts of probability distributions, statistical analysis, and data visualization through simulation.

---

## 📋 Contents
* Generation of **3,000 wait times** using a **Uniform Distribution** (Regular Days)
* Generation of **3,000 wait times** using a **Normal Distribution** (Busy Days)
* Data cleaning — replacing negative wait times with 0
* Calculation of:
  * Mean
  * Median
  * Standard Deviation
  * Maximum Wait Time
* Plotting histograms:
  * Side-by-side subplots for direct comparison
  * Overlaid histograms with transparency

---

## 🛠️ Libraries Used
* **NumPy** – for random number generation and statistical calculations
* **Matplotlib** – for histogram plotting and visualization
* **Seaborn** – imported for extended styling support

---

## 📊 Visualization
The project visualizes both distributions using:
- A **two-subplot histogram** comparing regular and busy day wait times side by side
- An **overlaid histogram** with transparency to highlight distribution differences on a single graph

---

## 📐 Distribution Details

| Day Type | Distribution | Parameters |
|---|---|---|
| Regular Days | Uniform | Min = 2 min, Max = 12 min |
| Busy Days | Normal | Mean = 8 min, Std Dev = 2 min |

---

## 🎯 Learning Outcomes
* Understanding and applying probability distributions (Uniform & Normal)
* Simulating real-world scenarios using `numpy.random`
* Cleaning and validating simulated data
* Computing descriptive statistics programmatically
* Visualizing and comparing distributions using Matplotlib
* Strengthening problem-solving skills in simulation and modeling

---

## ✅ Conclusion
This assignment provides hands-on experience with simulation techniques and statistical analysis, demonstrating how different probability distributions model real-world customer behavior. It serves as a strong foundation for further studies in simulation modeling, queuing theory, and data-driven decision making.
