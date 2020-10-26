# ML-Project-Classification-With-Python
Maching Learning Project : A classification problem using K Nearest Neighbor(KNN), Decision Tree, Support Vector Machine, and Logistic Regression algorithms
# Table of Contents:
- [Overviw](#overview)
- [About Dataset](#about-dataset)
- [Alogotithms and Technologies](#algorithms-and-technologies)
- [Evaluation](#evaluation)
- [Few Take Aways](#few-take-aways)
- [References](#references)
- [Author Infos](#author-infos)
---
## Overview
In this Mini Project, we'll try to practice all the classification algorithms that we learned in the [Machine Learning With Python](https://www.coursera.org/learn/machine-learning-with-python) course. So, we'll load a dataset using Pandas library, and apply the following algorithms, and find the best one for this specific dataset by accuracy evaluation methods.

---
## About Dataset
This dataset is about past loans. The Loan_train.csv data set includes details of 346 customers whose loan are already paid off or defaulted. It includes following fields:

<table>
  <thead>
    <tr><th> Field </th><th> Description </th></tr>
  </thead>
  <tr>
    <td>Loan_status</td>
    <td>Whether a loan is paid off on in collection</td>
  </tr>
  <tr>
    <td>Principal</td>
    <td>Basic principal loan amount at the</td>
  </tr>
  <tr>
    <td>Terms</td>
    <td>Origination terms which can be weekly (7 days), biweekly, and monthly payoff schedule</td>
  </tr>
  <tr>
    <td>Effective_date</td>
    <td>When the loan got originated and took effects</td>
  </tr>
  <tr>
    <td>Due_date</td>
    <td>Since it’s one-time payoff schedule, each loan has one single due date</td>
  </tr>
  <tr>
    <td>Age</td>
    <td>Age of applicant</td>
  </tr>
  <tr>
    <td>Education</td>
    <td>Education of applicant</td>
  </tr>
  <tr>
    <td>Gender</td>
    <td>The gender of applicant</td>
  </tr>
</table>

You can download the dataset **Loan_train.csv** by clicking [here](https://s3-api.us-geo.objectstorage.softlayer.net/cf-courses-data/CognitiveClass/ML0101ENv3/labs/loan_train.csv)

---
## Algorithms and Technologies
**We used:**
- Python (Pandas, seaborn, matplotlib,numpy) and the amazing ML library **Scikit-learn**  
- IBM Cloud (Waston Studio, Jupyter Notebook)

**For building our models we will be using the folowing algorithms:**
- K Nearest Neighbor(KNN)
- Decision Tree
- Support Vector Machine
- Logistic Regression

---
## Evaluation
The report below shows the accuracies of all built models using different evaluation metrics:

<table>
  <thead>
    <tr><th> Algorithm </th><th> Jaccard </th> <th> F1-score </th><th> LogLoss </th></tr>
  </thead>
  <tr>
    <td>KNN</td>
    <td>0.67</td>
    <td>0.63</td>
    <td>NA</td>
  </tr>
  <tr>
    <td>Decision Tree</td>
    <td>0.76</td>
    <td>0.77</td>
    <td>NA</td>
  </tr>
  <tr>
    <td>SVM</td>
    <td>0.80</td>
    <td>0.76</td>
    <td>NA</td>
  </tr>
  <tr>
    <td>Logistic Regression</td>
    <td>0.74</td>
    <td>0.70</td>
    <td>0.67</td>
  </tr>
</table>

---
## Few Take Aways

---
## References
- [Machine Learning With Python](https://www.coursera.org/learn/machine-learning-with-python)
---
## Author Infos
- LinkedIn - [Nour Eddine ZEKAOUI](https://www.linkedin.com/in/nour-eddine-zekaoui-ba43b1177/)
- You can view my verified achievement from Coursera and IBM: [Coursera Certification](https://www.coursera.org/account/accomplishments/verify/KWS4X9SS5WEH) - [IBM Badge](https://www.youracclaim.com/earner/earned/badge/1acbd652-ea5f-42bf-ba30-7366c11e4900)
---
[Back To The Top](#ml-project-classification-with-python)
