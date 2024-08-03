# Classification of heartbeats with machine learning

The purpose of this project is to train models with classification algorithm in attempt to predict various types of cardiac arrhythmias based on ECG Data. According to WHO, ischaemic heart disease is the world’s biggest killer, responsible for 16% of the world’s total deaths. Every seconds count in treating heart attacks. Machine learning models could be used to indentify cardiac arrhythmias faster, helping emergency unit to prioritise patients in need.

An ECG (Electrocardiogram) is a medical test that records the electrical signals in the heart. It's a common and painless test used to quickly detect heart problems and monitor the heart's health. A healthy individual's heartbeat on an ECG is characterized by a distinctive waveform, representing normal functioning of the heart. When the heart is not functioning optimally, the ECG could detect distortions in the anticipated waveform, severe and life-threatening arrhythmias might present a different or nonexistent waveform altogether.

This repository is intended as extension of my previous project [Heartbeat ECG Classification](https://github.com/Chiuchiyin/Heartbeat-ECG-Classification) which I did for university assignment. I have also included the work in [this repository](https://github.com/Chiuchiyin/Classification-of-heartbeats-with-machine-learning/tree/main/00-Original-work) for your convenience.

# Work Plan
The original project uses [Segmented and Preprocessed dataset from MIT-BIH Arrhythmia Database](https://www.kaggle.com/datasets/shayanfazeli/heartbeat/data?select=mitbih_test.csv). The algorithm used to train the models were KNN, Random Forest, Gradient Boost and SVM. 
![The resulting models from earlier work](/img/original_model_metrics.png "Model Metrics")
While the resulting models are rather impressive, I would like to explore the possibility of building better models. What I plan to do includes:
1. Build deep learning model
2. Generate synthetic data with GAN
3. Build models with synthetic data
4. Process the raw data myself
5. Include other data sources such as Fantasia