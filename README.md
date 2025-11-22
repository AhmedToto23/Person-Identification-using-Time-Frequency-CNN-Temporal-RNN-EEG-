# Person-Identification-using-Time-Frequency-CNN-Temporal-RNN-EEG-


Person Identification from EEG: “Person Identification using Time-Frequency CNN + Temporal RNN”

Dataset:  PhysioNet (https://physionet.org/content/eegmmidb/1.0.0/?utm_source=chatgpt.com)
Description:
 This dataset was collected from 109 healthy subjects while they performed or imagined simple motor tasks such as :Moving the left hand, right hand, both hands, or both feet.

Each subject completed two sessions on different days, allowing for cross-session evaluation (testing generalization over time).

Goal: Train a CNN + RNN hybrid model to classify which subject (1–109) a given EEG segment belongs to, based on brainwave patterns..Goal: Train a CNN + RNN hybrid model to classify which subject (1–109) a given EEG segment belongs to, based on brainwave patterns..

Preprocessing notebook (loading, filtering, segmenting EEG)

CNN + RNN model notebook (training and evaluation)

Performance report including:
Confusion matrix
Accuracy and F1-score
Discussion of model performance

Visualization of spectrograms or feature embeddings (t-SNE)
