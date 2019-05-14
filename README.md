# Neural-Machine-Translation

In this project used a neural network to translate from French to English.by the simple but powerful idea of the sequence to sequence network, in which two recurrent neural networks work together to transform one sequence to another. An encoder network condenses an input sequence into a vector, and a decoder network unfolds that vector into a new sequence.To improve upon this model we’ll use an attention mechanism, which lets the decoder learn to focus over a specific range of the input sequence.

### Encoder Decoder Architecture
#### Encoder Network
![Screenshot](images/encoder-network.png)
#### Decoder Network with attention
![Screenshot](images/attention-decoder-network.png)

## Output

[KEY: > input, = target, < output]

> il est en train de peindre un tableau . <br>
= he is painting a picture . <br>
< he is painting a picture . <br>

> pourquoi ne pas essayer ce vin delicieux ? <br>
= why not try that delicious wine ? <br>
< why not try that delicious wine ? <br>

> elle n est pas poete mais romanciere . <br>
= she is not a poet but a novelist . <br>
< she not not a poet but a novelist . <br>

> vous etes trop maigre . <br>
= you re too skinny . <br>
< you re all alone . <br>

### Resources used

https://pytorch.org/tutorials/intermediate/seq2seq_translation_tutorial.html

