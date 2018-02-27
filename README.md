# seq2seq_NMT_keras

This is a character level sequence-to-sequence model for neural machine translation (english to french).

## Introduction

Sequence to sequence model is widely used in research papers, but it is hard to find code about it on how to build one with keras. I found a good resource these days, and tried to understand and rewrote the code.

## Methodology

1. Prepare data for encoder and decoder.
2. Build a encoder-decoder model for training (teacher forcing).
3. Build another model for inference.
4. Testing
Note: For layer reusing, we need to define a Functional model. 

## Result

Input sentence: Many fish died. </br>
Decoded sentence: L'aidenu en laume. </br>

Input sentence: This is silly. </br>
Decoded sentence: C'est simple. </br>

Input sentence: We can meet. </br>
Decoded sentence: Nous pouvons le saiver. </br>

Input sentence: Who cares? </br>
Decoded sentence: Qui s'en soucie ? </br>

Input sentence: Did I say that? </br>
Decoded sentence: Ai-je dit cela ? </br>

Input sentence: They're early. </br>
Decoded sentence: Elles sont en avance. </br>

Input sentence: He also saw it. </br>
Decoded sentence: Il l’a aussi vu. </br>

Input sentence: Bring him to me. </br>
Decoded sentence: Apportez-le-moi. </br>

Input sentence: Bottoms up! </br>
Decoded sentence: Santé ! </br>

Input sentence: I'm not sad. </br>
Decoded sentence: Je ne suis pas sourde. </br>


## References:
https://blog.keras.io/a-ten-minute-introduction-to-sequence-to-sequence-learning-in-keras.html </br>
https://jovianlin.io/keras-models-sequential-vs-functional/
