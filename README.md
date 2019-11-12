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
- trained models
- training data (or link to training data)

## Code

Your code for generating your project:
- Python: generative_code.py
- Jupyter notebooks: generative_code.ipynb

## Results

- The sample folder containts all the files that were generetade using Performance_RNN

## Technical Notes

Any implementation details or notes we need to repeat your work. 
- Does this code require other pip packages, software, etc?
- Does it run on some other (non-datahub) platform? (CoLab, etc.)

## Reference

References to any papers, techniques, repositories you used:
- Papers
- Repositories
     + Performance_RNN: https://colab.research.google.com/notebooks/magenta/gansynth/gansynth_demo.ipynb#scrollTo=EwFvRyg6xSoz
     + GANSynth: https://colab.research.google.com/notebooks/magenta/gansynth/gansynth_demo.ipynb
     + Pydub: https://github.com/jiaaro/pydub
- Blog posts:
     + https://magenta.tensorflow.org/gansynth
