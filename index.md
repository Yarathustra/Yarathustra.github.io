---
layout: default
title: Zhangrui Yang (杨章睿) | Tongji University
---

<style>
  /* 1. 统一全局变量 */
  :root {
    --primary-color: #2c3e50;
    --accent-color: #007bff;
    --text-muted: #666;
    --bg-light: #f8f9fa;
    --border-color: #e9ecef;
    --heading-color: #1a2a3a;
  }

  body {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
    line-height: 1.6;
    color: var(--primary-color);
    max-width: 850px;
    margin: 40px auto;
    padding: 0 20px;
  }

  /* 2. 顶部简介区域 (替换掉原本的 table) */
  .profile-header {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    gap: 40px;
    margin-bottom: 40px;
    flex-wrap: wrap; /* 适配手机屏幕 */
  }

  .profile-bio { flex: 1; min-width: 300px; }
  
  .profile-bio h1 { 
    margin-top: 0; 
    font-size: 2.2em; 
    color: var(--heading-color); 
  }

  .profile-photo {
    width: 180px;
    border-radius: 12px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  }

  .contact-links {
    margin-top: 15px;
    display: flex;
    gap: 12px;
    flex-wrap: wrap;
  }

  .contact-links a {
    text-decoration: none;
    color: var(--accent-color);
    font-weight: 500;
  }

  .contact-links a:hover { text-decoration: underline; }

  /* 3. 通用章节与卡片 */
  h2 {
    border-bottom: 2px solid var(--border-color);
    padding-bottom: 8px;
    margin-top: 50px;
    font-weight: 700;
    color: var(--heading-color);
  }

  .intro-text { font-size: 1.1em; color: #34495e; }
  .highlight { color: var(--accent-color); font-weight: 600; }

  .card {
    border: 1px solid var(--border-color);
    border-radius: 10px;
    padding: 20px;
    margin-bottom: 20px;
    transition: all 0.3s ease;
  }
  .card:hover { 
    transform: translateY(-3px); 
    box-shadow: 0 6px 15px rgba(0,0,0,0.05);
    border-color: #cbd5e0; 
  }

  .card-header { display: flex; justify-content: space-between; align-items: baseline; }
  .card-title { font-weight: bold; font-size: 1.15em; color: var(--heading-color); }
  .card-date { color: var(--text-muted); font-size: 0.9em; }

  /* 4. 论文列表样式 */
  .pub-item { margin-bottom: 30px; }
  .pub-title { font-weight: bold; font-size: 1.1em; color: var(--heading-color); display: block; margin-bottom: 4px; }
  .pub-authors { color: #555; font-size: 0.95em; }
  .pub-venue { font-style: italic; color: #444; font-size: 0.95em; }
  .under-review { color: #e67e22; font-weight: bold; font-size: 0.85em; margin-left: 5px; }

  /* 5. 标签与勋章 (Pills) */
  .badge {
    display: inline-block;
    padding: 3px 12px;
    font-size: 0.8em;
    border-radius: 6px;
    text-decoration: none;
    margin-top: 8px;
    margin-right: 6px;
    transition: 0.2s;
  }
  
  .badge-link { background-color: var(--accent-color); color: #fff !important; }
  .badge-link:hover { opacity: 0.85; }
  .badge-arxiv { background-color: #B31B1B; color: #fff !important; }
  .badge-code { background-color: #24292e; color: #fff !important; }
  
  .badge-rank { background: #fff3cd; color: #856404; border: 1px solid #ffeeba; font-weight: 600; border-radius: 20px; }
  .badge-skill { background: #eef2f7; color: #495057; border: 1px solid #d1d9e6; border-radius: 4px; }

  /* 6. 列表与网格 */
  .honor-list { list-style: none; padding-left: 0; }
  .honor-item { margin-bottom: 12px; display: flex; align-items: center; }
  .honor-item::before { content: "🏆"; margin-right: 12px; font-size: 1.1em; }

  .course-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
    gap: 12px;
    margin-top: 10px;
  }
  .course-item { font-size: 0.9em; color: #555; display: flex; align-items: center; }
  .course-item::before { content: "▹"; margin-right: 8px; color: var(--accent-color); font-weight: bold; }
</style>

<header class="profile-header">
  <div class="profile-bio">
    <h1>Zhangrui Yang (杨章睿)</h1>
    <p>
      Undergraduate Researcher<br>
      Computer Science and Technology (Elite Program)<br>
      <a href="https://ghc.tongji.edu.cn/" target="_blank" style="color: inherit;">Guohao College</a>, Tongji University
    </p>
    
    <div class="contact-links">
      <a href="mailto:jerry.zryang@hotmail.com">📧 Email</a>
      <a href="https://github.com/Yarathustra" target="_blank">🐙 GitHub</a>
      <a href="https://scholar.google.com/citations?user=1io0foEAAAAJ" target="_blank">🎓 Google Scholar</a>
    </div>
  </div>
  <img src="assets/images/profile.jpg" alt="Zhangrui Yang" class="profile-photo">
</header>

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

<section>
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
  
  <p style="font-size: 0.85em; color: var(--text-muted); margin-top: -10px;">* Equal contribution.</p>
</section>

<section>
  <h2>Research Experience</h2>
  <div class="card">
    <div class="card-header">
      <span class="card-title">Global Wheat Full Semantic Segmentation (GWFSS)</span>
      <span class="badge badge-rank">Global Rank #2</span>
    </div>
    <p style="margin-top: 10px; color: #555;">
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
  <div class="card" style="border: none; background: var(--bg-light);">
    <div class="card-header">
      <span class="card-title">Tongji University</span>
      <span class="card-date">2023 – 2027 (Expected)</span>
    </div>
    <div style="margin-bottom: 15px;">B.S. in Computer Science and Technology (Elite Program)</div>
    
    <div style="font-weight: 600; font-size: 0.9em; border-top: 1px solid #ddd; padding-top: 10px;">Selected Coursework:</div>
    <div class="course-grid">
      <div class="course-item">Mathematical Analysis</div>
      <div class="course-item">Linear Algebra</div>
      <div class="course-item">Probability & Statistics</div>
      <div class="course-item">Data Structures & Algorithms</div>
      <div class="course-item">Pattern Recognition</div>
      <div class="course-item">Database Systems</div>
    </div>
  </div>
</section>

<section>
  <h2>Contact</h2>
  <p>📧 Email: <a href="mailto:jerry.zryang@hotmail.com" style="color: var(--accent-color); text-decoration: none; font-weight: 500;">jerry.zryang@hotmail.com</a></p>
</section>
