# BCI-idea
Brain–Computer Interface (BCI) using EEG Signals – Signal Processing &amp; Peak Detection
This project demonstrates a Brain–Computer Interface (BCI) system using EEG signals. It covers signal acquisition, filtering, statistical thresholding, and peak detection. The implementation highlights how neural signals can be processed to detect significant brain responses such as P300 for assistive communication systems.
Key technical components include:

EEG signal model:
x(t) = s(t) + n(t)

Bandpass filtering (0.5–40 Hz)

50 Hz power-line noise suppression

Nyquist sampling considerations

Statistical thresholding:
Threshold = μ + kσ

Local maxima detection conditions:
x(n) > x(n-1), x(n) > x(n+1), x(n) > Threshold
HERE IS THE LINK FOR VIDEO:
https://drive.google.com/file/d/1F35DHcTUgSsymzTVE29w0aAotzCPJlMJ/view?usp=sharing
