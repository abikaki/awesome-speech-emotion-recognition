

# Awesome Speech Emotion Recognition 
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![GNU GPLv3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0.en.html)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-YES-green.svg)](https://github.com/abikaki/awesome-speech-emotion-recognition/graphs/commit-activity)
![GitHub last commit](https://img.shields.io/github/last-commit/abikaki/awesome-speech-emotion-recognition)
![Visitors](https://api.visitorbadge.io/api/combined?path=https://github.com/abikaki/awesome-speech-emotion-recognition&label=Visitors&countColor=%23263759&style=flat)
<!--![Downloads](https://img.shields.io/github/downloads/abikaki/awesome-speech-emotion-recognition/total.svg)
[![Count of Action Users](https://badgen.net/github/dependents-repo/abikaki/awesome-speech-emotion-recognition?icon=github&label=used%20by)](https://github.com/abikaki/awesome-speech-emotion-recognition/network/dependents)-->

## Topics

* [What's New](#whats-new)
* [Reviews](#reviews)
* [Databases](#databases)
* [Developing](#developing)
* [Training](#training)
* [Publishing](#publishing)
* [Learning](#learning)
* [Maybe Useful](#maybe-useful)


## What's New
| Year  | Month | Database | Title | Topics |
|-------| ------| -------- | ----- | ------ |
| 2024  | February | EURASIP Journal on Audio, Speech, and Music Processing | [Deep learning-based expressive speech synthesis: a systematic review of approaches, challenges, and resources](https://doi.org/10.1186/s13636-024-00329-7) | A systematic review of the literature on expressive speech synthesis models published within the last 5 years, with a particular emphasis on approaches based on deep learning | 
| 2024  | February | Information Fusion | [Emotion recognition and artificial intelligence: A systematic review (2014–2023) and research recommendations](https://doi-org.ezproxy.lib.uh.edu/10.1016/j.inffus.2023.102019) | A systematic review of emotion recognition from different input signals (e.g, physical, physiological) |
<!--[![fighsare](https://img.shields.io/badge/FigShare-DOI:00.0000/m9.figshare.00000000-556472?logo=figshare&logoColor=white)](https://figshare.com/account/home)-->

## Reviews
|Year| Database | Title | Topics |
| -- | -------- | ----- | ------ |
| 2023 | Neurocomputing | [An ongoing review of speech emotion recognition](https://www.sciencedirect.com/science/article/pii/S0925231223000103) | <b>A comprehensive review of most popular datasets, and current machine learning and neural networks models for SER </b> | 
| 2023 | Information Fusion | [Multimodal sentiment analysis: A systematic review of history, datasets, multimodal fusion methods, applications, challenges and future directions](https://doi.org/10.1016/j.inffus.2022.09.025) | A review on multimodal fusion architectures |
| 2022 | Neural Computing and Applications | [Human emotion recognition from EEG-based brain-computer interface using machine learning: a comprehensive review](https://doi.org/10.1007/s00521-022-07292-4) | Human emotion recognition using EEG-based brain signals and machine learning | 
| 2022 | Wireless Personal Communications | [Survey of Deep Learning Paradigms for Speech Processing](https://doi.org/10.1007/s11277-022-09640-y) | Machine learning techniques for speech processing | 
| 2022 | Electronics | [Bringing Emotion Recognition Out of the Lab into Real Life: Recent Advances in Sensors and Machine Learning](https://www.mdpi.com/2079-9292/11/3/496) | This work reviews progress in sensors and machine learning methods and techniques |
| 2021 | IEEE Access | [A Comprehensive Review of Speech Emotion Recognition Systems](https://doi.org/10.1109/ACCESS.2021.3068045) | SER systems' varied design components/methodologies, databases |
| 2021 | Electronics | [A Review on Speech Emotion Recognition Using Deep Learning and Attention Mechanism](https://www.mdpi.com/2079-9292/10/10/1163) | Extensive comparison of Deep Learning architectures, mainly on the IEMOCAP benchmark database | 
| 2021 | Digital Signal Processing | [A survey of speech emotion recognition in natural environment](https://doi.org/10.1016/j.dsp.2020.102951) | A comprehensive survey of SER in the natural environment, various issues of SER in the natural environment, databases, feature extraction, and models |
| 2021 | Archives of Computational Methods in Engineering | [Survey on Machine Learning in Speech Emotion Recognition and Vision Systems Using a Recurrent Neural Network (RNN)](https://doi.org/10.1007/s11831-021-09647-x)| A survey of deep learning algorithms in speech and vision applications and restrictions |
| 2021 | Applied Sciences | [Deep Multimodal Emotion Recognition on Human Speech: A Review](https://doi.org/10.3390/app11177962) | An extensive review of the state-of-the-art in multimodal speech emotion recognition methodologies |

## Databases

<p>
  <span> Russell's circumplex model of affect [1] is a model of human emotion that posits that all emotions can be represented as points on a two-dimensional space, with one dimension representing valence (pleasantness vs. unpleasantness) and the other dimension representing arousal (activation vs. deactivation). Valence refers to the positive and negative degree of emotion and arousal refers to the intensity of emotion. Most categorical emotions used in SER databases are based on this model</span> <br/><br/>
  
<img src='https://media.springernature.com/full/springer-static/image/art%3A10.1038%2Fsrep04998/MediaObjects/41598_2014_Article_BFsrep04998_Fig1_HTML.jpg?as=webp' alt="A graphical representation of the circumplex model of affect with the horizontal axis representing the valence or pleasant dimension and the vertical axis representing the arousal or activation dimension" width=450 height=300/>
<!--<img src='https://user-images.githubusercontent.com/87717559/168854583-56c98ed1-6c51-4551-b9e2-0b2bd1b811a3.png' alt="Russell's circumplex model" width=300 height=300/>-->

</p>
A graphical representation of the circumplex model of affect with the horizontal axis representing the valence or pleasant dimension and the vertical axis representing the arousal or activation dimension [2].
<br/><br/>
[1] Russell, J. A. (1980). A circumplex model of affect. Journal of Personality and Social Psychology, 39(6), 1161–1178. https://doi.org/10.1037/h0077714 <br/>
[2] Valenza, G., Citi, L., Lanatá, A. et al. Revealing Real-Time Emotional Responses: a Personalized Assessment based on Heartbeat Dynamics. Sci Rep 4, 4998 (2014). https://doi.org/10.1038/srep04998 <br/>

### Datasets for Emotion Recognition

<div style="width:100%">

  
| Dataset | Lang | Size                                                                                               | Type | Emotions | Modalities | Resolution |
| ------- | ----- |----------------------------------------------------------------------------------------------------| :--: | ------- | ----- | :------: |
| [AffectNet](http://mohammadmahoor.com/affectnet/) | N/A | ~450.000 subjects                                                                                  | Natural |  Continuous valence/arousal values and categorical emotions: anger, contempt, disgust, fear, happiness, neutral, sadness, surprise | Visual | 425x425 |
| [Belfast Naturalistic Database](https://pureadmin.qub.ac.uk/ws/portalfiles/portal/2125652/IEEE+Transactions+on+Affective+Computing+2011+Sneddon.pdf) | Spanish | 127 multi-cultural speakers of 298 emotional clips                                                 | Natural |  Amusement, anger, disgust, fear, frustration, sadness, surprise | Audio<br/>Visual | N/A |
| [Berlin Database of Emotional Speech (Emo-DB)](http://emodb.bilderbar.info/docu/) | German | 5 male and 5 female speakers, with more than 500 utterances                                        | Acted | Anger, boredom, disgust, fear/anxiety, happiness, neutral, sadness | Audio | Audio: 48kHz, downsampled to 16kHz <br/> Formats:.wav |
| [CMU Multimodal Opinion Sentiment and Emotion Intensity (CMU-MOSEI)](http://multicomp.cs.cmu.edu/resources/cmu-mosei-dataset/) | English | 1000 gender-balanced YouTube speakers, 23500 sentences                                             | Natural | Sentiment: Negative, weakly negative, neutral, weakly positive, positive Emotions: Anger, disgust, fear, happiness, sadness, surprise  | Audio<br/>Visual<br/>Text | N/A | 
| [CaFE](https://dl.acm.org/doi/10.1145/3204949.3208121) <br/> [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1478765.svg)](https://doi.org/10.5281/zenodo.1478765) | French (Canadian) | 12 actors, 6 males, and 6 females, 6 sentences                                                     | Acted | Anger, disgust, fear, happiness, neutral, sadness, surprise in two different intensities | Audio | Audio: 192kHz and 48kHz <br/> Formats:.aiff |
| [CREMA-D](https://ieeexplore.ieee.org/document/6849440) <br/> [![GitHub](https://img.shields.io/github/stars/CheyneyComputerScience/CREMA-D)](https://github.com/CheyneyComputerScience/CREMA-D) | English | 91 actors,48 males, and 43 females, 12 sentences                                                   | Acted | Anger, disgust, fear, happy, neutral and sad / Emotional Intensity | Audio<br/>Visual | Audio: 16kHz <br/> Formats:.wav,.mp3,.flv |
| [ESD](https://github.com/HLTSingapore/Emotional-Speech-Data?tab=readme-ov-file) <br/> [![GitHub](https://img.shields.io/github/stars/HLTSingapore/Emotional-Speech-Data)](https://github.com/HLTSingapore/Emotional-Speech-Data) | English (North American), Chinese (Mandarin) | 10 English (5 males, 5 females) and 10 Chinese (5 males, 5 females) speakers, 700 utterances | Acted | Anger, happiness, neutral, sadness, surprise | Audio <br> Text | Audio: 16kHz <br/> Formats: wav    
| [Interactive Emotional Motion Capture (USC-IEMOCAP)](https://sail.usc.edu/iemocap/) <br/> [![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)](https://pytorch.org/audio/2.0.1/generated/torchaudio.datasets.IEMOCAP.html#torchaudio.datasets.IEMOCAP) | English | A 12h multimodal and multispeaker (5 males and 5 females) database                                 | Acted<br/>Elicited | Anger, frustration, happiness, neutral, sadness as well as dimensional labels such as valence, activation and dominance | Audio<br/>Visual | Audio: 48kHz <br/> Video: 120 fps |
| [MELD: Multimodal EmotionLines Dataset](https://affective-meld.github.io/) | English | More than 13000 utterances from multiple speakers                                                  | Natural | Anger, disgust, fear, joy, neutral, non-neutral, sadness, surprise | Audio<br/>Visual<br/>Text | Audio: 16bit PCM <br/> Formats: .wav |
| [OMG-Emotion](https://www2.informatik.uni-hamburg.de/wtm/OMG-EmotionChallenge/) | English | 10 hours of YouTube videos around 1min long                                                        | Natural | Continuous valence/arousal values and categorical emotions: anger, disgust, fear, happiness, neutral, sadness, surprise | Audio<br/>Visual<br/>Text | N/A | 
| [Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS)](https://smartlaboratory.org/ravdess/) <br/> [![DOI](https://zenodo.org/badge//DOI/10.5281/zenodo.1188976.svg)](https://doi.org/10.5281/zenodo.1188976)| English | A database of emotional speech and song of 12 males and 12 females                                 | Acted | Anger, disgust, calmness, fear, happiness, neutral, sadness, surprise | Audio<br/>Visual | Audio: 48kHz - 16bit  <br/> Video: 720p <br/> Formats: .wav,.mp4 | 
| [SEMAINE](https://semaine-db.eu/) | English | 95 sessions of human-agent interactions                                                            | Natural | 4D Emotional space | Audio<br/>Visual<br/>Text | N/A | 
| [Surrey Audio-Visual Expressed Emotion (SAVEE)](http://kahlan.eps.surrey.ac.uk/savee/) <br/> [![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)](https://www.tensorflow.org/datasets/catalog/savee) | English | 4 male speakers x 480 utterances                                                                   | Acted | Anger, disgust, fear, happiness, neutral, sadness, surprise | Audio<br/>Visual | Audio: 44.1kHz - mono - 16bit <br/> Video: 256p - 60fps <br/> Formats: .wav, .avi | 
| [SUSAS](https://catalog.ldc.upenn.edu/LDC99S78) | English | Speech under stress corpus with more than 16000 utterances from 32 speakers (13 females, 19 males) | Acted | Ten stress styles such as speaking style, single tracking task, and Lombard effect domain | Audio | 8kHz, 8bit PCM |

</div>

### Datasets for Sound Classification

|   Database   | Year | Type |                        Resolution                        |
| :----------: | ---- | ---- |:--------------------------------------------------------:|
| [VGGSound](http://www.robots.ox.ac.uk/~vgg/data/vggsound/) <br/> [![GitHub](https://img.shields.io/github/stars/hche11/VGGSound)](https://github.com/hche11/VGGSound) | 2020 | more than 210k videos for 310 audio classes | N/A, 10sec long |
| [AudioSet](https://research.google.com/audioset/) <br/> [![GitHub](https://img.shields.io/github/stars/audioset/ontology)](https://github.com/audioset/ontology) | 2017 |2.1 million sound clips from YouTube videos, 632 audio event classes |  N/A, 10sec long  |
| [UrbanSound8K](https://urbansounddataset.weebly.com/urbansound8k.html) <br/> [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1203745.svg)](https://doi.org/10.5281/zenodo.1203745)| 2014 | Urban sound excerpts | sampling rate may vary from file to file, duration<=4sec |
| [ESC-50](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/YDEPUT)  <br/> [![GitHub](https://img.shields.io/github/stars/karolpiczak/ESC-50#repository-content)](https://github.com/karolpiczak/ESC-50#repository-content) | 2000 | Environmental audio recordings |  44.1kHz, mono, 5sec long  |

    
## Developing
### Software
  
* C++
  * [Essentia](https://github.com/MTG/essentia) | &nbsp; [![GitHub](https://img.shields.io/github/stars/MTG/essentia)](https://github.com/MTG/essentia) &nbsp; |A C++ library for audio and music analysis, description, and synthesis, including Python bindings
  * [openSMILE](https://www.audeering.com/research/opensmile/) |  &nbsp; [![GitHub](https://img.shields.io/github/stars/audeering/opensmile)](https://github.com/audeering/opensmile) &nbsp;  |An open-source toolkit for audio feature extraction and classification of speech and music signals, including a C API with Python and C# bindings 
* MATLAB
  * [Audio Toolbox](https://www.mathworks.com/products/audio.html) | Provides tools for audio processing, speech analysis, and acoustic measurement
  * [Covarep](https://github.com/covarep/covarep) | &nbsp; [![GitHub](https://img.shields.io/github/stars/covarep/covarep)](https://github.com/covarep/covarep) &nbsp; | A Cooperative Voice Analysis Repository for Speech Technologies
* Python Libraries
  * [Aubio](http://aubio.org) |  &nbsp; [![GitHub](https://img.shields.io/github/stars/aubio/aubio)](https://github.com/aubio/aubio) &nbsp; | Free, open source library for audio and music analysis
  * [Librosa](https://librosa.org/doc/latest/index.html) | &nbsp; [![GitHub](https://img.shields.io/github/stars/librosa/librosa)](https://github.com/librosa/librosa) &nbsp; | A Python package for music and audio analysis
  * [OpenSoundscape](https://github.com/kitzeslab/opensoundscape) |  &nbsp; [![GitHub](https://img.shields.io/github/stars/kitzeslab/opensoundscape)](https://github.com/kitzeslab/opensoundscape) &nbsp; | A Python utility library for analyzing bioacoustic data
  * [Parselmouth](https://parselmouth.readthedocs.io/) | &nbsp; [![GitHub](https://img.shields.io/github/stars/YannickJadoul/Parselmouth)](https://github.com/YannickJadoul/Parselmouth) &nbsp; | A Pythonic interface to the [Praat](http://www.praat.org/) software 
  * [PyAudioAnalysis](https://github.com/tyiannak/pyAudioAnalysis/wiki) |  &nbsp; [![GitHub](https://img.shields.io/github/stars/tyiannak/pyAudioAnalysis)](https://github.com/tyiannak/pyAudioAnalysis) &nbsp; | A Python library that provides a wide range of audio-related functionalities focusing on feature extraction, classification, segmentation, and visualization issues
  * [Pydub](https://github.com/jiaaro/pydub) |  &nbsp; [![GitHub](https://img.shields.io/github/stars/jiaaro/pydub)](https://github.com/jiaaro/pydub) &nbsp;  | Manipulate audio with a simple and easy high-level interface
  * [SoundFile](https://python-soundfile.readthedocs.io/en/0.10.3post1/) |   &nbsp; [![GitHub](https://img.shields.io/github/stars/bastibe/python-soundfile)](https://github.com/bastibe/python-soundfile) &nbsp;  | A python library for audio IO processing

### Tools 
  * [Audacity](https://www.audacityteam.org/) |  &nbsp; [![GitHub](https://img.shields.io/github/stars/audacity/audacity)](https://github.com/audacity/audacity) &nbsp; | Free, open source, cross-platform audio software
  * [AudioGPT](https://github.com/AIGC-Audio/AudioGPT) |  &nbsp; [![GitHub](https://img.shields.io/github/stars/AIGC-Audio/AudioGPT)](https://github.com/AIGC-Audio/AudioGPT) &nbsp;  | Solve AI tasks with speech, music, sound, and talking head understanding and generation in multi-round dialogues, which empower humans to create rich and diverse audio content with unprecedented ease ([paper](https://arxiv.org/abs/2304.12995))
  * [ESPNet](https://github.com/espnet/espnet) |  &nbsp; [![GitHub](https://img.shields.io/github/stars/espnet/espnet)](https://github.com/espnet/espnet) &nbsp; | ESPnet is an end-to-end speech processing toolkit covering end-to-end speech recognition, text-to-speech, speech translation, speech enhancement, speaker diarization, and spoken language understanding
  * [Kaldi](https://kaldi-asr.org/) | &nbsp; [![GitHub](https://img.shields.io/github/stars/kaldi-asr/kaldi)](https://github.com/kaldi-asr/kaldi) &nbsp; | Kaldi is an  automatic speech recognition toolkit  
  * [S3PRL](https://s3prl.github.io/s3prl/) | &nbsp; [![GitHub](https://img.shields.io/github/stars/s3prl/s3prl)](https://github.com/s3prl/s3prl) &nbsp; | A toolkit targeting for Self-Supervised Learning for speech processing. It supports three major features: i) Pre-training, ii) Pre-trained models (Upstream) collection, and iii) Downstream Evaluation
  * [SpeechBrain](https://speechbrain.github.io/) |  &nbsp; [![GitHub](https://img.shields.io/github/stars/speechbrain/speechbrain)](https://github.com/speechbrain/speechbrain) &nbsp; | A PyTorch speech and all-in-one conversational AI toolkit

  
## Training
### Embeddings
* Audio/Speech
  * [Data2vec 2.0](https://github.com/facebookresearch/fairseq/tree/main/examples/data2vec)
  * [DeepSpectrum](https://github.com/DeepSpectrum/DeepSpectrum)
  * [ECAPA-TDNN](https://huggingface.co/speechbrain/spkrec-ecapa-voxceleb) 
  * [emotion2vec](https://github.com/ddlBoJack/emotion2vec)
  * [HuBERT](https://huggingface.co/docs/transformers/model_doc/hubert)
  * [OpenL3](https://github.com/marl/openl3)
  * [Resemblyzer](https://github.com/resemble-ai/Resemblyzer)
  * [UniSpeech-SAT](https://huggingface.co/docs/transformers/model_doc/unispeech-sat)
  * [VGGish](https://github.com/tensorflow/models/blob/master/research/audioset/vggish/README.md)
  * [Wav2Vec 2.0](https://huggingface.co/docs/transformers/model_doc/wav2vec2)


### Audio/Speech Data Augmentation
* [Audiomentations](https://iver56.github.io/audiomentations/) - A Python library for audio data augmentation
* [torch-audiomentations](https://github.com/asteroid-team/torch-audiomentations) - Fast audio data augmentation in PyTorch


## Publishing
### Journals
| Name | Impact Factor | Review Method | First-decision |
| ------------ | ----------- | ------------ |-----------|
| [Frontiers in Computer Science](https://www.frontiersin.org/journals/computer-science#) | 1.039 | Peer-review | 13w | 
| [International Journal of Speech Technology](https://www.springer.com/journal/10772/) | 1.803 | Peer-review | 61d |
| [Machine Vision and Applications](https://www.springer.com/journal/138) |  2.012 | Peer-review | 44d |
| [Applied Accoustics](https://www.journals.elsevier.com/applied-acoustics) | 2.639 | Peer-review | 7.5w |
| [Applied Sciences](https://www.mdpi.com/journal/applsci) | 2.679 | Peer-review | 17.7d |
| [Multimedia Tools and Applications](https://www.springer.com/journal/11042) |  2.757 | Peer-review | 99d |
| [IEEE Sensors](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=7361) | 3.301 | Peer-review | 60d |
| [IEEE Access](https://ieeeaccess.ieee.org/about-ieee-access/learn-more-about-ieee-access/) | 3.367 | Binary Peer-review | 4-6w |
| [Computational Intelligence and Neuroscience](https://www.hindawi.com/journals/cin/) | 3.633 | Peer-review | 40d |
| [IEEE/ACM Transactions on Audio, Speech and Language Processing](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=6570655) | 3.919 | Peer-review | N/A |
| [Neurocomputing](https://www.journals.elsevier.com/neurocomputing) |  5.719 | Peer-review | 74d |
| [IEEE Transactions on Affective Computing](https://ieeexplore.ieee.org/xpl/aboutJournal.jsp?punumber=5165369) | 10.506 | Peer-review | N/A |


### Conferences

<details>
<summary> <b>2023</b> </summary>

| Name                                                                                                           | Date           | Location |                                                                                                                            More                                                                                                                             |
|----------------------------------------------------------------------------------------------------------------|----------------|:--------:|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| [IEEE / CVF Computer Vision and Pattern Recognition Conference (CVPR)](https://cvpr2023.thecvf.com/)           | June 2023      |  Canada  | [![GitHub](https://badgen.net/badge/conferences/CVPR2023/blue?icon=github)](https://github.com/DmitryRyumin/CVPR-2023-Papers) <br/> [![GitHub](https://badgen.net/badge/conferences/CVPR2023/orange?icon=github)](https://github.com/52CV/CVPR-2023-Papers) |
| [International Conference on Acoustics, Speech, & Signal Processing (ICASSP)](https://2023.ieeeicassp.org/)    | June 2023      |  Greece  |  [![GitHub](https://badgen.net/badge/conferences/ICASSP2023/yellow?icon=github)](https://github.com/DmitryRyumin/ICASSP-2023-24-Papers) |
| [International Speech Communication Association - Interspeech (ISCA)](https://interspeech2023.org)             | August 2023    | Ireland  | [![GitHub](https://badgen.net/badge/conferences/ISCA2023/green?icon=github)](https://github.com/DmitryRyumin/INTERSPEECH-2023-Papers)  | 
| [European Signal Processing Conference (EUSIPCO)](http://eusipco2023.org/)                                     | September 2023 | Finland  |      :heavy_minus_sign:                                  |
| [Workshop on Detection and Classification of Acoustic Scenes and Events (DCASE)](https://dcase.community/workshop2023/index) | September 2023 | Finland  | [![GitHub](https://badgen.net/badge/conferences/DCASE2023/darkgray?icon=github)](https://github.com/abikaki/DCASE-2023-Papers)                                |
| [International Society for Music Information Retrieval Conference (ISMIR)](https://ismir2023.ismir.net/)       | November 2023  |  Italy   |  [![GitHub](https://badgen.net/badge/conferences/ISMIR2023/red?icon=github)](https://github.com/yamathcy/ISMIR-2023-Papers)                                 |

</details>

<details>

<summary> <b>2024</b> </summary>

| Name      | Date           |        Location        |                                                                                              More    |
|-----------|----------------|:----------------------:|:----------------------------------------------------------------------------------------------------:|
| [International Conference on Acoustics, Speech, & Signal Processing (ICASSP)](https://2024.ieeeicassp.org/)    | April 2024     |      Seoul, Korea      | [![GitHub](https://badgen.net/badge/conferences/ICASSP2024/yellow?icon=github)](https://github.com/DmitryRyumin/ICASSP-2023-24-Papers) | 
| [IEEE / CVF Computer Vision and Pattern Recognition Conference (CVPR)](https://cvpr.thecvf.com/)           | June 2024      |    Seattle, WA, USA    | :heavy_minus_sign: |
| [International Conference on Machine Learning (ICML)](https://icml.cc/Conferences/2024) | July 2024 | Vienna, Austria | :heavy_minus_sign: | 
| [European Signal Processing Conference (EUSIPCO)](https://eusipcolyon.sciencesconf.org/)  | August 2024    |      Lyon, France      | :heavy_minus_sign: |
| [International Speech Communication Association - Interspeech (ISCA)](https://interspeech2024.org/)        | September 2024 |      Kos, Greece       | :heavy_minus_sign: |
| [Workshop on Detection and Classification of Acoustic Scenes and Events (DCASE)](https://dcase.community/workshop2024/index) | October 2024   |      Tokyo, Japan      | [![GitHub](https://badgen.net/badge/conferences/DCASE2024/darkgray?icon=github)](https://github.com/abikaki/DCASE-Workshop-Papers/blob/main/2024/README.md)
| [International Society for Music Information Retrieval Conference (ISMIR)](https://ismir2024.ismir.net/)       | November 2024  | San Fransisco, CA, USA | :heavy_minus_sign: |
| [Conference and Workshop on Neural Information Processing Systems (NeurIPS)](https://neurips.cc/) | December 2024 | Vancouver, Canada |  :heavy_minus_sign: |

</details>

## Learning
* [Introduction to Speech Processing, 2nd Edition, Aalto University](https://speechprocessingbook.aalto.fi/)
* Mastering Audio - The Art and the Science, Robert A. Katz
* [Spectral Audio Signal Processing, Julius O. Smith III](https://ccrma.stanford.edu/~jos/sasp/)
* [The Scientist and Engineer's Guide to Digital Signal Processing, Steven W. Smith](https://www.dspguide.com/pdfbook.htm)
  

## Maybe Useful
### Other Awesome Material

* [Awesome Speaker Diarization](https://github.com/wq2012/awesome-diarization)
* [Awesome-SOTA-FER](https://github.com/kdhht2334/awesome-SOTA-FER) a curated list of facial expression recognition in both 7-emotion classification and affect estimation
* [Casual Conversations Dataset](https://ai.facebook.com/datasets/casual-conversations-dataset/)
* [Music Emotion Recognition Datasets](https://github.com/juansgomez87/datasets_emotion)
* [Room Impulse Responses Datasets](https://github.com/RoyJames/room-impulse-responses)
* [SER Datasets](https://superkogito.github.io/SER-datasets/#)
* [Voice Datasets](https://github.com/jim-schwoebel/voice_datasets)
* [Project TaRSila](https://sites.google.com/view/tarsila-c4ai/) speech datasets for Brazilian Portuguese language
* ✨❔

### Perspectives

<table>
  <tr>
    <td width="30%">
       A picture(s) is worth a thousand words! A <a href="https://www.youtube.com/watch?v=t685WM5R6aM">2-min visual example</a> of how we communicate emotions, our perceptions, the role of subjectivity and what is effective listening.<br/><br/>Are emotions consistent?<br/><br/>What about the dynamics of the context to our decisions and emotional wellness?
    </td>
    <td width="70%">
        <a href="https://www.youtube.com/watch?v=t685WM5R6aM"><img src="images/video-insideout.PNG"></a>
    </td>
  </tr>
</table>

