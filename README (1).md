#  JOB-SALARY-PREDICTION Analysis using Hadoop

<p align="center">
  <b>Big Data Fundamentals Project</b><br>
  <i>Implemented using Hadoop Ecosystem (HDFS, MapReduce, Hive)</i>
</p>

---

## 📌 Project Overview

This project demonstrates a **complete Big Data processing pipeline** to analyze JOB SALARY PREDICTION datasets using the Hadoop ecosystem.

With the rapid growth of population, large volumes of user require Job (AI Engineer, Data Analyst, etc.) are produced. Traditional systems struggle to process such data efficiently.

This project solves that problem using **distributed computing techniques** to extract meaningful insights such as:

* Average number of skill_count
* Top Salary Job.

---

## 🎯 Objectives

* To store large datasets using **HDFS**
* To process data using **MapReduce (Python)**
* To perform analytical queries using **Hive**
* To understand distributed data processing
* To generate insights from raw data

---

## 🏗️ Architecture

```
Raw CSV Dataset
        ↓
HDFS (Storage Layer)
        ↓
MapReduce (Processing Layer)
        ↓
Processed Output (HDFS)
        ↓
Hive (Analysis Layer)
        ↓
Insights (Top Movies)
```

---

## ⚙️ Technologies & Tools Used

* HDFS (Storage Layer)
* MapReduce (Data Processing)
* Hive (Data Analysis)
* Python
* Linux / Cloudera
* ChatGPT (Generative AI Assistance)

---

## 📊 Dataset Information

The dataset contains JOB SALARY information along with user job experience.

### 📌 Key Attributes:

* Job Title – Role of the employee
* Experience Years – Total work experience
* Education Level – Qualification (e.g., Bachelor’s, Master’s)
* Skills Count – Number of skills possessed
* Industry – Sector of work
* Company Size – Small, Medium, or enterprise
* Location – Job location
* Remote Work – Yes/No (hybrid)
* Certifications – Professional certifications count
* Salary – Compensation earned

---

## 🔄 Workflow Explanation

* The dataset is stored in HDFS for distributed storage
* MapReduce processes the data to calculate average salary
* Processed data is stored back in HDFS
* Hive is used to analyze and query the results
* Final insights such as job salary are generated

---

## 📈 Output

* Average Salary of each job
* Identification of top salary
* Structured insights from raw data

---

## 🤖 Use of Generative AI

Generative AI played an important role in this project:

* Code generation (Mapper & Reducer)
* Debugging support
* Hive query assistance
* Concept understanding of Big Data tools

---

## 🔐 Validation

All generated code and outputs were:

* Manually tested
* Verified for correctness
* Successfully executed in the Hadoop environment

---

## 🌟 Key Features

* Scalable Big Data processing
* Efficient handling of large datasets
* Distributed computing approach
* Integration of AI for enhanced productivity

---

## 🎯 Conclusion

This project successfully demonstrates how the Hadoop ecosystem can be used to process and analyze large-scale datasets efficiently.

By combining **HDFS, MapReduce, and Hive**, the system transforms raw Job Salary  into meaningful insights, enabling better decision-making in real-world scenarios.

---

## 👨‍💻 Author

**CHAHAT SINGH**  
🎓 BCA (Data Science & AI)  
🏫 Babu Banarasi Das University

---

## ⭐ Final Note

This project reflects a real-world Big Data solution where distributed computing is essential for handling large-scale data efficiently.
