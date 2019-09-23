# Short-Range-automotive-RADAR-
This project aims to design and simulate a short range range, this RADAR operates around 79 GHz and the bandwith should responds to the desired range resolution.
Project steps:

1. Modeling the FMCW radar tranmsitted signal 
2. Modeling the received signal  and adding noise and multipath effects
3. Modeling the total received signal inclduing interfrences 
4. Extract IF signal ( output Mixer)
5. Digital signal processing 
 - Interference detection and mitigation in time domain
 - Range FFT
 - Doppler FFT
 - DOA and Angle FFT
 - Mutual interference mitigation in frequency domain
6. CFAR detectors
7. Clustring
8. Tracking
9. Traget recognition


All this project scripts will be written in MATLAB language at the first time, then I will create another project of the same radar using C language.
