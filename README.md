Music Generation using RBMs
Authors
Nirmay Bhavsar
Purva Chopdekar
Overview
This project aims to generate music using Restricted Boltzmann Machines (RBMs). It involves converting MIDI files into a suitable format, training RBMs on the music data, and using the trained models to generate new compositions. The implementation is done in Python using TensorFlow.

Instructions
Setup: Install the required dependencies using pip install -r requirements.txt.
Data Preparation: Place your MIDI files in the data directory.
Training: Run rbm_chords.py to train the RBM models.
Generation: Use merge_samples.py to generate new music samples.
Enjoy: Explore the generated compositions and tweak the parameters for different results.
File Structure
rbm_chords.py: Script for training RBM models.
merge_samples.py: Script for merging MIDI samples into a single composition.
midi_manipulation.py: Utilities for converting MIDI files to note state matrices and vice versa.
data/: Directory to store MIDI files.
generated/: Directory to store generated MIDI samples.
final.mid: Final merged composition.
Dependencies
Python 3.x
TensorFlow
NumPy
tqdm
License
This project is licensed under the MIT License. Feel free to use and modify it according to your needs.
