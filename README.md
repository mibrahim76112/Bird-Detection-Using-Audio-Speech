# Bird-Detection-Using-Audio-Speech
In this project, we downloaded the bird audio using an online link. Due to the limited computation power to process a large dataset, we selected only a few classes. The audios were then converted into Mel spectrograms, As in a simple spectrogram, the frequencies are linearly spaced, meaning each frequency bin represents an equal interval on the frequency scale. On the other hand, Mel spectrograms use the Mel scale, which is a non-linear scale based on human auditory perception.
Next, the obtained images were used for the training process of our custom model, which we designed with fewer convolutional layers to accommodate the available computation power.
Additionally, a sound was stored in our directory, which played when a bird was detected, effectively scaring them away.
