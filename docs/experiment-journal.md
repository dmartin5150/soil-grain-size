# Experiment Journal

## Project Objective

Learn how to solve a real computer vision problem from end to end, including model selection, experimentation, evaluation, and productization.

---

## Initial Observations

### Dataset

- Only 24 independently labeled soil samples.
- Each soil sample contains multiple photographs.
- Images belonging to the same sample must remain together during train/validation splitting.
- Camera metadata includes pixels-per-millimeter information.
- The target is an 11-point cumulative grain-size distribution.
- Predictions must be monotonic and end at 100%.

### Initial Hypotheses

1. Transfer learning should perform better than training a CNN from scratch due to the small dataset.
2. Physical scale normalization using PPM may improve performance.
3. Predicting grain-size mass bins and converting them to a cumulative distribution may perform better than directly predicting 11 cumulative values.
4. Higher-resolution images may improve prediction of smaller grain sizes.
5. Combining multiple photographs from each soil sample may outperform individual-photo predictions.

---

## Experiment 0 — Baseline

**Status:** Not started

**Question:** How well can we perform without using image information?

**Approach:** Predict the average training grain-size distribution.

**Result:** TBD

**What we learned:** TBD