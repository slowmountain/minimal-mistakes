---
title: "Score aligner"
excerpt: "A simple audio-to-midi score alignment program in MATLAB, with a helpful GUI."
tags: [music, research, MATLAB]
header:
  teaser: /assets/images/projects/thesis/score_aligner.png
  image: /assets/images/projects/thesis/score_aligner.png
sidebar:
  - title: "Year"
    text: "2014"
  - title: "Type"
    text: "PhD side project"
  - title: "Link"
    text: "[Github repository](https://github.com/slowmountain/scorealigner)"
---

Score aligner was created during my PhD thesis in the [Music Technology Group](https://www.upf.edu/web/mtg) of Universitat Pompeu Fabra, at first as a tool to help me deal with the large amount of recorded material that needed to be annotated with note onset and offset times. Eventually it proved useful to other colleagues within the MTG, so I decided to release it as open source software under a permissive license.

This software reads an audio file (in .wav and .mp3 format for windows, .wav for OSX) as well as a MIDI score and computes a temporal alignment between the two using my own implementation of [Simon Dixon's On-line Time Warping (OLTW) algorithm](https://code.soundsoftware.ac.uk/projects/match).

{% include figure image_path="/assets/images/projects/thesis/score_aligner.png" alt="Screenshot of the GUI" caption="A screenshot of Score Aligner in action." %}