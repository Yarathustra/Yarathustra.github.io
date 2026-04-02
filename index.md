---
layout: default
title: Zhangrui Yang (杨章睿) | Tongji University
---

<div style="display:flex; align-items:flex-start; gap:36px; margin-bottom:40px;">

<div style="flex:1;" markdown="1">
<table>
<tr>

<td width="70%">

<h2>Zhangrui Yang (杨章睿)</h2>

Undergraduate Researcher<br>
Computer Science and Technology (Elite Program)<br>
<a href="https://ghc.tongji.edu.cn/">Guohao College</a>, Tongji University<br><br>

Email: <a href="mailto:jerry.zryang@hotmail.com">jerry.zryang@hotmail.com</a><br>
<a href="https://github.com/Yarathustra">GitHub</a> /
<a href="https://scholar.google.com/citations?user=1io0foEAAAAJ">Google Scholar</a>

</td>

<td width="30%">
<img src="assets/images/profile.jpg" width="180" style="border-radius:8px;">
</td>

</tr>
</table>
---
<style>
  /* 基础样式与字体 */
  :root {
    --primary-color: #2c3e50;
    --accent-color: #007bff;
    --text-muted: #666;
    --bg-light: #f8f9fa;
    --border-color: #e9ecef;
  }
  
  body {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
    line-height: 1.6;
    color: var(--primary-color);
    max-width: 850px;
    margin: 40px auto;
    padding: 0 20px;
  }

  h2 {
    border-bottom: 2px solid var(--border-color);
    padding-bottom: 8px;
    margin-top: 40px;
    font-weight: 700;
  }

  /* About 部分强化 */
  .intro-text { font-size: 1.1em; color: #34495e; }
  .highlight { color: var(--accent-color); font-weight: 600; }

  /* 卡片式容器 */
  .card {
    border: 1px solid var(--border-color);
    border-radius: 8px;
    padding: 18px;
    margin-bottom: 20px;
    transition: transform 0.2s;
  }
  .card:hover { transform: translateY(-2px); border-color: #ccc; }

  .card-header { display: flex; justify-content: space-between; align-items: baseline; }
  .card-title { font-weight: bold; font-size: 1.1em; }
  .card-date { color: var(--text-muted); font-size: 0.9em; }

  /* 标签/勋章样式 */
  .badge {
    display: inline-block;
    padding: 2px 10px;
    font-size: 0.85em;
    border-radius: 20px;
    margin-right: 5px;
    margin-top: 5px;
  }
  .badge-rank { background: #fff3cd; color: #856404; border: 1px solid #ffeeba; font-weight: 600; }
  .badge-skill { background: #eef2f7; color: #495057; border: 1px solid #d1d9e6; }
  .badge-honor { background: #d4edda; color: #155724; }

  /* 列表样式优化 */
  .honor-list { list-style: none; padding-left: 0; }
  .honor-item { margin-bottom: 10px; display: flex; align-items: center; }
  .honor-item::before { content: "🏆"; margin-right: 10px; }

  /* 课程列表展示 */
  .course-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(180px, 1fr));
    gap: 10px;
    margin-top: 10px;
  }
  .course-item { font-size: 0.9em; color: #555; }
</style>

<section>
  <h2>About</h2>
  <p class="intro-text">
    I am an undergraduate researcher in the <span class="highlight">Elite Program</span> at Tongji University. 
    My research lies at the intersection of <span class="highlight">vision-language models</span> and <span class="highlight">spatial reasoning</span>.
  </p>
  <p>
    Recent large multimodal models demonstrate impressive visual reasoning performance, yet emerging evidence suggests that many spatial reasoning capabilities arise from dataset-level statistical regularities rather than structured geometric understanding. My work investigates how multimodal models represent spatial structure and how evaluation protocols can distinguish genuine spatial reasoning from shortcut learning.
  </p>
</section>

---

<style>
  .pub-item { margin-bottom: 25px; line-height: 1.6; }
  .pub-title { font-weight: bold; font-size: 1.1em; color: #2c3e50; display: block; }
  .pub-authors { color: #555; }
  .pub-venue { font-style: italic; color: #444; }
  .badge {
    display: inline-block;
    padding: 2px 8px;
    font-size: 0.8em;
    color: #fff;
    background-color: #007bff;
    border-radius: 4px;
    text-decoration: none;
    margin-top: 5px;
    transition: 0.3s;
  }
  .badge:hover { background-color: #0056b3; }
  .badge-arxiv { background-color: #B31B1B; } /* arXiv 红色 */
  .badge-code { background-color: #24292e; }  /* GitHub 黑色 */
  .under-review { color: #e67e22; font-weight: bold; font-size: 0.9em; }
</style>

<h2>Publications</h2>

<div class="pub-item">
  <span class="pub-title">Enhancing Adversarial Attacks with Decision Boundary Information</span>
  <span class="pub-authors"><strong>Zhangrui Yang</strong>, Shengming Yuan, Bo Wang, Yaya Cheng, Pengpeng Zeng, Zheng Wang, Xuanhan Wang, Jingkuan Song</span><br>
  <span class="pub-venue">Information Fusion, 2026</span> <span class="under-review">[Under Review]</span><br>
  <a href="https://github.com/Yarathustra/BF-Attack" class="badge badge-code">Code</a>
</div>

<div class="pub-item">
  <span class="pub-title">Pseudo-Label Refinement for Robust Wheat Head Segmentation via Two-Stage Hybrid Training</span>
  <span class="pub-authors">Jiahao Jiang*, <strong>Zhangrui Yang</strong>*, Xuanhan Wang, Jingkuan Song</span><br>
  <span class="pub-venue">CVPPA Workshop, ICCV 2025</span><br>
  <a href="https://arxiv.org/abs/2512.11874" class="badge badge-arxiv">arXiv</a>
</div>

<p style="font-size: 0.8em; color: #888;">* Equal contribution.</p>
---

<section>
  <h2>Research Experience</h2>
  <div class="card">
    <div class="card-header">
      <span class="card-title">Global Wheat Full Semantic Segmentation (GWFSS)</span>
      <span class="badge badge-rank">Global Rank #2</span>
    </div>
    <p style="margin: 10px 0 0 0; color: #555;">
      Developed a pseudo-label refinement framework for wheat head segmentation under limited annotation settings. The work focuses on improving pseudo-label reliability through iterative teacher–student training and systematic ablation analysis.
    </p>
  </div>
</section>
<section>
  <h2>Selected Honors</h2>
  <ul class="honor-list">
    <li class="honor-item">Global 2nd Place — Global Wheat Full Semantic Segmentation Competition</li>
    <li class="honor-item">National First Prize — iCAN AI Innovation Competition (SurgeryMind)</li>
    <li class="honor-item">Shanghai Second Prize — National Mathematical Modeling Contest</li>
    <li class="honor-item">Academic Scholarship — Guohao College, Tongji University</li>
  </ul>
</section>

<section>
  <h2>Selected Projects</h2>
  <div class="card">
    <div class="card-header">
      <span class="card-title">SurgeryMind — Multimodal Surgical Assistant</span>
    </div>
    <p style="margin: 10px 0 0 0; color: #555;">
      Designed a multimodal surgical interaction system integrating speech recognition, gesture-based control, and web-based visualization. The system enables surgeons to interact with imaging systems through natural multimodal commands during operations.
    </p>
  </div>
</section>

<section>
  <h2>Technical Skills</h2>
  <div style="margin-bottom: 10px;">
    <strong>Programming:</strong> 
    <span class="badge badge-skill">Python</span> <span class="badge badge-skill">C++</span> <span class="badge badge-skill">Verilog HDL</span> <span class="badge badge-skill">SQL</span>
  </div>
  <div style="margin-bottom: 10px;">
    <strong>Frameworks:</strong> <span class="badge badge-skill">PyTorch</span>
  </div>
  <div>
    <strong>Tools:</strong> <span class="badge badge-skill">Linux</span> <span class="badge badge-skill">Git</span> <span class="badge badge-skill">LaTeX</span>
  </div>
</section>

<section>
  <h2>Education</h2>
  <div class="card" style="border: none; background: var(--bg-light);">
    <div class="card-header">
      <span class="card-title">Tongji University</span>
      <span class="card-date">2023 – 2027 (Expected)</span>
    </div>
    <div>B.S. in Computer Science and Technology (Elite Program)</div>
    <div style="margin-top: 15px; font-weight: 600; font-size: 0.9em;">Selected Coursework:</div>
    <div class="course-grid">
      <div class="course-item">• Mathematical Analysis</div>
      <div class="course-item">• Linear Algebra</div>
      <div class="course-item">• Probability & Statistics</div>
      <div class="course-item">• Data Structures & Algorithms</div>
      <div class="course-item">• Pattern Recognition</div>
      <div class="course-item">• Database Systems</div>
    </div>
  </div>
</section>

<section>
  <h2>Contact</h2>
  <p>📧 Email: <a href="mailto:jerry.zryang@hotmail.com" style="color: var(--accent-color); text-decoration: none;">jerry.zryang@hotmail.com</a></p>
</section>
