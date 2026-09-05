## Deep Learning 101: from SSM to Mamba

> TL;DR: This educational material explains Mamba in Deep Learning 101 style, without prior knowledge of Transformers.

### The Concept
Mamba is one of several sequence-model backbones proposed as alternatives to Transformers, so many existing tutorials introduce it through direct comparison with Transformers. However, understanding the core ideas behind Mamba and related SSM-based models does not require prior knowledge of attention. The authors also provide optimized implementations, allowing learners to begin using Mamba without first mastering all of its mathematical and systems details. This educational resource therefore introduces the core ideas behind Mamba to learners who are familiar with the fundamentals of CNNs and RNNs.

### Leveling and Prerequisite Knowledge
Anyone who has studied CNN and RNN. This includes the following:
- CNN: convolutional kernel, skip/residual connection
- RNN: autoregressive model, backpropagation through time, gating mechanism

### Learning Objectives and Outcomes
This educational resource aims to provide an intuitive introduction to the core ideas behind Mamba.

The readers/audiences are expected to learn the following after watching the video and slides:
- SSM: continuous-time SSM, discrete-time SSM, the characteristics of SSM in deep learning, SSM before Mamba
- Mamba: time-(in)variance, selective SSM, Mamba structure, implementation
- Applications: Mamba in text, image, and time series domains

### Teaching Materials Summary
- `NeurIPS'26 - Mamba101 slides.pptx`: A 44-page PowerPoint slides.
- `NeurIPS'26 - Mamba101 quick quizzes.html`: Five quizzes to check understanding.
- [`[NeurIPS'26 Edu Track] DL101: from SSM to Mamba`](https://www.youtube.com/watch?v=AnbgV0UnmKI): A 30-minute YouTube video.
