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

My name is Yuancheng Wang (王远程). I'm a first-year Ph.D. student at the Chinese University of Hong Kong, Shenzhen (CUHK-Shenzhen), supervised by Professor [Zhizheng Wu](http://www.drwuz.com/). before that, I received my B.S. degree at CUHK-Shenzhen. I also collaborate with [Xu Tan (谭旭)](https://www.microsoft.com/en-us/research/people/xuta/) from Microsoft Research Asia.

My research interest includes **text-to-speech synthesis**, **text-to-audio generation**, and **unified audio representation and generation**. I am one of the main contributors and leaders of the open-source [Amphion](https://github.com/open-mmlab/Amphion) toolkit. I have developed [NaturalSpeech 3](https://arxiv.org/abs/2403.03100), which is an advanced text-to-speech model with factorized speech representation and modeling.

# 🔥 News
<!-- - *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet -->
- *2024.09*: 🔥 We released [MaskGCT](https://arxiv.org/abs/2409.00750), A new SOTA large-scale TTS system with masked generative models.
- *2024.08*: 🎉 our papers, [Amphion](https://arxiv.org/abs/2312.09911) and [Emilia](https://arxiv.org/abs/2407.05361) got accepted by IEEE SLT 2024.
- *2024.07*: 🔥 We released [Emilia](https://arxiv.org/abs/2407.05361v1), an extensive, multilingual, and diverse speech dataset for large-scale speech generation with 101k hours of speech in six languages and features diverse speech with varied speaking styles.
- *2024.05*: 🎉 Our paper [Factorized Diffusion Models are Natural and Zero-shot Speech Synthesizers](https://arxiv.org/abs/2304.00830), aka NaturalSpeech 3, got accepted by ICML 2024 as an Oral presentation!
- *2024.03*: 🎉 We are delighted to release [NaturalSpeech 3](https://arxiv.org/abs/2403.03100), which is an advanced version of the NaturalSpeech series with speech factorization. And we release **FACodec** checkpoints and demo in [HuggingFace Amphion Space](https://huggingface.co/amphion).
- *2023.11*: 🔥 We released [Amphion v0.1](https://github.com/open-mmlab/Amphion) (⭐️ 4.4k+), which is an open-source toolkit for audio, music, and speech generation.
- *2023.09*: 🎉 My first paper about audio generation and editing [AUDIT: Audio Editing by Following Instructions with Latent Diffusion Models](https://arxiv.org/abs/2304.00830) got accepted by NeurIPS 2023!


# 📝 Publications 

<tr>
            <td valign="center">
              <span class="tag">SLT 2024</span>&nbsp;&nbsp;
              <a href="https://github.com/open-mmlab/Amphion">
                <img src="https://img.shields.io/github/stars/open-mmlab/Amphion?color=success&logo=github">
              </a>
              &nbsp;&nbsp;
              <papertitle>
                Amphion: An Open-Source Audio, Music and Speech Generation Toolkit
              </papertitle>
              <br>
              <span class="underline">Xueyao Zhang</span>*, <a class="black"
                href="https://scholar.google.com/citations?user=KNqxVT0AAAAJ&hl=zh-CN">Liumeng Xue</a>*, <a
                class="black" href="https://www.yichenggu.com/">Yicheng
                Gu*</a>, <a class="black"
                href="https://scholar.google.com/citations?user=60uamz4AAAAJ&hl=en&oi=sra">Yuancheng
                Wang</a>*, Jiaqi Li*, Haorui He, Chaoren Wang, Songting Liu, Xi Chen, Junan Zhang, Zihao Fang, Haopeng
              Chen, Tze Ying Tang,
              Lexiao Zou, Mingxuan Wang, <a class="black" href="https://stevenhan1991.github.io/">Jun Han</a>, <a
                class="black" href="https://chenkai.site/">Kai
                Chen</a>, <a class="black" href="https://www.colips.org/~eleliha/">Haizhou Li</a>, <a class="black"
                href="https://drwuz.com/">Zhizheng
                Wu</a> (*: Equal Contribution)
              <br>
              <i>Proceedings of the IEEE Spoken Language Technology Workshop 2024</i>
              <br>
              <a href="https://arxiv.org/pdf/2312.09911.pdf">Preprint</a> /
              <a href="https://github.com/open-mmlab/Amphion">GitHub</a> /
              <!-- <a href="data/HAT/slides.pdf">Slides</a> / -->
              <a href="https://huggingface.co/amphion">HuggingFace</a> /
              <a href="https://openxlab.org.cn/usercenter/Amphion">OpenXLab</a>
              <br>
              <span class="tldr">TL;DR: We develop a unified audio generation open-source toolkit.
              </span>
            </td>
</tr>

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2024 Oral</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations
- *2023.09 - now*, Ph.D. student, the Chinese University of Hong Kong, Shenzhen.
- *2019.09 - 2023.05*, Undergraduate, the Chinese University of Hong Kong, Shenzhen.
- *2015.09 - 2019.06*, Hefei No.1 High School, Hefei, Anhui.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2024.05 - now*, ByteDance, Shenzhen.
- *2022.12 - 2023.06*, Microsoft, Beijing.