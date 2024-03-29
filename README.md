# Audio and Image Recognition
This work consists in the developement of several Machine Learning and Deep Learning models for recognition of audio and images.
We develop two tasks:
- Audio Recognition, we try to identify the identity of the speaker starting from a mono-dimensional signal;
- Face Recognition, we aims to identify the indentity of the subject into an image.

First, we collected manually the audios and the images used for train our models. In particular we recorded 300 audio of five seconds (next segmented into overlapping smaller fragments of 2 seconds) and 300 images containing faces with different facial expressions and different light conditions.

For the task of audio recognition we experimented different approaches:
- SVM;
- RF;
- Neural Network from Scratch;
- CNN using the *spectrograms* of the audios.

For the task of face recognition we used the **Fine Tuning** technique testing different CNN including:
- MobileNetV2;
- VGG;
- VGGface.

About us:

Ginevra Mariani - [enigarv](https://github.com/enigarv)

Lorenzo Mora - [lomProg](https://github.com/lomProg)

Riccardo Confalonieri - [rconfa](https://github.com/rconfa)


