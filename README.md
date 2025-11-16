# AI-based LinkedIn Profile Classifier (Final Prototype)


## Project Overview

This project is an **AI-powered LinkedIn profile classifier** that categorizes profiles into professional types based on their headlines.  
It leverages **Natural Language Processing (NLP)** techniques to classify profiles such as:

- Exited Entrepreneurs  
- Serial Business Angels  
- Top Mentors  
- Big Tech C-levels  
- Board Members / Private Investors  
- Ex-Consulting Professionals  

The classifier can be useful for recruiters, networking platforms, or analysts looking to segment professional profiles automatically.

---

## Features

- Automatically reads a dataset of LinkedIn profiles (`CSV` format)  
- Classifies profiles based on the headline using **TF-IDF vectorization** and **Naive Bayes classifier**  
- Outputs a clean CSV with predicted profile types  
- Simple to extend with more categories or training data  

---

## Tech Stack / Tools Used

- **Python 3.x**  
- **Pandas** – for data manipulation  
- **Scikit-learn** – for TF-IDF vectorization and Naive Bayes classification  
- **CSV** files for input/output  

---

