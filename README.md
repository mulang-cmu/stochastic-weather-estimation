# Stochastic Weather Estimation: Kalman Filters & HMMs

## Project Overview
This project implements state estimation and regime-switching models to analyze and denoise temperature time-series data. 

## Key Technical Details
- **Kalman Filter (KF):** Implemented a linear state estimator to smooth temperature readings, achieving a **Mean Absolute Error (MAE) of 1.649**.
- **Hidden Markov Model (HMM):** Developed a Gaussian HMM to decode hidden weather states (e.g., Sunny vs. Rainy) using **Baum-Welch training** and **Viterbi decoding**.
- **Results:** Achieved **62.67% accuracy** in state decoding despite overlapping temperature distributions.
- **Stationarity Analysis:** Conducted rolling mean and variance tests to demonstrate how smoothing restores practical stationarity to noisy signals.

## Files
- [View Technical Report](./mmulang_ASP_H6.pdf)# stochastic-weather-estimation
Implementing Kalman Filters and Hidden Markov Models (HMM) for temperature smoothing and state decoding.
