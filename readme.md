Music Source Separation using Nussl, Spleeter, Demux, and FastICA
This repository provides a simple implementation of music source separation using four different libraries - Nussl, Spleeter, Demux, and FastICA. These libraries are widely used for audio signal processing and provide different methods for separating the different sources present in a music recording.

Requirements
Python 3.6 or later
Nussl
Spleeter
Demux
FastICA
NumPy
SciPy
You can install the required packages by running pip install -r requirements.txt in your terminal.

Usage
To use this code, simply run python main.py in your terminal. This will run each of the four libraries on a sample music file and save the resulting separated audio sources to disk.

Notes
The sample music file used in this repository is a short clip from a popular song, and is included for demonstration purposes only.
The output from each library may differ slightly due to the different methods used for source separation.
You can modify the code to use your own music files by changing the input file path and other parameters as necessary.
References

Nussl: https://interactiveaudiolab.github.io/nussl/
Spleeter: https://github.com/deezer/spleeter
Demux: https://github.com/CenterForTheBuiltEnvironment/demucs
FastICA: https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.FastICA.html


Since the file is too large for github to display, you can follow the following link to colab to directly access the notebook
https://colab.research.google.com/drive/1pbLjG3HKaQk_78vwZLMSQt2xMZDo0Ew5?usp=sharing
https://colab.research.google.com/drive/1MRzGr9YSP8nQoMigL5RUvshx6eNWCKib?usp=sharing