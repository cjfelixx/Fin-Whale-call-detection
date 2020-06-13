# Whale-Detector

This is a Digital Signal Processing (EE 415) project  on whale detection.

The following are the steps to detect whale calls.
* Downsampling: To speed up the processing and make computation manageable we
will downsample our data.
* Spectrum Analysis using a Spectrogram: The whale sounds are irregular spaced,
and each sound file is 5-minutes long. We use the Short Time Discrete Fourier Transform to study the frequency content of windowed sequences of the sound file.
* Removing background Noise: Over each frequency bin in our spectrogram we find the average energy for all windows. We then subtract this energy level (noise) from our spectrogram.
* Energy Detection: We use a basic principle in classifying the presence of the whale call. Here we plot the energy level over a range of frequencies of interest from the spectrogram.

## Dataset Link
<!---https://www.dropbox.com/sh/69es402x2jrmpvx/AADUTdnw37jKXMh1Xwbbb-Ena/03?dl=0&subfolder_nav_tracking=1 --->:

