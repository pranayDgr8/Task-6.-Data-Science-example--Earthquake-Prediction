# Task-6.-Data-Science-example--Earthquake-Prediction
Earthquake prediction on lanl Dataset

dataset Kaggle LANL Earthquake Prediction : https://www.kaggle.com/c/LANL-Earthquake-Prediction/data?select=sample_submission.csv File descriptions:

train.csv - A single, continuous training segment of experimental data. test - A folder containing many small segments of test data. sample_sumbission.csv - A sample submission file in the correct format.

Data fields:

acoustic_data - the seismic signal [int16] time_to_failure - the time (in seconds) until the next laboratory earthquake [float64] seg_id - the test segment ids for which predictions should be made (one prediction per segment)


Applied feature engineering to generate statistcal features mainly-min,max,kurtosis,skew,quantile,mean from the "Accoustic Data".


