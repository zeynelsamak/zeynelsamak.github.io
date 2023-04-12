---
layout: page
title: TranSOP&#58; Transformer-based Multimodal Classification for Stroke Treatment Outcome Prediction
description:
img: /assets/img/publication_preview/transop.png
importance: 2
category: stroke
refs: [samak]
---

[Zeynel Abidin Samak](https://zeynelsamak.github.io/)<sup>1</sup>, [Philip Clatworthy](http://www.bris.ac.uk/clinical-sciences/people/231094/overview.html)<sup>2,3</sup> and [Majid Mirmehdi](http://people.cs.bris.ac.uk/~majid//)<sup>1</sup>

<sup>1</sup>Dept. of Computer Science, University of Bristol, <sup>2</sup>Translational Health Sciences, University of Bristol, <sup>3</sup>Stroke Neurology, Southmead Hospital, North Bristol NHS Trust, Bristol, UK

<div class="md-12">
    <img class="col three left" src="{{ site.baseurl }}/assets/img/transop_network.png" alt="" title="stroke evolution"/>
</div>

## Abstract
Acute ischaemic stroke, caused by an interruption in blood flow to brain tissue, is a leading cause of disability and mortality worldwide. The selection of patients for the most optimal ischaemic stroke treatment is a crucial step for a successful outcome, as the effect of treatment highly depends on the time to treatment. We propose a transformer-based multimodal network (TranSOP) for a classification approach that employs clinical metadata and imaging information, acquired on hospital admission, to predict the functional outcome of stroke treatment based on the modified Rankin Scale (mRS). This includes a fusion module to efficiently combine 3D non-contrast computed tomography (NCCT) features and clinical information. In comparative experiments using unimodal and multimodal data on the MRCLEAN dataset, we achieve a state-of-the-art AUC score of 0.85.

## Poster

<embed src="/assets/pdf/ISBI23_poster_357.pdf" width="770" height="400"  type="application/pdf"> 

## Downloads
*   Paper [\[arXiv\]](https://arxiv.org/abs/2301.10829)
*   Code  [\[GitHub\]](https://github.com/zeynelsamak/TranSOP/)

## Bibtex
```latex
@inproceedings{samak2023transop,
  title={TranSOP: Transformer-based Multimodal Classification for Stroke Treatment Outcome Prediction},
  author={Samak, Zeynel A and Clatworthy, Philip L and Mirmehdi, Majid},
  booktitle={20th IEEE International Symposium on Biomedical Imaging, ISBI 2023},
  year={2023},
  organization={IEEE Computer Society}
}
```

## Acknowledgements
The authors would like to thank the Principal Investigators of the MR CLEAN trial: Profs Aad van der Lugt, Diederik W.J. Dippel, Charles B.L.M. Majoie, Yvo B. W.E.M. Roos, Wim H. van Zwam and Robert J. van Oostenbrugge for providing the data. Zeynel Abidin Samak is funded by the Ministry of Education (1416/YLSY), the Republic of Turkiye.

<!-- <div class="md-12">
<h3>Related Publications</h3>
{% for r in page.refs %}
  {% bibliography -f papers -q @*[key = {{r}}] %}
{% endfor %}
</div> -->
