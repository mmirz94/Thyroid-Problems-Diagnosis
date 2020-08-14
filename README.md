# Thyroid-Problems-Diagnosis

It is estimated that 200 million people in the world have some form of thyroid disease. In Canada there is a staggering number of people affected. Recent studies indicate that 1 in 10 Canadians suffer from a thyroid condition of one type or another! Of those, as many as 50% are undiagnosed! (based on data in https://thyroid.ca/)

### Types of Thyroid problem:
**1) Hypothyroidism: The thyroid fails to make enough thyroid hormones and slows down many of your body's functions**

**2) Hyperthyroidism: The thyroid makes more thyroid hormone than the body needs, which speeds up many of your body's functions.**

### The objectives of the project:
Develope a system with a low "False Negative" rate. The goal of this project is to alarm the physicians and suggest them that there might something wrong which needs further assessment. Having this in mind we can decrease the number of undiagnosed patients. 

The second objective is to have the lowest False positives (those healthy individuals who are flagged as "hyperthyroid" or "hypothyroid" by mistake). However, this is not as important as the former goal as a physician can further assess the case and make sure that the person is healthy.

### Information about the project:
In this project a SVM classifier is used to predict whether a person has a thyroid problem or not. The classifier was tuned so that it can achieve the highest f1-score for all of the three classes (specially the "hyperthyroid" & "hypothyroid" classes). 
For further information. Please visit the notebook of the project. 
