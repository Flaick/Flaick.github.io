---
title: "Learning Multi-modal Representations by Watching Hundreds of Surgical Video Lectures"
collection: publications
permalink: /publication/surgvlp
date: 2023-07-27
venue: 'Arxiv'
---
Abstract
======
Recent advancements in surgical computer vision applications have been driven by fully-supervised methods, primarily using only visual data. These methods rely on manually annotated surgical videos to predict a fixed set of object categories, limiting their generalizability to unseen surgical procedures and downstream tasks. In this work, we put forward the idea that the surgical video lectures available through open surgical e-learning platforms can provide effective supervisory signals for multi-modal representation learning without relying on manual annotations. We address the surgery-specific linguistic challenges present in surgical video lectures by employing multiple complementary automatic speech recognition systems to generate text transcriptions. We then present a novel method, SurgVLP - Surgical Vision Language Pre-training, for multi-modal representation learning. SurgVLP constructs a new contrastive learning objective to align video clip embeddings with the corresponding multiple text embeddings by bringing them together within a joint latent space. To effectively show the representation capability of the learned joint latent space, we introduce several vision-and-language tasks for surgery, such as text-based video retrieval, temporal activity grounding, and video captioning, as benchmarks for evaluation. We further demonstrate that without using any labeled ground truth, our approach can be employed for traditional vision-only surgical downstream tasks, such as surgical tool, phase, and triplet recognition. The code will be made available at this [URL](https://github.com/CAMMA-public/SurgVLP)
