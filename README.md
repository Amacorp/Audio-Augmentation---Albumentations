# Audio-Augmentation---Albumentations

Data augmentation is a method for generating synthetic data i.e. creating new samples by tweaking small factors in the original samples. By altering these small factors we can get large amount of data for a single sample. This not only helps us to increase the size of our dataset but also gives multiple variations of single sample which helps our model to avoid overfitting and become more generalized.


To generate syntactic data for audio, we can apply noise injection, shifting time, changing pitch and speed. numpy provides an easy way to handle noise injection and shifting time while librosa (library for Recognition and Organization of Speech and Audio) help to manipulate pitch and speed with just 1 line of code.
