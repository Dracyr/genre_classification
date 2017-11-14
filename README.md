# Genre Classification

This is a small notebook for making genre classifications from audio tracks.

The code simply pre-processes the tracks into mel-normalized spectrograms and reads annotations from the [giantsteps-tempo](https://github.com/GiantSteps/giantsteps-tempo-dataset) dataset.


## How to set up everything


### Dependences
pip install should work for all of them

0. sklearn
0. librosa
0. numpy
0. matplotlib

```
pip install sklearn librosa numpy matplotlib
```


### Preparing dataset
0. Download the files from the drive given, if you are on python3 you might get by with `audio_data.pkl`, else get them all
0. Extract `annotations.zip` to a folder named `annotations` and `audio_files.zip` to a folder named `audio`

