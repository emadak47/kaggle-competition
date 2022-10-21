# Mortality Prediction & Length of Stay 
Group project for STAT3612. 

## Dataset
The dataset for this competition is electronic health record (EHR) data transformed from MIMIC-III database. Specifically, the input features are hourly aggregated time-varying vitals and labs (hourly mean, count and standard deviation).

* The index for each sample has the format: {subject_id}_{hadm_id}_{icustay_id}.
* Labs means laboratory test results (for example, hematology, chemistry, and microbiology results).
* Vital sign means patients' information routinely monitored by medical professionals and health care providers, including: heart rate, mean blood pressure, oxygen saturation, etc.
