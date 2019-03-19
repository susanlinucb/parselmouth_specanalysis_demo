# parselmouth_specanalysis_demo
A demonstration of using the `parselmouth` library to obtain certain spectral information from audio files.  Provides an incidental demonstration of methods for integrating `audiolabel` with `pandas`.

This notebook originally written to assist Ernesto Gutiérrez (UC Berkeley) in processing of audio data collected for a research project.  Sample audio and annotated TextGrids from are included with participants' permission.

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
