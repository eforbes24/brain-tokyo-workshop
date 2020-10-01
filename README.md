# Eden's WANNs

This repo contains an augmentation of the brain-tokyo-workshop code for my thesis. Below is a running list of changes made from the original repo which can be found here: https://github.com/google/brain-tokyo-workshop 

The following files have been changed in the prettyNeatWann folder to try to implement the XOR problem:

classify_gym.py --> This is where the dataset is being defined (and where most of the problems are being had, as of now one-hot encoding is implemented here); starting line 91

make_env.py --> Here an env for XOR has been specified; lines 43-45

config.py --> Here, the subfunction for XOR within the general classify architecture is defined; lines 72-78

XOR.json --> This is a new file that defines the hyperparameters for the XOR problem (can be found in the folder 'p' within the prettyNeatWann folder)
