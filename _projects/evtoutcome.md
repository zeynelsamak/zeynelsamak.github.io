---
layout: page
title: Prediction of Thrombectomy Functional Outcomes using Multimodal Data
description:
img: assets/img/stroke.jpg
importance: 2
category: stroke
refs: [samak]
---

[Zeynel Abidin Samak](https://zeynelsamak.github.io/)<sup>1</sup>, [Philip Clatworthy](http://www.bris.ac.uk/clinical-sciences/people/231094/overview.html)<sup>2,3</sup> and [Majid Mirmehdi](http://people.cs.bris.ac.uk/~majid//)<sup>1</sup>

<sup>1</sup>Dept. of Computer Science, University of Bristol, <sup>2</sup>Translational Health Sciences, University of Bristol, <sup>3</sup>Stroke Neurology, Southmead Hospital, North Bristol NHS Trust, Bristol, UK

<div class="md-12">
    <img class="col three left" src="{{ site.baseurl }}/assets/img/miua_network.jpg" alt="" title="stroke evolution"/>
</div>

## Abstract
Recent randomised clinical trials have shown that while patients with ischaemic stroke benefit from endovascular thrombectomy, determining whether a patient's circumstance is favourable for the treatment remains a challenge. We propose a novel deep learning approach to directly exploit multimodal data (clinical metadata information and medical imaging, as well as clinical scores obtained from images) to estimate the success of ischaemic stroke treatment. We
incorporate an attention mechanism in our architecture to model global feature inter-dependencies, both channel-wise and spatially. We perform comparative experiments using unimodal and multimodal data, and achieve 0.75 AUC in dichotomised mRS scores and 0.35 classification accuracy in individual mRS scores.

## Video
<iframe width="770" height="400" src="https://www.youtube.com/embed/MKhkJZHT4Zw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Downloads
*   Paper [\[arXiv\]](https://arxiv.org/abs/2005.13061)
*   Code  [\[GitHub\]](https://github.com/zeynelsamak/Thrombectomy-Outcome)

## Bibtex
```latex
@inproceedings{samak2020prediction,
  title={Prediction of thrombectomy functional outcomes using multimodal data},
  author={Samak, Zeynel A and Clatworthy, Philip and Mirmehdi, Majid},
  booktitle={Medical Image Understanding and Analysis: 24th Annual Conference, MIUA 2020, Oxford, UK, July 15-17, 2020, Proceedings 24},
  pages={267--279},
  year={2020},
  organization={Springer}
}
```

## Acknowledgements
The authors would like to thank the MR CLEAN Registry team: Prof Aad van der Lugt, Prof Diederik W.J. Dippel, Prof. Charles B.L.M. Majoie, Prof. Wim H. van Zwam and Prof. Robert J. van Oostenbrugge for providing the data. Zeynel Samak gratefully acknowledges funding from Ministry of Education (1416/YLSY), the Republic of Turkey. The Titan V used for this research was donated by the NVIDIA Corporation.

<!-- <div class="md-12">
<h3>Related Publications</h3>
{% for r in page.refs %}
  {% bibliography -f papers -q @*[key = {{r}}] %}
{% endfor %}
</div> -->
