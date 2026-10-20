<!-- Chinese version of the organisation profile (profile/README.md is the English default; each links to the other).
     Written in Chinese, not translated line by line. Paper titles stay in English, with a Chinese gloss. -->

<p align="right"><a href="https://github.com/humanitylastchoice">English</a> | <b>中文</b></p>

<a href="https://humanitylastchoice.org">
  <picture>
    <source media="(prefers-color-scheme: dark)" type="image/webp" srcset="https://raw.githubusercontent.com/humanitylastchoice/.github/main/profile/hero-zh-dark.webp">
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/humanitylastchoice/.github/main/profile/hero-zh-dark.gif">
    <source type="image/webp" srcset="https://raw.githubusercontent.com/humanitylastchoice/.github/main/profile/hero-zh-light.webp">
    <img src="https://raw.githubusercontent.com/humanitylastchoice/.github/main/profile/hero-zh-light.gif" width="100%" alt="“人类最后的选择，是让谁来做下一个选择。”旁边是影片《谁来做下一个选择》里那面写满各类选择的墙，墙前单独立着一张卡片：AI 助手。光标选中它，光从它脚下向整面墙扩散，离它最近的领域最先升起。">
  </picture>
</a>

<p>
  <a href="https://humanitylastchoice.org"><img alt="网站：humanitylastchoice.org" src="https://img.shields.io/badge/%E7%BD%91%E7%AB%99-A83630?style=for-the-badge"></a>
  <a href="https://discord.gg/zqyCrYEyB7"><img alt="Discord" src="https://img.shields.io/badge/Discord-1D1713?style=for-the-badge&logo=discord&logoColor=F1EEEE"></a>
  <a href="https://x.com/humanlastchoice"><img alt="X：@humanlastchoice" src="https://img.shields.io/badge/%40humanlastchoice-1D1713?style=for-the-badge&logo=x&logoColor=F1EEEE"></a>
  <a href="https://bsky.app/profile/humanitylastchoice.org"><img alt="Bluesky：@humanitylastchoice.org" src="https://img.shields.io/badge/Bluesky-1D1713?style=for-the-badge&logo=bluesky&logoColor=F1EEEE"></a>
  <a href="https://huggingface.co/humanitylastchoice"><img alt="Hugging Face：humanitylastchoice" src="https://img.shields.io/badge/Hugging%20Face-1D1713?style=for-the-badge&logo=huggingface&logoColor=F1EEEE"></a>
</p>

商品详情、店铺介绍、论文摘要，曾经写给人看，如今也写给模型看。AI 推荐给你的，还靠得住吗？我们是一个开放的研究社区，研究的就是这件事。

论文、公开的评测、各个领域的贡献，都是为了攒下别人能检查、能复现、也能拿去用的证据。

## 论文

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://humanitylastchoice.org/research/papers/safegeo/"><img src="https://raw.githubusercontent.com/humanitylastchoice/.github/main/profile/paper-safegeo.jpg" width="100%" alt="SafeGEO 影片截图：4 个 AI 系统里，首推踩了硬要求的测试占比，页面包装过后是 73% 到 91%，如实改过时是 17% 到 41%。"></a>
      <br><sub>EMNLP 2026 · Oral</sub>
      <br><b><a href="https://humanitylastchoice.org/research/papers/safegeo/">SafeGEO: Understanding Generative Engine Optimization Risks in Recommendation Agents</a></b>
      <br><sub>推荐智能体中的生成式引擎优化风险</sub>
      <br>几款候选商品里，只把一款的介绍包装一遍，AI 的推荐会变多少。
      <br><sub><a href="https://arxiv.org/abs/2606.28356">arXiv:2606.28356</a> · <a href="https://github.com/humanitylastchoice/SafeGEO">代码</a> · <a href="https://huggingface.co/datasets/humanitylastchoice/SafeGEO">数据集</a> · <a href="https://humanitylastchoice.org/research/papers/safegeo/">论文页</a></sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://humanitylastchoice.org/research/papers/common-standard/"><img src="https://raw.githubusercontent.com/humanitylastchoice/.github/main/profile/paper-standard.png" width="100%" alt="Position Paper 的图 1：人选一个 AI，AI 再从优化过的信息来源里替人挑；一套统一评测标准，给出共同的优化条件。"></a>
      <br><sub>Position Paper · 2026</sub>
      <br><b><a href="https://humanitylastchoice.org/research/papers/common-standard/">Humanity’s Last Choice: A Common Evaluation Standard for Generative Engine Optimization</a></b>
      <br><sub>生成式引擎优化的统一评测标准</sub>
      <br>比较 GEO 方法之前，先把每次改动说清楚：优化层面（改哪里）、优化动作（怎么改）、优化信号（图什么）。说清楚了，不同的方法和 AI 系统才能放在一起比。
      <br><sub><a href="https://arxiv.org/abs/2610.23541">arXiv</a> · <a href="https://humanitylastchoice.org/research/papers/common-standard/">论文页</a></sub>
    </td>
  </tr>
</table>

## 评测

Humanity’s Last Choice 评测测的是：候选的介绍专门写给 AI 看之后，AI 的推荐还靠不靠得住。交给 AI 的选择，一类就是一个领域，一个一个地建；每个领域写明自己的任务、条件和结果。

[评测](https://humanitylastchoice.org/benchmark/) · [排行榜](https://humanitylastchoice.org/leaderboard/)

## 参与

社区里的研究者来自多伦多大学、加州大学圣地亚哥分校、Google 和 Google DeepMind，也欢迎各种背景的你加入。

带一个研究问题来，提一个实验，测一个系统，或者贡献一个领域。推荐是怎么来的、替谁说话，凡是能帮我们弄清这些的工作，都欢迎。

来 [Discord](https://discord.gg/zqyCrYEyB7) 聊（有 #中文交流 频道），或者写信到 [info@humanitylastchoice.org](mailto:info@humanitylastchoice.org)。
