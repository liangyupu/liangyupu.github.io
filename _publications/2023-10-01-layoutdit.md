---
title: "LayoutDIT: Layout-Aware End-to-End Document Image Translation with Multi-Step Conductive Decoder"
collection: publications
permalink: /publication/2023-10-01-layoutdit
date: 2023-10-01
venue: 'EMNLP 2023 Findings'
paperurl: '[openreview](https://openreview.net/forum?id=NeOsOzNMiS)'
---
Document image translation (DIT) aims to translate text embedded in images from one language to another.
It is a challenging task that needs to understand visual layout with text semantics simultaneously.
However, existing methods struggle to capture the crucial visual layout in real-world complex document images.
In this work, we make the first attempt to incorporate layout knowledge into DIT in an end-to-end way.
Specifically, we propose a novel Layout-aware end-to-end Document Image Translation (LayoutDIT) with multi-step conductive decoder.
A layout-aware encoder is first introduced to model visual layout relations with raw OCR results.
Then a novel multi-step conductive decoder is unified with hidden states conduction across three step-decoders to achieve the document translation step by step.
Benefiting from the layout-aware end-to-end joint training, our LayoutDIT outperforms state-of-the-art methods with better parameter efficiency.
Besides, we create a new multi-domain document image translation dataset to validate the model’s generalization.
Extensive experiments show that LayoutDIT has a good generalization in diverse and complex layout scenes.

Download: [openreview](https://openreview.net/forum?id=NeOsOzNMiS)

Recommended citation:
```latex
@inproceedings{
zhang2023layoutdit,
title={Layout{DIT}: Layout-Aware End-to-End Document Image Translation with Multi-Step Conductive Decoder},
author={Zhiyang Zhang and Yaping Zhang and Yupu Liang and Lu Xiang and Yang Zhao and Yu Zhou and Chengqing Zong},
booktitle={The 2023 Conference on Empirical Methods in Natural Language Processing},
year={2023},
url={https://openreview.net/forum?id=NeOsOzNMiS}
}
```
