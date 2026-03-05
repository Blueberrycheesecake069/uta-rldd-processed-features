# UTA-RLDD Processed Feature Dataset

This repository contains a processed feature dataset derived from the UTA Real-Life Drowsiness Dataset (UTA-RLDD). The original dataset provides raw driver videos from 48 participants. To simplify machine learning experimentation, these videos were processed and converted into a structured CSV dataset containing approximately **1.7 million rows of features**.

The extracted features capture both **facial fatigue indicators** and **3D head pose information**, which are commonly used for **driver drowsiness detection and driver monitoring systems (DMS)**.

---

## Dataset Features

The dataset includes the following columns:

- `perclos`
- `norm_avg_ear`
- `ear_std`
- `avg_mar`
- `yawn_count`
- `blink_rate`
- `avg_blink_dur`
- `pitch`
- `yaw`
- `roll`
- `img_path`
- `target`

These features capture important behavioral and physiological signals related to driver fatigue such as **eye closure patterns, blinking behavior, yawning frequency, and head orientation**.

---

## Dataset Summary

| Property | Value |
|--------|--------|
| Dataset | UTA-RLDD Processed Features |
| Rows | ~1.7 Million |
| Participants | 48 |
| Features | 12 |
| Format | CSV |
| Task | Driver Drowsiness Detection |

---

## Purpose

The original UTA-RLDD dataset consists of raw video recordings. Extracting usable features from these videos requires significant preprocessing. This repository provides **pre-extracted features** to help researchers and engineers focus directly on:

- Machine learning experiments
- Driver drowsiness detection models
- Driver monitoring system development
- Behavioral analysis of fatigue signals

---

## Original Dataset

This dataset is derived from the **UTA Real-Life Drowsiness Dataset (UTA-RLDD)**.

Credit goes to the researchers at the University of Texas at Arlington who created the original dataset.

---

## Author

Created by Achintya.

If you are working on **computer vision, driver monitoring systems, or fatigue detection**, feel free to connect and collaborate.
