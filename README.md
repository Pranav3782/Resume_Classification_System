# Resume_Classification_System

This project is a Resume Classification System that categorizes resumes into different job roles using machine learning.

This project is a **Resume Classification System** that categorizes resumes into different job roles using **machine learning**. Here’s a simple breakdown of what happens in the project:

### **Step-by-step explanation:**
1. **Load the Resume Data**  
   - The dataset `UpdatedResumeDataSet.csv` contains resumes and their respective job categories.  
   
2. **Explore and Visualize the Data**  
   - Displays the unique categories of resumes and their counts.  
   - Uses bar charts and pie charts to visualize the distribution of resume categories.  

3. **Clean the Resume Text**  
   - Removes URLs, hashtags, special characters, and extra spaces.  
   - Converts resumes into a **cleaned format** for processing.  

4. **Generate Word Cloud & Word Frequency Analysis**  
   - Finds the most common words in resumes (excluding stopwords).  
   - Displays a **word cloud** to visualize frequently used words.  

5. **Convert Job Categories into Numbers**  
   - Uses **Label Encoding** to convert text labels (job categories) into numbers for machine learning.  

6. **Convert Text Data into Features**  
   - Uses **TF-IDF Vectorization** to convert resume text into numerical data.  
   - This helps the model understand which words are important.  

7. **Split Data into Training & Testing Sets**  
   - The dataset is divided into **80% training** and **20% testing** to evaluate performance.  

8. **Train a Machine Learning Model**  
   - Uses **K-Nearest Neighbors (KNN)** classifier to predict job categories based on resume text.  
   - The model is trained on the **training set** and tested on the **test set**.  

9. **Evaluate the Model’s Accuracy**  
   - Prints accuracy scores for both **training and test sets**.  
   - Displays a **classification report** showing precision and recall for each category.  

