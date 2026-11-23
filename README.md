# Kirill Starkov

**ML Systems Engineer · GPU Infrastructure · LLM Inference · AI Agents**

I build production ML systems, from GPU kernels and distributed compute to LLM serving, model deployment, and reliable agent runtimes. Previously a Tech Lead at Flexus and an ML systems engineer at Refact.ai.

[LinkedIn](https://www.linkedin.com/in/kirill-starkov/) · [Refact-1.6B on Hugging Face](https://huggingface.co/refactai/Refact-1_6B-fim) · [AWS case study](https://aws.amazon.com/solutions/case-studies/refactai-case-study/)

## Selected engineering work

- **GPU platform & scheduling:** Built Kubernetes-based provisioning for a 16-node / 128× RTX A5000 cluster, including shared training/inference capacity. Queue-aware Rust routing and autoscaling reduced allocated serving GPUs from 16 to 8–10 under comparable traffic.
- **LLM inference & model integration:** Built C++/CUDA/Triton inference components and the Hugging Face-compatible release for Refact-1.6B, a code model that reached 32.0% HumanEval pass@1 at launch.
- **Alternative accelerators:** Ported StarCoder2 inference to AWS Inferentia2/Neuron and helped deliver an AWS Marketplace deployment. [AWS reported up to 1.5× performance per dollar](https://aws.amazon.com/solutions/case-studies/refactai-case-study/) against comparable GPU configurations.
- **AI agent infrastructure:** Led a five-engineer team redesigning the Flexus agent runtime around recoverable execution, shared state, permission-aware tools, and independently developed agents.

## Selected public code

- [**Refact**](https://github.com/smallcloudai/refact) — open-source AI coding assistant and agent platform.
- [**Refact for JetBrains**](https://github.com/smallcloudai/refact-intellij) — IDE integration and developer tooling.
- [**voice-agent**](https://github.com/reymondzzzz/voice-agent) — experimental LiveKit / Qwen Omni voice agents, background tasks, and specialist handoffs.
- [**dynamic-weights Conv2D for TensorRT**](https://github.com/reymondzzzz/dynamic_weights_conv2d_trt_plugin) — C++/CUDA plugin and ONNX export prototype.
- [**nn_plugins**](https://github.com/reymondzzzz/nn_plugins) — PyTorch and TensorRT custom-operator experiments, including DCNv2 adaptation.

**Tools:** Python · C++ · Rust · CUDA · Triton · PyTorch · vLLM · TensorRT · Kubernetes · NCCL · InfiniBand
