Numerical Investigation of Propeller Noise Reduction
# FFT Based Audio Noise Reduction

## Description
This project focuses on reducing drone propeller noise from audio recordings using Fast Fourier Transform (FFT). The noisy audio signal is transformed into the frequency domain, noise frequencies are filtered using a threshold, and the cleaned signal is reconstructed using inverse FFT.

## Methodology
1. Load propeller noise audio
2. Convert stereo audio to mono
3. Apply FFT to obtain frequency components
4. Identify noise frequencies using threshold filtering
5. Apply inverse FFT to reconstruct anti-noise signal
6. Subtract anti-noise from original signal

## Technologies Used
Python  
NumPy  
PyTorch  
Torchaudio  
Matplotlib
