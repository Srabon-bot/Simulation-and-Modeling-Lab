# 🎯 Monte Carlo π Estimation Simulation

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![NumPy](https://img.shields.io/badge/NumPy-Random%20Simulation-orange.svg)
![Status](https://img.shields.io/badge/Assignment-Completed-brightgreen.svg)
![Monte
Carlo](https://img.shields.io/badge/Method-Monte%20Carlo-red.svg)
![Academic](https://img.shields.io/badge/Academic-Project-lightgrey.svg)

------------------------------------------------------------------------

## 👤 Student Information

-   **Name:** Md. Shahriar Hossain Srabon
-   **ID:** 0432310005101056
-   **Section:** B1
-   **Batch:** 53

------------------------------------------------------------------------

## 🧮 Assignment Overview

This project estimates the value of **π (pi)** using a customized
**Monte Carlo Simulation** technique.

Unlike the traditional method that uses the range `[0,1]`, this
assignment personalizes the simulation using:

-   The last two digits of the student ID\
-   The number of letters in the full name

Random points are generated inside a square, and the proportion of
points that fall inside a circle is used to approximate π.

------------------------------------------------------------------------

## ⚙️ Personalization Details

### 🔢 Range Determination

-   Last two digits of ID = **56**
-   Let **R = 56**
-   Random number range = **\[0, R/10\] = \[0, 5.6\]**
-   Circle radius = **5.6**

------------------------------------------------------------------------

### 🔤 Number of Points

Full name (letters only, no spaces):

MdShahriarHossainSrabon

-   Total letters = **23**
-   Minimum random points:

200 × 23 = **4600**

------------------------------------------------------------------------

## 🧠 Simulation Logic

### 1️⃣ Random Point Generation

-   50% of points generated using `random.uniform()`
-   50% of points generated using `numpy.random.rand()` (scaled to
    custom range)

------------------------------------------------------------------------

### 2️⃣ Circle Inclusion Check

A point (x, y) is inside the circle if:

x² + y² ≤ r²

Where r = 5.6

------------------------------------------------------------------------

### 3️⃣ π Estimation Formula

π ≈ 4 × (Points Inside Circle / Total Points)

Error is calculated as:

\|π_estimated − π_actual\|

------------------------------------------------------------------------

## 📊 Output Format

The simulation prints results in tabular format:

  --------------------------------------------------------------------------
  Range Used   Total Points  Points Inside Estimated π   Error from math.pi
  ------------ ------------- ------------- ------------- -------------------

  --------------------------------------------------------------------------

------------------------------------------------------------------------

## 🔁 Repeated Simulation

The simulation is executed **5 times** using increasing sample sizes:

-   4600\
-   9200\
-   13800\
-   18400\
-   23000

This demonstrates:

-   Convergence toward actual π\
-   Reduction in estimation error\
-   Effect of sample size on accuracy

------------------------------------------------------------------------

## 🛠️ Libraries Used

-   NumPy\
-   random\
-   math

------------------------------------------------------------------------

## 📚 Learning Outcomes

-   Understanding Monte Carlo simulation\
-   Applying geometric probability\
-   Customizing simulations dynamically\
-   Comparing random generation methods\
-   Observing convergence behavior\
-   Performing statistical error analysis

------------------------------------------------------------------------

## ✅ Conclusion

This assignment demonstrates how Monte Carlo methods approximate
mathematical constants through probability and randomness.

As the number of simulated points increases, the estimated value of π
converges toward the true value, illustrating the Law of Large Numbers
in practice.

This project strengthens understanding of simulation modeling, numerical
approximation, and statistical reasoning.

------------------------------------------------------------------------
