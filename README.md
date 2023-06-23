# EEG

Epilepsy Detection through EEG Signal Analysis 
EEG from Healthy Subjects with Eyes Closed / EEG (Epileptogenic Brain Region) from Patients with Epilepsy during Seizures

1.Reading and Data Filtering: The EEG data was retrieved and filtered from two sets of files to eliminate noise and artifacts, ensuring clean EEG signals.

2.Visualization of EEG Signals: The unfiltered and filtered EEG signals from healthy and diseased patients were displayed to highlight the differences and peculiarities between the two signal categories.

3.Feature Extraction: Relevant features were extracted from the processed EEG signals (Mean Value, Standard Deviation, Minimum Value, Maximum Value, Maximum Argument, Minimum Argument, Peak-to-Peak Value, Root Mean Square, Mean Absolute Difference, Skewness, Kurtosis Direction). These features were saved in a matrix for later use.

4.Feature Calculation and Concatenation: The requested 12 features were calculated and then concatenated to form an extended feature vector, aiming to represent significant differences between the EEG signals of healthy and diseased patients.

5.Label Vector Calculation: A label vector was generated for the utilized data, indicating the corresponding class of each EEG signal (healthy or diseased), which was used in subsequent steps.

6.SVM Algorithm Utilization: The SVM (Support Vector Machine) algorithm was implemented for classifying the EEG signals. Two types of kernels were tested: radial and linear. The algorithm was trained and evaluated using 10% test data and 90% training data, as well as 20% test data and 80% training data.

7.Performance Measures: Performance measures were calculated for the classification model, including accuracy, precision, and recall. Performance measures were computed for each combination of SVM algorithm and kernel used.

8.Confusion Matrix: The confusion matrix was calculated, indicating the number of correctly and incorrectly classified examples based on the class membership. The confusion matrix provides a detailed perspective on the classifier's performance regarding the correct and incorrect classification of EEG signals.

9.ROC Curve (Receiver Operating Characteristic): An ROC curve was generated to evaluate the performance of the classification model.


