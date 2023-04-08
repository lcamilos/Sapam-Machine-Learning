# Sapam-Machine-

In this project, I utilized machine learning techniques to classify emails as either spam or not spam. The project involved several stages of data preprocessing, model training, and performance evaluation.

First, I loaded a CSV file containing email data and removed any duplicate rows from the DataFrame. I then created a list of labels corresponding to the email data, where the value '1' represented spam and '0' represented not spam. This list was then used to create a new column in the DataFrame with the corresponding label for each email.

After data preprocessing, I split the dataset into training and testing sets using the train_test_split function from scikit-learn. I then used the TfidfVectorizer class from scikit-learn to convert the email text into numerical vectors. The resulting vectors were fed into a Random Forest classifier, which was trained on the training set.

Using the trained model, I made predictions on the testing set and evaluated the model's performance using various metrics such as accuracy, classification report, and confusion matrix. The classification report provided detailed information on the precision, recall, and F1 score of the model, while the confusion matrix helped visualize the number of true positives, true negatives, false positives, and false negatives.

Finally, I created a new column in the original DataFrame with the predicted spam label and converted the predicted labels to '1' and '0'. The modified DataFrame was then saved to a CSV file for future use.

Overall, this project demonstrates the application of machine learning techniques to classify emails as spam or not spam, and highlights the importance of data preprocessing and model evaluation in achieving accurate results.
