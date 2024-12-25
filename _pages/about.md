---
layout: about
title: About
permalink: /
# subtitle: <a href='#'>Affiliations</a>. Address. Contacts. Moto. Etc.
subtitle:

profile:
  align: right
  image: mypic.jpeg
  more_info: University Center 101, HKUST, Clear Water Bay
  # more_info: Room 1111, Thomas M. Siebel Center for Computer Science, UIUC.

news: false  # includes a list of news items
latest_posts: false  # includes a list of the newest posts
selected_papers: false # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
---

## Bibliography

I am Zihao Wang （王子豪）, a final year Ph.D. candidate from [CSE department](https://cse.hkust.edu.hk/), [HKUST](https://hkust.edu.hk/) since Sept. 2020. My advisor is [Prof. Yangqiu Song](https://cse.hkust.edu.hk/~yqsong/). I obtained my master's degree in [Computer Science and Technology](https://www.cs.tsinghua.edu.cn/csen/) in 2020 with [Prof. Yong Zhang](https://dagege.github.io/), my primary bachelor's degree in [Energy and Power Engineering](https://www.depe.tsinghua.edu.cn/depeen/) in 2017, and my secondary bachelor's degree in [Pure and Applied Mathematics](https://math.tsinghua.edu.cn) in 2018 with [Prof. Hao Wu](https://haowu1983.github.io), all from [Tsinghua University](https://www.tsinghua.edu.cn/en/index.htm).

From Aug. 2023 to Jan. 2024, I visited the IDEA lab @ UIUC under the supervision of [Prof. Hanghang Tong](http://tonghanghang.org/).

<br/><br/>

---

## Research interests

My new research interest is the measurement of interconnected data.

### Summary at the end of 2023

<details><summary>(click to expand)</summary>
The general theme of my research is **reasoning** with **data**, with special interests in *logic on graphs*, *language models*, *optimal transport*, and *AI for sciences*.

{% include figure.html path="assets/img/research-overview.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}

#### First-order reasoning on KG
During my PhD, I studied graph problems justified by the first-order language.

$$(\text{Reason}, \text{Data}) = (\text{First-order language}, \text{Graph})$$

My work includes:
- On the language aspect, I build empirical datasets and benchmarks to cover the Existential First Order (EFO) [NeurIPS'21, arXiv:2304.07063, arXiv:2307.13701]
- On the model aspect, I build deep learning and representation learning methods to answer first-order queries [NAACL'22, ACL'23, ICLR'23]

#### Natural language reasoning (beyond the first-order language)
My research work also involves reasoning with natural languages, which is beyond the first order.

$$(\text{Reason}, \text{Data}) = (\text{Natural language}, \text{World knowledge})$$

My research can be roughly separated by knowledge representation and reasoning

- World knowledge representation: Commonsense knowledge representation [EMNLP'22a]
- World knowledge reasoning: Neurosymbolic reasoning for natural language query [EMNLP'22b]

✨ My recent interest includes the reasoning capability of multi-agent LLMs. (arXiv:2311.07076)

#### Data modeling (within the first-order language)
I frame the machine learning tasks as a single predicate $$ \text{Prediction}(\text{Input}, \text{Output}) $$

$$(\text{Reason}, \text{Data}) = (\text{Single Predicate}, \text{Multimodal data})$$

<details open>
  <summary> Shallow reasoning by data modeling </summary>
  ✨ My recent interest includes on modeling of molecule graphs. (arXiv:2310.03152)
  <div style="margin-left: 40px">
    <details>
    <summary>The predicate <ins> IsLabelOf </ins> (supervised learning)</summary>
    <ul>
      <li>Understanding deep learning tricks [arXiv:2010.12648]</li>
      <li>Designing neural heuristics for applications [AJODO'23, JORC'23]</li>
      <li>Compressing deep neural networks [ICML'23]</li>
    </ul>
    </details>
    <details>
      <summary>The predicate <ins> IsLatentCodeOf </ins> (unsupervised learning)</summary>
    <ul>
      <li>Understanding the variational auto encoder [NeurIPS'22]</li>
      <li>Modeling temporal encoding/decoding process [VTC'21]</li>
      <li>ML for hardware design [ICCT'21]</li>
    </ul>
    </details>
    <details>
      <summary>The predicate <ins> IsSameDistribution </ins> (optimal transport)</summary>
    <ul>
      <li>Efficient algorithms [JSC'23,CSIAM-AM'23,CMS'22]</li>
      <li>Application to point cloud alignment [ACL'20, EMNLP'20, COLING'22]</li>
      <li>Application to cross-domain recommendation [CIKM'22]</li>
    </ul>
    </details>
  </div>
</details>

</details>

<br/><br/>

## Academic services
- Conference Reviewer:
  - NLP: EMNLP 2021 - 2024; ACL 2023 - 2024; EACL 2024; NAACL 2024 - 2025;
  - ML: ICLR 2024 - 2025; ICML 2024; NeurIPS 2023 - 2024; NeurIPS dataset & benchmark 2023 - 2024.
  - AI & Data Mining: AAAI 2024 - 2025; CVPR 2023; KDD 2023 - 2024; CIKM 2023;
- Journal Reviewer: TNNLS, TASLP, TIST, TIP, Information Fusion, DMLR, CSIAM Transaction on Applied Mathematics

<br/><br/>

