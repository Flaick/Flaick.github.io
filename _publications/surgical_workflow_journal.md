---
title: "Anticipation for Surgical Workflow Using Instrument Interaction and Recognized Signals"
collection: publications
permalink: /publication/surgical_workflow_journal
date: 2022-09-06
venue: 'Medical Image Analysis'
---
Abstract
======
Surgical workflow anticipation is an essential task for computer-assisted intervention (CAI) systems. It aims at predicting the future surgical phase and instrument occurrence, providing support for intra-operative decision-support system. Recent studies have promoted the development of the anticipation task by transforming it into a remaining time prediction problem, but without factoring the surgical instruments’ behaviors and their interactions with surrounding anatomies in the network design. In this paper, we propose an Instrument Interaction Aware Anticipation Network (IIA-Net) to overcome the previous deficiency while retaining the merits of two-stage models through using spatial feature extractor and temporal model. Spatially, feature extractor utilizes tooltips’ movement to extracts the instrument–instrument interaction, which helps model concentrate on the surgeon’s actions. On the other hand, it introduces the segmentation map to capture the rich instrument-surrounding features about the instrument surroundings. Temporally, the temporal model applies the causal dilated multi-stage temporal convolutional network to capture the long-term dependency in the long and untrimmed surgical videos with a large receptive field. Our IIA-Net enforces an online inference with reliable predictions even with severe noise and artifacts in the recorded videos and presence signals. Extensive experiments on Cholec80 dataset demonstrate the performance of our proposed method exceeds the state-of-the-art method by a large margin . For reproduction purposes, all the original codes are made public at this [URL](https://github.com/Flaick/Surgical-Workflow-Anticipation)
