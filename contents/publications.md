<sup>#</sup> denotes co-first authors, † denotes the corresponding author

<style>
   .paper-section {
      display: flex;
      align-items: start;
      gap: 30px;
      margin-bottom: 35px;
      padding: 20px;
      background: #fafbfc;
      border-radius: 12px;
      border: 1px solid #e8e8e8;
      transition: box-shadow 0.2s ease;
    }

   .paper-section:hover {
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.08);
    }

   .journal-logo {
      padding: 4px 12px;
      border-radius: 6px 6px 0 0;
      width: 180px; 
      text-align: center;
    }

   .journal-name {
      color: white;
      font-weight: bold;
      font-size: 0.95rem;
    }

   .paper-info {
      flex: 1;
    }

   .paper-title {
      margin-top: 0;
      margin-bottom: 12px;
      font-size: 1.3rem;
      line-height: 1.5;
      color: #1a1a2e;
    }

   .authors {
      margin-bottom: 8px;
      color: #555;
      font-size: 0.95rem;
      line-height: 1.6;
    }

   .conference-info {
      margin-bottom: 0;
      font-size: 0.9rem;
    }

   .action-buttons {
      display: flex;
      flex-direction: column;
      gap: 8px;
      align-items: flex-end;
    }

   .button {
      padding: 6px 14px;
      height: auto; 
      line-height: 1.4; 
      text-decoration: none;
      border-radius: 6px;
      color: #333;
      border: 1px solid #ccc;
      background: #fff;
      font-size: 0.85rem;
      font-weight: 500;
      transition: all 0.2s ease;
      min-width: 70px;
      text-align: center;
    }

   .button:hover {
      background: #f0f0f0;
      border-color: #999;
      color: #000;
    }

   .paper-img {
      max-width: 100%;
      width: 180px;
      height: 120px;
      object-fit: contain;
      background: #fff;
      margin-bottom: 0;
      border-radius: 6px;
      box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
    }

   .paper-img-container {
      width: 180px;
      flex-shrink: 0;
    }

    .aaai-logo {
      background-color: #003973;
    }

   .acl_series-logo {
      background-color: #ed1d24;
    }
    .arXiv-logo {
      background-color: #b31b1b;
    }

    .bibm-logo {
      background-color: #e6a937;
    }

    .eswa-logo {
      background-color: #519dac;
    }

    /* 添加 hr 样式 */
    hr.separator {
      border: 0;
      border-top: 2px solid #e0e0e0;
      margin: 30px 0;
    }

    /* Section titles */
    .pub-section-title {
      font-size: 1.2rem;
      font-weight: 700;
      color: #2c3e50;
      margin-bottom: 20px;
      padding-bottom: 8px;
      border-bottom: 3px solid #4a90e2;
      display: inline-block;
    }
</style>

<div class="pub-section-title">Preprint</div>

<p style="color: #888; font-style: italic;">Coming soon...</p>

<!-- 添加分隔线 -->
<hr class="separator">

<div class="pub-section-title">Conference Papers</div>

<div class="paper-section">
    <div class="paper-img-container">
      <div class="journal-logo acl_series-logo">
        <span class="journal-name">EMNLP</span>
      </div>
      <img src="contents/publication_img/UNCO.png" alt="UNCO" class="paper-img">
    </div>
    <div class="paper-info">
      <h2 class="paper-title">UnCo: Uncertainty-Driven Collaborative Framework of Large and Small Models for Grounded Multimodal NER</h2>
      <p class="authors">
      Jielong Tang, <strong>Yang Yang</strong>, Jianxing Yu, Zhen-Xing Wang, Haoyuan Liang, Liang Yao and Jian Yin†.
         </p>
      <p class="conference-info">
        <strong>In EMNLP 2025 Main Conference. </strong>
      </p>
    </div>
    <div class="action-buttons">
      <a href="https://aclanthology.org/2025.emnlp-main.388.pdf" class="button">Paper</a>
      <a href="https://github.com/tangjielong928/UnCo" class="button">Code</a>
    </div>
  </div>


