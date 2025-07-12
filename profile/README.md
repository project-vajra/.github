# Project Vajra

> Next-generation AI inference engine built for performance, scale, and simplicity.

State-of-the-art AI systems are rapidly gaining new capabilities—multimodal processing, extreme context lengths, complex reasoning chains. While companies like Google and OpenAI have built proprietary infrastructure to serve these advanced models, the open source ecosystem is struggling to keep pace.

AI systems are becoming fundamental infrastructure. We need serving systems built for the long term, designed to evolve with AI capabilities rather than constantly playing catch-up.

## What We're Building

Rather than incrementally improving existing architectures, we're building Vajra from the ground up. Our approach starts with understanding the performance characteristics that matter most: latency, throughput, memory efficiency, and fault tolerance. Every design decision flows from real constraints we've measured and bottlenecks we've debugged.

Vajra synthesizes learnings from our previous systems research into a unified inference engine. We've designed novel batching and scheduling techniques that improved serving throughput by up to 6.9x in **[Sarathi-Serve](https://arxiv.org/abs/2403.02310)** (OSDI 2024). We've built simulation frameworks like **[Vidur](https://arxiv.org/abs/2405.05465)** (MLSys 2024) that reduce deployment exploration from 42K GPU hours to 1 CPU hour. We've enabled production-scale long-context inference with **[Medha](https://arxiv.org/abs/2409.17264)**, supporting up to 10M tokens while reducing latency by 30x.

Each project taught us something essential about performance characteristics, failure modes, and scaling challenges. Vajra brings together these insights to tackle high-performance inference with minimal latency, intelligent resource allocation across distributed clusters, native support for multimodal processing, extreme context lengths, and robust error handling under real-world conditions.

## Current Status

Our C++ core is operational and delivering strong performance gains. The foundational architecture is in place, with core inference pipelines running and initial benchmarks looking promising. We're methodically expanding capabilities while maintaining the performance characteristics that define Vajra. Initial release planned for winter 2025.

## Collaborative Development

We're looking for contributors who share our interest in AI infrastructure and systems research. This includes researchers, engineers, and students who want to work on challenging technical problems with real-world impact.

The project benefits from diverse perspectives—whether you're focused on low-level optimization, distributed systems design, or understanding AI workload characteristics, there's meaningful work to be done.

- 🌐 [Website](https://project-vajra.github.io)
- 💬 [Discord](https://discord.gg/wjaSvGgsNN)
- 🐦 [Twitter](https://x.com/ProjectVajra)
