# [NN-SVG](https://alexlenail.me/NN-SVG/) : NN-Architecture Schematics

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![status](https://joss.theoj.org/papers/52b511ab107595a805107aa4ad70161d/status.svg)](https://joss.theoj.org/papers/52b511ab107595a805107aa4ad70161d)
| [Docs](https://github.com/zfrenchee/NN-SVG/wiki) | [Contributing](https://github.com/zfrenchee/NN-SVG/wiki/Contributing)

(This repo is a minimal modification / expansion of the original code by [Alex LeNail](https://github.com/alexlenail/NN-SVG), made with gratitude and admiration!)

NN-SVG is a tool for creating Neural Network (NN) architecture drawings parametrically rather than manually. It also provides the ability to export those drawings to Scalable Vector Graphics (SVG) files, suitable for inclusion in academic papers or web pages.

The tool provides the ability to generate figures of three kinds: classic Fully-Connected Neural Network (FCNN) figures, Convolutional Neural Network (CNN) figures of the sort introduced in [the LeNet paper](http://yann.lecun.com/exdb/publis/pdf/lecun-01a.pdf), and Deep Neural Network figures following the style introduced in [the AlexNet paper](https://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks.pdf). The former two are accomplished using the [D3 javascript library](https://d3js.org/) and the latter with the javascript library [Three.js](https://threejs.org/). NN-SVG provides the ability to style the figure to the user's liking via many size, color, and layout parameters.

<img src="resources/images/example.svg">


### Citation

> LeNail, (2019). NN-SVG: Publication-Ready Neural Network Architecture Schematics. <br>
> Journal of Open Source Software, 4(33), 747, https://doi.org/10.21105/joss.00747

### Related

- [vdumoulin/conv_arithmetic](https://github.com/vdumoulin/conv_arithmetic)
- [TensorSpace](https://github.com/tensorspace-team/tensorspace)