# RockPaperScissors

Image classification of rock-paper-scissors pictures without using Tensorflow.

Steps taken to classify picture:
 - Binarization
 - Image crop
 - Finding attributes of a picture
    - Aspect ratio
    - Top Brightness Relative to Bottom
    - Top Halfway Row Mean
    - Finger Segment Mean Area
- Classification using supervised learning decision tree classifier

All the steps taken to decide which attributes are useful and wchich classifier is the best are described in file *Raport.pdf* and Jupyter Notebook *Kod.ipynb*.

## Authors
* [Martyna Jakubowska](https://github.com/mjakubowska)
* [Kacper Seredyn](https://github.com/scintilla4evr)
* [Hubert Nakielski](https://github.com/nakielsh)
