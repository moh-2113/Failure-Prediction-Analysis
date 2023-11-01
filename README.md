# Failure-Prediction-Analysis
Coal Injection systems are used in sponge iron rotary kilns to improve thermal efficiency and reduce fuel costs. Advanced failure prediction methods can help identify potential problems and prevent failure before it occurs in such systems.

**Problem Statement**

The coal is driven to the rotary kiln through lances/pipes injection systems. Over time the use of these injection systems (movement of coal) causes wear of the lance which cannot be predicted other than a visual inspection. Once a visual failure is observed, the plant stops production to make the necessary repairs which otherwise decreases production quality and contributes to several other economic issues.

**Approach**

**FFT(Fast Fourier Transform)** has been applied using **NumPy** to estimate the possible patterns of failure but FFT provides with difficulties to carry the time-frequency information of non-stationary signals.
Thus we use **Wavelet Transform** to capture such patterns which is done using **PyWavelets**. A GUI for the same has been developed using **Tkinter**. All the visualisation has been made possible using Matplotlib.  
https://imprc.tfbor.bg.ac.rs/download/IMPRC_2023_Proceedings.pdf (Pg no:423)
