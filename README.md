<div align="center">

# 🔥 LLM Interview Hand-Coding

**大模型面试手撕代码宝典**

[![GitHub stars](https://img.shields.io/github/stars/your-username/llm-interview-coding?style=social)](https://github.com/your-username/llm-interview-coding)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

<p align="center">
  <strong>🎯 一站式 LLM 面试手撕代码准备 | 告别东翻西找 | 从原理到实现</strong>
</p>

<p align="center">
  <a href="#-快速开始">快速开始</a> •
  <a href="#-题目分类">题目分类</a> •
  <a href="#-高频题目">高频题目</a> •
  <a href="#-贡献指南">贡献指南</a>
</p>

---

**"面试官让你手撕 Multi-Head Attention，你还在紧张？"**

**"PPO、DPO、GRPO 的区别，你能写出来吗？"**

**"KV Cache 怎么实现？Flash Attention 的核心思想是什么？"**

这个项目帮你一次搞定所有 LLM 面试手撕代码！

</div>

---

## ✨ 项目特点

| 特点 | 描述 |
|:---:|:---|
| 🎯 **面试导向** | 专注 LLM 领域高频手撕题，按面试频率标注 |
| 📝 **详细注释** | 每行代码都有清晰注释，理解原理而非死记 |
| 🔥 **工业级实现** | 包含数值稳定性、边界处理等生产细节 |
| 🧠 **追问准备** | 每道题附带常见追问和深度扩展 |
| 📊 **复杂度分析** | 时间/空间复杂度 + 内存占用分析 |

---

## 📚 题目分类

### 核心模块

| 分类 | 题目数 | 难度 | 链接 |
|:---|:---:|:---:|:---:|
| 🧠 **Attention 机制** | 8+ | ⭐⭐⭐⭐ | [查看](docs/01-attention.md) |
| 📏 **归一化层** | 3+ | ⭐⭐ | [查看](docs/02-normalization.md) |
| 📍 **位置编码** | 4+ | ⭐⭐⭐ | [查看](docs/03-position-encoding.md) |
| 🎲 **采样策略** | 5+ | ⭐⭐⭐ | [查看](docs/04-sampling.md) |
| 📉 **损失函数** | 8+ | ⭐⭐⭐ | [查看](docs/05-loss-functions.md) |
| ⚡ **优化器** | 5+ | ⭐⭐⭐ | [查看](docs/06-optimizers.md) |
| 🎮 **强化学习** | 8+ | ⭐⭐⭐⭐⭐ | [查看](docs/07-reinforcement-learning.md) |
| 🚀 **高效训练** | 4+ | ⭐⭐⭐⭐ | [查看](docs/08-efficient-training.md) |
| ⚡ **推理优化** | 5+ | ⭐⭐⭐⭐ | [查看](docs/09-inference-optimization.md) |
| 🏗️ **Transformer 架构** | 5+ | ⭐⭐⭐ | [查看](docs/10-transformer-architecture.md) |

---

## 🔥 高频题目 Top 15

> 面试出现频率 90%+ 的必会题目

| 排名 | 题目 | 分类 | 难度 | 链接 |
|:---:|:---|:---|:---:|:---:|
| 1 | Multi-Head Attention | Attention | ⭐⭐⭐⭐ | [查看](docs/01-attention.md#multi-head-attention) |
| 2 | KV Cache | 推理优化 | ⭐⭐⭐⭐ | [查看](docs/09-inference-optimization.md#kv-cache) |
| 3 | RoPE 位置编码 | 位置编码 | ⭐⭐⭐⭐ | [查看](docs/03-position-encoding.md#rope) |
| 4 | Cross Entropy Loss | 损失函数 | ⭐⭐⭐ | [查看](docs/05-loss-functions.md#cross-entropy) |
| 5 | Adam 优化器 | 优化器 | ⭐⭐⭐ | [查看](docs/06-optimizers.md#adam) |
| 6 | Top-p Sampling | 采样策略 | ⭐⭐⭐ | [查看](docs/04-sampling.md#top-p) |
| 7 | LayerNorm / RMSNorm | 归一化 | ⭐⭐ | [查看](docs/02-normalization.md#rmsnorm) |
| 8 | PPO | 强化学习 | ⭐⭐⭐⭐⭐ | [查看](docs/07-reinforcement-learning.md#ppo) |
| 9 | DPO Loss | 强化学习 | ⭐⭐⭐⭐ | [查看](docs/07-reinforcement-learning.md#dpo) |
| 10 | GRPO | 强化学习 | ⭐⭐⭐⭐⭐ | [查看](docs/07-reinforcement-learning.md#grpo) |
| 11 | LoRA | 高效训练 | ⭐⭐⭐⭐ | [查看](docs/08-efficient-training.md#lora) |
| 12 | Beam Search | 采样策略 | ⭐⭐⭐ | [查看](docs/04-sampling.md#beam-search) |
| 13 | GQA / MQA | Attention | ⭐⭐⭐⭐ | [查看](docs/01-attention.md#gqa) |
| 14 | Causal Mask | Attention | ⭐⭐⭐ | [查看](docs/01-attention.md#causal-mask) |
| 15 | GAE | 强化学习 | ⭐⭐⭐⭐ | [查看](docs/07-reinforcement-learning.md#gae) |

---

## 🚀 快速开始

### 环境要求

```bash
Python >= 3.8
PyTorch >= 2.0
```

### 克隆项目

```bash
git clone https://github.com/your-username/llm-interview-coding.git
cd llm-interview-coding
```

### 运行示例

```python
# 快速验证 Multi-Head Attention 实现
python -c "
import torch
from code.attention import MultiHeadAttention

mha = MultiHeadAttention(d_model=512, num_heads=8)
x = torch.randn(2, 10, 512)
output, weights = mha(x, x, x)
print(f'Input: {x.shape} -> Output: {output.shape}')
print('✅ MHA 实现正确!')
"
```

---

## 📖 如何使用本项目

### 1️⃣ 面试前突击（1-2天）

```
推荐路线：高频 Top 15 → Attention → 损失函数 → 采样策略
```

### 2️⃣ 系统学习（1周）

```
推荐路线：按分类顺序学习，每个分类先看原理再看代码
```

### 3️⃣ 查漏补缺

```
根据目标公司的技术栈选择性学习：
- 大厂基础岗：Attention + 损失函数 + 优化器
- RLHF 方向：强化学习全部 + 损失函数
- 推理优化方向：推理优化 + Attention + 高效训练
```

---

## 📊 题目难度说明

| 难度 | 说明 | 建议准备时间 |
|:---:|:---|:---:|
| ⭐ | 基础概念，必须秒答 | 10 分钟 |
| ⭐⭐ | 常规实现，需要熟练 | 30 分钟 |
| ⭐⭐⭐ | 有一定技巧，需要理解原理 | 1 小时 |
| ⭐⭐⭐⭐ | 复杂实现，需要深入理解 | 2 小时 |
| ⭐⭐⭐⭐⭐ | 综合性强，需要系统掌握 | 3+ 小时 |

---

## 🤝 贡献指南

欢迎贡献新题目、修复错误、改进文档！

### 贡献方式

1. **Fork** 本仓库
2. 创建你的特性分支 (`git checkout -b feature/new-algorithm`)
3. 提交你的更改 (`git commit -m 'Add: XXX algorithm'`)
4. 推送到分支 (`git push origin feature/new-algorithm`)
5. 提交 **Pull Request**

### 题目格式规范

每道题目应包含：

```markdown
## 题目名称

### 🎯 核心思想
一句话说明这个算法解决什么问题

### 📝 实现代码
带详细注释的代码

### 🔍 复杂度分析
时间/空间复杂度

### 💡 面试追问
常见的追问问题和答案

### 🔗 相关题目
关联的其他题目
```

---

## 📜 参考资源

- [Attention Is All You Need](https://arxiv.org/abs/1706.03762)
- [RoFormer: Enhanced Transformer with Rotary Position Embedding](https://arxiv.org/abs/2104.09864)
- [Training language models to follow instructions with human feedback](https://arxiv.org/abs/2203.02155)
- [Direct Preference Optimization](https://arxiv.org/abs/2305.18290)
- [DeepSeekMath: Pushing the Limits of Mathematical Reasoning](https://arxiv.org/abs/2402.03300)

---

## ⭐ Star History

如果这个项目对你有帮助，请给一个 Star ⭐ 支持一下！

[![Star History Chart](https://api.star-history.com/svg?repos=your-username/llm-interview-coding&type=Date)](https://star-history.com/#your-username/llm-interview-coding&Date)

---

## 📄 License

MIT License - 随意使用，欢迎标注来源

---

<div align="center">

**Made with ❤️ for LLM Interview Preparation**

如果觉得有用，请点个 ⭐ Star 支持一下！

[Report Bug](https://github.com/your-username/llm-interview-coding/issues) · [Request Feature](https://github.com/your-username/llm-interview-coding/issues)

</div>
