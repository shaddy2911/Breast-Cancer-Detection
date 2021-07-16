# Breast-Cancer-Detection
This is the classification of cancerous tumor and non-cancerous tumor
The flow of the model is as follows:
1) Upload data to Google Colab (only if using colaboratory) if using any other IDE then just need to read it in that particular IDE
2) The whole dataset is in 'int64' except 'bare_neucleoli', had to convert 'bare_neucleoli' into NULL and then replace it with its median,
this is because there were 16 '?' object type in 'bare_neucleoli' column which had to be converted for the creation of model.
3) Dropping of 'Id' column as it was not relevant to the classification of the cancerous and non-cancerous tumor
4) I have used two Algorithms KNN and SVM (K-NearestNeighbours and Support Vector Machine)
5) KNN gave an accuracy of 97%
6) SVM gave an accuracy of 98%
7) Compared predictions of both the models
8) Created confusion Matrix for both KNN and SVM
