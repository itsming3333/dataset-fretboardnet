# dataset-fretboardnet

Fretboardnet is a dataset used for deep learning thesis.
Fretboardnet is a set of guitar fretboard images for research purposes,
especially for the task of chord recognition with visual approach.

There are 13,457 images in total, consisting of 14 classes which is 14 basic guitar major and minor chord.

| Class | Images |
| ----- | ------ |
| A | 1002 |
| AM | 928 |
| B | 974 |
| BM | 1026 |
| C | 998 |
| CM | 983 |
| D | 1025 |
| DM | 859 |
| E | 1004 |
| EM | 849 |
| F | 995 |
| FM | 900 |
| G | 985 |
| GM | 929 |

## Dataset

The dataset will consist multiple files :

- Fretboard.zip		: raw images of guitar fretboard
- Fretboard_Normalized.zip : normalize images of guitar fretboard
- GuitarChord-<IMAGE_SIZE>x<IMAGE_SIZE>-<DATA_COUNT> Images-<CLASS_SCENARIO>.pkl : Pickle files of guitar fretboard
- GuitarChord-<CLASS_SCENARIO>.csv : CSV files consisting class list depends on the scenario