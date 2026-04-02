---
layout: default
title: Zhangrui Yang (杨章睿) | Tongji University
---

<style>
  /* 1. 兼容性变量：仅作用于我们自己的元素 */
  #academic-profile {
    --primary: #2c3e50;
    --accent: #007bff;
    --border: #e9ecef;
    --text-m: #666;
    color: var(--primary);
    line-height: 1.6;
  }

  /* 2. 修复重叠：给内容区顶部留出呼吸空间 */
  .profile-container {
    padding-top: 20px;
    display: block; /* 弃用 flex 以防主题干扰 */
    overflow: hidden;
  }

  /* 3. 个人简介：改用更稳健的浮动或响应式网格 */
  .header-box {
    margin-bottom: 30px;
    border-bottom: 1px solid var(--border);
    padding-bottom: 20px;
  }

  .profile-pic {
    float: right;
    width: 150px;
    border-radius: 8px;
    margin-left: 20px;
    margin-bottom: 10px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
  }

  @media (max-width: 600px) {
    .profile-pic { float: none; display: block; margin: 0 auto 20px; }
  }

  /* 4. 章节标题优化：避开主题自带样式的重叠 */
  #academic-profile h2 {
    border-bottom: 2px solid var(--border);
    padding-bottom: 5px;
    margin-top: 40px !important; /* 强制间距 */
    color: var(--primary);
    clear: both; /* 确保不被浮动图片遮挡 */
  }

  /* 5. 卡片系统 */
  .pub-card {
    border-left: 4px solid var(--border);
    padding: 5px 15px;
    margin-bottom: 25px;
    background: #fcfcfc;
  }

  .exp-card {
    border: 1px solid var(--border);
    border-radius: 8px;
    padding: 15px;
    margin-bottom: 15px;
    background: #fff;
  }

  .badge-row { margin-top: 8px; display: flex; gap: 8px; flex-wrap: wrap; }
  
  .pill {
    padding: 2px 10px;
    font-size: 0.8em;
    border-radius: 4px;
    text-decoration: none !important;
    display: inline-block;
  }
  .pill-blue { background: var(--accent); color: white !important; }
  .pill-red { background: #B31B1B; color: white !important; }
  .pill-gray { background: #24292e; color: white !important; }
  .pill-yellow { background: #fff3cd; color: #856404; border: 1px solid #ffeeba; }
  .pill-skill { background: #f0f2f5; color: #495057; border: 1px solid #d1d9e6; margin-right: 5px; }

  /* 6. 课程表 */
  .course-list {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(180px, 1fr));
    gap: 8px;
    list-style: none;
    padding: 0;
  }
  .course-list li::before { content: "• "; color: var(--accent); }
</style>

<div id="academic-profile">

  <div class="profile-container">
    <img src="assets/images/profile.jpg" class="profile-pic">
    <div class="header-box">
      <h1 style="margin-top:0;">Zhangrui Yang (杨章睿)</h1>
      <p>
        Undergraduate Researcher<br>
        Computer Science and Technology (Elite Program)<br>
        <a href="https://ghc.tongji.edu.cn/">Guohao College</a>, Tongji University
      </p>
      <p style="margin-top: 10px;">
        <a href="mailto:jerry.zryang@hotmail.com">📧 Email</a> | 
        <a href="https://github.com/Yarathustra">🐙 GitHub</a> | 
        <a href="https://scholar.google.com/citations?user=1io0foEAAAAJ">🎓 Scholar</a>
      </p>
    </div>
  </div>

  <section>
    <h2>About</h2>
    <p style="font-size: 1.1em; color: #34495e; font-weight: 500;">
      I am an undergraduate researcher in the <span style="color:var(--accent)">Elite Program</span> at Tongji University. 
      My research lies at the intersection of <span style="color:var(--accent)">vision-language models</span> and <span style="color:var(--accent)">spatial reasoning</span>.
    </p>
    <p>
      My work investigates how multimodal models represent spatial structure and how evaluation protocols can distinguish genuine spatial reasoning from shortcut learning.
    </p>
  </section>

  <section>
    <h2>Publications</h2>
    
    <div class="pub-card">
      <strong style="display:block; font-size:1.1em;">Enhancing Adversarial Attacks with Decision Boundary Information</strong>
      <span style="color:#555"><strong>Zhangrui Yang</strong>, Shengming Yuan, Bo Wang, Yaya Cheng, Pengpeng Zeng, Zheng Wang, Xuanhan Wang, Jingkuan Song</span><br>
      <span style="font-style:italic">Information Fusion, 2026</span> <span style="color:#e67e22; font-weight:bold; font-size:0.9em;">[Under Review]</span><br>
      <div class="badge-row">
        <a href="https://github.com/Yarathustra/BF-Attack" class="pill pill-gray">Code</a>
      </div>
    </div>

    <div class="pub-card">
      <strong style="display:block; font-size:1.1em;">Pseudo-Label Refinement for Robust Wheat Head Segmentation</strong>
      <span style="color:#555">Jiahao Jiang*, <strong>Zhangrui Yang</strong>*, Xuanhan Wang, Jingkuan Song</span><br>
      <span style="font-style:italic">CVPPA Workshop, ICCV 2025</span><br>
      <div class="badge-row">
        <a href="https://arxiv.org/abs/2512.11874" class="pill pill-red">arXiv</a>
      </div>
    </div>
    <small>* Equal contribution</small>
  </section>

  <section>
    <h2>Research Experience</h2>
    <div class="exp-card">
      <div style="display:flex; justify-content:space-between; align-items: center;">
        <strong>Global Wheat Full Semantic Segmentation</strong>
        <span class="pill pill-yellow">Global Rank #2</span>
      </div>
      <p style="margin-top:8px; font-size:0.95em; color:#555;">
        Developed a pseudo-label refinement framework for wheat head segmentation, focusing on iterative teacher-student training.
      </p>
    </div>
  </section>

  <section>
    <h2>Selected Honors</h2>
    <ul style="list-style:none; padding:0;">
      <li style="margin-bottom:8px;">🏆 Global 2nd Place — Global Wheat Full Semantic Segmentation Competition</li>
      <li style="margin-bottom:8px;">🏆 National First Prize — iCAN AI Innovation Competition (SurgeryMind)</li>
      <li style="margin-bottom:8px;">🏆 Shanghai Second Prize — National Mathematical Modeling Contest</li>
      <li style="margin-bottom:8px;">🏆 Academic Scholarship — Guohao College, Tongji University</li>
    </ul>
  </section>

  <section>
    <h2>Technical Skills</h2>
    <p>
      <strong>Programming:</strong> <span class="jerry-badge bg-skill">Python</span> <span class="jerry-badge bg-skill">C++</span> <span class="jerry-badge bg-skill">Verilog HDL</span> <span class="jerry-badge bg-skill">SQL</span><br>
      <strong>Frameworks:</strong> <span class="jerry-badge bg-skill">PyTorch</span><br>
      <strong>Tools:</strong> <span class="jerry-badge bg-skill">Linux</span> <span class="jerry-badge bg-skill">Git</span> <span class="jerry-badge bg-skill">LaTeX</span>
    </p>
  </section>

  <section>
    <h2>Education</h2>
    <div style="background: #f8f9fa; padding: 15px; border-radius: 8px;">
      <div style="display:flex; justify-content:space-between;">
        <strong>Tongji University</strong>
        <span style="color:#666">2023 – 2027</span>
      </div>
      <div>B.S. in Computer Science and Technology (Elite Program)</div>
      <p style="margin-top:10px; font-weight:600; font-size:0.9em; border-top:1px solid #ddd; padding-top:10px;">Selected Coursework:</p>
      <ul class="course-list">
        <li>Mathematical Analysis</li>
        <li>Data Structures & Algorithms</li>
        <li>Pattern Recognition</li>
        <li>Probability & Statistics</li>
        <li>Linear Algebra</li>
        <li>Database Systems</li>
      </ul>
    </div>
  </section>

</div>
