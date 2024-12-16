# Medical Text Classification Repository

This repository contains a comprehensive project for classifying medical transcriptions into corresponding medical specialties. It involves text preprocessing, handling class imbalances, and implementing various machine learning and deep learning models, including transformer-based architectures like BERT and PubMedBERT.

## Project Structure

The repository is organized into folders and files as follows:

### Files in the Root Directory:
- **`LICENSE`**: License information for the repository.
- **`README.md`**: Documentation file.
- **`report.pdf`**: Detailed project report, including methodology and results.
- **`analyzing_error.ipynb`**: Notebook for error analysis and evaluation of models.

### **13 Classes Folder**
Contains the implementation and results for reducing medical specialties to 13 classes:
- **`medical_balancing_dataset.ipynb`**: Notebook for handling class imbalance in the dataset.
- **`medical_lstm_2_(1).ipynb`**: Implementation of LSTM-based classification.
- **`medical_svm_pp_LR_2.ipynb`**: SVM and Logistic Regression implementation with preprocessing.
- **`results_r.zip`**: Compressed folder with results and evaluation metrics for 13-class models.

### **40 Classes Folder**
Contains the implementation and results for the original 40-class dataset:
- **`medical_dataset_bert.ipynb`**: BERT-based classification notebook.
- **`medical_lstm.ipynb`**: LSTM-based classification implementation.
- **`medical_svm_pp_LR.ipynb`**: SVM and Logistic Regression implementation with preprocessing.
- **`results.zip`**: Compressed folder with results and evaluation metrics for 40-class models.

## Key Features
1. **Text Preprocessing**:
   - Removing punctuation, converting to lowercase.
   - Stopwords removal, stemming, and lemmatization.

2. **Class Imbalance Handling**:
   - Reduction of classes to 13 by grouping underrepresented classes.

3. **Model Implementations**:
   - **Traditional Machine Learning**: Support Vector Machines (SVM) and Logistic Regression.
   - **Deep Learning**: LSTM and Bi-LSTM architectures.
   - **Transformers**: BERT and PubMedBERT.

4. **Error Analysis**:
   - Analysis of misclassified cases using confusion matrices and classification reports.

## Results
- **13 Classes**: PubMedBERT achieved the highest accuracy of **40.8%**.
- **40 Classes**: Detailed results for each model are provided in the `report.pdf` and corresponding results files.

## License
 - This project is licensed under the terms of the LICENSE file in this repository.

## Acknowledgments
- Data preparation and modeling notebooks created by the contributors.
- Transformer models implemented using Hugging Face Transformers.
- For further details, refer to the report.pdf.


Let me know if you want any modifications!
