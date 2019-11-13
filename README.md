# Project 3 Generative Audio

Bao Hoang, bghoang@ucsd.edu

## Abstract

For this project, I want to combine the two kinds of music together. The idea is simple: I will use Python libraries to get some random music samples, 
then I will combine those sample together and fix the combined sample to make it sounds nice. To generate these samples, I will use the Performance RNN
colab to get the midi files. I will then use GANSynth to modify these files. Then I will mix these files together and see what I have at the end. 
Hopefully, the end result will generate something sounds good, if not, I will problably try to find different training models/ music samples in the future
to make the sound better. 

## Model/Data

Briefly describe the files that are included with your repository:
- train_model folder
- sample folder
- result folder
- mashup file is the final result sound

## Code

Your code for generating your project:
- Jupyter notebooks: https://colab.research.google.com/drive/1kscoXV4JFpTTzT5YxKu-cqxhrpH1Rz25

## Results

- The train_model folder contains all the files that I used to train for Performance_RNN
- The sample folder containts all the files that were generated using Performance_RNN
- The result sample containts all the files that were generated using GANSynthOB
- Link to hear the sound: https://drive.google.com/file/d/1Yn38t84GLBCu95LMEsmVTe24fDnnfjdx/view?usp=sharing

## Technical Notes

Everything I did is on Google Colab so no need to download anything.
I had issue with getting the midi file from the Performance_RNN.

## Reference

References to any papers, techniques, repositories you used:
- Repositories
     + Performance_RNN: https://colab.research.google.com/notebooks/magenta/gansynth/gansynth_demo.ipynb#scrollTo=EwFvRyg6xSoz
     + GANSynth: https://colab.research.google.com/notebooks/magenta/gansynth/gansynth_demo.ipynb
     + Pydub: https://github.com/jiaaro/pydub
- Blog posts:
     + https://magenta.tensorflow.org/gansynth
