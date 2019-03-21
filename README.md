# parselmouth_specanalysis_demo
A demonstration of using the `parselmouth` library to obtain certain spectral information from audio files.  Provides an incidental demonstration of methods for integrating `audiolabel` with `pandas`.

This notebook originally written to assist Ernesto Gutiérrez (UC Berkeley) in processing of audio data collected for a research project.  **Sample audio and annotated TextGrids included with explicit permission from Gutiérrez and relevant participants.**

View the [notebook on its own](https://github.com/susanlinucb/parselmouth_specanalysis_demo/blob/master/specanalysis_demo.ipynb), check out [sample output](https://github.com/susanlinucb/parselmouth_specanalysis_demo/blob/master/specanalysis_demo_data.csv), or [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/susanlinucb/parselmouth_specanalysis_demo/master) to open it in an interactive environment.

## Dependencies
The demo notebook requires the following dependencies:
* `numpy`
* `audiolabel`
* `parselmouth`
* `pandas`
* `matplotlib`

## File structure
Code in the demo notebook assume the following file structure:

```
./
./S01
./S01/S01_words.wav
./S01/S01_English_aligned.TextGrid
./S01/S01_Spanish_aligned.TextGrid
./S02
./S02/S02_words.wav
./S02/S02_English_aligned.TextGrid
./S02/S02_Spanish_aligned.TextGrid
./etc...
```
