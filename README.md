# Description

This is a jupyter notebook python project about recreating a guitar sound. The aim is to analyze a recording of a guitar, extract its overtone envelopes, and rebuild the sound using those envelopes. If all that sounds complicated, the basic idea is to deconstruct the recording into special sine waves, then reconstruct it using those special sine waves.

Libraries used: Numpy, scipy, IPython, matplotlib

More information and the code itself can be found in the 'Guitar sound recreation.ipynb' notebook file.

This file is viewable on github, so you don't need to actually run it to see the contents of it. This includes the outputs of the cells, with the exception of audio files. If you want to listen to the audio without running the notebook, you can simply listen to the .wav files in the repo. 'Guitar 100Hz.wav' is the original recording, 'Synthesized guitar.wav' is the recreation generated at the end of the notebook.