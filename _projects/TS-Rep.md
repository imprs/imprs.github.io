---
layout: page
title: TS-Rep
description:
img: /assets/img/projects/methodology.png
importance: 1
category: work
---

#### TS-Rep: Self-supervised time series representation learning from robot sensor data

<br />
<a href="https://sslneurips22.github.io/paper_pdfs/paper_74.pdf" target="blank">Paper,</a>
<a href="https://github.com/imprs/TS-Rep" target="blank">Code,</a>
and Posters: <a href="https://zenodo.org/record/7135205/" target="blank">M2L Summer School</a>, <a href="https://tinyurl.com/SSL-NeurIPS22-Poster/" target="blank">SSL-NeurIPS2022</a>


In this paper, we propose TS-Rep, a self-supervised method that learns representations from multi-modal varying-length time series sensor data from real robots. TS-Rep is based on a simple yet effective technique for triplet learning, where we randomly split the time series into two segments to form anchor and positive while selecting random subseries from the other time series in the mini-batch to construct negatives. We additionally use the nearest neighbour in the representation space to increase the diversity in the positives. For evaluation, we perform a clusterability analysis on representations of three heterogeneous robotics datasets. Then learned representations are applied for anomaly detection, and our method consistently performs well. A classifier trained on TS-Rep learned representations outperforms unsupervised methods and performs close to the fully-supervised methods for terrain classification. Furthermore, we show that TS-Rep is, on average, the fastest method to train among the baselines. Our code is available at <a href="https://github.com/imprs/TS-Rep" target="blank">https://github.com/imprs/TS-Rep</a>.

<div class="row justify-content-md-center">
    <div class="col-lg-16">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/projects/methodology.png' | relative_url }}" alt="" data-zoomable title="ts-rep"/>
    </div>
</div>
