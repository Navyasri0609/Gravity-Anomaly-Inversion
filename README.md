Gravity Anomaly Inversion using Talwani Method and FFT

## Overview

This project implements a gravity anomaly modelling and inversion workflow for subsurface density anomalies. The forward gravity response is generated using the Talwani Method for 2D rectangular bodies. The simulated gravity data is contaminated with Gaussian noise, filtered using Fast Fourier Transform (FFT) based low-pass filtering, and further refined using Gradient Descent Optimization to improve the inversion accuracy.

## Features

- Forward modelling of gravity anomalies using the Talwani Method
- Simulation of positive and negative density anomalies
- Addition of Gaussian noise to synthetic gravity data
- FFT-based frequency domain analysis
- Low-pass filtering for noise removal
- Inverse FFT for signal reconstruction
- Gradient Descent optimization for improving inversion accuracy
- Visualization of gravity anomaly, power spectrum, residual error, and optimization results

## Methodology

1. Generate a synthetic subsurface density model.
2. Compute the gravity anomaly using the Talwani Method.
3. Add Gaussian noise to simulate field observations.
4. Transform the signal into the frequency domain using FFT.
5. Apply a low-pass filter to remove high-frequency noise.
6. Reconstruct the filtered signal using Inverse FFT.
7. Improve the reconstructed signal using Gradient Descent Optimization.
8. Compare the reconstructed gravity response with the original model.

## Technologies Used

- Python
- NumPy
- Matplotlib

## Project Structure

```
Gravity-Anomaly-Inversion/
│── gravity_anomaly_inversion.ipynb
│── README.md
│── LICENSE
```

## Results

The project demonstrates that combining FFT-based filtering with Gradient Descent Optimization significantly improves the reconstruction of gravity anomaly data, achieving high agreement with the original synthetic model.

## Author
**Navya Sri Potnuru**
Indian Institute of Technology Kharagpur
