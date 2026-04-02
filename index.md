---
layout: default
title: Zhangrui Yang (杨章睿) | Tongji University
---

<style>
  /* 1. 风格变量统一 */
  :root {
    --primary: #2c3e50;
    --accent: #007bff;
    --text-muted: #666;
    --card-bg: #ffffff;
    --border: #e9ecef;
  }

  /* 2. 容器隔离：防止干扰主题侧边栏 */
  #main-content-wrapper {
    color: var(--primary);
    line-height: 1.6;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Arial, sans-serif;
  }

  /* 3. 头部信息流式布局：修复重叠问题 */
  .bio-header {
    display: flex;
    flex-wrap: wrap; /* 关键：自动换行防止重叠 */
    gap: 30px;
    margin-bottom: 40px;
    align-items: center;
  }
  .bio-text { flex: 1; min-width: 300px; }
  .bio-photo { width: 180px; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.1); }

  /* 4. 章节标题 */
  h2 {
    border-bottom: 2px solid var(--border);
    padding-bottom: 8px;
    margin-top: 45px !important;
    font-weight: 700;
    clear: both;
  }

  /* 5. 卡片式设计：用于经验、项目、教育 */
  .custom-card {
    border: 1px solid var(--border);
    border-radius: 10px;
    padding: 20px;
    margin-bottom: 20px;
    background: var(--card-bg);
    transition: transform 0.2s, box-shadow 0.2s;
  }
  .custom-card:hover {
    transform: translateY(-3px);
    box-shadow: 0 6px 15px rgba(0,0,0,0.05);
  }
  .card-top { display: flex; justify-content: space-between; align-items: baseline; flex-wrap: wrap; }

  /* 6. 标签/勋章 (Badges) */
  .badge {
    display: inline-block;
    padding: 3px 12px;
    font-size: 0.85em;
    border-radius: 6px;
    text-decoration: none !important;
    margin: 4px 4px 0 0;
  }
  .badge-skill { background: #f0f2f5; color: #495057; border: 1px solid #d1d9e6; }
  .badge-rank { background: #fff3cd; color: #856404; border: 1px solid #ffeeba; font-weight: bold; border-radius: 20px; }
  .badge-code { background: #24292e; color: #fff !important; }
  .badge-arxiv { background: #B31B1B; color: #fff !important; }
  
  /* 7. 论文项样式 */
  .pub-item { margin-bottom: 25px; }
  .pub-title { font-weight: bold; font-size: 1.1em; display: block; margin-bottom: 4px; }
  .under-review { color: #e67e22; font-weight: bold; margin-left: 5px; font-size: 0.9em; }

  /* 8. 课程网格 */
  .course-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(180px, 1fr));
    gap: 10px;
    margin-top: 15px;
    padding-top: 10px;
    border-top: 1px solid #eee;
  }
</style>

<div id="main-content-wrapper">

  <header class="bio-header">
    <div class="bio-text">
      <h1 style="margin-top:0;">Zhangrui Yang (杨章睿)</h1>
      <p style="font-size: 1.1em; margin-bottom: 15px;">
        Undergraduate Researcher<br>
        Computer Science and Technology (Elite Program)<br>
        <a href="https://ghc.tongji.edu.cn/" target="_blank">Guohao College</a>, Tongji University
      </p>
      <p>
        📧 Email: <a href="mailto:jerry.zryang@hotmail.com">jerry.zryang@hotmail.com</a><br>
        🔗 <a href="https://github.com/Yarathustra" target="_blank">GitHub</a> / <a href="https://scholar.google.com/citations?user=1io0foEAAAAJ" target="_blank">Google Scholar</a>
      </p>
    </div>
    <img src="assets/images/profile.jpg" alt="Zhangrui Yang" class="bio-photo">
  </header>

  <section>
    <h2>About</h2>
    <p style="font-size: 1.1em; color: #34495e;">
      I am an undergraduate researcher in the <span style="color: var(--accent); font-weight: 600;">Elite Program</span> at Tongji University. My research lies at the intersection of <span style="color: var(--accent); font-weight: 600;">vision-language models</span> and <span style="color: var(--accent); font-weight: 600;">spatial reasoning</span>.
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
    
    <div class="pub-item">
      <span class="pub-title">Enhancing Adversarial Attacks with Decision Boundary Information <span class="under-review">Under Review</span></span>
      <span><strong>Zhangrui Yang</strong>, Shengming Yuan, Bo Wang, Yaya Cheng, Pengpeng Zeng, Zheng Wang, Xuanhan Wang, Jingkuan Song</span><br>
      <span style="font-style: italic; color: #555;">Information Fusion, 2026</span><br>
      <a href="https://github.com/Yarathustra/BF-Attack" class="badge badge-code">Code</a>
    </div>

    <div class="pub-item" style="border-top: 1px solid #f0f0f0; padding-top: 20px;">
      <span class="pub-title">Pseudo-Label Refinement for Robust Wheat Head Segmentation via Two-Stage Hybrid Training</span>
      <span>Jiahao Jiang*, <strong>Zhangrui Yang</strong>*, Xuanhan Wang, Jingkuan Song</span><br>
      <span style="font-style: italic; color: #555;">CVPPA Workshop, ICCV 2025</span><br>
      <a href="https://arxiv.org/abs/2512.11874" class="badge badge-arxiv">arXiv</a>
    </div>

    <p style="font-size: 0.85em; color: var(--text-muted);">* Equal contribution.</p>
  </section>

  <section>
    <h2>Research Experience</h2>
    <div class="custom-card">
      <div class="card-top">
        <strong style="font-size: 1.1em;">Global Wheat Full Semantic Segmentation (GWFSS)</strong>
        <span class="badge badge-rank">Global Rank #2</span>
      </div>
      <p style="margin-top: 10px; color: #555;">
        Developed a pseudo-label refinement framework for wheat head segmentation under limited annotation settings. The work focuses on improving pseudo-label reliability through iterative teacher–student training and systematic ablation analysis.
      </p>
    </div>
  </section>

  <section>
    <h2>Selected Honors</h2>
    <ul style="list-style: none; padding: 0;">
      <li style="margin-bottom: 10px;">🏆 Global 2nd Place — Global Wheat Full Semantic Segmentation Competition</li>
      <li style="margin-bottom: 10px;">🏆 National First Prize — iCAN AI Innovation Competition (SurgeryMind)</li>
      <li style="margin-bottom: 10px;">🏆 Shanghai Second Prize — National Mathematical Modeling Contest</li>
      <li style="margin-bottom: 10px;">🏆 Academic Scholarship — Guohao College, Tongji University</li>
    </ul>
  </section>

  <section>
    <h2>Selected Projects</h2>
    <div class="custom-card">
      <div class="card-top">
        <strong style="font-size: 1.1em;">SurgeryMind — Multimodal Surgical Assistant</strong>
      </div>
      <p style="margin-top: 10px; color: #555;">
        Designed a multimodal surgical interaction system integrating speech recognition, gesture-based control, and web-based visualization. The system enables surgeons to interact with imaging systems through natural multimodal commands during operations.
      </p>
    </div>
  </section>

  <section>
    <h2>Technical Skills</h2>
    <div style="margin-bottom: 12px;">
      <strong>Programming:</strong> 
      <span class="badge badge-skill">Python</span> <span class="badge badge-skill">C++</span> <span class="badge badge-skill">Verilog HDL</span> <span class="badge badge-skill">SQL</span>
    </div>
    <div style="margin-bottom: 12px;">
      <strong>Frameworks:</strong> <span class="badge badge-skill">PyTorch</span>
    </div>
    <div>
      <strong>Tools:</strong> <span class="badge badge-skill">Linux</span> <span class="badge badge-skill">Git</span> <span class="badge badge-skill">LaTeX</span>
    </div>
  </section>

  <section>
    <h2>Education</h2>
    <div class="custom-card" style="background: var(--bg-light); border: none;">
      <div class="card-top">
        <strong style="font-size: 1.1em;">Tongji University</strong>
        <span style="color: var(--text-muted);">2023 – 2027 (Expected)</span>
      </div>
      <div>B.S. in Computer Science and Technology (Elite Program)</div>
      
      <div style="margin-top: 15px; font-weight: 600; font-size: 0.9em; color: var(--primary);">Selected Coursework:</div>
      <div class="course-grid">
        <div style="font-size: 0.9em;">• Mathematical Analysis</div>
        <div style="font-size: 0.9em;">• Linear Algebra</div>
        <div style="font-size: 0.9em;">• Probability & Statistics</div>
        <div style="font-size: 0.9em;">• Data Structures & Algorithms</div>
        <div style="font-size: 0.9em;">• Pattern Recognition</div>
        <div style="font-size: 0.9em;">• Database Systems</div>
      </div>
    </div>
  </section>

  <section>
    <h2>Contact</h2>
    <p>📧 Email: <a href="mailto:jerry.zryang@hotmail.com" style="color: var(--accent); font-weight: 500;">jerry.zryang@hotmail.com</a></p>
  </section>

</div>
