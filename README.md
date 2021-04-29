# Intelligibility and naturalness of articulatory text-to-speech synthesis compared to established speech synthesis technologies
This repository contains the supplementary materials to the paper: P. K. Krug et al., "Intelligibility and naturalness of articulatory synthesis with VocalTractLab compared to established speech synthesis technologies" in SSW11, 2021 (Submitted).


## What is this repository for?



## Requirements
If you would like to reproduce the audio samples presented in this repo, you will have to access the respective TTS and re-synthesis systems.
In case of Azure<sup id="a1">[1](#f1)</sup> (neural and standard), Google<sup id="a2">[1](#f2)</sup> (neural and standard) and MaryTTS<sup id="a3">[1](#f3)</sup> you can use the respetive online demo services.
In case of MBROLA-Res you will have to set up the open source software MBROLA<sup id="a4">[1](#f4)</sup> and synthesize the utterances using the provided ".pho" files from this repository.
In case of VTL-Res and VTL-TTS, the utterances can be reproduced using the open source software VocalTractLab<sup id="a5">[1](#f5)</sup> and the provided ".seg" and ".ges" files.
In case of DRESS you will have to set up the DRESS TTS system.

For more information regarding each type of syntheses, see the "Info.txt" files provided in each folder.




## File description

This repository is organized the following way:
- `` README.md`` .
- ```supplementary materials``` Contains all relevant audio files used in the experiments as well as data and information needed to reproduce the samples.

  ```└─── Name of the synthesis system``` Contains all audio samples of a specific type.
  
  ```   └─── "Name of the utterance".wav``` Contains the VTL version 2.3 speaker files.

  ```   └─── Info.txt``` Contains the VTL version 2.3 speaker files.

  ```   └─── (If necessary) data``` Contains the VTL version 2.3 speaker files.
  
  ```       └─── "Name of the utterance".datafile``` Contains the VTL version 2.3 speaker files.
  
- ```Example sentence``` Used at the beginning of the listening experiment, in order to set the volume level.




## How to cite this work

This work is distributed under the GNU GPL 3.0 License. If you use parts of this work in your own work, please cite the following reference:

- P. K. Krug et al., "Intelligibility and naturalness of articulatory synthesis with VocalTractLab compared to established speech synthesis technologies" in SSW11, 2021 (Submitted)

## References
<b id="f1">1</b> https://vocaltractlab.de/ [↩](#a1)

<b id="f2">1</b> https://azure.microsoft.com/en-us/services/cognitive-services/text-to-speech/ [↩](#a2)

<b id="f3">1</b> https://cloud.google.com/text-to-speech [↩](#a3)

<b id="f4">1</b> http://mary.dfki.de:59125/ [↩](#a4)

<b id="f5">1</b> https://vocaltractlab.de/ [↩](#a5)
