# PART 2: CHAIN LINKING AUDIO-TO-TEXT NLP TASKS
![](https://pbs.twimg.com/media/EwQH8xLUYAc2w7E?format=jpg&name=large)

In [notebook3.0](https://github.com/chuachinhon/wav2vec2_transformers/blob/main/notebooks/3.0_transcribe_translate_sentiment_analysis.ipynb), I demo a simple workflow to:

- transcribe a longish English speech (~24 minutes)
- translate it into Chinese
- plot the 'sentiment structure' of the Engish speech.

I used Biden's [first prime time speech](https://www.youtube.com/watch?v=JYBatFW-BP4) on Mar 11/12 2021 (depending on which time zone you are in). The audio clip was split in 71 20-second clips.

Results are a bit rough, but it's interesting that you can do this in 1 go (and in 1 notebook) these days. Future possibilities are interesting to say the least.


---


# PART 1: TRANSCRIBING POETRY AND SPEECHES WITH WAV2VEC2 
![](https://cdn-images-1.medium.com/max/1600/1*KVYnVHPhJlY9SS7XtFKUQw.png)

This series of notebooks is aimed at helping fellow NLP enthusiasts experiment with the Wav2Vec2 model by FB and implemented in transformers by Hugging Face.

I was curious to see how well the model would perform for short and long audio clips, different accents and different "delivery formats" - be it formal speeches or a poetry recital. The accents in these audio clips involve speakers who are: White American, African American and Singaporean Chinese.

 - [Notebook 1.0](https://github.com/chuachinhon/wav2vec2_transformers/blob/main/notebooks/1.0_wav2vec2_short.ipynb): This is the simplest trial of the Wav2Vec2 model, involving a 62s clip of John F Kennedy's famous inaugural speech in 1961.
 
 - [2.0](https://github.com/chuachinhon/wav2vec2_transformers/blob/main/notebooks/2.0_wav2vec2_poetry.ipynb): Longer audio clips tend to crash notebooks using the Wav2Vec2 model, so I used a work around to transcribe Amanda Gorman's evocative inauguration poem (5 minutes 34 seconds)
 
 - [2.1](https://github.com/chuachinhon/wav2vec2_transformers/blob/main/notebooks/2.1_wav2vec2_colab.ipynb): Colab notebook to transcribe a 12.5 minutes speech by the Singapore Prime Minister, to see how the model deals with an Asian accent.
 
 
The necessary audio files are included in this repo. If you want to use your own clips, make sure to downsample them to 16kHz.


---
