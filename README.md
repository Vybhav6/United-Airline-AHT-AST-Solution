# United-Airline-AHT-AST-Solution

---

# Optimizing Call Center Efficiency for Enhanced Customer Experience

---

##  Project Overview

This project focuses on improving call center efficiency and enhancing customer experience for United Airlines using a **data-driven approach**. The analysis aims to reduce Average Handle Time (AHT), improve Average Sentiment Tone (AST), and optimize customer-agent interactions through actionable insights.

---

##  Dataset Description

The project uses the following datasets:

* **calls.csv**
  Contains detailed call interaction data such as call timings, agent assignment, and transcripts.

* **customer.csv**
  Includes customer details like customer ID, name, and loyalty status (elite level).

* **reason.csv**
  Maps each call to its primary reason (e.g., baggage, booking, IRROPS).

* **sentiment_statistics.csv**
  Provides sentiment-related metrics such as:

  * Agent tone
  * Customer tone
  * Average sentiment score
  * Silence percentage

 These datasets are used to analyze performance, behavior, and operational inefficiencies. 

---

##  Objectives

### Key Business Goals

* Reduce **Average Handle Time (AHT)**
* Improve **Average Sentiment Tone (AST)**
* Enhance **customer satisfaction**
* Reduce unnecessary agent workload

---

##  Problem Statements

### S1: Identify Drivers of High AHT & AST

* What agent-specific factors increase call duration?
* Does customer sentiment impact AHT?
* How do call types affect handling time?

### S2: Reduce Agent Workload via Self-Service

* Which issues can be resolved without agents?
* How can IVR systems be improved?
* What automation strategies reduce workload?

---

##  Data Processing

* Memory optimization reduced dataset size by **13.2%**
* Improved computational efficiency and processing speed
 

---

##  Exploratory Data Analysis

### Key Visual Insights

* Call reasons significantly impact waiting time and AHT
* High volume calls observed during **7 AM – 6 PM**
* Clustering revealed patterns in:

  * Waiting time
  * Sentiment
  * Call duration

---

##  Machine Learning Insights

###  AHT Prediction (Random Forest Model)

Top influencing factors:

1. **Silence Percentage (Most Important)**
2. Average Sentiment
3. Hour of Day
4. Waiting Time
5. Customer Tone

Reducing silence and improving interaction quality can significantly reduce AHT.


---

###  AST Prediction

Top influencing factors:

1. **Handle Time (HT)**
2. Call Reasons (Mileage Plus, Checkout, Communications)
3. Silence Percentage
4. Customer Tone

 Longer calls tend to correlate with worse sentiment.


---

## 🧠 Key Insights

* Complex issues like **IRROPS, Baggage, Post Flight** → High AHT (14–25 min)
* Simple issues like **Digital Support, Seating** → Low AHT → Good candidates for automation
* Customer sentiment drops by **~33%** when agent tone is negative
* High AST observed in:

  * Checkout
  * Traveler Updates
  * Unaccompanied Minor


---

##  Root Cause Analysis (4 WHYs)

1. **Why high AHT?**
   → Complex issues + poor agent tone

2. **Why complex calls take longer?**
   → Lack of streamlined workflows

3. **Why IRROPS worst?**
   → Limited self-service + unclear communication

4. **Why agents overloaded?**
   → Repetitive tasks not automated


---

##  Recommendations

###  Process Improvements

* Streamline workflows for complex issues
* Provide better tools for agents

###  IVR & Automation

* Add self-service options for:

  * Baggage
  * Booking
  * Digital support
* Specialized IVR for:

  * Disability support
  * IRROPS

###  Proactive Communication

* Notify customers via SMS/email for delays & cancellations
* Reduce inbound call volume

###  Agent Training

* Improve empathy and tone
* Encourage personalized communication

###  Operational Enhancements

* Callback options for calm/polite customers
* Automate repetitive queries

*(Pages 15–16)* 

---

##  Expected Outcomes

* Reduced AHT and AST
* Improved customer satisfaction
* Lower agent workload
* Better resource utilization
* Faster issue resolution

---

## 🛠️ Tech Stack (Inferred)

* Python
* Pandas / NumPy
* Matplotlib / Seaborn
* Scikit-learn (Random Forest)
* NLP for transcript analysis

---

##  Conclusion

This project demonstrates how **data analytics + machine learning + process optimization** can significantly improve call center performance. By focusing on automation, sentiment improvement, and efficient workflows, organizations can deliver better customer experiences while reducing operational costs.

---

Click for detailed PPT - https://canva.link/tn806zn3nboh6fx

