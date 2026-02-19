---
layout: page
title: Global Context Vision Mixture of Experts
description: GCViMoE integrates the Mixture of Experts paradigm with the Global Context Vision Transformer, achieving efficiency through selective expert activation while maintaining rich contextual features.
img: https://raw.githubusercontent.com/vu-duy-tung/GCViMoE/main/assets/GCViMoE_block.png
importance: 1
category: work
github: https://github.com/vu-duy-tung/GCViMoE
---

## Introduction

We propose Global Context Vision Mixture of Experts (GC-ViMoE), which integrates the Mixture of Experts paradigm with the Global Context Vision Transformer. By replacing traditional multilayer perceptron blocks with dynamically routed expert blocks, our architecture maintains the rich contextual features and locality-aware properties of GCViT while substantially reducing computational overhead.

GCViMoE is expected to achieve efficiency through selective expert activation based on input characteristics, demonstrating comparable or superior performance to state-of-the-art models with significantly lower computational requirements.

<div class="row justify-content-center">
    <div class="col-sm-5 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="https://raw.githubusercontent.com/vu-duy-tung/GCViMoE/main/assets/GCViMoE_block.png" title="GCViMoE Architecture" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The main block in the architecture of GCViMoE
</div>

## Key Features

- **Mixture of Experts Integration**: Dynamically routes inputs to specialized expert networks
- **Global Context Modeling**: Maintains rich contextual features from GCViT architecture
- **Computational Efficiency**: Significantly reduces computational overhead through selective expert activation
- **State-of-the-art Performance**: Achieves comparable or superior performance with lower computational requirements

## Implementation

The project is implemented in PyTorch and includes:

- Training scripts for ImageNet-tiny dataset
- Support for multi-GPU training
- Model validation and testing utilities
- ONNX conversion support

For more details and code, visit the [GitHub repository](https://github.com/vu-duy-tung/GCViMoE).
