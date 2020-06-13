# Whale-Detector

This is a Digital Signal Processing (EE 415) project on whale call detection. In this project, we performed signal analysis on sound recordings of Fin Whales. The objective is to construct an algorithm that will detect whale calls. The purpose of this project is to apply fundamental Signal processing concepts in this application.

The following are the steps to detect whale calls.
* Downsampling: Speeds the the signal data processing computations, while maintaining data quality.
* Spectrum Analysis using a Spectrogram: The whale sounds are irregular spaced,
and each sound file is 5-minutes long. We used the Short Time Discrete Fourier Transform (DFT)to study the frequency content of windowed sequences of the sound file.
* Removing background Noise: Over each frequency bin in our spectrogram, we find the average energy for all windows. We then subtract this energy level (noise) from our spectrogram.
* Energy Detection: Here, we plot the energy level over a range of frequencies of interest from the spectrogram. We then classified whale called using a thresholding algorithm on energy peaks. 


<!---https://www.dropbox.com/sh/69es402x2jrmpvx/AADUTdnw37jKXMh1Xwbbb-Ena/03?dl=0&subfolder_nav_tracking=1 --->:

