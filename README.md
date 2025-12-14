# Diabetes Prediction Using Machine Learning

This project implements a Machine Learning model for predicting the likelihood of diabetes using patient health data.  The model is trained on a labeled dataset of medical records and can classify whether a person is diabetic or non-diabetic based on input features.  Such a system can support doctors and healthcare workers in early risk assessment and decision-making.[1]

## Dataset

The dataset used for training and validation is a structured diabetes dataset containing medical and demographic attributes along with an `Outcome` label.[1]
- Features include: pregnancies, glucose level, blood pressure, skin thickness, insulin, BMI, diabetes pedigree function, and age.[1]
- The `Outcome` column indicates diabetic (1) or non-diabetic (0) status for each record.[1]

## Features

- Data preprocessing with handling of missing values and feature standardization using `StandardScaler`.[1]
- Split into training and testing sets with an 80–20 ratio, stratified by class labels.[1]
- Implementation of a Support Vector Machine (SVM) classifier with a linear kernel for binary classification.[1]
- Evaluation using accuracy on both training and test data, with scope to extend to precision, recall, F1-score, and AUC-ROC.[1]
- Example prediction pipeline for new patient data, including scaling and model inference to output diabetic or non-diabetic result.[1]

## Technologies Used

- Programming language: Python[1]
- Libraries:  
  - `numpy`, `pandas` for data handling and analysis[1]
  - `scikit-learn (sklearn)` for preprocessing, model training (`SVC`), and evaluation metrics[1]

## Future Enhancements

- Experimenting with additional algorithms such as Logistic Regression, KNN, Decision Tree, Random Forest, Gradient Boosting, Naive Bayes, and Neural Networks.[1]
- Improving model interpretability and validating performance on larger and more diverse healthcare datasets.[1]

[1](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/images/125402517/3b7a1fed-6c43-4749-9b76-950504d9944a/image.jpg?AWSAccessKeyId=ASIA2F3EMEYE7BHRD2CV&Signature=FTuccdY%2F%2FxpJK3r7IM0z1W8%2B%2FEg%3D&x-amz-security-token=IQoJb3JpZ2luX2VjEGgaCXVzLWVhc3QtMSJGMEQCIHC2AqUsi%2FotND4bYafJbunLn9oWvzvDKHxbhjIDdBrDAiBSpMmM2DWT7U0YPb8AwNKHxqNByCfWkjVHd7VvT%2BCp7CrzBAgxEAEaDDY5OTc1MzMwOTcwNSIMvsbEp8rKyXuWBguoKtAE6YvAUGMDKgm3f1S6x9a2NyiSUz6cS7NJwSpSVhXwsOakMZ3sRnyV2R9EtCKGsrkJ9eNvuffrHxujyr5sguKQGZVy8i2apTybHJ5UGJkdS9NVRG1Yp62jEqI5tcrujGDioFIufT96Rlfe%2BaawKwEnO0bGI7vAd8ub%2B0GvBaY2Z3Gym46kO7nVmWRb301mjqIbskKsco1ntHix9bPo3uLfpCctjapXHFIK2BP1W2HEy%2F1Apixvcf3Cz7lpXbajm%2FdVYzmdduHgo1h7g4OSuCDZqyhdjhKjR0Z3I%2FtGtihY5uTK%2BJhRMHsGvo5epgRxy1H0FCuFzr%2BfPiHCIarN5j6U2C484jcCoqSUmxIbQ%2BdmIng9davFVywDy1NWvu%2B3OY2CdGzw%2FqyukVW%2BDAzDCKROpiaq5tYbcyBmsC1DMK19aV%2BW7CS8zIC8wWwdW%2FrPLhuDMGadNZcy96dPMig4lVsCaqF5QDnLWbAgO0S%2F8wEe9FwsqRhgoUd6r%2BvbWvDklVal4bxGtRXpZ9JvcU%2FoGfw9BoezJwsmLxVvq%2F1BTlNseSdIQUqssoL%2FrH86vW%2FqJ64NbIts29eqLCPXBbpseck4he6z0TiaiiUcsxzDJdlDhL%2BHJvOaJ2i6NECUSzspBTZGSbBiT47OdcSBZwV4CBhOz0hCLYmPgbkXlsP%2Bw2faRzq%2BwEUDiKkdRFFxN8p3UbqOoN9VWD7E6chYWnE5ENReNFeMYRYJANgzZtFMJGq3Eqbfr8P%2FAdBPyYpDpn3di8R14dY7WVfOzjCoyGER0un%2BJjDQ2fnJBjqZARw9wvd6tpZ19opt5zRYVOr%2FEMGPornQrdbYOinLODbNlWFpdES7QvV3F4Lz24xnyEdL93x0nro1HwnOBBykDgNvpfqqVXHQ8oW7YzSRhWwoBJnU8zi%2BM3ak8mcgzC2RtqHnNJD1cFg1A3DnkdSCoLhv55IR%2FpeF84fUeABcnFL7fOyYoh8809%2Fbbz9zsSwdnt%2FzL3YRRINKRA%3D%3D&Expires=1765700706)
