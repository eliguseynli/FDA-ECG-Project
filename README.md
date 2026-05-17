# Functional Data Analysis of ECG Heartbeat Signals


## Project Description

The project applies Functional Data Analysis ideas to ECG heartbeat signals from the ECG200 dataset. Each ECG signal is treated as a curve observed over a normalized time interval.

The main goal is to investigate whether Functional Data Analysis techniques can help identify differences in the shape of ECG signals between the two classes.

## Dataset

The ECG200 dataset contains 200 ECG heartbeat signals. Each signal has 96 time points. The dataset has two classes.

In this project, each ECG signal is interpreted as one functional observation.

## Methods Used

- Functional representation of ECG signals
- Smoothing using the Savitzky-Golay filter
- Mean function comparison by class
- Functional PCA approximation
- Logistic regression using the first three FPCA scores

## Main Results

The first three functional principal components explain approximately 79% of the total variation in the ECG curves.

Using only the first three FPCA scores, logistic regression achieved about 80% mean cross-validation accuracy.

## Files

- `Ali_Huseynli_FDA_ECG_Project.pdf`: final project report
- `Functional_Data_Analysis_of_ECG_Heartbeat_Signals.ipynb`: Google Colab notebook with code, plots, and outputs

## Author

Ali Huseynli
