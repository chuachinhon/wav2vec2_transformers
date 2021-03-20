# PART 2: CHAIN LINKING AUDIO-TO-TEXT NLP TASKS

# 2A: TRANSCRIBE-TRANSLATE-SENTIMENT-ANALYSIS
![](https://miro.medium.com/max/4800/1*xq91N5qzjsLIS9m921E6nw.png)

In [notebook3.0](https://github.com/chuachinhon/wav2vec2_transformers/blob/main/notebooks/3.0_transcribe_translate_sentiment_analysis.ipynb), I demo a simple workflow to:

- transcribe a longish English speech (~24 minutes)
- translate it into Chinese
- plot the 'sentiment structure' of the Engish speech.

I used Biden's [first prime time speech](https://www.youtube.com/watch?v=JYBatFW-BP4) on Mar 11/12 2021 (depending on which time zone you are in). The audio clip was split in 71 20-second clips.

Results are a bit rough, but it's interesting that you can do this in 1 go (and in 1 notebook) these days. Future possibilities are interesting to say the least.

### Note: 
Code was updated on Mar 18 2021 for a cleaner approach.


# 2B: TRANSCRIBE-SUMMARISE
![](https://cdn-images-1.medium.com/max/2400/1*08Y3kmNv7gcplR2vvJxJCA.png)

In [notebook3.1](https://github.com/chuachinhon/wav2vec2_transformers/blob/main/notebooks/3.1_transcribe_summarise.ipynb), I demo a simple workflow to:

- transcribe a short English speech (4 minutes)
- summarize it via FB/Bart or Google/Pegasus

Summarisation is one of the toughest NLP tasks to get right, so I used a shorter audio file - a 4-minute clip by [Singapore Prime Minister Lee Hsien Loong talking about populism](https://www.youtube.com/watch?v=4bUl9R2N90A). 


# MEDIUM

A short write up on the results in this [Medium post](https://towardsdatascience.com/chain-linking-nlp-tasks-with-wav2vec2-transformers-7297181db3a7).


---


# PART 1: TRANSCRIBING POETRY AND SPEECHES WITH WAV2VEC2 
![](https://cdn-images-1.medium.com/max/1600/1*KVYnVHPhJlY9SS7XtFKUQw.png)

This series of notebooks is aimed at helping fellow NLP enthusiasts experiment with the Wav2Vec2 model by FB and implemented in transformers by Hugging Face.

I was curious to see how well the model would perform for short and long audio clips, different accents and different "delivery formats" - be it formal speeches or a poetry recital. The accents in these audio clips involve speakers who are: White American, African American and Singaporean Chinese.

 - [Notebook 1.0](https://github.com/chuachinhon/wav2vec2_transformers/blob/main/notebooks/1.0_wav2vec2_short.ipynb): This is the simplest trial of the Wav2Vec2 model, involving a 62s clip of John F Kennedy's famous inaugural speech in 1961.
 
 - [2.0](https://github.com/chuachinhon/wav2vec2_transformers/blob/main/notebooks/2.0_wav2vec2_poetry.ipynb): Longer audio clips tend to crash notebooks using the Wav2Vec2 model, so I used a work around to transcribe Amanda Gorman's evocative inauguration poem (5 minutes 34 seconds)
 
 - [2.1](https://github.com/chuachinhon/wav2vec2_transformers/blob/main/notebooks/2.1_wav2vec2_colab.ipynb): Colab notebook to transcribe a 12.5 minutes speech by the Singapore Prime Minister, to see how the model deals with an Asian accent.
 
 
  - [2.2](https://github.com/chuachinhon/wav2vec2_transformers/blob/main/notebooks/2.2_wav2vec2_poetry_alt.ipynb): Notebook with revised and cleaner code for dealing with longer audio files.
 
 
The necessary audio files are included in this repo. If you want to use your own clips, make sure to downsample them to 16kHz.

# MEDIUM

A short write up on the results in this [Medium post](https://towardsdatascience.com/transcribing-poetry-and-speeches-with-wav2vec2-2658c6510f06).

---
