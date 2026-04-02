---
layout: default
title: Zhangrui Yang (杨章睿) | Tongji University
---

<style>
  /* 1. 样式隔离：仅作用于此 ID 内部，不干扰主题侧边栏 */
  #academic-page-container {
    color: #2c3e50;
    line-height: 1.6;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Arial, sans-serif;
  }

  /* 2. 头部区域：使用浮动布局（最稳健，防止重叠） */
  .profile-header-area {
    margin-bottom: 30px;
    overflow: hidden; /* 清除浮动 */
  }

  .profile-img {
    float: right;
    width: 160px;
    border-radius: 8px;
    margin-left: 20px;
    margin-bottom: 10px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
  }

  /* 3. 章节标题样式 */
  #academic-page-container h2 {
    border-bottom: 2px solid #e9ecef;
    padding-bottom: 8px;
    margin-top: 45px !important;
    font-weight: 700;
    color: #1a2a3a;
    clear: both; /* 确保不被头像遮挡 */
  }

  /* 4. 卡片式容器（经验、项目、教育） */
  .styled-card {
    border: 1px solid #e9ecef;
    border-radius: 8px;
    padding: 18px;
    margin-bottom: 20px;
    background: #fff;
  }

  /* 5. 论文项样式 */
  .pub-entry { margin-bottom: 25px; }
  .pub-title { font-weight: bold; font-size: 1.1em; color: #1a2a3a; display: block; }
  .status-tag { color: #e67e22; font-weight: bold; font-size: 0.85em; margin-left: 5px; }

  /* 6. 标签/勋章样式 */
  .jerry-badge {
    display: inline-block;
    padding: 2px 10px;
    font-size: 0.8em;
    border-radius: 4px;
    text-decoration: none !important;
    margin-top: 6px;
    margin-right: 6px;
  }
  .bg-black { background: #24292e; color: #fff !important; }
  .bg-red { background: #B31B1B; color: #fff !important; }
  .bg-gold { background: #fff3cd; color: #856404; border: 1px solid #ffeeba; font-weight: bold; border-radius: 20px; }
  .bg-skill { background: #f0f2f5; color: #495057; border: 1px solid #d1d9e6; }

  /* 7. 课程网格布局 */
  .course-list {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(180px, 1fr));
    gap: 8px;
    margin-top: 10px;
    padding-top: 10px;
    border-top: 1px solid #eee;
  }
</style>

<div id="academic-page-container">

  <div class="profile-header-area">
    <img src="assets/images/profile.jpg" class="profile-img">
    <h2 style="border:none; margin-top:0 !important; padding:0;">Zhangrui Yang (杨章睿)</h2>
    <p>
      Undergraduate Researcher<br>
      Computer Science and Technology (Elite Program)<br>
      <a href="https://ghc.tongji.edu.cn/">Guohao College</a>, Tongji University
    </p>
    <p>
      Email: <a href="mailto:jerry.zryang@hotmail.com">jerry.zryang@hotmail.com</a><br>
      <a href="https://github.com/Yarathustra">GitHub</a> /
      <a href="https://scholar.google.com/citations?user=1io0foEAAAAJ">Google Scholar</a>
    </p>
  </div>

  <section>
    <h2>About</h2>
    <p style="font-size: 1.1em; color: #34495e;">
      I am an undergraduate researcher in the <strong>Elite Program</strong> at Tongji University. My research lies at the intersection of <strong>vision-language models</strong> and <strong>spatial reasoning</strong>.
    </p>
    <p>
      Recent large multimodal models demonstrate impressive visual reasoning performance, yet emerging evidence suggests that many spatial reasoning capabilities arise from dataset-level statistical regularities rather than structured geometric understanding. My work investigates how multimodal models represent spatial structure and how evaluation protocols can distinguish genuine spatial reasoning from shortcut learning.
    </p>
    <p>
      More broadly, I am interested in multimodal representation learning, spatial intelligence in foundation models, and robust perception under distribution shift.
    </p>
  </section>

  <section>
    <h2>Publications</h2>
    <div class="pub-entry">
      <span class="pub-title">Enhancing Adversarial Attacks with Decision Boundary Information <span class="status-tag">Under Review</span></span>
      <span><strong>Zhangrui Yang</strong>, Shengming Yuan, Bo Wang, Yaya Cheng, Pengpeng Zeng, Zheng Wang, Xuanhan Wang, Jingkuan Song</span><br>
      <span style="font-style:italic; color:#666;">Information Fusion, 2026</span><br>
      <a href="https://github.com/Yarathustra/BF-Attack" class="jerry-badge bg-black">Code</a>
    </div>

    <div class="pub-entry">
      <span class="pub-title">Pseudo-Label Refinement for Robust Wheat Head Segmentation via Two-Stage Hybrid Training</span>
      <span>Jiahao Jiang*, <strong>Zhangrui Yang</strong>*, Xuanhan Wang, Jingkuan Song</span><br>
      <span style="font-style:italic; color:#666;">CVPPA Workshop, ICCV 2025</span><br>
      <a href="https://arxiv.org/abs/2512.11874" class="jerry-badge bg-red">arXiv</a>
    </div>
    <small style="color:#888;">* Equal contribution.</small>
  </section>

  <section>
    <h2>Research Experience</h2>
    <div class="styled-card">
      <div style="display:flex; justify-content:space-between; align-items:center; flex-wrap:wrap;">
        <strong>Global Wheat Full Semantic Segmentation (GWFSS)</strong>
        <span class="jerry-badge bg-gold">Global Rank #2</span>
      </div>
      <p style="margin-top:10px; font-size:0.95em; color:#555;">
        Developed a pseudo-label refinement framework for wheat head segmentation under limited annotation settings. The work focuses on improving pseudo-label reliability through iterative teacher–student training and systematic ablation analysis.
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
    <h2>Selected Projects</h2>
    <div class="styled-card">
      <strong>SurgeryMind — Multimodal Surgical Assistant</strong>
      <p style="margin-top:10px; font-size:0.95em; color:#555;">
        Designed a multimodal surgical interaction system integrating speech recognition, gesture-based control, and web-based visualization. The system enables surgeons to interact with imaging systems through natural multimodal commands during operations.
      </p>
    </div>
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
    <div class="styled-card" style="background:#fcfcfc;">
      <div style="display:flex; justify-content:space-between; flex-wrap:wrap;">
        <strong>Tongji University</strong>
        <span style="color:#666;">2023 – 2027 (expected)</span>
      </div>
      <div>B.S. in Computer Science and Technology (Elite Program)</div>
      <div style="margin-top:15px; font-weight:600; font-size:0.9em; border-top:1px solid #eee; padding-top:10px;">Selected Coursework:</div>
      <div class="course-list">
        <div style="font-size:0.85em;">• Mathematical Analysis</div>
        <div style="font-size:0.85em;">• Linear Algebra</div>
        <div style="font-size:0.85em;">• Probability & Statistics</div>
        <div style="font-size:0.85em;">• Data Structures & Algorithms</div>
        <div style="font-size:0.85em;">• Pattern Recognition</div>
        <div style="font-size:0.85em;">• Database Systems</div>
      </div>
    </div>
  </section>

  <section>
    <h2>Contact</h2>
    <p>📧 Email: <a href="mailto:jerry.zryang@hotmail.com">jerry.zryang@hotmail.com</a></p>
  </section>

</div>
