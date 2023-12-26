# Signal Processing Simulation with BPSK

This MATLAB script simulates a basic signal processing system using Binary Phase Shift Keying (BPSK) modulation. The simulation includes the transmission of BPSK symbols, the addition of AWGN (Additive White Gaussian Noise), matched filtering using averaging and rational impulse response (IR) filters, and the calculation of detection probabilities.

## Instructions

1. **Setting Up Parameters:**
   - Adjust the parameters `n`, `Tsym`, `SNRstep`, and `SNR_dB` based on your simulation requirements.
   - `n`: Number of data symbols.
   - `Tsym`: Symbol time in terms of sample time or oversampling rate.
   - `SNRstep`: Step size for varying Signal-to-Noise Ratio (SNR).
   - `SNR_dB`: Range of SNR values in decibels.

2. **Running the Simulation:**
   - Execute the script in MATLAB.

3. **Simulation Results:**
   - The script will generate multiple plots showing the transmitted BPSK symbols, received signals with noise, matched filter (averaging filter and rational IR filter) outputs, and various performance metrics.
   - Results include Probability of Detection (P_D), Probability of False Alarm (P_F_A), Probability of Miss Detection (P_M), Total Error Rate (TER), and more.

4. **Analysis of Dynamic and Static Thresholds:**
   - The script compares dynamic and static thresholds for detection.
   - Visualizations include simulated dynamic thresholds, theoretical static thresholds, and their comparison.

5. **Graphical Analysis:**
   - Several figures show the impact of changing SNR on detection probabilities, error rates, and threshold values.
   - The performance of the system is analyzed under different SNR conditions.

6. **Interpreting Results:**
   - Analyze the graphs and figures to understand the impact of noise and filtering on the detection performance.
   - Compare dynamic and static thresholds to observe their effectiveness under varying SNR conditions.

**Note:** This script is for educational purposes and provides insights into the performance of a basic BPSK communication system in the presence of noise. It is essential to understand the simulation parameters and results for meaningful interpretation.
