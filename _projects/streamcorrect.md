---
layout: page
title: StreamCorrect
description: Bringing offline ASR performance to streaming via error correction. A lightweight error corrector that mitigates accumulated errors in real-time streaming speech recognition.
img: https://raw.githubusercontent.com/vu-duy-tung/StreamCorrect/main/assets/streamcorrect_overview.png
importance: 2
category: work
github: https://github.com/vu-duy-tung/StreamCorrect
---

## 📖 About StreamCorrect

StreamCorrect addresses the challenges of streaming ASR (Automatic Speech Recognition), where error propagation and limited context often degrade performance compared to offline models. It introduces a lightweight error corrector fine-tuned on self-generated data to mitigate accumulated errors in real-time. This approach bridges the gap between offline ASR quality and streaming requirements, preserving pretrained model performance without requiring distillation into streaming-style architectures.

<div class="row justify-content-center">
    <div class="col-sm-5 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="https://raw.githubusercontent.com/vu-duy-tung/StreamCorrect/main/assets/streamcorrect_overview.png" title="StreamCorrect Overview" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    StreamCorrect system overview
</div>

## ✨ Key Features

- **🎯 Real-time Error Correction**: Lightweight corrector mitigates accumulated errors in streaming ASR
- **🚀 Preserves Offline Quality**: Bridges the gap between offline ASR quality and streaming requirements
- **💡 Self-supervised Training**: Fine-tuned on self-generated data without manual annotation
- **🔧 Easy Integration**: Works with existing pretrained ASR models

## 🔧 Implementation

The project includes:

- **Single Audio File Inference**: Process individual audio files with StreamCorrect
- **Batch Processing**: Efficient processing of multiple audio files
- **Error Corrector Fine-tuning**: Custom training scripts for model adaptation
- **Flexible Configuration**: Support for different chunk sizes (100ms, 500ms, 1000ms)

## 🎬 Demo

StreamCorrect provides real-time error correction for streaming ASR, significantly improving transcription quality compared to standard streaming approaches. The system maintains low latency while achieving near-offline ASR performance.

For detailed usage, training instructions, and model checkpoints, visit the [GitHub repository](https://github.com/vu-duy-tung/StreamCorrect).
