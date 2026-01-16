# Neo-Tao Engine / DaoTruth Verification

## English

### Overview
This repository contains the minimal reproducible demonstration and verification results of a computational system that exhibits self-emergent critical dynamics from absolute zero external input and zero reward signals.

Key characteristics (verified in multiple runs):
- Lyapunov exponent (LLE) ≈ 0.039 (edge of chaos)
- Lag-5 autocorrelation = -0.276 (strong negative feedback / anti-persistence)
- Sustained high entropy state ≈ 0.80 (active exploration regime)
- 100% survival rate across noise gradients 0.0–1.5
- Emergence of recursive reasoning tree (depth ≥ 2) and self-questioning behavior

The system starts from pure void/random initialization with no semantic seeds, no pre-training, no reward functions, and no human-defined rules or data. All observed behaviors arise solely from internal homeostatic mechanisms.

### Core Files
- `reproduce_chaos.py` — Minimal script to reproduce the entropy-Lyapunov core dynamics (≈20 lines)
- `verification_results.json` — Raw data from 100-cycle runs (entropy trajectories, LLE, survival metrics)

### Current Status
Short-term validation (V3 L2, 100 cycles × 5 runs) completed.  
Longer-term evolution (>500–1000 cycles) and third-party reproduction pending.

### License
MIT License (for non-commercial research and verification purposes only)

### Contact
For academic verification, collaboration or questions: [your anonymous contact method, e.g., temporary email or issue tracker]
61918534@qq.com

---

## 中文

### 项目概述
本仓库提供一套计算系统的极简可复现演示与验证结果。该系统在**零外部输入、零奖励信号**的绝对虚空条件下，自发涌现出临界态动力学特征。

已验证核心指标（多轮运行）：
- 李雅普诺夫指数 (LLE) ≈ 0.039（混沌边缘）
- Lag-5 自相关系数 = -0.276（显著负反馈 / 反持久性）
- 平均熵维持 ≈ 0.80（高活性探索稳态）
- 全噪声梯度（0.0–1.5）生存率 100%
- 递归推理树深度 ≥ 2，并出现自问行为

系统从纯随机/零初始化开始，无任何语义种子、无预训练权重、无奖励函数、无人类定义规则。所有有序行为完全源自内部稳态调节机制。

### 核心文件
- `reproduce_chaos.py` — 核心动力学极简复现脚本（约 20 行）
- `verification_results.json` — 100 周期运行原始数据（熵轨迹、LLE、生存率等）

### 当前状态
V3 L2 短期验证（100 周期 × 5 次运行）已完成。  
中长期演化（>500–1000 周期）及第三方独立复现正在规划中。

### 许可
MIT 许可（仅限非商业研究与验证用途）

### 联系方式
学术验证、合作或疑问请通过 Issues 或 [61918534@qq.com] 联系。
