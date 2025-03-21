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
  
   
### **Algorithm Used: K-Nearest Neighbors (KNN)**  

### **Why is KNN Preferred?**  
KNN is chosen because:  
1. **Easy to Implement** – It’s simple and doesn’t require complex training.  
2. **Non-Parametric** – It makes no assumptions about data distribution, making it flexible.  
3. **Good for Small Datasets** – Works well when the dataset size is manageable.  
4. **Handles Multi-Class Classification** – Can classify resumes into multiple categories.  



### **Advantages of Using KNN**  
✅ **No Training Phase** – Unlike deep learning, KNN doesn’t need a long training process.  
✅ **Interpretable & Simple** – Easy to understand and visualize.  
✅ **Adapts to New Data** – Can classify new resumes without retraining the whole model.  
✅ **Works with Multi-Class Data** – Can handle multiple job categories effectively.  

However, KNN can be **slow for large datasets** because it calculates the distance for each new resume. If speed is an issue, alternatives like **Naïve Bayes or SVM** could be used.

### **Best Performing Algorithm: KNN** ✅  

Here’s a simple breakdown of the results:  

- **Naïve Bayes** → **Accuracy: 8.8%** (Very poor) ❌  
- **SVM** → **Accuracy: 50%** (Average) ⚠️  
- **KNN** → **Accuracy: 79.4%** (Best) ✅  

### **Why KNN performed best?**  
- It works well with small datasets.  
- It considers similarity between data points rather than making assumptions (like Naïve Bayes).  
- Unlike SVM, it doesn’t struggle with class imbalances in this case.  

### **Final Verdict:**  
KNN is the best choice for your dataset! 🚀


