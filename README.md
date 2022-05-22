# Awesome Speech Emotion Recognition [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/abikaki/awesome-speech-emotion-recognition) [![Maintenance](https://img.shields.io/badge/Maintained%3F-YES-green.svg)](https://github.com/abikaki/awesome-speech-emotion-recognition/graphs/commit-activity)

## Topics

* [What's New](#WhatsNew)
* [Reviews](#Reviews)
* [Databases](#Databases)
* [Software](#Software)
* [Journals](#Journals)
* [Conferences](#Conferences)
* [Other Awesome-related Material](#OtherAwesome)
* [Perspectives](#Perspectives)

## What's New
|Year| Month | Database | Title | Topics |
| -- | ------| -------- | ----- | ------ |
| 2022 | May | Speech Prosody 2022 | [Speech Emotion Recognition using Time-frequency Random Circular Shift and Deep Neural Networks](https://hal.archives-ouvertes.fr/hal-03583535) | <b>Data augmentation</b> based on circular shift of the input time-frequency representation | 


## Reviews
|Year| Database | Title | Topics |
| -- | -------- | ----- | ------ |
| 2022 | Neural Computing and Applications | [Human emotion recognition from EEG-based brain–computer interface using machine learning: a comprehensive review](https://doi.org/10.1007/s00521-022-07292-4) | Human emotion recognition using EEG-based brain signals and machine learning | 
| 2022 | Wireless Personal Communications | [Survey of Deep Learning Paradigms for Speech Processing](https://doi.org/10.1007/s11277-022-09640-y) | Machine learning techniques for speech processing | 
| 2021 | IEEE Access | [A Comprehensive Review of Speech Emotion Recognition Systems](https://doi.org/10.1109/ACCESS.2021.3068045) | SER systems' varied design components/methodologies, databases |
| 2021 | Electronics | [A Review on Speech Emotion Recognition Using Deep Learning and Attention Mechanism](https://www.mdpi.com/2079-9292/10/10/1163) | Extensive comparison of Deep Learning architectures, mainly on the IEMOCAP benchmark database | 
| 2021 | Digital Signal Processing | [A survey of speech emotion recognition in natural environment](https://doi.org/10.1016/j.dsp.2020.102951) | A comprehensive survey of SER in the natural environment, various issues of SER in the natural environment, databases, feature extraction, and models |
| 2021 | Archives of Computational Methods in Engineering | [Survey on Machine Learning in Speech Emotion Recognition and Vision Systems Using a Recurrent Neural Network (RNN)](https://doi.org/10.1007/s11831-021-09647-x)| A survey of deep learning algorithms in speech and vision applications and restrictions |
| 2021 | Applied Sciences | [Deep Multimodal Emotion Recognition on Human Speech: A Review](https://doi.org/10.3390/app11177962) | An extensive review of state of the art in multimodal speech emotion recognition methodologies |

## Databases

<p>
  <span>Russell's circumplex model. In the model, emotions are distributed in a two-dimensional plane. The x-axis represents valence and the y-axis represents arousal. Valence refers to the positive and negative degree of emotion and arousal refers to the intensity of emotion. Most categorical emotions used in SER databases are based to this model</span> <br/>
  
<img src='https://user-images.githubusercontent.com/87717559/168854583-56c98ed1-6c51-4551-b9e2-0b2bd1b811a3.png' alt="Russell's circumplex model" width=300 height=300/>

</p>

<br/>

|Database| Language | Size | Type | Emotions | Modalities | Resolution |
| ------ | -------- | ---- | ---- | -------- | ---------- | ---------- |
| [Belfast Naturalistic Database](https://pureadmin.qub.ac.uk/ws/portalfiles/portal/2125652/IEEE+Transactions+on+Affective+Computing+2011+Sneddon.pdf) | Spanish | 127 multi-cultural speakers of 298 emotional clips | Natural |  Amusement, anger, disgust, fear, frustration, sadness, surprise | Audio/Visual | N/A |
| [Berlin Database of Emotional Speech (Emo-DB)](http://emodb.bilderbar.info/docu/) | German | 5 male and 5 female speakers, with more than 500 utterances | Acted | Anger, boredom, disgust, fear/anxiety, happiness, neutral, sadness | Audio | Audio: 48KHz, downsampled to 16KHz - .wav |
| [Interactive Emotional Motion Capture (USC-IEMOCAP)](https://sail.usc.edu/iemocap/) | English | A 12h multimodal and multispeaker (5 males and 5 females) database | Acted/Elicited | Anger, frustration, happiness, neutral, sadness as well as dimensional labels such as valence, activation and dominance | Audio/Visual | Audio: 48KHz, Video: 120 fps |
| [MELD: Multimodal EmotionLines Dataset](https://affective-meld.github.io/) | English | More than 13000 utterances from multiple speakers | Natural | Anger, disgust, fear, joy, neutral, non-neutral, sadness, surprise | Audio/Visual/Text | Audio: 16bit PCM - .wav |
| [OMG-Emotion](https://www2.informatik.uni-hamburg.de/wtm/OMG-EmotionChallenge/) | English | 10 hours of YouTube videos around 1min long | Natural | Continuous valence/arousal values and categorical emotions: anger, disgust, fear, happiness, neutral, sadness, surprise | Audio/Visual/Text | N/A | 
| [Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS)](https://smartlaboratory.org/ravdess/) | English | A database of emotional speech and song of 12 males and 12 females | Acted | Anger, disgust, calmness, fear, happiness, neutral, sadness, surprise | Audio/Visual | Audio: 48KHz - 16bit - .wav, Video: 720p - .mp4 | 
| [SEMAINE](https://semaine-db.eu/) | English | 95 sessions of human-agent interactions | Natural | 4D Emotional space | Audio/Visual/Text | N/A | 
| [Surrey Audio-Visual Expressed Emotion (SAVEE)](http://kahlan.eps.surrey.ac.uk/savee/) | English | 4 male speakers x 480 utterances | Acted | Anger, disgust, fear, happiness, neutral, sadness, surprise | Audio/Visual | Audio: 44KHz - Mono - 16bit - .wav, Video: 256p - 60fps - .avi | 
| [SUSAS](https://catalog.ldc.upenn.edu/LDC99S78) | English | Speech under stress corpus with more than 16000 utterances from 32 speakers (13 females, 19 males) | Acted | Ten stress styles such as speaking style, single tracking task, and Lombard effect domain | Audio | 8KHz, 8bit PCM |


## Software

* MATLAB
  * Audio Toolbox
* Python Libraries
  * [Librosa](https://librosa.org/doc/latest/index.html) | A python package for music and audio analysis
  * [PyAudioAnalysis](https://github.com/tyiannak/pyAudioAnalysis/wiki) | A python library that provides a wide range of audio-related functionalities focusing on feature extraction, classification, segmentation and visualization issues
  * [Pydub](https://github.com/jiaaro/pydub) | Manipulate audio with a simple and easy high level interface 

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
| Name | Year | Location | 
| ---- | ---- | -------- |
| [International Conference on Acoustics, Speech, & Signal Processing (ICASSP)](https://2022.ieeeicassp.org/) | 2022 | Singapore | 
| [Interspeech (ISCA)](https://interspeech2022.org) | 2022 | Korea | 

## Other Awesome-related Material

* [Awesome Speaker Diarization](https://github.com/wq2012/awesome-diarization)
* [Casual Conversations Dataset](https://ai.facebook.com/datasets/casual-conversations-dataset/)
* [SER Datasets](https://superkogito.github.io/SER-datasets/#)
* ✨❔

## Perspectives

<table>
  <tr>
    <td width="30%">
       A picture or picture(s) is or are worth a thousand words! A <a href="https://www.youtube.com/watch?v=t685WM5R6aM">1-min visual example</a> of how we communicate emotions, our perceptions, the role of subjectivity and what is effective listening.<br/><br/>Are emotions consistent?<br/><br/>What about the dynamics of the context to our decisions and emotional wellness?
    </td>
    <td width="70%">
        <a href="https://www.youtube.com/watch?v=t685WM5R6aM"><img src="images/video-insideout.PNG"></a>
    </td>
  </tr>
</table>

