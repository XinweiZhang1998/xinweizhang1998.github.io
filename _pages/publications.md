---
permalink: /publications/
title: "Publications"
excerpt: ""
author_profile: true
---

<style>
  .publication-cards > ul {
    display: grid;
    gap: 1rem;
    margin: 1rem 0 2.5rem;
    padding: 0;
    list-style: none;
  }

  .publication-cards > ul > li {
    display: flex;
    flex-direction: column;
    justify-content: center;
    min-height: 9rem;
    margin: 0;
    padding: 1.4rem 1.65rem;
    overflow: hidden;
    border: 1px solid #e6e8eb;
    border-radius: 1rem;
    background: #fff;
    box-shadow: 0 0.35rem 1.2rem rgba(31, 41, 55, 0.06);
    line-height: 1.55;
    transition: transform 0.2s ease, box-shadow 0.2s ease;
  }

  .publication-cards > ul > li:hover {
    transform: translateY(-2px);
    box-shadow: 0 0.7rem 1.8rem rgba(31, 41, 55, 0.1);
  }

  .publication-cards > ul > li > p {
    margin: 0;
  }

  .publication-cards > ul > li > p > strong:first-child,
  .publication-cards > ul > li > p > strong:first-child a {
    color: #343a40;
    font-size: 1rem;
    line-height: 1.4;
  }

  .publication-cards > ul > li > p > strong:first-child ~ strong,
  .publication-cards > ul > li > p > strong:first-child ~ a > strong {
    color: #343a40;
    font-size: 1.16rem;
    font-weight: 700;
    line-height: 1.4;
  }

  .publication-authors {
    display: inline-block;
    margin-top: 0.6rem;
    color: #68717a;
    font-size: 0.94rem;
  }

  .publication-venue {
    display: inline-block;
    margin-top: 0.35rem;
    color: #68717a;
    font-size: 0.94rem;
    font-weight: 400;
  }

  .publication-cards .pub-links {
    display: inline-flex;
    gap: 0.45rem;
    margin-left: 0.55rem;
    vertical-align: middle;
  }

  .publication-cards img[src*="shields.io"] {
    margin: 0 0.35rem 0 0.2rem;
    vertical-align: text-bottom;
  }

  @media (max-width: 600px) {
    .publication-cards > ul > li {
      min-height: 0;
      padding: 1.2rem 1.25rem;
      font-size: 0.92rem;
    }
  }
</style>

# 📖 Publications
(✉️ is the corresponding author)

## Preprints

<div class="publication-cards" markdown="1">

