# Kaggle BirdCLEF 2022

Birds are all around us, and just by listening to them we can learn a lot about our surroundings. Ecologists use birds to understand food systems and the health of environments - for example, if there are more woodpeckers in a forest, it means that there is a lot of dead wood. On the other hand, because birds communicate and mark their territory with songs and calls, it is more effective to identify them based on audio. 

# Table of contents

1. [Competition description](#competition-description)
2. [Data analysis](#data-analysis)
3. [Data preparation](#data-preparation)
4. [Baseline](#baseline)
5. [Avenues explored](#avenues-explored)
6. [Results](#results)
7. [References](#references)

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

[Back to table of contents](#table-of-contents)

# Data preparation

<img src="https://raw.githubusercontent.com/jamesbarthelemy/images/main/data_prepa.png" width="600">

[Back to table of contents](#table-of-contents)

# Baseline

<img src="https://raw.githubusercontent.com/jamesbarthelemy/images/main/baseline.png" width="600">

[Back to table of contents](#table-of-contents)

# Avenues explored

1. Computer vision algorithms
2. VGGish
3. TRILL
4. Stacking

[Back to table of contents](#table-of-contents)

# Results

<img src="https://raw.githubusercontent.com/jamesbarthelemy/images/main/scores.png" width="1200">

[Back to table of contents](#table-of-contents)

# References

1. [Baseline](https://www.kaggle.com/code/duythanhng/birdclef-2022-keras-simple-tutorial)
2. [Vocal separation](https://librosa.org/librosa_gallery/auto_examples/plot_vocal_separation.html)
3. [Data augmentation](https://www.kaggle.com/code/CVxTz/audio-data-augmentation/notebook)
4. [VGGish](https://github.com/tensorflow/models/tree/master/research/audioset/vggish)
5. [TRILL](https://arxiv.org/pdf/2002.12764.pdf)
6. [Stacking](https://machinelearningmastery.com/out-of-fold-predictions-in-machine-learning/)

[Back to table of contents](#table-of-contents)
