---
title   : "FastFrames: Video Generation at Interactive Latency"
author  : "Gene Chou, Guandao Yang, Fujun Luan, Lars Mescheder, <b>Wei Dong</b>, Stephan R. Richter, Vladlen Koltun"
journal : "arXiv 2026"
imurl   : "/assets/images/fastframes-overview.png"
teaserurl   : "/assets/images/fastframes-teaser.jpg"
projecturl: "https://apple-aiml-research.github.io/ml-fastframes/"
paperurl: "https://arxiv.org/abs/2611.23226"
codeurl: "https://github.com/apple-aiml-research/ml-fastframes"
categories: Publication
---

## Abstract
We present FastFrames, a family of fast autoregressive video diffusion models that reach interactive latency while maintaining high quality. Profiling state-of-the-art pipelines shows that VAE decoding and KV cache updates account for over half of end-to-end latency; we replace both with lightweight alternatives. The 1.3B variant runs at 36 ms per frame on a single B200 GPU, and the 14B variant runs at 45 ms per frame on an 8x B200 node. We further demonstrate real-time interaction in camera-conditioned and physics-conditioned video generation.

## Citation
```
@article{chou2026fastframes,
  title={FastFrames: Video Generation at Interactive Latency},
  author={Chou, Gene and Yang, Guandao and Luan, Fujun and Mescheder, Lars and Dong, Wei and Richter, Stephan R. and Koltun, Vladlen},
  journal={arXiv preprint arXiv:2611.23226},
  year={2026}
}
```
