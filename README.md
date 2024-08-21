<div style="text-align: center;">
  <h1>Training script for contentvec</h1>
</div>

This script makes the environment ready to start preprocessing the dataset, preprocess it, and start training afterwards. Tested on Ubuntu via WSL

## Setting up the environment

1. Install the miniconda
2. Extract the file present in Releases to the home folder
3. Run the "setup.sh" script

## Preprocess the dataset and start training

1. Convert the audios to 16kHz, in .wav
2. Place the audios in the "dataset" folder
3. Run the "process-dataset-and-start.sh" script and that's it, the training will start right after processing the dataset

## Credits

- [ContentVec](https://github.com/auspicious3000/contentvec) by [auspicious3000](https://github.com/auspicious3000)
- Dictionary creation script by [freds0](https://github.com/freds0)
