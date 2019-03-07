# Pokemon-name-generator

We start by finding all the Pokémon names online on a website that has an API for Pokmon data. We then clean the data to ransform it into a form that the neural network can take.

The next step is to train a recurrent neural network with a LSTM layer on the data. This is then used to generate new names. A few nice examples of the results are:
- oscalish
- incono
- unteri
- pine

The model does surprisingly not to bad given the amount of data. Most of the names are coherent, way more than earlier in the training, and some of them would even be usable.
