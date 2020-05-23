# Music language model

Experiments with setting up a language model using MusicNet's labels (i.e. using transcripts as sentences)

## Data preparation

The original musicnet labels provided a trascript of each note played in each piece. In order to featurise it into text for a potential language model, all notes playing together at any given beat of the piece have been concatenated together as the "word" being used in that beat.

Ideas to try:

- Can we use model encoding to train a classifier?
- Can new music be generated?