<!-- 第一篇论文 -->
<div class="paper-section">
    <div class="paper-img-container">
      <div class="journal-logo aaai-logo">
        <span class="journal-name">AAAI</span>
      </div>
      <img src="contents/publication_img/MSE-Adapter.png" alt="MSE-Adapter" class="paper-img">
    </div>
    <div class="paper-info">
      <h2 class="paper-title">MSE-Adapter: A Lightweight Plugin Endowing LLMs with the Capability to Perform Multimodal Sentiment Analysis and Emotion Recognition</h2>
      <p class="authors">
        <strong>Yang Yang</strong>,
        Xunde Dong†  
        and Yupeng Qiang.
         </p>
      <p class="conference-info">
        <strong>In AAAI 2025.</strong>
      </p>
    </div>
    <div class="action-buttons">
      <a href="https://ojs.aaai.org/index.php/AAAI/article/download/34755/36910" class="button">Paper</a>
      <a href="https://arxiv.org/pdf/2502.12478" class="button">arXiv</a>
      <a href="https://github.com/AZYoung233/MSE-Adapter" class="button">Code</a>
    </div>
  </div>

  <!-- 第二篇论文 -->
<div class="paper-section">
    <div class="paper-img-container">
      <div class="journal-logo acl_series-logo">
        <span class="journal-name">NAACL</span>
      </div>
      <img src="contents/publication_img/CLGSI.png" alt="CLGSI" class="paper-img">
    </div>
    <!-- 这里是绝对路径！特别傻逼 -->
    <div class="paper-info">
      <h2 class="paper-title">CLGSI: A Multimodal Sentiment Analysis Framework based on Contrastive Learning Guided by Sentiment Intensity</h2>
       <p class="authors">
        <strong>Yang Yang</strong>,
        Xunde Dong†  
        and Yupeng Qiang.
      </p>
      <p class="conference-info">
        <strong>In NAACL 2024 Findings.</strong>
      </p>
    </div>
    <div class="action-buttons">
      <a href="https://aclanthology.org/2024.findings-naacl.135.pdf" class="button">Paper</a>
      <a href="https://github.com/AZYoung233/CLGSI" class="button">Code</a>
    </div>
  </div>

<!-- 添加分隔线 -->
<hr class="separator">

<div class="pub-section-title">Journal Papers</div>

  <div class="paper-section">
    <div class="paper-img-container">
      <div class="journal-logo eswa-logo">
        <span class="journal-name">ESWA</span>
      </div>
      <img src="contents/publication_img/CP.png" alt="CP" class="paper-img">
    </div>
    <!-- 这里是绝对路径！特别傻逼 -->
    <div class="paper-info">
      <h2 class="paper-title">Large language models are contrastive reasoners</h2>
       <p class="authors">
        Liang Yao† , <strong>Yang Yang</strong>.
      </p>
      <p class="conference-info">
        <strong>In ESWA 2026.</strong>
      </p>
    </div>
    <div class="action-buttons">
      <a href="https://www.sciencedirect.com/science/article/abs/pii/S0957417425040229" class="button">Paper</a>
      <a href="https://github.com/yao8839836/cp" class="button">Code</a>
    </div>
  </div>



<!-- BIBM的论文，就不放了 -->
<!-- <div class="paper-section">
    <div>
      <div class="journal-logo bibm-logo">
        <span class="journal-name">BIBM</span>
      </div>
      <img src="contents/publication_img/PMQ.png" alt="PMQ" class="paper-img">
    </div>
    <div class="paper-info">
      <h2 class="paper-title">Enhancing Contrastive Learning-based Electrocardiogram Pretrained Model with Patient Memory Queue</h2>
      <p class="authors">
        Xiaoyu Sun<sup>#</sup>,
        <strong>Yang Yang</strong><sup>#</sup>,
        and Xunde Dong†.
         </p>
      <p class="conference-info">
        <strong>In BIBM 2025 Short Paper. This paper was sponsored by the SCUT Student Research Project. </strong>
      </p>
    </div>
    <div class="action-buttons">
      <a href="https://arxiv.org/pdf/2506.06310" class="button">arXiv</a>
      <a href="https://github.com/3hiuwoo/PMQ" class="button">Code</a>
    </div>
  </div> -->