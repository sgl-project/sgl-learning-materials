# Materials for learning SGLang

## Announcement

🎉 Through dedicated efforts from July to December 2024, the SGLang team has achieved significant milestones with three major releases: [v0.2](https://lmsys.org/blog/2024-07-25-sglang-llama3/), [v0.3](https://lmsys.org/blog/2024-09-04-sglang-v0-3/), and [v0.4](https://lmsys.org/blog/2024-12-04-sglang-v0-4/). For detailed optimization insights, please refer to our corresponding blog posts.

🚀 We're proud to announce that SGLang has been adopted as:
- The dominant LLM engine by AMD
- The default LLM engine for xAI

For more information, please check out [AMD's ROCm 6.3 official announcement](https://community.amd.com/t5/ai/unlocking-new-horizons-in-ai-and-hpc-with-the-release-of-amd/ba-p/726434) and [xAI's presentation](https://www.amd.com/en/developer/resources/advancing-ai/developer-sessions.html) at the AMD Advancing AI Conference 2024.

## Blog

## LMSYS Org

[2024-12-04] [SGLang v0.4: Zero-Overhead Batch Scheduler, Cache-Aware Load Balancer, Faster Structured Outputs](https://lmsys.org/blog/2024-12-04-sglang-v0-4/)

[2024-09-04] [SGLang v0.3 Release: 7x Faster DeepSeek MLA, 1.5x Faster torch.compile, Multi-Image/Video LLaVA-OneVision](https://lmsys.org/blog/2024-09-04-sglang-v0-3/)

[2024-07-25] [Achieving Faster Open-Source Llama3 Serving with SGLang Runtime (vs. TensorRT-LLM, vLLM)](https://lmsys.org/blog/2024-07-25-sglang-llama3/)

[2024-02-05] [Fast JSON Decoding for Local LLMs with Compressed Finite State Machine](https://lmsys.org/blog/2024-02-05-compressed-fsm/)

[2024-01-17] [Fast and Expressive LLM Inference with RadixAttention and SGLang](https://lmsys.org/blog/2024-01-17-sglang/)

## AMD

[2024-11-13] [SGLang: Fast Serving Framework for Large Language and Vision-Language Models on AMD GPUs](https://rocm.blogs.amd.com/artificial-intelligence/sglang/README.html)

## Slides

### CAMEL-AI Hackathon: Mastering Multi-Agent Systems

[2024-12-21] [SGLang v0.4 Optimization](https://gamma.app/docs/SGLang-v04-Optimization-6x6pml7351oy58r?mode=doc)

### GPU MODE

[2024-11-10] [SGLang Performance Optimization](slides/SGLang-Performance-Optimization-YinengZhang.pdf)

### The first LMSYS online meetup: Efficient LLM Deployment and Serving

[2024-10-16] [SGLang Overview & CPU Overhead Hiding](slides/lmsys_1st_meetup_sglang.pdf)

[2024-10-16] [Faster Constrained Decoding](slides/lmsys_1st_meetup_constrained_decoding.pdf)

[2024-10-16] [SGLang DeepSeek MLA](slides/lmsys_1st_meetup_deepseek_mla.pdf)

[2024-10-16] [Universal LLM deployment and low-latency serving in MLC LLM](slides/lmsys_1st_meetup_mlcengine.pdf)

[2024-10-16] [XGrammar: Flexible And Efficient Structured Generation Engine for Large Language Models](slides/lmsys_1st_meetup_xgrammar.pdf)

[2024-10-16] [Review of the first LMSYS online meetup: Efficient LLM Deployment and Serving](blogs/Efficient%20LLM%20Deployment%20and%20Serving.md)

### AMD Advancing AI 2024

[2024-10-10] [Efficient LLM Inference with SGLang](slides/amd_dev_day_v2.pdf)

### SGLang Biweekly Meeting

[2024-11-30] [Update Weights From Distributed](slides/update-weights-from-distributed.pdf)

[2024-11-16] [SGLang Router](slides/sglang_router.pdf) and [Side-Channel KV Cache Attack](slides/Possible_Timing_Side_Channel_Of_KV_Cache.pdf)

[2024-11-02] [Quantization on AMD](slides/sglang-fp8-mxfp-quantizations.pdf)

[2024-10-05] [SGLang Double Sparsity](https://docs.google.com/presentation/d/1ibXDY7hjsk12QYcLeDpsFDYGlNvbkEF1XBgQJ-CqRDE)

[2024-09-21] [SGLang DeepSeek MLA](https://docs.google.com/presentation/d/1wB_Ul0LZwIDL47qFl64b8hVhH1_ya-1YPAPSSv0cKMs)

### Other

[SGLang v0.2: Faster Interface and Runtime for LLM Inference](slides/sglang_v0_2.pdf)

## Videos

Welcome to follow our YouTube [channel](https://www.youtube.com/@lmsys-org).

### GPU MODE

[2024-11-10] [SGLang Performance Optimization](https://www.youtube.com/watch?v=XQylGyG7yp8)

### The first LMSYS online meetup

[2024-10-16] [The First SGLang Online Meetup](https://www.youtube.com/watch?v=_mzKptPj0hE)

### AMD Advancing AI 2024

[2024-10-10] [Efficient LLM Inference with SGLang](https://www.youtube.com/watch?v=Ny4xxErgFgQ)

### SGLang Biweekly Meeting

[2024-12-28] [SGLang Developer Sync 20241228](https://www.youtube.com/watch?v=mtdcxS2vIkE)

[2024-12-14] [SGLang Developer Sync 20241214](https://www.youtube.com/watch?v=zbEaV1ypm9g)

[2024-11-30] [SGLang Developer Sync 20241130](https://www.youtube.com/watch?v=CcdGb310KWU)

[2024-11-16] [SGLang Developer Sync 20241116](https://www.youtube.com/watch?v=0ka7P0IWUxY)

[2024-11-03] [SGLang Developer Sync 20241103](https://www.youtube.com/watch?v=k8Jo6-XcStM)

[2024-10-19] [SGLang Developer Sync 20241019](https://www.youtube.com/watch?v=wEUxk2WrMg8)

[2024-10-05] [SGLang Developer Sync 20241005](https://www.youtube.com/watch?v=GdLE5nd2nJo)

[2024-09-21] [SGLang Developer Sync 20240921](https://www.youtube.com/watch?v=bPtM-LLlCCU)

## Paper

[NeurIPS 24] [SGLang: Efficient Execution of Structured Language Model Programs](https://arxiv.org/abs/2312.07104)


## Documentaion

[SGLang Documentation](https://sgl-project.github.io/)