- **[Preprint]** **[IDDM: Identity-Decoupled Personalized Diffusion Models with a Tunable Privacy-Utility Trade-off](https://arxiv.org/abs/2604.00903)** <br />
<span class="publication-authors" markdown="span">Linyan Dai, **<ins>Xinwei Zhang</ins>**, Haoyang Li, Qingqing Ye, Haibo Hu</span><br />
<span class="publication-venue" markdown="span">_Arxiv_, 2026.</span><span class="pub-links"><a class="pub-icon pub-icon--pdf" href="https://xinweizhang1998.github.io/_pages/File/Arxiv26_IDDM.pdf" target="_blank" rel="noopener" aria-label="PDF" title="PDF"><i class="fas fa-file-pdf" aria-hidden="true"></i></a></span>

- **[Preprint]** **[Grounding-Driven Attack: Improving Encoder-based Adversarial Transferability against Large Vision-Language Models](https://arxiv.org/abs/2602.09431)** <br />
<span class="publication-authors" markdown="span">**<ins>Xinwei Zhang</ins>**, Li Bai, Tianwei Zhang, Youqian Zhang, Qingqing Ye, Yingnan Zhao, Ruochen Du, Haibo Hu</span><br />
<span class="publication-venue" markdown="span">_Arxiv_, 2026.</span><span class="pub-links"><a class="pub-icon pub-icon--pdf" href="https://xinweizhang1998.github.io/_pages/File/Arxiv26_GDA.pdf" target="_blank" rel="noopener" aria-label="PDF" title="PDF"><i class="fas fa-file-pdf" aria-hidden="true"></i></a></span>

</div>

## 2026

<div class="publication-cards" markdown="1">

- **[ICML'26]** | ![CCF-A](https://img.shields.io/badge/CCF-A-red) **[On the Adversarial Robustness of Large Vision-Language Models under Visual Token Compression](https://openreview.net/forum?id=q5sBPXOuHC)** <br />
<span class="publication-authors" markdown="span">**<ins>Xinwei Zhang</ins>**, Hangcheng Liu, Li Bai✉️, Hao Wang, Qingqing Ye, Tianwei Zhang, Haibo Hu</span><br />
<span class="publication-venue" markdown="span">_In Proc. of International Conference on Machine Learning_, 2026.</span><span class="pub-links"><a class="pub-icon pub-icon--code" href="https://github.com/XinweiZhang1998/CAGE" target="_blank" rel="noopener" aria-label="Code" title="Code"><i class="fab fa-github" aria-hidden="true"></i></a><a class="pub-icon pub-icon--pdf" href="https://xinweizhang1998.github.io/_pages/File/ICML_26_CAGE.pdf" target="_blank" rel="noopener" aria-label="PDF" title="PDF"><i class="fas fa-file-pdf" aria-hidden="true"></i></a></span>

- **[USENIX SEC'26]** | ![CCF-A](https://img.shields.io/badge/CCF-A-red) **[United We Defend: Collaborative Membership Inference Defenses in Federated Learning](https://www.usenix.org/conference/usenixsecurity26/presentation/bai)** <br />
<span class="publication-authors" markdown="span">Li Bai, Junxu Liu, Sen Zhang, **<ins>Xinwei Zhang</ins>**, Qingqing Ye, Haibo Hu✉️</span><br />
<span class="publication-venue" markdown="span">_In Proc. of USENIX Security Symposium_, 2026.</span><span class="pub-links"><a class="pub-icon pub-icon--code" href="https://github.com/BaiLibl/CoFedMID" target="_blank" rel="noopener" aria-label="Code" title="Code"><i class="fab fa-github" aria-hidden="true"></i></a><a class="pub-icon pub-icon--pdf" href="https://xinweizhang1998.github.io/_pages/File/Sec26a-CoFedMID.pdf" target="_blank" rel="noopener" aria-label="PDF" title="PDF"><i class="fas fa-file-pdf" aria-hidden="true"></i></a></span>

- **[TDSC'26]** | ![CCF-A](https://img.shields.io/badge/CCF-A-red) **[A Deep Dynamic Graph Generative Framework for Blockchain Phishing Detection](https://ieeexplore.ieee.org/document/11435482)** <br />
<span class="publication-authors" markdown="span">Siyi Xiao, Lejun Zhang✉️, **<ins>Xinwei Zhang</ins>**, Sen Zhang, Shen Su, Jing Qiu, Ran Guo, Haibo Hu</span><br />
<span class="publication-venue" markdown="span">_IEEE Transactions on Dependable and Secure Computing (TDSC)_, 2026.</span><span class="pub-links"><a class="pub-icon pub-icon--pdf" href="https://xinweizhang1998.github.io/_pages/File/TDSC26_GraphFlowGen.pdf" target="_blank" rel="noopener" aria-label="PDF" title="PDF"><i class="fas fa-file-pdf" aria-hidden="true"></i></a></span>

</div>

## 2025

<div class="publication-cards" markdown="1">

- **[WWW'25]** | ![CCF-A](https://img.shields.io/badge/CCF-A-red) [**MER-Inspector: Assessing Model Extraction Risks from An Attack-Agnostic Perspective**](https://dl.acm.org/doi/abs/10.1145/3696410.3714894) <br />
<span class="publication-authors" markdown="span">**<ins>Xinwei Zhang</ins>**, Haibo Hu✉️, Qingqing Ye, Li Bai, Huadi Zheng</span><br />
<span class="publication-venue" markdown="span">_In Proc. of The ACM Web Conference (WWW)_, 2025.</span><span class="pub-links"><a class="pub-icon pub-icon--code" href="https://github.com/XinweiZhang1998/MER_Inspector" target="_blank" rel="noopener" aria-label="Code" title="Code"><i class="fab fa-github" aria-hidden="true"></i></a><a class="pub-icon pub-icon--pdf" href="https://xinweizhang1998.github.io/_pages/File/WWW25_MER_Inspector.pdf" target="_blank" rel="noopener" aria-label="PDF" title="PDF"><i class="fas fa-file-pdf" aria-hidden="true"></i></a></span>

- **[NeurIPS'25]** | ![CCF-A](https://img.shields.io/badge/CCF-A-red) [**Toward Efficient Inference Attacks: Shadow Model Sharing via Mixture-of-Experts**](https://openreview.net/forum?id=bSs0d6NLiw&referrer=%5Bthe%20profile%20of%20Xinwei%20Zhang%5D) <br />
<span class="publication-authors" markdown="span">Li Bai, Qingqing Ye, **<ins>Xinwei Zhang</ins>**, Sen Zhang, Zi Liang, Jianliang Xu, Haibo Hu✉️</span><br />
<span class="publication-venue" markdown="span">_In Proc. Neural Information Processing Systems (NeurIPS)_, December 2025.</span><span class="pub-links"><a class="pub-icon pub-icon--code" href="https://github.com/BaiLibl/ShadowPool" target="_blank" rel="noopener" aria-label="Code" title="Code"><i class="fab fa-github" aria-hidden="true"></i></a><a class="pub-icon pub-icon--pdf" href="https://xinweizhang1998.github.io/_pages/File/NIPS25_SHAPOOL.pdf" target="_blank" rel="noopener" aria-label="PDF" title="PDF"><i class="fas fa-file-pdf" aria-hidden="true"></i></a></span>

- **[TIFS'25]** | ![CCF-A](https://img.shields.io/badge/CCF-A-red) [**ProVFL: Property Inference Attacks against Vertical Federated Learning**](https://ieeexplore.ieee.org/document/11045555) <br />
<span class="publication-authors" markdown="span">Li Bai, **<ins>Xinwei Zhang</ins>**, Sen Zhang, Qingqing Ye, Haibo Hu✉️</span><br />
<span class="publication-venue" markdown="span">_IEEE Transactions on Information Forensics and Security (TIFS)_, vol. 20, pp. 6529–6543, 2025.</span><span class="pub-links"><a class="pub-icon pub-icon--code" href="https://github.com/BaiLibl/ProVFL" target="_blank" rel="noopener" aria-label="Code" title="Code"><i class="fab fa-github" aria-hidden="true"></i></a><a class="pub-icon pub-icon--pdf" href="https://xinweizhang1998.github.io/_pages/File/TIFS25_ProVFL.pdf" target="_blank" rel="noopener" aria-label="PDF" title="PDF"><i class="fas fa-file-pdf" aria-hidden="true"></i></a></span>

</div>

## 2024 and Before

<div class="publication-cards" markdown="1">

- **[TVT'24]** | ![JCR-Q1](https://img.shields.io/badge/JCR-Q1-red) [**Enabling Deep Learning-based Physical-layer Secret Key Generation for FDD-OFDM Systems in Multi-Environments**](https://ieeexplore.ieee.org/document/10440494)<br />
<span class="publication-authors" markdown="span">**<ins>Xinwei Zhang</ins>**, Guyue Li✉️, Junqing Zhang, Linning Peng, Aiqun Hu, Xianbin Wang</span><br />
<span class="publication-venue" markdown="span">_IEEE Transactions on Vehicular Technology (TVT)_, vol. 73, no. 7, pp. 10135–10149, July 2024.</span><span class="pub-links"><a class="pub-icon pub-icon--pdf" href="https://xinweizhang1998.github.io/_pages/File/TVT24_MultiEnvSKG.pdf" target="_blank" rel="noopener" aria-label="PDF" title="PDF"><i class="fas fa-file-pdf" aria-hidden="true"></i></a></span>

- **[ICC'24]** | ![CCF-C](https://img.shields.io/badge/CCF-C-blue) [**A Secure and Reliable Blockchain-based Audit Log System**](https://ieeexplore.ieee.org/document/10623012) <br />
<span class="publication-authors" markdown="span">Zhonghao Liu, **<ins>Xinwei Zhang</ins>**, Guyue Li, Helei Cui, Jiaheng Wang, Bin Xiao✉️</span><br />
<span class="publication-venue" markdown="span">_In Proc. IEEE International Conference on Communications (ICC)_, 2024.</span>

- **[ICC'23]** | ![CCF-C](https://img.shields.io/badge/CCF-C-blue) [**DBE-voting: A Privacy-preserving and Auditable Blockchain-based E-voting System**](https://ieeexplore.ieee.org/document/10279692)  <br />
<span class="publication-authors" markdown="span">Zhonghao Liu, **<ins>Xinwei Zhang</ins>**, Laphou Lao, Guyue Li, Bin Xiao✉️</span><br />
<span class="publication-venue" markdown="span">_In Proc. IEEE International Conference on Communications (ICC)_, 2023.</span><span class="pub-links"><a class="pub-icon pub-icon--pdf" href="https://xinweizhang1998.github.io/_pages/File/2023-ICC.pdf" target="_blank" rel="noopener" aria-label="PDF" title="PDF"><i class="fas fa-file-pdf" aria-hidden="true"></i></a></span>

- **[IoT-J'22]** | ![JCR-Q1](https://img.shields.io/badge/JCR-Q1-red) [**Deep Learning-based Physical-Layer Secret Key Generation for FDD Systems**](https://ieeexplore.ieee.org/document/9526766)  <br />
<span class="publication-authors" markdown="span">**<ins>Xinwei Zhang</ins>**, Guyue Li✉️, Junqing Zhang, Aiqun Hu, Zongyue Hou, Bin Xiao</span><br />
<span class="publication-venue" markdown="span">_IEEE Internet of Things Journal (IoT-J)_, vol. 9, no. 8, pp. 6081–6094, April 2022.</span><span class="pub-links"><a class="pub-icon pub-icon--code" href="https://github.com/XinweiZhang1998/Code-of-KGNet" target="_blank" rel="noopener" aria-label="Code" title="Code"><i class="fab fa-github" aria-hidden="true"></i></a><a class="pub-icon pub-icon--pdf" href="https://xinweizhang1998.github.io/_pages/File/IoTJ22_KGNet.pdf" target="_blank" rel="noopener" aria-label="PDF" title="PDF"><i class="fas fa-file-pdf" aria-hidden="true"></i></a></span>

- **[VTC'21]** [**Secret Key Generation for FDD Systems Based on Complex-Valued Neural Network**](https://ieeexplore.ieee.org/document/9625252)  <br />
<span class="publication-authors" markdown="span">**<ins>Xinwei Zhang</ins>**, Guyue Li✉️, Zongyue Hou, Aiqun Hu</span><br />
<span class="publication-venue" markdown="span">_In Proc. 2021 IEEE 94th Vehicular Technology Conference (VTC)_, 2021.</span>
  
- **[INFOCOM-W'21]** | ![CCF-A Workshop](https://img.shields.io/badge/CCF--A-Workshop-red) [**Secret Key Generation Scheme Based on Generative Adversarial Networks in FDD Systems**](https://ieeexplore.ieee.org/document/9484457)  <br />
<span class="publication-authors" markdown="span">Zongyue Hou, **<ins>Xinwei Zhang</ins>**✉️</span><br />
<span class="publication-venue" markdown="span">_In Proc. IEEE Conference on Computer Communications Workshops (INFOCOM WKSHPS)_, 2021.</span>

</div>

## Other Publications

<div class="publication-cards" markdown="1">

- **[China Patent] 一种基于深度学习的频分双工系统密钥生成方法** <br />
<span class="publication-authors" markdown="span">李古月；**<ins>张鑫伟</ins>**；侯宗越；王星宇</span><br />
<span class="publication-venue">已授权，2022/11/18，CN112906035B.</span>

</div>
