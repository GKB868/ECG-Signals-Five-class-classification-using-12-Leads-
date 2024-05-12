Here's a README file tailored to your new project:

---

# ECG Five-Class Classification using TQWT and DWT

## Introduction

Electrocardiography (ECG) classification plays a crucial role in cardiovascular medicine, assisting clinicians in diagnosing and managing heart conditions. By categorizing ECG findings through various classification systems, healthcare professionals can make accurate diagnoses and treatment decisions. Understanding key terminology and recognizing deviations from normal waveforms are essential skills in ECG interpretation.

This project aims to classify ECG signals into five classes using the TQWT (Tuned Q Wavelet Transform) and DWT (Discrete Wavelet Transform) techniques.

## Dataset Description

The PTB-XL ECG dataset is a large dataset containing 21,799 clinical 12-lead ECGs from 18,869 patients, each with a length of 10 seconds. The dataset includes two CSV files: `ptbxl_database.csv` and `scp_statements.csv`. The `ptbxl_database.csv` contains information about the ECG signals, while `scp_statements.csv` contains diagnostic statements related to the ECG signals. These two CSV files need to be aggregated to add labels, with the diagnostic superclass of `scp_statements` mapped inside `ptbxl_database` with SCP codes.

## Project Goals

1. Extract and classify 12 leads separately using deep learning models with TQWT and DWT.
2. Evaluate the accuracy, specificity, and sensitivity of the models.
3. Combine leads 2, 4, 6, and 12 and classify using deep learning models with TQWT and DWT.
4. Evaluate the accuracy, specificity, and sensitivity of the combined leads model.
5. Perform binary classification: normal (0) vs. abnormal (1).

## Usage

1. **Data Preprocessing:** Aggregate the `ptbxl_database.csv` and `scp_statements.csv` files for label addition.
2. **Feature Extraction:** Use TQWT and DWT to extract features from ECG signals.
3. **Model Training:** Utilize deep learning models to train on the extracted features.
4. **Evaluation:** Evaluate the trained models using accuracy, specificity, and sensitivity metrics.
5. **Binary Classification:** Perform binary classification using the trained models.

## Requirements

- Python 3.x
- TensorFlow
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## References

- PTB-XL dataset: [Link to dataset](https://physionet.org/content/ptb-xl/1.0.3/)
- Tuned Q Wavelet Transform (TQWT) 
- Discrete Wavelet Transform (DWT)

## Contributors

- Gourav Kumar Biswal
- [Gourav Biswal or gouravbiswal868@gmail.com]

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to customize it further based on your specific project details and requirements!
