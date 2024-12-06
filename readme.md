# **Customer Complaints Classification System**

## **Overview**  
The **Customer Complaints Classification System** is a machine learning-based application designed to classify banking-related complaints into predefined categories. The project incorporates both traditional and fuzzy classification techniques, enabling nuanced insights into complaint categorization and prioritization.

---

## **Key Features**  
- **Without Fuzzy Classification**:  
  - Uses **Multinomial Naïve Bayes** with an accuracy of **88%**.  
  - Efficient classification of complaints into predefined categories.  
  - Deployed on **Streamlit** to classify input complaints and display results.  

- **With Fuzzy Classification**:  
  - Incorporates **similarity scoring** for assigning complaints to overlapping categories.  
  - Trained using **Support Vector Machine (SVM)** with an accuracy of **79%**.  
  - Highlights real-world ambiguities, addressing scenarios where complaints span multiple categories.  

- **Anomalies and Challenges**:  
  - SVM occasionally misclassifies complaints, especially for edge cases, showcasing the limitations of the current fuzzy classification approach.  

---

## **Methodology**  
1. **Preprocessing**:  
   - Tokenization, stopword removal, and **TF-IDF vectorization** for text normalization.  
   - Similarity scores computed using **cosine similarity** for fuzzy classification.  

2. **Models Used**:  
   - **Multinomial Naïve Bayes** for traditional classification.  
   - **SVM** for fuzzy classification to handle transformed similarity-based data.  

3. **Deployment**:  
   - The system is deployed on **Streamlit**, providing an interactive interface for testing classification models.  

---

## **Applications**  
- Helps banks efficiently classify and prioritize customer complaints.  
- Identifies critical complaints for faster resolution, improving customer satisfaction.  

---

## **Future Improvements**  
- Enhancing fuzzy classification with advanced models or ensemble techniques.  
- Adding support for multilingual complaints.  
- Implementing sentiment analysis to further refine classifications.  

