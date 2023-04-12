---
layout: page
title: FeMA&#58; Feature Matching Auto-encoder for Predicting Ischaemic Stroke Evolution and Treatment Outcome
description:
img: assets/img/publication_preview/fema.png
importance: 2
category: stroke
refs: [samak]
---

[Zeynel Abidin Samak](https://zeynelsamak.github.io/)<sup>1</sup>, [Philip Clatworthy](http://www.bris.ac.uk/clinical-sciences/people/231094/overview.html)<sup>2,3</sup> and [Majid Mirmehdi](http://people.cs.bris.ac.uk/~majid//)<sup>1</sup>

<sup>1</sup>Dept. of Computer Science, University of Bristol, <sup>2</sup>Translational Health Sciences, University of Bristol, <sup>3</sup>Stroke Neurology, Southmead Hospital, North Bristol NHS Trust, Bristol, UK

<div class="md-12">
    <img class="col three left" src="{{ site.baseurl }}/assets/img/fema_network.png" alt="" title="stroke evolution"/>
</div>

## Abstract
Although, predicting ischaemic stroke evolution and treatment outcome provide important information one step towards individual treatment planning, classifying functional outcome and modelling the brain tissue evolution remains a challenge due to data complexity and visually subtle changes in the brain. We propose a novel deep learning approach, Feature Matching Auto-encoder (FeMA) that consists of two stages, predicting ischaemic stroke evolution at one week without voxel-wise annotation and predicting ischaemic stroke treatment outcome at 90 days from a baseline scan. In the first stage, we introduce feature similarity and consistency objective, and in the second stage, we show that adding stroke evolution information increase the performance of functional outcome prediction. Comparative experiments demonstrate that our proposed method is more effective to extract representative follow-up features and achieves the best results for functional outcome of stroke treatment.


## Downloads
*   Paper [\[ScienceDirect\]](https://www.sciencedirect.com/science/article/pii/S0895611122000623)
*   Code  [\[GitHub\]](https://github.com/zeynelsamak/FeMA)

## Bibtex
```latex
@article{samak2022fema,
  title={FeMA: Feature matching auto-encoder for predicting ischaemic stroke evolution and treatment outcome},
  author={Samak, Zeynel A and Clatworthy, Philip and Mirmehdi, Majid},
  journal={Computerized Medical Imaging and Graphics},
  volume={99},
  pages={102089},
  year={2022},
  publisher={Elsevier}
}
```

## Acknowledgements
The authors would like to thank the MR CLEAN Trial Principal Investigators: Prof Aad van der Lugt, Prof Diederik W.J. Dippel, Prof. Charles B.L.M. Majoie, Prof. Yvo B. W.E.M. Roos, Prof. Wim H. van Zwam and Prof. Robert J. van Oostenbrugge for providing the data. Zeynel Samak gratefully acknowledges funding from the Republic of Turkey Ministry of National Education Grant MoNE-1416/YLSY).

<!-- <div class="md-12">
<h3>Related Publications</h3>
{% for r in page.refs %}
  {% bibliography -f papers -q @*[key = {{r}}] %}
{% endfor %}
</div> -->
