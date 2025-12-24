# 2025-12-24: Planning and thoughts
1. Final Goal
    1. Have network which fits on FPGA
    2. Clear anomaly metric
    3. Inputs are zero-suppressed raw LArTPC data?
1. Things to improve
    1. Better anomaly metric: Ideally, need rare/BSM event. Not possible within open data framework. Investigate possibility of proxy? e.g. Train on tracks, validate if showers are anomalous.
    2. Compare anomaly score (loss) to ordinary ADC based cuts: Interesting possibility.
    3. Reducing model size: Need outside help
2. To Consider
    1. Normalizing input
    2. Which dataset to use? Would ideally need data with labels. uB public only labels for nu. Maybe PiLArNet?
3. To Do
    1. Explore both datasets to see which would be a better fit