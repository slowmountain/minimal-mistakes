---
title: "RepoVizz-Opensignals integration"
excerpt: "Towards a community for sharing biosignal recordings"
tags: [prototype, python, multimodal]
header:
  teaser: /assets/images/projects/rapid-mix/opensignals_repovizz.png
sidebar:
  - title: "Year"
    text: "2016"
  - title: "Type"
    text: "Prototype, product"
---

This prototype was developed within the [RAPID-MIX](http://rapidmix.goldsmithsdigital.com/) project as the seed towards the creation of an open online community for sharing biosignal data recordings, in collaboration with [PLUX](https://www.plux.info) and the [Bitalino](http://bitalino.com) platform.

The signal acquisition and visualization software [OpenSignals](http://biosignalsplux.com/en/software/opensignals) is a central part of PLUX’s framework, used for carrying out biosignal recordings with their entire range of acquisition devices. OpenSignals stores data in a hierarchically structured file using the HDF5 format, where metadata information as well as annotated events can be also stored.

UPF’s multimodal data repository and visualizer [RepoVizz](http://repovizz.upf.edu/) is used in this prototype as a repository for data recorded using OpenSignals. The biosignal recordings are converted into RepoVizz datasets (after removing sensitive and personal information) and uploaded to RepoVizz using a RESTful web API. This facilitates the sharing of biosignal recordings by OpenSignals users, as well as collaborative remote work on the data using RepoVizz itself. 

This prototype was eventually integrated inside the Opensignals software, as well as its online counterpart [Opensignals.net](http://opensignals.net/).

<blockquote class="embedly-card"><h4><a href="https://drive.google.com/open?id=0B7_Yy_acP_cnNEpwNUhIM1JRR00">OpenBiosignalRepository.mp4</a></h4><p>null</p></blockquote>
<script async src="//cdn.embedly.com/widgets/platform.js" charset="UTF-8"></script>

