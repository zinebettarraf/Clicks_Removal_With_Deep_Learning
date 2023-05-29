The goal of the project is to remove clicks(considered as noise) in audios:
- data : In this folder, you will find training and test datasets :
    -  voixref_train : Clean audios (without clicks) for training.
    -  voixclicks_train : Audios with clicks for training.
    -  voixref_test : the clean audios (without clicks) for testing.
    -  voixref_test : Audios with clicks for testing.
- clicks_removal_dl : a notebook that displays the data and show the different methods used to tackle the problem :
    -   WAVE-U-NET architecture [https://arxiv.org/pdf/1806.03185.pdf].
    -   U-NET architecture on spectrograms amplitude, then reconstruct the audio from the predicted spectrogram amplitude using griffinlim library.
