# TRANSCRIBING POETRY AND SPEECHES WITH WAV2VEC2 
![](https://cdn-images-1.medium.com/max/1600/1*KVYnVHPhJlY9SS7XtFKUQw.png)

This series of notebooks is aimed at helping fellow NLP enthusiasts experiment with the Wav2Vec2 model by FB and implemented in transformers by Hugging Face.

I was curious to see how well the model would perform for short and long audio clips, different accents and different "delivery formats" - be it formal speeches or a poetry recital. The accents in these audio clips involve speakers who are: White American, African American and Singaporean Chinese.

 - [Notebook 1.0](https://github.com/chuachinhon/wav2vec2_transformers/blob/main/notebooks/1.0_wav2vec2_short.ipynb): This is the simplest trial of the Wav2Vec2 model, involving a 62s clip of John F Kennedy's famous inaugural speech in 1961.
 
 - [2.0](https://github.com/chuachinhon/wav2vec2_transformers/blob/main/notebooks/2.0_wav2vec2_poetry.ipynb): Longer audio clips tend to crash notebooks using the Wav2Vec2 model, so I used a work around to transcribe Amanda Gorman's evocative inauguration poem (5 minutes 34 seconds)
 
 - [2.1](https://github.com/chuachinhon/wav2vec2_transformers/blob/main/notebooks/2.1_wav2vec2_colab.ipynb): Colab notebook to transcribe a 12.5 minutes speech by the Singapore Prime Minister, to see how the model deals with an Asian accent.
 
 
The necessary audio files are included in this repo. If you want to use your own clips, make sure to downsample them to 16kHz.


---
