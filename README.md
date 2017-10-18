# Speech-Recognition-Simple
Very simple implementation of Speech Recognition.

The speech audio file passes through an LSTM layer and then through a Dense Layer which has output nodes equal to the total vocabulary. This tells which text the output sequence has. This does not have a time dependent output which will tell how the text should unroll.

dataset: http://homepages.inf.ed.ac.uk/jyamagis/release/VCTK-Corpus.tar.gz


## Model-2
This is a bit more complex as it feeds the input audio directly through an LSTM and we get output which is time unrolled.
