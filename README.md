# Kaggle BirdCLEF 2022

Birds are all around us, and just by listening to them we can learn a lot about our surroundings. Ecologists use birds to understand food systems and the health of environments - for example, if there are more woodpeckers in a forest, it means that there is a lot of dead wood. On the other hand, because birds communicate and mark their territory with songs and calls, it is more effective to identify them based on audio. 

# Table of contents

1. Competition description
2. Data analysis
3. Data preparation
4. Baseline
5. Avenues explored
6. Results
7. References

# Competition description

<img src="https://raw.githubusercontent.com/jamesbarthelemy/images/main/desc.png" width="1200">

# Data analysis

1. 14852 audio files available
2. 152 classes
3. Imbalanced data
4. Mainly 1 bird per sound but can be up to 6
5. Average file duration: 53 seconds
6. Audio sample rate: 22050 Hz

<img src="https://raw.githubusercontent.com/jamesbarthelemy/images/main/distri_all.png" width="600">
<img src="https://raw.githubusercontent.com/jamesbarthelemy/images/main/distri_21.png" width="600">
<img src="https://raw.githubusercontent.com/jamesbarthelemy/images/main/birds_per_sound.png" width="300">
<img src="https://raw.githubusercontent.com/jamesbarthelemy/images/main/audio_file_duration.png" width="300">

# Data preparation

<img src="https://raw.githubusercontent.com/jamesbarthelemy/images/main/data_prepa.png" width="600">

# Baseline

<img src="https://raw.githubusercontent.com/jamesbarthelemy/images/main/baseline.png" width="600">

# Avenues explored

1. Computer vision algorithms
2. VGGish
3. TRILL
4. Stacking

# Results

<img src="https://raw.githubusercontent.com/jamesbarthelemy/images/main/scores.png" width="600">

# References

[Baseline](https://www.kaggle.com/code/duythanhng/birdclef-2022-keras-simple-tutorial)
[Vocal separation](https://librosa.org/librosa_gallery/auto_examples/plot_vocal_separation.html)
[Data augmentation](https://www.kaggle.com/code/CVxTz/audio-data-augmentation/notebook)
[VGGish](https://github.com/tensorflow/models/tree/master/research/audioset/vggish)
[TRILL](https://arxiv.org/pdf/2002.12764.pdf)
[Stacking](https://machinelearningmastery.com/out-of-fold-predictions-in-machine-learning/)
