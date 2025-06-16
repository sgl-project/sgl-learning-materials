# Materials for learning SGLang

Please join our Slack Channel https://slack.sglang.ai. For enterprises interested in adopting or deploying SGLang at scale, including technical consulting, sponsorship opportunities, or partnership inquiries, please contact us at contact@sglang.ai.

## Announcement

### May 2025

The SGLang team is delighted to announce that SGLang has become the first fully open-source LLM serving engine to support large-scale Expert-Parallelism (EP) and Prefill-Decode disaggregation, achieving throughput that matches the performance reported in the DeepSeek official blog. The cost has been reduced to $0.20 per 1M output tokens. For more details, please refer to our [LMSYS blog](https://lmsys.org/blog/2025-05-05-large-scale-ep/) and the [slides](./slides/sglang_pytorch_china_2025.pdf) presented at PyTorch Day China.

### March 2025

The SGLang team is thrilled to announce that SGLang has officially joined the PyTorch ecosystem and has achieved SOTA performance on AMD nightly image. We look forward to further open-source enhancements and improvements! For more details, please refer to the official blogs. Cheers! 🚀🚀🚀

[SGLang Joins PyTorch Ecosystem: Efficient LLM Serving Engine](https://pytorch.org/blog/sglang-joins-pytorch)

[Supercharge DeepSeek-R1 Inference on AMD Instinct MI300X](https://rocm.blogs.amd.com/artificial-intelligence/DeepSeekR1-Part2/README.html)

### February 2025
The SGLang Team is honored to announce that the following well-known companies and teams, among others, have adopted SGLang for running DeepSeek V3 and R1.
[AMD](https://www.amd.com/en/developer/resources/technical-articles/amd-instinct-gpus-power-deepseek-v3-revolutionizing-ai-development-with-sglang.html), [NVIDIA](https://build.nvidia.com/deepseek-ai/deepseek-r1/modelcard), [Microsoft Azure](https://techcommunity.microsoft.com/blog/azurehighperformancecomputingblog/running-deepseek-r1-on-a-single-ndv5-mi300x-vm/4372726), [Baseten](https://www.baseten.co/library/deepseek-v3/), [Novita AI](https://openrouter.ai/deepseek/deepseek-chat), [ByteDance Volcengine](https://mp.weixin.qq.com/s/0BItMZq7ZQwXpxYmfljvCA), [DataCrunch](https://datacrunch.io/blog/deploy-deepseek-r1-on-8x-nvidia-h200), [Hyperbolic](https://x.com/zjasper666/status/1872657228676895185), [Vultr](https://docs.vultr.com/how-to-deploy-deepseek-v3-large-language-model-llm-using-sglang), [RunPod](https://blog.runpod.io/whats-new-for-serverless-llm-usage-in-runpod-in-2025/) and so on.

### December 2024
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

[2025-03-21] [Supercharge DeepSeek-R1 Inference on AMD Instinct MI300X](https://rocm.blogs.amd.com/artificial-intelligence/DeepSeekR1-Part2/README.html)

[2025-02-21] [Unlock DeepSeek-R1 Inference Performance on AMD Instinct™ MI300X GPU](https://rocm.blogs.amd.com/artificial-intelligence/DeepSeekR1_Perf/README.html)

[2025-01-07] [AMD Instinct™ GPUs Power DeepSeek-V3: Revolutionizing AI Development with SGLang](https://www.amd.com/en/developer/resources/technical-articles/amd-instinct-gpus-power-deepseek-v3-revolutionizing-ai-development-with-sglang.html)

[2024-11-13] [SGLang: Fast Serving Framework for Large Language and Vision-Language Models on AMD GPUs](https://rocm.blogs.amd.com/artificial-intelligence/sglang/README.html)

## Meta PyTorch

[2025-03-19] [SGLang Joins PyTorch Ecosystem: Efficient LLM Serving Engine](https://pytorch.org/blog/sglang-joins-pytorch)

[2025-01-21] [Accelerating LLM Inference with GemLite, TorchAO and SGLang](https://pytorch.org/blog/accelerating-llm-inference/)

## Microsoft Azure

[2025-01-31] [Running DeepSeek-R1 on a single NDv5 MI300X VM](https://techcommunity.microsoft.com/blog/azurehighperformancecomputingblog/running-deepseek-r1-on-a-single-ndv5-mi300x-vm/4372726)

## Slides

### Hyperbolic in-person meetup

[2025-01-15] [Efficient LLM Inference with SGLang](https://gamma.app/docs/Hyperbolic-SGLang-Meet-Up-d539eo3jb9yna29?mode=doc)

[2025-01-15] [Cache-Aware Load Balancer in SGLang](slides/sglang-router.pdf)

[2025-01-15] [SGLang DeepSeek Model Optimizations](slides/sglang_deepseek_model_optimizations.pdf)

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

[2025-4-22] [Optimizing Large Scale RLHF with SGLang](https://gamma.app/docs/Optimizing-Large-Scale-RLHF-with-SGLang-dc69w8usckezkcu)

[2025-1-25] [A fair and efficient scheduling algorithm](slides/sglang-FLPM.pdf)

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

[2025-01-25] [SGLang Developer Sync 20250125](https://www.youtube.com/watch?v=KwCrPPiRwso)

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
