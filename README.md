# fhb-pitch-shift

Code used in paper "Improved Fetal Heartbeat Detection Using Pitch Shifting and Psychoacoustics" by Vican, Krekovic, Jambrosic

## Tools

Python 3.6 and MATLAB 2020a have been used to develop the code used in the paper. 

## Feature extraction

Run master_extraction_sim.m or master_extraction_custom.m to extract features from simulated or custom datasets, respectively.
A dataset in CSV format, including a number of classic audio, psychoacoustic and EMD-based features will be extracted, along with a class.
Classification is binary and represents whether a subwindow used for extraction contains an S1 sound of fetal phonocardiographic signal.

## Data analysis and model training

Run cells in the available Jupyter Notebook, found in the feature_analysis folder. Several data analysis tools and models for training and inference are available.

## Citation

To be provided upon acceptance in a prominent journal.