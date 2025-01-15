# Padding-Tone

A repository for the paper [Padding Tone: A Mechanistic Analysis of Padding Tokens in T2I Models](https://arxiv.org/pdf/2501.06751).

**Code coming soon.**

---

## Abstract

Text-to-image (T2I) diffusion models rely on encoded prompts to guide the image generation process. Typically, these prompts are extended to a fixed length by adding padding tokens before text encoding. Despite being a default practice, the influence of padding tokens on the image generation process has not been investigated. In this work, we conduct the first
in-depth analysis of the role padding tokens play in T2I models. We develop two causal techniques to analyze how information is encoded in the representation of tokens across ifferent components of the T2I pipeline. Using these techniques, we investigate when and how padding tokens impact the image generation process. Our findings reveal three distinct cenarios: padding tokens may affect the model’s output during text encoding, during the diffusion process, or be effectively ignored. Moreover, we identify key relationships between these scenarios and the model’s architecture (cross or self-attention) and its training process (frozen or trained text encoder). These insights contribute to a deeper understanding
of the mechanisms of padding tokens, potentially informing future model design and training practices in T2I systems.
---

## Main Figure

![Main Figure](flux_pad.jpeg)
