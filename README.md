# Vangelis AI: Generation of Symbolic Spectromorphological Gestures Using MPE Datasets and Science Fictional Images

![Main](https://github.com/php0614/AI-Spectromorphology/assets/6575931/e0ccb4c5-0389-49b7-8b2b-706dfa4985db)
 Fig. The overall structure



This GitHub repository contains several practical outcomes of this project: [1] audio examples below, comparing the original rendition of an MPE keyboard and the generated one; [2] code for tokenization of control changes and channel numbers; and [3] code for visual analysis.


[![ORIGINAL](http://img.youtube.com/vi/your-video-id/0.jpg)](https://github.com/php0614/AI-Spectromorphology/assets/6575931/b69e7e5a-7ab7-4c71-8baf-16cefa9eb927)

Audio 1. An audio piece created from ORIGINAL sampled MIDI Polyphonic Expression data (a rendition of an MPE keyboard)

[![GENERATED](http://img.youtube.com/vi/your-video-id/0.jpg)](https://github.com/php0614/AI-Spectromorphology/assets/6575931/0a0f12e5-7131-45ac-98e1-335567d9afd2)

Audio 2. An audio piece created from GENERATED MIDI Polyphonic Expression data (through RNN)



### ABSTRACT
Symbolic music generation using deep learning represents a Copernican turn in computer-aided composition. In addition to existing deep learning-based methods for notes-only symbolic music generation, our aim is to generate MIDI Polyphonic Expression (MPE) sequences that include musical expression data in control change (CC) format, fitting the impressions from a given image. In other words, our method automates part of the creative practice of film composers or sonic artists who frequently employ a spectromorphological framework in their work while establishing audio-visual relationships. First, we created an MPE dataset from a rendition on an MPE keyboard by a professional player, called PolySynthWave, targeted to be sonified with a typical subtractive synthesizer in mind. We then used this data, not only for the note information but also for the included five expressions per note. To tokenize, train, infer, and generate new control change curves along with the generated notes, we added a new pipeline to the existing ‘for notes-only’ model. Additionally, adjustments based on the visual analysis of an input image are involved during the inference phase. This research enables the generation of MPE sequences with human-like polyphonic expressions that align with the attributes of the input image. These sequences are recommended to be routed to common effect parameters such as pitch shift or filter cutoff, but can be utilized for various other applications.
