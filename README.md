<h2>Project: Voice Decoder for identifying the person</h2>

<li>Automatic Speaker Recognition algorithms in Python</li>

This repository contains Python programs that can be used for identifying speaker. ASR is done by extracting MFCCs and LPCs from each speaker and then forming a speaker-specific codebook of the same by using Vector Quantization. After that, the system is trained and tested for 8 different speakers.

To test the algorithm, run test.py from the terminal. Certain parameters are open to be changed, such as the order of LPC coefficients, the number of Mel filterbanks and the number of centroids in each codebook. Everything is included in the repository, including .wav files for testing and training, hence cloning it and running test.py should work.

To plot the spectrogram of an audio signal, run spectrogram.py. The program will take a random audio signal from the train folder and plot for that file, if you wish to plot for a particular audio file, change the filename variable in the .py file.

The following PDF that has been included explains the theory and provides links to relevant websites and projects.
