# Star Wars Character Name Generator
## Overview
This project is about generating new, unseen Star Wars character names. The original work is posted on [Kaggle](https://www.kaggle.com/code/kacperrabczewski/make-a-friend-for-r2-d2-with-nlp) and I recommend watching it there. So the read isn't boring everything comes with a story of R2-D2 being a bit lonely of a droid and creating new friend for him!

## Model
The model used in this project is a simple bidirectional LSTM with layer normalization. It uses a 300D non-pretrained embedding layer for input. The model is trained to generate new Star Wars character names.

## Fine-Tuning
After generating the character names, the model is fine-tuned to generate names that sound like Star Wars robot names. This way, we can ensure that R2-D2’s new friend will be a robot like him!

## Results
The results of this project are fascinating. The model successfully generates new character names that fit into the Star Wars universe like **Darth Sinta, Grexderge, Admiral Dabax, Quinfah Vosaa and Qu Rahn Din**. After fine-tuning, it also generates robot-like names: **R5-75, A999 Crod, A-99L, 3-P3 and R2-D4**.
