---
permalink: /
title: ""
excerpt: "Taihao Zhang is a master's student in Cyberspace Security at Qingdao University, researching privacy-preserving, Byzantine-robust, and verifiable federated learning. Expected graduation: June 2027."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<h1 id="about-me">👋 About Me</h1>

I am **Taihao Zhang (张泰浩)**, a master's student in **Cyberspace Security** at the [College of Computer Science and Technology](https://cst.qdu.edu.cn/), [Qingdao University](https://www.qdu.edu.cn/), advised by [**Associate Professor Wenting Shen (沈文婷)**](https://cst.qdu.edu.cn/info/1072/7573.htm). I expect to graduate in **June 2027**. I also received my bachelor's degree in Information Security from Qingdao University in June 2023.

My research focuses on **privacy and security in federated learning**, with an emphasis on protecting client model updates while enabling efficient, robust, and verifiable collaborative training. During my master's studies, I have authored three manuscripts as first author, covering verifiable aggregation with independent sparsification, privacy-preserving Byzantine-robust learning, and adaptive clustered federated learning under heterogeneous data.

<div class="phd-notice" markdown="1">
**Seeking Ph.D. Opportunities** · I am interested in pursuing doctoral research in privacy-preserving and secure federated learning. Please feel free to contact me about relevant Ph.D. opportunities.
</div>

<h1 id="research">🔬 Research Interests</h1>

- **Privacy-Preserving and Verifiable Federated Learning:** Protecting model updates and sparse parameter indices while verifying aggregation by untrusted servers.
- **Byzantine-Robust Federated Learning:** Privacy-preserving anomaly detection and robust aggregation under heterogeneous data and malicious clients.
- **Adaptive Clustered Federated Learning:** Using structural information in model updates to group clients while balancing privacy, model utility, and efficiency.

<h1 id="publications">📝 Publications &amp; Manuscripts</h1>

<p class="publication-note">I am the first author of all three works below. Submission and acceptance statuses are indicated for each manuscript.</p>

<div class="paper-box">
  <div class="paper-box-image">
    <a href="{{ '/images/publications/spirit-fl.png' | relative_url }}" target="_blank" rel="noopener" aria-label="View the SPIRIT-FL system model">
      <img src="{{ '/images/publications/spirit-fl.png' | relative_url }}" alt="SPIRIT-FL system model showing clients, an aggregation server, a trusted authority, and blockchain-assisted verification." loading="lazy">
    </a>
  </div>
  <div class="paper-box-text" markdown="1">

### SPIRIT-FL: A Sparse Polynomial Framework for Privacy-Preserving and Verifiable Federated Learning with Independent Sparsification

**Taihao Zhang**, Wenting Shen, Chenliang Tian, Jiewang Cai

<p class="paper-venue">Submitted to the Network and Distributed System Security Symposium (NDSS) <span class="paper-status">Under review</span></p>

Represents independently sparsified model updates as sparse polynomials, encoding coordinates as exponents and update values as coefficients to enable private alignment and aggregation. Polynomial-based verification, sparse interpolation, and blockchain-assisted Bottom-ℓ sketches support verifiable aggregation and adaptive weighting while reducing computation and communication overhead.

<p class="paper-links"><a href="{{ '/files/papers/SPIRIT-FL.pdf' | relative_url }}" target="_blank" rel="noopener"><i class="fas fa-file-pdf" aria-hidden="true"></i> Manuscript PDF</a><span>Independent sparsification · Verifiable aggregation</span></p>

  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <a href="{{ '/images/publications/epbfl.png' | relative_url }}" target="_blank" rel="noopener" aria-label="View the EPBFL system model">
      <img src="{{ '/images/publications/epbfl.png' | relative_url }}" alt="EPBFL system model showing clients, an aggregation server, and a decryption server for encrypted dissimilarity computation and clustered aggregation." loading="lazy">
    </a>
  </div>
  <div class="paper-box-text" markdown="1">

### Efficient Privacy-Preserving Byzantine-Robust Federated Learning with Top-k Sparsification

**Taihao Zhang**, Wenting Shen, Jing Qin

<p class="paper-venue">Submitted to IEEE Transactions on Information Forensics and Security (TIFS) <span class="paper-status">Under review</span></p>

Combines Top-k sparsification with masked block-wise P-ary encoding to align sparse updates without revealing clients' retained parameter indices. CKKS homomorphic encryption enables efficient encrypted pairwise dissimilarity computation, while density-based clustering and cluster-wise weighted aggregation mitigate Byzantine attacks under heterogeneous data.

<p class="paper-links"><a href="{{ '/files/papers/EPBFL.pdf' | relative_url }}" target="_blank" rel="noopener"><i class="fas fa-file-pdf" aria-hidden="true"></i> Manuscript PDF</a><span>Top-k sparsification · Homomorphic encryption · Byzantine robustness</span></p>

  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <a href="{{ '/images/publications/pa-cfl.png' | relative_url }}" target="_blank" rel="noopener" aria-label="View the PA-CFL system model">
      <img src="{{ '/images/publications/pa-cfl.png' | relative_url }}" alt="PA-CFL system model showing users, a management server for pre-clustering and shuffling, and an aggregation server for fine clustering and aggregation." loading="lazy">
    </a>
  </div>
  <div class="paper-box-text" markdown="1">

### PA-CFL: Privacy-Preserving Adaptive Clustered Federated Learning under Heterogeneous Data

**Taihao Zhang**, Wenting Shen, Hanlin Zhang, Chenbin Zhao

<p class="paper-venue">Mathematics <span class="paper-status paper-status--accepted">Accepted</span></p>

Introduces a structure-aware similarity metric and a two-stage adaptive clustering process to reduce reliance on manually specified clustering parameters. Applies differentiated protection to important and less important gradient subvectors through permutation obfuscation, local randomization, and intra-cluster shuffling, balancing privacy, model utility, and efficiency under heterogeneous data.

<p class="paper-links"><a href="{{ '/files/papers/PA-CFL.pdf' | relative_url }}" target="_blank" rel="noopener"><i class="fas fa-file-pdf" aria-hidden="true"></i> Accepted Manuscript</a><span>Adaptive clustering · Data heterogeneity · Privacy protection</span></p>

  </div>
</div>

<h1 id="education">🎓 Education</h1>

<div class="education-entry" markdown="1">
<span class="education-date">Sep. 2024 - Jun. 2027 (expected)</span>

**Qingdao University**<br>
Master's student in Cyberspace Security, College of Computer Science and Technology
</div>

<div class="education-entry" markdown="1">
<span class="education-date">Sep. 2019 - Jun. 2023</span>

**Qingdao University**<br>
Bachelor's degree in Information Security, College of Computer Science and Technology
</div>

<h1 id="skills">🛠️ Skills</h1>

- **Programming Languages & Research Tools:** Python, C++, PyTorch, TensorFlow, and LaTeX.
- **Language Qualifications:** College English Test Band 6 (CET-6) and Putonghua Proficiency Test, Level 2-B.
- **Machine Learning:** Federated Learning, Deep Learning, Privacy-Preserving Machine Learning, Robust Machine Learning, Clustering and Unsupervised Learning, and Model Compression.
- **Mathematics:** Probability Theory and Stochastic Processes, Stochastic Optimization and Convergence Analysis, Linear Algebra and Numerical Methods, and Discrete Mathematics.

<h1 id="awards">🎖️ Honors &amp; Awards</h1>

- Qingdao University Scholarship (awarded twice)
- Third Prize, Shandong Provincial Competition, Lanqiao Cup Algorithm Competition
