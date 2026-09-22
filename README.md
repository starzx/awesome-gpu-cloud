# Awesome GPU Cloud ☁️🖥️

> A curated list of GPU cloud computing platforms for AI/ML workloads. Compare prices, specs, and features at [TransAtlas](https://compare.transatlas.co).

[![Price Comparison](https://img.shields.io/badge/Compare%20Prices-Live%20Data-brightgreen)](https://compare.transatlas.co/gpu-list)
[![Cost Calculator](https://img.shields.io/badge/Cost%20Calculator-Free%20Tool-blue)](https://compare.transatlas.co/tools/calculator)

## Contents

- [Major Cloud Providers](#major-cloud-providers)
- [Dedicated GPU Cloud](#dedicated-gpu-cloud)
- [Community Marketplaces](#community-marketplaces)
- [Regional / Chinese Platforms](#regional--chinese-platforms)
- [Edge & Inference Specialists](#edge--inference-specialists)
- [Bare Metal Providers](#bare-metal-providers)
- [Comparison Tools](#comparison-tools)
- [Benchmark Resources](#benchmark-resources)
- [Contributing](#contributing)

---

## Major Cloud Providers

| Provider | GPU Types | Regions | Review |
|----------|-----------|---------|--------|
| **AWS** | P4, P5, G5, G6, P5e | 30+ regions | [TransAtlas Review](https://compare.transatlas.co/providers/aws) |
| **Google Cloud (GCP)** | A100, H100, T4, L4, V100 | 35+ regions | [TransAtlas Review](https://compare.transatlas.co/providers/gcp) |
| **Microsoft Azure** | A100, H100, A10, V100 | 60+ regions | [TransAtlas Review](https://compare.transatlas.co/providers/azure) |
| **Oracle Cloud (OCI)** | A10, A100, H100 | 40+ regions | [TransAtlas Review](https://compare.transatlas.co/providers/oci) |

**Key considerations:**
- AWS and Azure offer the broadest GPU selection but at premium pricing
- GCP excels in TPU integration and custom AI accelerators
- OCI often has the most competitive pricing for A100/H100

---

## Dedicated GPU Cloud

| Provider | GPU Types | Best For | Review |
|----------|-----------|----------|--------|
| **[RunPod](https://runpod.io?ref=z50tdr4m)** | RTX 4090, A100, H100, H200 | On-demand GPU, serverless endpoints | [TransAtlas Review](https://compare.transatlas.co/providers/runpod) |
| **[Vast.ai](https://cloud.vast.ai/?ref_id=446966)** | RTX 3090-5090, A100, H100 | Budget-friendly community marketplace | [TransAtlas Review](https://compare.transatlas.co/providers/vastai) |
| **Lambda Cloud** | A100, H100, GH200 | On-demand and reserved instances | [TransAtlas Review](https://compare.transatlas.co/providers/lambdalabs) |
| **[Voltage Park](https://compare.transatlas.co/providers/voltagepark)** | A100-80GB, H100 | Long-term rentals, bare metal | [TransAtlas Review](https://compare.transatlas.co/providers/voltagepark) |
| **DataCrunch** | H100, H200, L40S | European GPU cloud, low latency | [TransAtlas Review](https://compare.transatlas.co/providers/datacrunch) |
| **Nebius** | H100, H200, L40S | AI cloud infrastructure | [TransAtlas Review](https://compare.transatlas.co/providers/nebius) |
| **Vultr** | A100, L40, A40 | Cloud GPU with global reach | [TransAtlas Review](https://compare.transatlas.co/providers/vultr) |

---

## Community Marketplaces

| Provider | Model | GPU Types | Review |
|----------|-------|-----------|--------|
| **Vast.ai** | Peer-to-peer marketplace | RTX 3090-5090, A100, H100 | [Review](https://compare.transatlas.co/providers/vastai) |
| **RunPod** | Serverless + on-demand | A100, H100, H200, RTX 4090 | [Review](https://compare.transatlas.co/providers/runpod) |
| **TensorDock** | Multi-cloud marketplace | A100, H100, RTX 4090 | [Review](https://compare.transatlas.co/providers/tensordock) |
| **CloudRift** | Community marketplace | A100, H100, RTX 4090 | [Review](https://compare.transatlas.co/providers/cloudrift) |
| **Shadeform** | Multi-cloud GPU | A100, H100, L40S | [Review](https://compare.transatlas.co/providers/shadeform) |

---

## Regional / Chinese Platforms

| Provider | GPU Types | Region | Review |
|----------|-----------|--------|--------|
| **AutoDL** | RTX 4090, A100, H100 | China | [TransAtlas Review](https://compare.transatlas.co/providers/autodl) |
| **UCloud** | A100, H100 | China | [TransAtlas Review](https://compare.transatlas.co/providers/ucloud) |
| **Verda** | A100, H100 | Korea/Asia | [TransAtlas Review](https://compare.transatlas.co/providers/verda) |

---

## Edge & Inference Specialists

| Provider | Specialization | Best For |
|----------|----------------|----------|
| **AWS Inferentia** | Custom ASIC (Inferentia2) | High-throughput inference |
| **GCP TPU** | Tensor Processing Units | JAX/PyTorch training |
| **Azure ND H100** | InfiniBand clusters | Large-scale distributed training |

---

## Bare Metal Providers

| Provider | GPU Types | Min. Rental Period | Review |
|----------|-----------|---------------------|--------|
| **Voltage Park** | A100-80GB, H100 | Monthly | [Review](https://compare.transatlas.co/providers/voltagepark) |
| **Lambda Cloud** | A100, H100, GH200 | Hourly + Reserved | [Review](https://compare.transatlas.co/providers/lambdalabs) |
| **CoreWeave** | A100, H100, H200 | Hourly + Reserved | — |

---

## Comparison Tools

- **[TransAtlas GPU Price Comparison](https://compare.transatlas.co/gpu-list)** — Real-time price comparison across 15+ platforms, updated every 4 hours
- **[TransAtlas Cost Calculator](https://compare.transatlas.co/tools/calculator)** — Calculate total cost for AI workloads across platforms
- **[TransAtlas GPU Detail Pages](https://compare.transatlas.co/gpu-detail/RTX%204090)** — Per-GPU pricing, specs, and provider comparison
- **[TransAtlas Provider Reviews](https://compare.transatlas.co/providers)** — In-depth reviews of each GPU cloud provider

---

## Benchmark Resources

- **[MLPerf](https://mlcommons.org/benchmarks/)** — Industry-standard ML benchmark suite
- **[NVIDIA GPU Specs](https://www.nvidia.com/en-us/data-center/)** — Official GPU specifications
- **[TransAtlas Price Data API](https://compare.transatlas.co/api-docs)** — Free daily GPU price snapshot API

---

## Quick Start: Finding the Right GPU Cloud

### 1. Define your workload
- **Training**: Need high VRAM + high interconnect bandwidth (H100 SXM5, A100-80GB)
- **Inference**: Optimize for cost-per-token (L4, A10, T4 for small models; H100 for large)
- **Fine-tuning**: Balance VRAM and cost (A100-40GB, RTX 4090 for smaller models)

### 2. Compare prices
Visit [TransAtlas GPU List](https://compare.transatlas.co/gpu-list) to see real-time prices across all platforms.

### 3. Calculate total cost
Use the [Cost Calculator](https://compare.transatlas.co/tools/calculator) to estimate total cost for your specific workload.

### 4. Read provider reviews
Check [Provider Reviews](https://compare.transatlas.co/providers) for in-depth analysis of each platform.

---

## GPU Quick Reference

| GPU | VRAM | Best For | Min. Price/h |
|-----|------|----------|---------------|
| NVIDIA H100 SXM5 | 80GB HBM3 | Large-scale training | [Check Live Price](https://compare.transatlas.co/gpu-detail/H100) |
| NVIDIA H200 | 141GB HBM3e | Largest models, RAG | [Check Live Price](https://compare.transatlas.co/gpu-detail/H200) |
| NVIDIA A100-80GB | 80GB HBM2e | Training & inference | [Check Live Price](https://compare.transatlas.co/gpu-detail/A100-80GB) |
| NVIDIA A100-40GB | 40GB HBM2e | Cost-effective training | [Check Live Price](https://compare.transatlas.co/gpu-detail/A100) |
| NVIDIA L40S | 48GB GDDR6 | Inference, rendering | [Check Live Price](https://compare.transatlas.co/gpu-detail/L40S) |
| NVIDIA RTX 4090 | 24GB GDDR6X | Budget training & inference | [Check Live Price](https://compare.transatlas.co/gpu-detail/RTX%204090) |
| NVIDIA RTX 5090 | 32GB GDDR7 | Next-gen consumer GPU | [Check Live Price](https://compare.transatlas.co/gpu-detail/RTX%205090) |
| NVIDIA A6000 | 48GB GDDR6 | Pro workloads | [Check Live Price](https://compare.transatlas.co/gpu-detail/A6000) |
| NVIDIA T4 | 16GB GDDR6 | Light inference | [Check Live Price](https://compare.transatlas.co/gpu-detail/T4) |
| NVIDIA L4 | 24GB GDDR6 | Cost-effective inference | [Check Live Price](https://compare.transatlas.co/gpu-detail/L4) |

---

## Contributing

Contributions are welcome! To add a new GPU cloud provider or update existing information:

1. Fork this repository
2. Add or update the provider entry in the appropriate section
3. Ensure the TransAtlas review link is included
4. Submit a Pull Request

### Guidelines

- Only list providers that offer GPU instances for rent (not just managed ML services)
- Include GPU types, regions, and a brief description
- Link to the TransAtlas review page if available
- Keep descriptions concise and factual

## License

This awesome list is maintained by [TransAtlas](https://compare.transatlas.co) — the intelligent GPU price comparison platform. Price data is collected automatically every 4 hours via [GitHub Actions](https://github.com/starzx/transatlas-compare).

---

<p align="center">
  <strong>Compare GPU prices in real-time at <a href="https://compare.transatlas.co">compare.transatlas.co</a></strong>
</p>
