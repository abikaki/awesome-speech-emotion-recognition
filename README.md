# Awesome Speech Emotion Recognition 
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/abikaki/awesome-speech-emotion-recognition) 
[![Maintenance](https://img.shields.io/badge/Maintained%3F-YES-green.svg)](https://github.com/abikaki/awesome-speech-emotion-recognition/graphs/commit-activity)
![GitHub last commit](https://img.shields.io/github/last-commit/abikaki/awesome-speech-emotion-recognition)

## Topics

* [What's New](#whats-new)
* [Reviews](#reviews)
* [Databases](#databases)
* [Software](#software)
* [Tools](#tools)
* [Embeddings](#embeddings)
* [Journals](#journals)
* [Conferences](#conferences)
* [Learning](#learning)
* [Other Awesome Material](#other-awesome-material)
* [Perspectives](#perspectives)

## What's New
|Year| Month | Database | Title | Topics |
| -- | ------| -------- | ----- | ------ |
| 2023 | April | Neurocomputing | [An ongoing review of speech emotion recognition](https://www.sciencedirect.com/science/article/pii/S0925231223000103) | <b>A comprehensive review of most popular datasets, and current machine learning and neural networks models for SER | 
| 2023 | March | Information Fusion | [Multimodal sentiment analysis: A systematic review of history, datasets, multimodal fusion methods, applications, challenges and future directions](https://doi.org/10.1016/j.inffus.2022.09.025) | A review on multimodal fusion architectures |


## Reviews
|Year| Database | Title | Topics |
| -- | -------- | ----- | ------ |
| 2022 | Neural Computing and Applications | [Human emotion recognition from EEG-based brain-computer interface using machine learning: a comprehensive review](https://doi.org/10.1007/s00521-022-07292-4) | Human emotion recognition using EEG-based brain signals and machine learning | 
| 2022 | Wireless Personal Communications | [Survey of Deep Learning Paradigms for Speech Processing](https://doi.org/10.1007/s11277-022-09640-y) | Machine learning techniques for speech processing | 
| 2022 | Electronics | [Bringing Emotion Recognition Out of the Lab into Real Life: Recent Advances in Sensors and Machine Learning](https://www.mdpi.com/2079-9292/11/3/496) | This work reviews progress in sensors and machine learning methods and techniques |
| 2021 | IEEE Access | [A Comprehensive Review of Speech Emotion Recognition Systems](https://doi.org/10.1109/ACCESS.2021.3068045) | SER systems' varied design components/methodologies, databases |
| 2021 | Electronics | [A Review on Speech Emotion Recognition Using Deep Learning and Attention Mechanism](https://www.mdpi.com/2079-9292/10/10/1163) | Extensive comparison of Deep Learning architectures, mainly on the IEMOCAP benchmark database | 
| 2021 | Digital Signal Processing | [A survey of speech emotion recognition in natural environment](https://doi.org/10.1016/j.dsp.2020.102951) | A comprehensive survey of SER in the natural environment, various issues of SER in the natural environment, databases, feature extraction, and models |
| 2021 | Archives of Computational Methods in Engineering | [Survey on Machine Learning in Speech Emotion Recognition and Vision Systems Using a Recurrent Neural Network (RNN)](https://doi.org/10.1007/s11831-021-09647-x)| A survey of deep learning algorithms in speech and vision applications and restrictions |
| 2021 | Applied Sciences | [Deep Multimodal Emotion Recognition on Human Speech: A Review](https://doi.org/10.3390/app11177962) | An extensive review of state of the art in multimodal speech emotion recognition methodologies |

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

<div style="width:690px">

|Database| Language | Size | Type | Emotions | Modalities | Resolution |
| ------ | -------- | ---- | ---- | -------- | ---------- | ---------- |
| [AffectNet](http://mohammadmahoor.com/affectnet/) | N/A | ~450.000 subjects | Natural |  Continuous valence/arousal values and categorical emotions: anger, contempt, disgust, fear, happiness, neutral, sadness, surprise | Visual | 425x425 |
| [Belfast Naturalistic Database](https://pureadmin.qub.ac.uk/ws/portalfiles/portal/2125652/IEEE+Transactions+on+Affective+Computing+2011+Sneddon.pdf) | Spanish | 127 multi-cultural speakers of 298 emotional clips | Natural |  Amusement, anger, disgust, fear, frustration, sadness, surprise | Audio/Visual | N/A |
| [Berlin Database of Emotional Speech (Emo-DB)](http://emodb.bilderbar.info/docu/) | German | 5 male and 5 female speakers, with more than 500 utterances | Acted | Anger, boredom, disgust, fear/anxiety, happiness, neutral, sadness | Audio | Audio: 48kHz, downsampled to 16kHz - .wav |
| [CMU Multimodal Opinion Sentiment and Emotion Intensity (CMU-MOSEI)](http://multicomp.cs.cmu.edu/resources/cmu-mosei-dataset/) | English | 1000 gender balanced YouTube speakers, 23500 sentences | Natural | Sentiment: Negative, weakly negative, neutral, weakly positive, positive Emotions: Anger, disgust, fear, happiness, sadness, surprise  | Audio/Visual/Text | N/A | 
| [Interactive Emotional Motion Capture (USC-IEMOCAP)](https://sail.usc.edu/iemocap/) | English | A 12h multimodal and multispeaker (5 males and 5 females) database | Acted/Elicited | Anger, frustration, happiness, neutral, sadness as well as dimensional labels such as valence, activation and dominance | Audio/Visual | Audio: 48kHz, Video: 120 fps |
| [MELD: Multimodal EmotionLines Dataset](https://affective-meld.github.io/) | English | More than 13000 utterances from multiple speakers | Natural | Anger, disgust, fear, joy, neutral, non-neutral, sadness, surprise | Audio/Visual/Text | Audio: 16bit PCM - .wav |
| [OMG-Emotion](https://www2.informatik.uni-hamburg.de/wtm/OMG-EmotionChallenge/) | English | 10 hours of YouTube videos around 1min long | Natural | Continuous valence/arousal values and categorical emotions: anger, disgust, fear, happiness, neutral, sadness, surprise | Audio/Visual/Text | N/A | 
| [Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS)](https://smartlaboratory.org/ravdess/) | English | A database of emotional speech and song of 12 males and 12 females | Acted | Anger, disgust, calmness, fear, happiness, neutral, sadness, surprise | Audio/Visual | Audio: 48kHz - 16bit - .wav, Video: 720p - .mp4 | 
| [SEMAINE](https://semaine-db.eu/) | English | 95 sessions of human-agent interactions | Natural | 4D Emotional space | Audio/Visual/Text | N/A | 
| [Surrey Audio-Visual Expressed Emotion (SAVEE)](http://kahlan.eps.surrey.ac.uk/savee/) | English | 4 male speakers x 480 utterances | Acted | Anger, disgust, fear, happiness, neutral, sadness, surprise | Audio/Visual | Audio: 44.1kHz - mono - 16bit - .wav, Video: 256p - 60fps - .avi | 
| [SUSAS](https://catalog.ldc.upenn.edu/LDC99S78) | English | Speech under stress corpus with more than 16000 utterances from 32 speakers (13 females, 19 males) | Acted | Ten stress styles such as speaking style, single tracking task, and Lombard effect domain | Audio | 8kHz, 8bit PCM |

</div>

### Datasets for Sound Classification

|Database| Size | Type | Resolution |
| ------ | ---- | ---- | ---------- |
| [ESC-50](https://github.com/karolpiczak/ESC-50#repository-content) | 2000 | Environmental audio recordings | 44.1kHz, mono, 5sec long | 

## Software

* C++
  * [Essentia](https://github.com/MTG/essentia) | A C++ library for audio and music analysis, description and synthesis, including Python bindings
  * [openSMILE](https://www.audeering.com/research/opensmile/) | An open-source toolkit for audio feature extraction and classification of speech and music signals, including a C API with Python and C# bindings 
* MATLAB
  * Audio Toolbox
  * [Covarep - A Cooperative Voice Analysis Repository for Speech Technologies](https://github.com/covarep/covarep) 
* Python Libraries
  * [Librosa](https://librosa.org/doc/latest/index.html) | A python package for music and audio analysis
  * [OpenSoundscape](https://github.com/kitzeslab/opensoundscape) | A python utility library for analyzing bioacoustic data
  * [PyAudioAnalysis](https://github.com/tyiannak/pyAudioAnalysis/wiki) | A python library that provides a wide range of audio-related functionalities focusing on feature extraction, classification, segmentation and visualization issues
  * [Pydub](https://github.com/jiaaro/pydub) | Manipulate audio with a simple and easy high level interface
  * [SpeechBrain](https://speechbrain.github.io/) | A PyTorch speech and all-in-one conversational AI toolkit
  * [SoundFile](https://python-soundfile.readthedocs.io/en/0.10.3post1/) | A python library for audio IO processing

## Tools
  * [Audacity](https://www.audacityteam.org/) | Free, open source, cross-platform audio software
  * [AudioGPT](https://github.com/AIGC-Audio/AudioGPT) in solving AI tasks with speech, music, sound, and talking head understanding and generation in multi-round dialogues, which empower humans to create rich and diverse audio content with unprecedented ease ([paper](https://arxiv.org/abs/2304.12995))
  * [S3PRL](https://s3prl.github.io/s3prl/) a toolkit targeting for Self-Supervised Learning for speech processing. It supports three major features: i) Pre-training, ii) Pre-trained models (Upstream) collection, and iii) Downstream Evaluation

  
## Embeddings
* Audio
  * [DeepSpectrum](https://github.com/DeepSpectrum/DeepSpectrum)
  * [ECAPA-TDNN](https://huggingface.co/speechbrain/spkrec-ecapa-voxceleb)
  * [OpenL3](https://github.com/marl/openl3)
  * [Resemblyzer](https://github.com/resemble-ai/Resemblyzer)
  * [VGGish](https://github.com/tensorflow/models/blob/master/research/audioset/vggish/README.md)
  * [Wav2Vec2](https://huggingface.co/docs/transformers/model_doc/wav2vec2)

## Journals
| Name | Impact Factor | Review Method | First-decision |
| ---- | ---- | -------- |-----------|
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


## Conferences
| Name | Year   | Location | More     |
| ---- | ------ |:--------:|:---------:|
| [IEEE / CVF Computer Vision and Pattern Recognition Conference (CVPR)](https://cvpr2023.thecvf.com/) | June 2023 | Vancouver Canada | [CVPR-2023-Papers](https://github.com/52CV/CVPR-2023-Papers) |
| [International Conference on Acoustics, Speech, & Signal Processing (ICASSP)](https://2023.ieeeicassp.org/) | June 2023 | Greece |  [ICASSP-2023-Papers](https://github.com/DmitryRyumin/ICASSP-2023-Papers) |
| [Interspeech (ISCA)](https://interspeech2023.org) | August 2023 | Ireland | [INTERSPEECH-2023-Papers](https://github.com/DmitryRyumin/INTERSPEECH-2023-Papers) | 


## Learning
* [Introduction to Speech Processing, 2nd Edition, Aalto University](https://speechprocessingbook.aalto.fi/)
* Mastering Audio - The Art and the Science, Robert A. Katz
* [Spectral Audio Signal Processing, Julius O. Smith III](https://ccrma.stanford.edu/~jos/sasp/)
* [The Scientist and Engineer's Guide to Digital Signal Processing, Steven W. Smith](https://www.dspguide.com/pdfbook.htm)
  

## Other Awesome Material

* [Awesome Speaker Diarization](https://github.com/wq2012/awesome-diarization)
* [Awesome-SOTA-FER](https://github.com/kdhht2334/awesome-SOTA-FER) a curated list of facial expression recognition in both 7-emotion classification and affect estimation
* [Casual Conversations Dataset](https://ai.facebook.com/datasets/casual-conversations-dataset/)
* [Music Emotion Recognition Datasets](https://github.com/juansgomez87/datasets_emotion)
* [SER Datasets](https://superkogito.github.io/SER-datasets/#)
* [Voice Datasets](https://github.com/jim-schwoebel/voice_datasets)
* [Project TaRSila](https://sites.google.com/view/tarsila-c4ai/) speech datasets for Brazilian Portuguese language
* ✨❔

## Perspectives

<table>
  <tr>
    <td width="30%">
       A picture or picture(s) is or are worth a thousand words! A <a href="https://www.youtube.com/watch?v=t685WM5R6aM">2-min visual example</a> of how we communicate emotions, our perceptions, the role of subjectivity and what is effective listening.<br/><br/>Are emotions consistent?<br/><br/>What about the dynamics of the context to our decisions and emotional wellness?
    </td>
    <td width="70%">
        <a href="https://www.youtube.com/watch?v=t685WM5R6aM"><img src="images/video-insideout.PNG"></a>
    </td>
  </tr>
</table>

