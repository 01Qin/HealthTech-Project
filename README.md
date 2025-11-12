# Heart Rate and HRV Analysis from PPG Signals

## Overview

This project analyzes photoplethysmogram (PPG) data to compute Heart Rate (HR) and Heart Rate Variability (HRV) metrics using Python. It demonstrates physiological signal processing by detecting peaks, calculating time-domain HRV metrics, and visualizing cardiac patterns.

---

## Objectives

* Detect heartbeats from PPG waveform using `scipy.signal.find_peaks`.
* Compute time-domain HRV metrics:

  * Mean PPI (ms)
  * Mean HR (bpm)
  * SDNN (ms)
  * RMSSD (ms)
* Visualize detected peaks and signal patterns.
* Compare results to standard physiological ranges.

---

## Dataset

**Source:** [BIDMC PPG Dataset - PhysioNet](https://physionet.org/content/bidmc/1.0.0/)

**Sampling Frequency:** 125–250 Hz
**Files:** CSV format containing PPG and other physiological channels.

---

## Methods

1. Load dataset with Pandas.
2. Extract PPG column.
3. Perform peak detection using `find_peaks`.
4. Compute PPI (peak-to-peak intervals).
5. Derive HRV metrics.
6. Visualize signal and statistical summaries.

---

## Example Results

| Metric   | Value    | Normal Range | Interpretation    |
| -------- | -------- | ------------ | ----------------- |
| Mean HR  | 79.3 bpm | 60–70 bpm    | Slightly elevated |
| Mean PPI | 756.7 ms | 850–1000 ms  | Moderate          |
| SDNN     | 122.8 ms | 30–60 ms     | High variability  |
| RMSSD    | 165.1 ms | 20–50 ms     | High variability  |

---

## Visualization

* **PPG Signal with Detected Peaks**
* **Distribution of PPI Intervals**

---

## Tools

* Python 3.x
* NumPy
* Pandas
* SciPy
* Matplotlib

---

## File Structure

```
HeartRate-HRV-Analysis/
├── data/
│   ├── bidmc_09_Signals.csv
│   └── README.md
├── src/
│   └── hrv_analysis.py
├── notebooks/
│   └── hrv_analysis_demo.ipynb
├── results/
│   ├── ppg_signal_plot.png
│   └── detected_peaks.png   
├── requirements.txt
├── README.md
└── LICENSE
```

---

## requirements.txt

```
numpy
pandas
matplotlib
scipy
```

---
## License
MIT License – see LICENSE for details.

