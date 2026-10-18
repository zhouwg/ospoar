# 开源项目观察与思考 (OSS Observations & Reflections)

> 本仓库是我个人对开源生态的观察、复盘与思考。

> This repository contains my personal observations, reviews and reflections on the open‑source ecosystem.

## 1.Project ggml-hexagon (originally by others, forked by me)

#### Overview

我的经历：自2024年3月起重度参与 [llama.cpp](https://github.com/ggml-org/llama.cpp) 项目，前后投入人民币2万元左右；截至2026年8月，我的3个GitHub账号均被该项目封禁。他们对美国大公司的“态度”我完全可以理解，我觉得最失望与最讽刺的是他们官网上如下一句话：

<mark>*"We built ggml in the spirit of play. Contributors are encouraged to try crazy ideas, build wild demos, and push the edge of what’s possible"*</mark>


My experience: Starting in March 2024, I took an active part in the [https://github.com/ggml-org/llama.cpp](https://github.com/ggml-org/llama.cpp) project. I spent about 20,000 RMB. By August 2026, all of my GitHub accounts (GitHub: [`zhouwg`](https://github.com/zhouwg) / [`jeffzhou‑zhouwg`](https://github.com/jeffzhou-zhouwg) / [`jeff‑zhouwg`](https://github.com/jeff-zhouwg) have been blocked by the upstream llama.cpp project. The first account was blocked on 2025‑07‑14(I made a mistake and I know the reason), and the other two were blocked recently(I have no idea why this happened). The thing I'm really disappointed about is the following statement on their official website:

<mark>*"We built ggml in the spirit of play. Contributors are encouraged to try crazy ideas, build wild demos, and push the edge of what’s possible"*</mark>

#### 文档 (Articles)

- [我对llama.cpp项目的观察与思考](https://github.com/zhouwg/ospoar/discussions/5)
- [My Observations and Reflections on the llama.cpp Project](https://github.com/zhouwg/ospoar/discussions/6)

## 2.Project Kan-Linux (founded and maintained by me)

#### Overview

Working on Kan-Linux from scratch has shifted my perspective on Linux distributions. so "Development Notes & Reflections on Kan-Linux" was born.

When adding Chinese input support on Oct 14 2026, I discovered T2 SDE. Having suffered through commercial projects built on [Yocto](https://www.yoctoproject.org/), I personally see it as another Yocto-like highly sophisticated and complex build system, which I don't wish to work with anymore. I greatly admire its maintainer’s over 20 years of work, yet it is striking to see it only has 741 GitHub stars (I added the 741st star), while Omarchy desktop shell reaches 40k+.

I previously only knew mainstream distros. This opened my eyes: hundreds of Linux distributions exist.

I adjusted Kan-Linux goals accordingly: **personal use first**, running my self-built OS on x86-64 PC and laptop. It is still published publicly, but the aarch64 port has been dropped to cut maintenance workload.

#### 文档 (Articles)

1. 看了t2sde Linux distro的感受（Thoughts on the T2 SDE Linux distro）, https://github.com/zhouwg/ospoar/discussions/8
2. 看了KaOS distro的感受（Thoughts on the KaOS distro）, https://github.com/zhouwg/ospoar/discussions/9




  
### 仓库定位(Role of the Repo)

本仓库聚焦客观事实记录、开源社区治理议题。

This repository focuses on documenting objective facts and open‑source community governance topics.

> ⚠️ 声明：
> - 所有记录基于我个人的视角与亲历事实，存在主观局限性。
> - 全部为个人观点。

> ⚠️ Statement:
> - All records are based on my personal perspective and first‑hand experience, and contain subjective limitations.
> - All content represents my personal views only.
