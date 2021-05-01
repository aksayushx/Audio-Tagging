# Audio-Tagging
Audio Tagging using Deep Learning and Signal Proccessing

## File Structure
1. **cfg.py** - Contains the configurations like model type and parameters for used in the computation of STFT.
2. **preprocess.py** - Creates signal envelopes and removes dead spaces from audio files, saving the clean files to `clean` directory.
3. **model.py** - Contains the code for building the features, training and saving the model.
4. **predict.py** - Loads a trained model and makes predictions, and saves it to `predictions.csv`.
