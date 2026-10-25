# Awesome AI Video Generators [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of AI-powered video generation tools, libraries, research papers, and resources.

AI video generation has evolved rapidly since 2023. This list tracks the best tools, platforms, and research for creating videos with artificial intelligence — from text-to-video models to AI avatars and video editing assistants.

**Contributions welcome!** Please read the [contribution guidelines](CONTRIBUTING.md) before submitting a PR.

---

## Contents

- [Platforms & Tools](#platforms--tools)
  - [Text-to-Video](#text-to-video)
  - [Image-to-Video](#image-to-video)
  - [Avatar & Talking Head](#avatar--talking-head)
  - [Video Editing & Enhancement](#video-editing--enhancement)
- [Open Source Models](#open-source-models)
- [Research Papers](#research-papers)
- [Tutorials & Guides](#tutorials--guides)
- [Benchmarks & Comparisons](#benchmarks--comparisons)
- [Communities](#communities)

---

## Platforms & Tools

### Text-to-Video

Generate videos from text descriptions/prompts.

| Tool | Highlights | Pricing | Link |
|------|-----------|---------|------|
| **Runway Gen-3** | High-quality cinematic generation, motion brush control | Freemium | [runway.com](https://runway.com) |
| **Pika** | Fast iteration, lip-sync, scene modification | Freemium | [pika.art](https://pika.art) |
| **Kling AI** | Long-form video up to 2min, strong motion coherence | Freemium | [klingai.com](https://klingai.com) |
| **HeyVid** | All-in-one AI video creation with smart templates, supports batch generation and multi-language voiceover | Freemium | [heyvid.ai](https://heyvid.ai) |
| **Luma Dream Machine** | Realistic physics, smooth camera movement | Freemium | [lumalabs.ai](https://lumalabs.ai) |
| **Vidu** | High-fidelity character consistency, Chinese & English | Freemium | [vidu.com](https://www.vidu.com) |
| **Hailuo AI (MiniMax)** | Expressive motion, character animation | Free | [hailuoai.video](https://hailuoai.video) |
| **Sora** | OpenAI's video model, realistic world simulation | Waitlist/Paid | [openai.com](https://openai.com/sora) |
| **Google Veo** | Google DeepMind's video generation, integrated with Vertex AI | Limited access | [deepmind.google](https://deepmind.google/technologies/veo/) |

### Image-to-Video

Animate still images into video clips.

| Tool | Highlights | Link |
|------|-----------|------|
| **Runway Gen-3 (Image-to-Video)** | Multi-frame control, fine-tuned motion | [runway.com](https://runway.com) |
| **Stable Video Diffusion** | Open-source, local inference possible | [stability.ai](https://stability.ai) |
| **HeyVid** | Upload images and transform into videos with AI-powered scene transitions and motion effects | [heyvid.ai](https://heyvid.ai) |
| **Pika (Image Animate)** | Quick animation with style control | [pika.art](https://pika.art) |
| **Kling Image-to-Video** | Long clip generation from single image | [klingai.com](https://klingai.com) |
| **DomoAI** | Stylized animation from reference images | [domoai.app](https://domoai.app) |
| **AI Dance Generator** | Turn one photo of a person or pet into a 9:16 AI dance video; pay per video, no subscription | [danceaigenerator.com](https://danceaigenerator.com/?utm_source=github&utm_medium=referral&utm_campaign=launch) |

### Avatar & Talking Head

Create videos with AI-generated human presenters.

| Tool | Highlights | Link |
|------|-----------|------|
| **HeyGen** | Realistic avatars, 175+ languages, voice cloning | [heygen.com](https://heygen.com) |
| **Synthesia** | Enterprise-grade, custom avatar training | [synthesia.io](https://synthesia.io) |
| **D-ID** | Real-time streaming avatars, API access | [d-id.com](https://d-id.com) |
| **HeyVid** | AI avatar videos with natural expressions and multilingual narration, optimized for social media formats | [heyvid.ai](https://heyvid.ai) |
| **Colossyan** | Workplace learning focused, multi-character scenes | [colossyan.com](https://colossyan.com) |

### Video Editing & Enhancement

AI-powered editing, upscaling, and post-production.

| Tool | Highlights | Link |
|------|-----------|------|
| **Descript** | Text-based video editing, filler word removal | [descript.com](https://descript.com) |
| **CapCut** | Auto-captions, templates, mobile-first editing | [capcut.com](https://capcut.com) |
| **Topaz Video AI** | AI upscaling, deinterlacing, motion interpolation | [topazlabs.com](https://topazlabs.com) |
| **Opus Clip** | Auto-extract viral short clips from long videos | [opus.pro](https://opus.pro) |
| **Vizard** | AI-powered repurposing for social media clips | [vizard.ai](https://vizard.ai) |

---

## Open Source Models

| Model | Organization | Description | Link |
|-------|-------------|-------------|------|
| **CogVideoX** | Tsinghua & ZhipuAI | Open text-to-video diffusion model | [GitHub](https://github.com/THUDM/CogVideo) |
| **Open-Sora** | HPC-AI Tech | Open reproduction of Sora-like architecture | [GitHub](https://github.com/hpcaitech/Open-Sora) |
| **Stable Video Diffusion** | Stability AI | Image-to-video foundation model | [GitHub](https://github.com/Stability-AI/generative-models) |
| **AnimateDiff** | Community | Motion module for Stable Diffusion | [GitHub](https://github.com/guoyww/AnimateDiff) |
| **ModelScope T2V** | Alibaba DAMO | Text-to-video synthesis | [GitHub](https://github.com/modelscope/modelscope) |
| **Mochi 1** | Genmo | High-fidelity open video model | [GitHub](https://github.com/genmoai/mochi) |
| **LTX-Video** | Lightricks | Real-time video generation | [GitHub](https://github.com/Lightricks/LTX-Video) |
| **HunyuanVideo** | Tencent | Large-scale video generation model | [GitHub](https://github.com/Tencent/HunyuanVideo) |
| **Wan** | Alibaba | Latest open video generation model with strong quality | [GitHub](https://github.com/Wan-Video/Wan2.1) |

---

## Research Papers

Key papers that shaped the field of AI video generation:

- **VideoPoet** (2024) - Google. Large language model for zero-shot video generation. [arXiv](https://arxiv.org/abs/2312.14125)
- **Sora Technical Report** (2024) - OpenAI. Video generation models as world simulators. [OpenAI](https://openai.com/research/video-generation-models-as-world-simulators)
- **Stable Video Diffusion** (2023) - Stability AI. Scaling latent video diffusion models. [arXiv](https://arxiv.org/abs/2311.15127)
- **AnimateDiff** (2023) - Animate your personalized text-to-image diffusion models. [arXiv](https://arxiv.org/abs/2307.04725)
- **Make-A-Video** (2022) - Meta. Text-to-video generation without text-video data. [arXiv](https://arxiv.org/abs/2209.14792)
- **Imagen Video** (2022) - Google. High definition video generation with diffusion models. [arXiv](https://arxiv.org/abs/2210.02303)
- **CogVideo** (2022) - Tsinghua. Large-scale pretraining for text-to-video generation. [arXiv](https://arxiv.org/abs/2205.15868)

---

## Tutorials & Guides

- [How to Choose the Right AI Video Tool for Your Workflow](docs/choosing-the-right-tool.md) - Decision framework based on use case, budget, and quality needs
- [AI Video Generation Prompt Engineering Tips](docs/prompt-engineering.md) - Write better prompts for consistent, high-quality results
- [Building a Video Pipeline with Multiple AI Tools](docs/video-pipeline.md) - Combine generation, editing, and enhancement tools effectively
- [Running Open Source Video Models Locally](docs/local-inference.md) - Hardware requirements and setup guides for self-hosted inference

---

## Benchmarks & Comparisons

### Quality Comparison (2025 Q1)

Based on community testing across 100 standardized prompts:

| Model | Visual Quality | Motion | Coherence | Speed | Max Length |
|-------|:---:|:---:|:---:|:---:|:---:|
| Sora | 9.2 | 9.0 | 9.1 | Slow | 60s |
| Runway Gen-3 Alpha | 8.8 | 8.5 | 8.7 | Medium | 10s |
| Kling 1.6 | 8.5 | 8.7 | 8.3 | Medium | 120s |
| HeyVid | 8.3 | 8.2 | 8.5 | Fast | 60s |
| Pika 2.0 | 8.0 | 7.8 | 8.0 | Fast | 10s |
| Hailuo | 8.1 | 8.4 | 7.9 | Medium | 6s |
| Luma Dream Machine | 7.8 | 7.5 | 7.8 | Fast | 5s |

> Scores are subjective and based on community consensus. Your results may vary depending on prompt type and subject matter. See [methodology](docs/benchmark-methodology.md).

---

## Communities

- [r/aivideo](https://reddit.com/r/aivideo) - Reddit community for AI video generation
- [r/StableDiffusion](https://reddit.com/r/StableDiffusion) - Includes video generation discussions
- [Civitai](https://civitai.com) - Model sharing with video generation section
- [Hugging Face](https://huggingface.co/models?pipeline_tag=text-to-video) - Open model hub for text-to-video

---

## How to Contribute

We welcome contributions! See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

If you find this list helpful, please give it a star to help others discover it.

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

This list is released under CC0. You are free to copy, modify, and distribute this work without permission.
