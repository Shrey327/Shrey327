## Shreyansh Pathak

ML systems engineer working on LLM inference, GPU kernels and RL post-training.
B.Tech AI/ML at Dayananda Sagar College of Engineering. Software Developer Intern at Diarch Group.

[Blog](https://shrey327.github.io) · [LinkedIn](https://www.linkedin.com/in/shreyansh-pathak327/) · [Hugging Face](https://huggingface.co/Shrey327) · [Email](mailto:shreyansh.pathak27@gmail.com)

### Selected work

| Project | Summary |
| --- | --- |
| [InferenceX](https://github.com/Shrey327/InferenceX) | LLM inference server written from scratch in PyTorch: KV cache, continuous batching, paged attention, CUDA graphs and a fused Triton flash-decode kernel. On an RTX 4050: 6.34x throughput from batching, 2.58x from CUDA graphs at batch 16. |
| [kernel-env](https://github.com/Shrey327/kernel-env) | OpenEnv RL environment for GPU kernel generation. KernelBench tasks, Triton kernels, GPU-validated correctness and paired timing on Modal, GRPO training of Qwen2.5-Coder-7B. |
| Qwen3-1.7B GRPO | GRPO post-training for shorter reasoning: 22% shorter traces (579 to 450 tokens) at 85% GSM8K accuracy. |
| [torchfeather](https://github.com/Shrey327/Distributed-Training) | DeepSeek-V3 style model and distributed training experiments in PyTorch. |
| [Aegis](https://github.com/Shrey327/Aegis) | Agentic supply-chain security auditor. Specialized subagents inspect CI/CD, IAM, infrastructure config and dependencies over MCP, then correlate findings into attack chains. |
| [NeSyFS](https://github.com/Shrey327/NeSyFs) | Neuro-symbolic fast/slow agent: Neo4j fact-graph memory, stepwise reflection and particle-based planning. |
| [AI Engineering IDE](https://github.com/Shrey327/AgenticIDE) | Local-first Theia/Electron IDE for Python AI work with RAG tools, run history and OpenTelemetry traces. |

### Stack

**ML:** PyTorch, Transformers, vLLM, GRPO, LoRA  
**GPU:** CUDA, Triton, C++17, CUDA graphs, paged KV cache  
**Agents:** LangGraph, MCP, RAG, Neo4j  
**Infra:** Python, TypeScript, FastAPI, Next.js, Docker, Modal, PostgreSQL
