---
title: "Automatic accompaniment"
excerpt: "An AI-powered accompaniment software using Query-by-humming and Dynamic Time Warping"
tags: [music, MATLAB, Max/MSP]
header:
  teaser: /assets/images/projects/qbh/pianoaccompanist.jpg
sidebar:
  - title: "Year"
    text: "2010"
  - title: "Type"
    text: "Master Thesis"
  - title: "Link"
    text: "[Fulltext version of paper](https://zenodo.org/record/849703)"
gallery:
  - url: /assets/images/projects/qbh/FinderGUI.png
    image_path: /assets/images/projects/qbh/FinderGUI.png
    title: "Screenshot of the user interface"
  - url: /assets/images/projects/qbh/overview.png
    image_path: /assets/images/projects/qbh/overview.png
    title: "An overview of the lyrics-matching system"
---

An automatic accompaniment system for the singing voice, which allows the user to begin singing from any point within the piece he/she desires. The system is based on the Dynamic Time Warping (DTW) algorithm, which is used as both a similarity measure as well as an alignment tool between the live performance and the reference. The user’s position within the piece is initially determined with a variation of current Query by humming/singing methods, based on three sets of acoustic features; pitch trajectory, RMS energy envelope and MFCCs. After locating the user, the system adapts the tempo of the accompaniment utilizing a known on-line DTW method. The system is implemented in MATLAB and Java, while audio playback is handled using Max/MSP.

This project was carried out as my master's thesis in the [Music Technology Group](https://www.upf.edu/web/mtg) of Universitat Pompeu Fabra, supervised by [Hendrik Purwins](http://www.dtic.upf.edu/~hpurwins/). For more details on the project, check out the [SMC 2010 paper](https://zenodo.org/record/849781) or [the thesis itself](http://www.mtg.upf.edu/node/2173).

{% include gallery %}