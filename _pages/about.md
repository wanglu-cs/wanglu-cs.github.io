---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am Lu Wang, a zero-year Ph.D. student at The Key Laboratory of Cognition and Decision Intelligence for Complex Systems, [Institute of Automation, Chinese Academy of Sciences](http://www.ia.ac.cn/) (CASIA). I am fortunate to be advised by [Prof. Jun Zhao](https://zhaojun-nlpr.github.io/). Before that, I received my B.E. degree in Software Engineering from [Dalian University of Technology](https://www.dlut.edu.cn/). My research interests include **multimodal large language models** and **streaming video understanding**.

# 🔎 Research

My research mainly focuses on **streaming video reasoning, with an emphasis on the understanding and reasoning capabilities of multimodal large language models in dynamic visual scenarios**. Through my research, I aim to **explore more efficient and reliable methods** for online video understanding and contribute to the development of multimodal intelligent systems.

<div style="border-left: 4px solid #e56565; background: #fff5f5; padding: 0.85em 1em; margin: 1em 0 1.25em 0; border-radius: 6px; box-shadow: 0 1px 4px rgba(0,0,0,0.06);">
  <div style="margin-bottom: 0.45em;">
    <i class="fa-solid fa-envelope" style="color:#e56565; margin-right: 8px" aria-hidden="true"></i>
    <span>If you are interested in my work or want to collaborate, feel free to contact me via: <strong>wanglu2026@ia.ac.cn</strong>.</span>
  </div>
</div>

# 🔥 News

* *2026-06*: 🎉 One paper is accepted by ECCV 2026.
* *2026-06*: 📰 We released a survey on [Agentic Environment Engineering](https://arxiv.org/pdf/2606.12191), which systematically summarizes recent progress in Environment Modeling, Synthesis, Evaluation, and Application, with nearly 600 papers reviewed.

# 📝 Publications

## Selected Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2026</div><img src='images/publication/think-while-watching.png' alt="Think While Watching" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Think While Watching: Online Streaming Segment-Level Memory for Multi-Turn Video Reasoning in Multimodal Large Language Models](https://arxiv.org/pdf/2603.11896) \\
**Lu Wang**, Zhuoran Jin, Yupu Hao, Yubo Chen, Kang Liu, Yulong Ao, Jun Zhao

[![Paper](https://img.shields.io/badge/Paper-ECCV_2026-b31b1b.svg?logo=arxiv)](https://arxiv.org/pdf/2603.11896) [![HuggingFace](https://img.shields.io/badge/%F0%9F%A4%97%20HuggingFace-Paper-blue.svg)](https://huggingface.co/papers/2603.11896) [![Code](https://img.shields.io/badge/GitHub-Code-black.svg?logo=github)](https://github.com/wl666hhh/Think_While_Watching/)

</div>
</div>

## 2026

* [Think While Watching: Online Streaming Segment-Level Memory for Multi-Turn Video Reasoning in Multimodal Large Language Models](https://arxiv.org/pdf/2603.11896). **ECCV 2026**.<br>
  **Lu Wang**, Zhuoran Jin, Yupu Hao, Yubo Chen, Kang Liu, Yulong Ao, Jun Zhao

# 📖 Educations

* *2026.09 - Present*, Ph.D., Institute of Automation, Chinese Academy of Sciences, supervised by [Prof. Jun Zhao](https://zhaojun-nlpr.github.io/).

* *2022.09 - 2026.06*, B.E., School of Software Engineering, [Dalian University of Technology](https://www.dlut.edu.cn/).

<section class="homepage-like" aria-label="页面互动">
  <button id="homepage-like-button" class="homepage-like__button" type="button" aria-pressed="false">
    <span class="homepage-like__icon" aria-hidden="true">♥</span>
    <span class="homepage-like__label">喜欢这个主页</span>
    <span id="homepage-like-count" class="homepage-like__count" aria-live="polite">0</span>
  </button>
  <span id="homepage-like-status" class="homepage-like__status" role="status"></span>
</section>

<section class="homepage-contact" aria-labelledby="wechat-title">
  <div class="homepage-contact__copy">
    <span class="homepage-contact__eyebrow">Let's connect</span>
    <h2 id="wechat-title">添加我的微信</h2>
    <p>扫码添加好友，欢迎交流研究、合作与想法。</p>
  </div>
  <div class="homepage-contact__qr">
    <img src="images/wechat-qr.png" alt="微信二维码，扫码添加我为好友" loading="lazy">
    <span>微信二维码</span>
  </div>
</section>
