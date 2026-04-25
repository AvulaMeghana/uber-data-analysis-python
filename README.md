# 🚖 Uber Data Analysis using Python

## 📌 Business Problem

You are a Data Analyst at Uber.

Riders are facing two major issues:

* Drivers cancel rides
* “No Cars Available” message

This leads to **thousands of failed bookings**, especially for airport trips.

🎯 Goal:
Identify **why rides are failing** and suggest **data-driven solutions**.

---

## 📊 What the Data Told Us

| Finding                            | Root Cause                              |
| ---------------------------------- | --------------------------------------- |
| 58% of ride requests fail          | Supply-demand mismatch                  |
| Airport → City gap (5–9 PM)        | Drivers don’t return after airport drop |
| City → Airport gap (5–9 AM)        | Drivers avoid airport trips             |
| Early Morning & Late Evening worst | Demand exceeds driver availability      |

---

## 📈 Key Insights

* High cancellations in **City rides**
* High “No Cars Available” at **Airport**
* Peak demand occurs during **rush hours**
* Different routes have **different problems**

---

## 🛠️ Recommended Solutions

| # | Recommendation         | Action                         | Expected Impact                |
| - | ---------------------- | ------------------------------ | ------------------------------ |
| 1 | Airport Waiting Bonus  | Pay drivers to wait after drop | Reduces “No Cars” at Airport   |
| 2 | Night Shift Premium    | Increase fares at night        | More drivers during low supply |
| 3 | Pre-position Fleet     | Move drivers before peak time  | Better demand handling         |
| 4 | Guaranteed Return Fare | Combine trips                  | Reduces cancellations          |
| 5 | Wider Search Radius    | Expand pickup range            | More driver availability       |

---

## 🧰 Tools Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn

---

## 📁 Project Files

* `uber_analysis.ipynb` → Full analysis
* `uber_data.csv` → Dataset

---

## 💡 Conclusion

This project shows how data can be used to:

* Identify real-world problems
* Understand patterns
* Suggest actionable solutions

🚀 This is part of my learning journey in Data Analytics.
