---
layout: page
title: Thrombectomy
description: Prediction of Thrombectomy Functional Outcomes using Multimodal Data
img: assets/img/stroke.jpg
importance: 2
category: thromb
refs: [samak]
---

<div class="md-12">
    <img class="col three left" src="{{ site.baseurl }}/assets/img/stroke.jpg" alt="" title="stroke evolution"/>
</div>


Recent randomised clinical trials have shown that while patients with ischaemic stroke benefit from endovascular thrombectomy, determining whether a patient's circumstance is favourable for the treatment remains a challenge. We propose a novel deep learning approach to directly exploit multimodal data (clinical metadata information and medical imaging, as well as clinical scores obtained from images) to estimate the success of ischaemic stroke treatment. We
incorporate an attention mechanism in our architecture to model global feature inter-dependencies, both channel-wise and spatially. We perform comparative experiments using unimodal and multimodal data, and achieve 0.75 AUC in dichotomised mRS scores and 0.35 classification accuracy in individual mRS scores.

<iframe width="800" height="400" src="https://www.youtube.com/embed/MKhkJZHT4Zw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<!-- <div class="md-12">
<h3>Related Publications</h3>
{% for r in page.refs %}
  {% bibliography -f papers -q @*[key = {{r}}] %}
{% endfor %}
</div> -->
