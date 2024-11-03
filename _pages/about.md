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

My name is Yuancheng Wang (王远程). I'm a second-year Ph.D. student at the Chinese University of Hong Kong, Shenzhen (CUHK-Shenzhen), supervised by Professor [Zhizheng Wu](http://www.drwuz.com/). before that, I received my B.S. degree at CUHK-Shenzhen. I also collaborate with [Xu Tan (谭旭)](https://www.microsoft.com/en-us/research/people/xuta/) from Microsoft Research Asia.

My research interest includes **text-to-speech synthesis**, **text-to-audio generation**, and **unified audio representation and generation**. I am one of the main contributors and leaders of the open-source [Amphion](https://github.com/open-mmlab/Amphion) toolkit. I have developed [NaturalSpeech 3](https://arxiv.org/abs/2403.03100), which is an advanced text-to-speech model with factorized speech representation and modeling.

# 🔥 News
- *2024.10*: 🔥 We released [code](https://github.com/HeCheng0625/AmphionOpen/tree/dev/maskgct/models/tts/maskgct)(2.5k+ stars in one week) and [checkpoints](https://huggingface.co/amphion/MaskGCT) of MaskGCT, MaskGCT has been used in [趣丸千音](https://voice.funnycp.com/#/). 
- *2024.09*: 🎉 Our paper, [SD-Eval](https://arxiv.org/abs/2406.13340), got accepted by NeurIPS 2024.
- *2024.09*: 🔥 We released [MaskGCT](https://arxiv.org/abs/2409.00750), A new SOTA large-scale TTS system with masked generative models.
- *2024.08*: 🎉 our papers, [Amphion](https://arxiv.org/abs/2312.09911) and [Emilia](https://arxiv.org/abs/2407.05361) got accepted by IEEE SLT 2024.
- *2024.07*: 🔥 We released [Emilia](https://arxiv.org/abs/2407.05361v1), an extensive, multilingual, and diverse speech dataset for large-scale speech generation with 101k hours of speech in six languages and features diverse speech with varied speaking styles.
- *2024.05*: 🎉 Our paper [Factorized Diffusion Models are Natural and Zero-shot Speech Synthesizers](https://arxiv.org/abs/2304.00830), aka NaturalSpeech 3, got accepted by ICML 2024 as an Oral presentation!
- *2024.03*: 🎉 We are delighted to release [NaturalSpeech 3](https://arxiv.org/abs/2403.03100), which is an advanced version of the NaturalSpeech series with speech factorization. And we release **FACodec** checkpoints and demo in [HuggingFace Amphion Space](https://huggingface.co/amphion).
- *2023.11*: 🔥 We released [Amphion v0.1](https://github.com/open-mmlab/Amphion)<a href="https://github.com/open-mmlab/Amphion/tree/main/preprocessors/Emilia"><img src="https://img.shields.io/github/stars/open-mmlab/Amphion?color=success&amp;logo=github" /></a>, which is an open-source toolkit for audio, music, and speech generation.
- *2023.09*: 🎉 My first paper about audio generation and editing [AUDIT: Audio Editing by Following Instructions with Latent Diffusion Models](https://arxiv.org/abs/2304.00830) got accepted by NeurIPS 2023!


# 📝 Publications 

<ul>
  <li>
    <p><strong>MaskGCT: Zero-Shot Text-to-Speech with Masked Generative Codec Transformer</strong><br />
<strong>Yuancheng Wang</strong>, Haoyue Zhan, Liwei Liu, Ruihong Zeng, Haotian Guo, Jiachen Zheng, Qiang Zhang, Shunsi Zhang, Zhizheng Wu<br />
<strong>Preprint</strong>:
<a href="https://arxiv.org/abs/2409.00750"><img src="https://img.shields.io/badge/arXiv-Paper-&lt;COLOR&gt;.svg" /></a> <a href="https://maskgct.github.io/"><img src="https://img.shields.io/badge/WebPage-Demo-red" alt="demo" /></a> <a href="https://huggingface.co/amphion/maskgct"><img src="https://img.shields.io/badge/%F0%9F%A4%97%20HuggingFace-MaskGCT-pink"/></a> <a href="https://github.com/HeCheng0625/AmphionOpen/tree/dev/maskgct/models/tts/maskgct"><img src="https://img.shields.io/badge/Code-MaskGCT-purple"/></a></p>
  </li>
  <li>
    <p><strong>SD-Eval: A Benchmark Dataset for Spoken Dialogue Understanding Beyond Words</strong><br />
Junyi Ao*, <strong>Yuancheng Wang*</strong>, Xiaohai Tian, Dekun Chen, Jun Zhang, Lu Lu, Yuxuan Wang, Haizhou Li, Zhizheng Wu<br />
<strong>NeurIPS 2024</strong>:
<a href="https://arxiv.org/abs/2406.13340"><img src="https://img.shields.io/badge/arXiv-Paper-&lt;COLOR&gt;.svg" /></a> <a href="https://huggingface.co/datasets/amphion/SD-Eval"><img src="https://img.shields.io/badge/%F0%9F%A4%97%20HuggingFace-SDEval-pink" alt="demo" /></a></p>
  </li>
  <li>
    <p><strong>NaturalSpeech 3: Zero-Shot Speech Synthesis with Factorized Codec and Diffusion Models</strong><br />
Zeqian Ju*, <strong>Yuancheng Wang*</strong>, Kai Shen*, Xu Tan*, Detai Xin, Dongchao Yang, Yanqing Liu, Yichong Leng, Kaitao Song, Siliang Tang, Zhizheng Wu, Tao Qin, Xiang-Yang Li, Wei Ye, Shikun Zhang, Jiang Bian, Lei He, Jinyu Li, Sheng Zhao.<br />
<strong>ICML 2024 (Oral)</strong>:
<a href="https://arxiv.org/abs/2403.03100"><img src="https://img.shields.io/badge/arXiv-Paper-&lt;COLOR&gt;.svg" /></a> <a href="https://huggingface.co/amphion/naturalspeech3_facodec"><img src="https://img.shields.io/badge/%F0%9F%A4%97%20HuggingFace-FACodec-pink" /></a></p>
  </li>
  <li>
    <p><strong>AUDIT: Audio editing by following instructions with latent diffusion models</strong><br />
<strong>Yuancheng Wang</strong>, Zeqian Ju, Xu Tan, Lei He, Zhizheng Wu, Jiang Bian<br />
<strong>NeurIPS 2023</strong>:
<a href="https://arxiv.org/abs/2304.00830"><img src="https://img.shields.io/badge/arXiv-Paper-&lt;COLOR&gt;.svg" /></a> <a href="https://audit-demo.github.io/"><img src="https://img.shields.io/badge/WebPage-Demo-red" alt="demo" /></a></p>
  </li>
  <li>
    <p><strong>Amphion: An Open-Source Audio, Music and Speech Generation Toolkit</strong><br />
Xueyao Zhang*, Liumeng Xue*, Yicheng Gu*, <strong>Yuancheng Wang*</strong>, Haorui He, Chaoren Wang, Xi Chen, Zihao Fang, Haopeng Chen, Junan Zhang, Tze Ying Tang, Lexiao Zou, Mingxuan Wang, Jun Han, Kai Chen, Haizhou Li, and Zhizheng Wu.<br />
<strong>SLT 2024</strong>:
<a href="https://github.com/open-mmlab/Amphion"><img src="https://img.shields.io/github/stars/open-mmlab/Amphion?color=success&amp;logo=github" /></a>
<a href="https://arxiv.org/abs/2312.09911"><img src="https://img.shields.io/badge/arXiv-Paper-&lt;COLOR&gt;.svg" /></a>
<a href="https://huggingface.co/amphion"><img src="https://img.shields.io/badge/%F0%9F%A4%97%20HuggingFace-Amphion-pink" /></a></p>
  </li>
  <li>
    <p><strong>Emilia: An Extensive, Multilingual, and Diverse Speech Dataset for Large-Scale Speech Generation</strong><br />
Haorui He*, Zengqiang Shang*, Chaoren Wang*, Xuyuan Li*, Yicheng Gu, Hua Hua, Liwei Liu, Chen Yang, Jiaqi Li, Peiyang Shi, <strong>Yuancheng Wang</strong>, Kai Chen, Pengyuan Zhang, and Zhizheng Wu<br />
<strong>SLT 2024</strong>:  <a href="https://github.com/open-mmlab/Amphion/tree/main/preprocessors/Emilia"><img src="https://img.shields.io/github/stars/open-mmlab/Amphion?color=success&amp;logo=github" /></a> <a href="https://arxiv.org/abs/2407.05361"><img src="https://img.shields.io/badge/arXiv-Paper-COLOR.svg" alt="arXiv" /></a> <a href="https://huggingface.co/datasets/amphion/Emilia-Dataset"><img src="https://img.shields.io/badge/%F0%9F%A4%97%20HuggingFace-Dataset-yellow" alt="hf" /></a> <a href="https://opendatalab.com/Amphion/Emilia"><img src="https://img.shields.io/badge/OpenDataLab-Dataset-blue" alt="OpenDataLab" /></a> <a href="https://emilia-dataset.github.io/Emilia-Demo-Page/"><img src="https://img.shields.io/badge/WebPage-Demo-red" alt="demo" /></a> <a href="https://x.com/realamphion/status/1811793307078643882"><img src="https://img.shields.io/badge/Tweet-Link-blue" alt="Tweet" /></a></p>
  </li>
</ul>

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

# 💬 Invited Talks
- *2024.07*, SD-Eval, OpenMMLab
- *2024.05*, Amphion, OpenMMLab
- *2024.04*, NaturalSpeech 3, Synced 机器之心
- *2024.03*, NaturalSpeech 3, Speech Home 语音之家
  
# 💻 Internships
- *2024.05 - now*, ByteDance, Shenzhen.
- *2022.12 - 2023.06*, Microsoft, Beijing.

# Services
**Reviewer**: International Conference on Learning Representations (ICLR), IEEE Transactions on Audio, Speech and Language Processing (TASLP)

**Teaching Assistant**: Fall 2024, CSC1001, Introduction to Computer Science: Programming Methodology, CUHK(SZ)
