# Awesome ML Model Compression [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

An awesome style list that curates the best machine learning model compression and acceleration research papers, articles, tutorials, libraries, tools and more. PRs are welcome!

# Contents

- [Papers](#papers)
  - [General](#general)
  - [Architecture](#architecture)
  - [Quantization](#quantization)
  - [Binarization](#binarization)
  - [Pruning](#pruning)
  - [Distillation](#distillation)
  - [Low Rank Approximation](#low-rank-approximation)
- [Articles](#articles)
  - [Howtos](#howtos)
  - [Assorted](#assorted)
  - [Reference](#reference)
  - [Blogs](#blogs)
- [Tools](#tools)
  - [Libraries](#libraries)
  - [Frameworks](#frameworks)
- [Videos](#videos)
  - [Talks](#talks)
  - [Training & tutorials](#training--tutorials)

---

## Papers

### General

- [A Survey of Model Compression and Acceleration for Deep Neural Networks](https://arxiv.org/abs/1710.09282)
- [Model compression as constrained optimization, with application to neural nets. Part I: general framework](https://arxiv.org/abs/1707.01209)
- [Model compression as constrained optimization, with application to neural nets. Part II: quantization](https://arxiv.org/abs/1707.04319)

### Architecture

- [MobileNets: Efficient Convolutional Neural Networks for Mobile Vision Applications](https://arxiv.org/abs/1704.04861)
- [MobileNetV2: Inverted Residuals and Linear Bottlenecks: Mobile Networks for Classification, Detection and Segmentation](https://arxiv.org/abs/1801.04381)
- [Xception: Deep Learning with Depthwise Separable Convolutions](https://arxiv.org/abs/1610.02357)
- [ShuffleNet: An Extremely Efficient Convolutional Neural Network for Mobile Devices](https://arxiv.org/abs/1707.01083)
- [SqueezeNet: AlexNet-level accuracy with 50x fewer parameters and <0.5MB model size](https://arxiv.org/abs/1602.07360)
- [Fast YOLO: A Fast You Only Look Once System for Real-time Embedded Object Detection in Video](https://arxiv.org/abs/1709.05943)
- [AddressNet: Shift-based Primitives for Efficient Convolutional Neural Networks](https://arxiv.org/abs/1809.08458)
- [ResNeXt: Aggregated Residual Transformations for Deep Neural Networks](https://arxiv.org/abs/1611.05431)
- [ResBinNet: Residual Binary Neural Network](https://arxiv.org/abs/1711.01243)
- [Residual Attention Network for Image Classification](https://arxiv.org/abs/1704.06904)
- [Squeezedet: Uniﬁed, small, low power fully convolutional neural networks](https://arxiv.org/abs/1612.01051)
- [SEP-Nets: Small and Effective Pattern Networks](https://arxiv.org/abs/1706.03912)
- [Dynamic Capacity Networks](https://arxiv.org/abs/1511.07838)
- [Learning Infinite Layer Networks Without the Kernel Trick](https://arxiv.org/abs/1606.05316v2)
- [Efficient Sparse-Winograd Convolutional Neural Networks](https://openreview.net/pdf?id=r1rqJyHKg)
- [DSD: Dense-Sparse-Dense Training for Deep Neural Networks](https://openreview.net/pdf?id=HyoST_9xl)
- [Coordinating Filters for Faster Deep Neural Networks](https://arxiv.org/abs/1703.09746v3)
- [Deep Networks with Stochastic Depth](https://arxiv.org/abs/1603.09382)

### Quantization

- [Quantized Convolutional Neural Networks for Mobile Devices](https://arxiv.org/abs/1512.06473)
- [Towards the Limit of Network Quantization](https://arxiv.org/abs/1612.01543)
- [Quantized Neural Networks: Training Neural Networks with Low Precision Weights and Activations](https://arxiv.org/abs/1609.07061)
- [Compressing Deep Convolutional Networks using Vector Quantization](https://arxiv.org/abs/1412.6115)
- [Trained Ternary Quantization](https://arxiv.org/abs/1612.01064)
- [The ZipML Framework for Training Models with End-to-End Low Precision: The Cans, the Cannots, and a Little Bit of Deep Learning](https://arxiv.org/abs/1611.05402)
- [ShiftCNN: Generalized Low-Precision Architecture for Inference of Convolutional Neural Networks](https://arxiv.org/abs/1706.02393)
- [Deep Learning with Low Precision by Half-wave Gaussian Quantization](https://arxiv.org/abs/1702.00953)
- [Loss-aware Binarization of Deep Networks](https://arxiv.org/abs/1611.01600)
- [Quantize weights and activations in Recurrent Neural Networks](https://arxiv.org/abs/1611.10176)
- [Fixed-Point Performance Analysis of Recurrent Neural Networks](https://arxiv.org/abs/1512.01322)
- [And the bit goes down: Revisiting the quantization of neural networks](https://arxiv.org/abs/1907.05686)

### Binarization

- [Binarized Convolutional Neural Networks with Separable Filters for Efficient Hardware Acceleration](https://arxiv.org/abs/1707.04693)
- [Binarized Neural Networks: Training Deep Neural Networks with Weights and Activations Constrained to +1 or -1](https://arxiv.org/abs/1602.02830)
- [Local Binary Convolutional Neural Networks](https://arxiv.org/abs/1608.06049)
- [XNOR-Net: ImageNet Classification Using Binary Convolutional Neural Networks](https://arxiv.org/abs/1603.05279)
- [DoReFa-Net: Training Low Bitwidth Convolutional Neural Networks with Low Bitwidth Gradients](https://arxiv.org/abs/1606.06160)

### Pruning

- [Faster CNNs with Direct Sparse Convolutions and Guided Pruning](https://arxiv.org/abs/1608.01409)
- [Deep Compression: Compressing Deep Neural Networks with Pruning, Trained Quantization and Huffman Coding](https://arxiv.org/abs/1510.00149)
- [Pruning Convolutional Neural Networks for Resource Efficient Inference](https://arxiv.org/abs/1611.06440)
- [Pruning Filters for Efficient ConvNets](https://arxiv.org/abs/1608.08710)
- [Designing Energy-Efficient Convolutional Neural Networks using Energy-Aware Pruning](https://arxiv.org/abs/1611.05128)
- [Learning to Prune: Exploring the Frontier of Fast and Accurate Parsing](http://www.cs.jhu.edu/~jason/papers/vieira+eisner.tacl17.pdf)
- [Fine-Pruning: Joint Fine-Tuning and Compression of a Convolutional Network with Bayesian Optimization](https://arxiv.org/abs/1707.09102)
- [Learning both Weights and Connections for Efficient Neural Networks](https://arxiv.org/abs/1506.02626)
- [ThiNet: A Filter Level Pruning Method for Deep Neural Network Compression](https://arxiv.org/abs/1707.06342)
- [Data-Driven Sparse Structure Selection for Deep Neural Networks](https://arxiv.org/abs/1707.01213)
- [Soft Weight-Sharing for Neural Network Compression](https://arxiv.org/abs/1702.04008)
- [Dynamic Network Surgery for Efficient DNNs](https://arxiv.org/abs/1608.04493)
- [Channel pruning for accelerating very deep neural networks](http://openaccess.thecvf.com/content_ICCV_2017/papers/He_Channel_Pruning_for_ICCV_2017_paper.pdf)
- [AMC: AutoML for model compression and acceleration on mobile devices](http://openaccess.thecvf.com/content_ECCV_2018/papers/Yihui_He_AMC_Automated_Model_ECCV_2018_paper.pdf)
- [ESE: Efficient Speech Recognition Engine with Sparse LSTM on FPGA](https://arxiv.org/abs/1612.00694)

### Distillation

- [Distilling the Knowledge in a Neural Network](https://arxiv.org/abs/1503.02531)
- [Deep Model Compression: Distilling Knowledge from Noisy Teachers](https://arxiv.org/abs/1610.09650)
- [Learning Efficient Object Detection Models with Knowledge Distillation](http://papers.nips.cc/paper/6676-learning-efficient-object-detection-models-with-knowledge-distillation.pdf)
- [Data-Free Knowledge Distillation For Deep Neural Networks](https://arxiv.org/abs/1710.07535)
- [Knowledge Projection for Effective Design of Thinner and Faster Deep Neural Networks](https://arxiv.org/abs/1710.09505)
- [Moonshine: Distilling with Cheap Convolutions](https://arxiv.org/abs/1711.02613)
- [Model Distillation with Knowledge Transfer from Face Classification to Alignment and Verification](https://arxiv.org/abs/1709.02929)
- [Like What You Like: Knowledge Distill via Neuron Selectivity Transfer](https://arxiv.org/abs/1707.01219)
- [Sequence-Level Knowledge Distillation](https://arxiv.org/abs/1606.07947)
- [Learning Loss for Knowledge Distillation with Conditional Adversarial Networks](https://arxiv.org/abs/1709.00513)
- [Dark knowledge](http://www.ttic.edu/dl/dark14.pdf)
- [DarkRank: Accelerating Deep Metric Learning via Cross Sample Similarities Transfer](https://arxiv.org/abs/1707.01220)
- [FitNets: Hints for Thin Deep Nets](https://arxiv.org/abs/1412.6550)
- [MobileID: Face Model Compression by Distilling Knowledge from Neurons](https://www.aaai.org/ocs/index.php/AAAI/AAAI16/paper/view/11977)
- [Paying More Attention to Attention: Improving the Performance of Convolutional Neural Networks via Attention Transfer](https://arxiv.org/abs/1612.03928)

### Low Rank Approximation

- [Speeding up convolutional neural networks with low rank expansions](http://www.robots.ox.ac.uk/~vgg/publications/2014/Jaderberg14b/jaderberg14b.pdf)
- [Compression of Deep Convolutional Neural Networks for Fast and Low Power Mobile Applications](https://arxiv.org/abs/1511.06530)
- [Convolutional neural networks with low-rank regularization](https://arxiv.org/abs/1511.06067)
- [Exploiting Linear Structure Within Convolutional Networks for Efficient Evaluation](https://arxiv.org/abs/1404.0736)
- [Accelerating Very Deep Convolutional Networks for Classification and Detection](https://arxiv.org/abs/1505.06798)
- [Efficient and Accurate Approximations of Nonlinear Convolutional Networks](https://arxiv.org/abs/1411.4229)

## Articles

Content published on the Web.

### Howtos

- [How to Quantize Neural Networks with TensorFlow](https://petewarden.com/2016/05/03/how-to-quantize-neural-networks-with-tensorflow/)

### Assorted

- [Why the Future of Machine Learning is Tiny](https://petewarden.com/2018/06/11/why-the-future-of-machine-learning-is-tiny/)
- [Deep Learning Model Compression for Image Analysis: Methods and Architectures](https://medium.com/comet-app/deep-learning-model-compression-for-image-analysis-methods-and-architectures-398f82b0c06f)

### Reference

### Blogs

- [TensorFlow Model Optimization Toolkit — Pruning API](https://medium.com/tensorflow/tensorflow-model-optimization-toolkit-pruning-api-42cac9157a6a?linkId=67380711)
- [Compressing neural networks for image classification and detection](https://ai.facebook.com/blog/compressing-neural-networks-for-image-classification-and-detection/) - Facebook AI researchers have developed a new method for reducing the memory footprint of neural networks by quantizing their weights, while maintaining a short inference time. They manage to get a 76.1% top-1 ResNet-50 that fits in 5 MB and also compress a Mask R-CNN within 6 MB.

## Tools
  
### Libraries

- [TensorFlow Model Optimization Toolkit](https://github.com/tensorflow/model-optimization). Accompanied blog post, [TensorFlow Model Optimization Toolkit — Pruning API](https://medium.com/tensorflow/tensorflow-model-optimization-toolkit-pruning-api-42cac9157a6a?linkId=67380711)

### Frameworks

### Paper Implementations

- [facebookresearch/kill-the-bits](https://github.com/facebookresearch/kill-the-bits) - code and compressed models for the paper, "And the bit goes down: Revisiting the quantization of neural networks" by Facebook AI Research.

## Videos

### Talks

### Training & tutorials

# License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Cedric Chee](https://github.com/cedrickchee) has waived all copyright and related or neighboring rights to this work.
