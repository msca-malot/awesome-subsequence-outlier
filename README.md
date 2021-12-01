# awesome-subsequence-outlier

## general

- [TKDE 2010] Anomaly detection for discrete sequences: A survey
- [ACM CSUR 2018] Spatio-temporal data mining: A survey of problems and methods
- [IJIM 2019] Real-time big data processing for anomaly detection: A survey

## anomalous trajectories

### survey

- [ACM TMIS 2020] Trajectory Outlier Detection: Algorithms, Taxonomies, Evaluation, and Open Challenges

### specific

- [CIKM 2010] TOP-EYE: Top-k evolving trajectory outlier detection
- [UbiComp 2011] iBAT: Detecting anomalous taxi trajectories from GPS traces
- [KDD 2016] Mantra: A scalable approach to mining temporally anomalous sub-trajectories
- [TITS 2013] iBOAT:Isolation-based online anomalous trajectory detection <img src="star-solid.svg" width="15" height="15">
- [TKDD 2014] Anomaly detection from incomplete data (BT-miner) <img src="star-solid.svg" width="15" height="15">
- [PMC 2015] Disorientation detection by mining GPS trajectories for cognitively-impaired elders (iBDD) <img src="star-solid.svg" width="15" height="15">
- [ICPR 2016] Granular trajectory based anomaly detection for surveillance (ROSE) <img src="star-solid.svg" width="15" height="15">
- [TODS 2017] Outlier detection over massive-scale trajectory streams (TN-outlier) <img src="star-solid.svg" width="15" height="15">

### datasets

- [GPS-UCI](https://archive.ics.uci.edu/ml/datasets/) 603 trajectories with 5,317 different points; the number of points per trajectory exceeds 2,000 (sparse)
- [Geolife](https://www.microsoft.com/en-us/research/publication/geolife-gps-trajectory-dataset-user-guide/) 17,621 trajectories with 152,241 different points; the number of points per trajectory exceeds 5,000
- [Manhattan](https://www.cs.cornell.edu/%E2%88%BCarb/data/Manhattan-taxi-trajectories)  1,000 taxi trajectories collected over a 1-year period; the number of points per trajectory exceeds 1,000 (sparse)
- [Geomesa](https://www.geomesa.org/) (1) taxi 13-1 containing 1.89 million trajectories, (2) taxi 13-2 containing 3.69 million trajectories, and (3) taxi 15 containing 57,000 trajectories; each trajectory contains more than 1,500 different points (sparse)

### evaluation metrics

usually ground truth is synthesized; random noise-injection approaches.

F-measures and AUC (accuracy of finding outlier (sub-)trajectories)

## anomalous time-series
