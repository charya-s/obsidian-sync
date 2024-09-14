These are algorithms that learn input-to-output mappings. These models are given [[Training Data]] with input *and* their corresponding output values. Using this, the model can map the inputs to the outputs.

```
x = English -> y = French     | Translation.
x = Audio   -> y = Text       | Transcription.
x = Email   -> y = Spam?      | Spam detection.
```

[[Testing Data]] is used afterwards to verify that the mapping was done correctly without [[Overfitting and Underfitting]].

Inputs are called "features" and outputs are called "targets".
