<!-- TOP HEADER: Web corners and animated glowing title -->
<div align="center">
  <svg width="100%" height="180" viewBox="0 0 800 180" fill="none" xmlns="http://www.w3.org/2000/svg">
    <style>
      .web-corner {
        stroke: #cc0000;
        stroke-width: 0.8;
        opacity: 0.18;
      }
      .eyebrow {
        font-family: 'Share Tech Mono', monospace;
        font-size: 12px;
        fill: #cc0000;
        letter-spacing: 5px;
        text-anchor: middle;
      }
      .title {
        font-family: 'Bebas Neue', 'Impact', sans-serif;
        font-size: 52px;
        fill: #ffffff;
        text-anchor: middle;
        letter-spacing: 3px;
        font-weight: bold;
        filter: drop-shadow(0 0 8px #cc0000);
        animation: pulse 2.5s ease-in-out infinite;
      }
      .subtitle {
        font-family: 'Share Tech Mono', monospace;
        font-size: 13px;
        fill: #880000;
        letter-spacing: 3px;
        text-anchor: middle;
      }
      @keyframes pulse {
        0%, 100% { fill: #ffffff; filter: drop-shadow(0 0 8px #cc0000) drop-shadow(0 0 20px #880000); }
        50% { fill: #ff4444; filter: drop-shadow(0 0 12px #ff0000) drop-shadow(0 0 30px #cc0000); }
      }
    </style>

    <!-- Left Web Corner -->
    <g class="web-corner">
      <line x1="0" y1="0" x2="120" y2="120"/>
      <line x1="0" y1="0" x2="80" y2="120"/>
      <line x1="0" y1="0" x2="40" y2="120"/>
      <line x1="0" y1="0" x2="120" y2="80"/>
      <line x1="0" y1="0" x2="120" y2="40"/>
      <path d="M0 20 Q10 10 20 0"/>
      <path d="M0 40 Q20 20 40 0"/>
      <path d="M0 60 Q30 30 60 0"/>
      <path d="M0 80 Q40 40 80 0"/>
      <path d="M0 100 Q50 50 100 0"/>
      <path d="M0 120 Q60 60 120 0"/>
    </g>

    <!-- Right Web Corner -->
    <g class="web-corner" transform="translate(800, 0) scale(-1, 1)">
      <line x1="0" y1="0" x2="120" y2="120"/>
      <line x1="0" y1="0" x2="80" y2="120"/>
      <line x1="0" y1="0" x2="40" y2="120"/>
      <line x1="0" y1="0" x2="120" y2="80"/>
      <line x1="0" y1="0" x2="120" y2="40"/>
      <path d="M0 20 Q10 10 20 0"/>
      <path d="M0 40 Q20 20 40 0"/>
      <path d="M0 60 Q30 30 60 0"/>
      <path d="M0 80 Q40 40 80 0"/>
      <path d="M0 100 Q50 50 100 0"/>
      <path d="M0 120 Q60 60 120 0"/>
    </g>

    <!-- Header Text Content -->
    <text x="400" y="55" class="eyebrow">⬡ YOUR FRIENDLY NEIGHBORHOOD DEV ⬡</text>
    <text x="400" y="115" class="title">WELCOME TO MY GITHUB</text>
    <text x="400" y="150" class="subtitle">// ddd047 · WITH GREAT CODE COMES GREAT RESPONSIBILITY //</text>
  </svg>
</div>

<!-- WEB DIVIDER -->
<div align="center">
  <svg width="100%" height="24" viewBox="0 0 800 24" fill="none" xmlns="http://www.w3.org/2000/svg">
    <line x1="0" y1="12" x2="380" y2="12" stroke="#cc0000" stroke-width="0.8" opacity="0.6"/>
    <polygon points="400,4 412,12 400,20 388,12" fill="#cc0000" opacity="0.9"/>
    <line x1="420" y1="12" x2="800" y2="12" stroke="#cc0000" stroke-width="0.8" opacity="0.6"/>
  </svg>
</div>

---

### 〉 ABOUT.ME

```bash
ddd047@spidey-lab:~$ ./bio.sh
```

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Share+Tech+Mono&size=16&duration=4000&pause=1000&color=E8E0F0&width=750&lines=🤖+AI%2FML+enthusiast+—+I+spin+neural+networks+like+Spidey+spins+webs.;🎓+B.Tech+student+with+a+sixth+sense+for+machine+learning.;🧠+Sharp+instincts+for+patterns+in+chaotic+data.;🔬+Deep+diving+into+NLP%2C+computer+vision+%26+deep+learning.;🌆+By+day+a+student%2C+by+night+training+models+on+my+laptop." alt="bio typing" />
</div>

---

### 〉 PROFILE.STATS

<div align="center">
  <svg width="100%" height="150" viewBox="0 0 800 150" fill="none" xmlns="http://www.w3.org/2000/svg">
    <style>
      .card {
        transition: transform 0.3s, stroke 0.3s;
        cursor: pointer;
      }
      .card:hover {
        transform: translateY(-5px);
        stroke: #cc0000;
      }
      .card-val {
        font-family: 'Bebas Neue', 'Impact', sans-serif;
        font-size: 22px;
        fill: #cc0000;
        text-anchor: middle;
        font-weight: bold;
      }
      .card-lbl {
        font-family: 'Share Tech Mono', monospace;
        font-size: 11px;
        fill: #660022;
        text-anchor: middle;
        letter-spacing: 2px;
      }
      .card-tip {
        font-family: 'Share Tech Mono', monospace;
        font-size: 10px;
        fill: #ff7777;
        text-anchor: middle;
        opacity: 0.8;
      }
    </style>

    <!-- Card 1: AI/ML -->
    <g class="card" transform="translate(0, 5)">
      <rect x="10" y="5" width="240" height="130" rx="10" fill="#0f0008" stroke="#2a0015" stroke-width="1.5"/>
      <text x="130" y="45" font-size="30" text-anchor="middle">🤖</text>
      <text x="130" y="80" class="card-val">AI/ML</text>
      <text x="130" y="100" class="card-lbl">ENTHUSIAST</text>
      <text x="130" y="118" class="card-tip">Spinning neural webs</text>
    </g>

    <!-- Card 2: B.Tech -->
    <g class="card" transform="translate(270, 5)">
      <rect x="10" y="5" width="240" height="130" rx="10" fill="#0f0008" stroke="#2a0015" stroke-width="1.5"/>
      <text x="130" y="45" font-size="30" text-anchor="middle">🎓</text>
      <text x="130" y="80" class="card-val">B.TECH</text>
      <text x="130" y="100" class="card-lbl">STUDENT</text>
      <text x="130" y="118" class="card-tip">Climbing the academic wall</text>
    </g>

    <!-- Card 3: Dedication -->
    <g class="card" transform="translate(540, 5)">
      <rect x="10" y="5" width="240" height="130" rx="10" fill="#0f0008" stroke="#2a0015" stroke-width="1.5"/>
      <text x="130" y="45" font-size="30" text-anchor="middle">🔴</text>
      <text x="130" y="80" class="card-val">100%</text>
      <text x="130" y="100" class="card-lbl">DEDICATION</text>
      <text x="130" y="118" class="card-tip">Spider-sense for bugs</text>
    </g>
  </svg>
</div>

---

### 〉 SKILLS.WEB

<div align="center">
  <svg width="100%" height="260" viewBox="0 0 800 260" fill="none" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="bar-grad" x1="0" y1="0" x2="1" y2="0">
        <stop offset="0%" stop-color="#440000" />
        <stop offset="100%" stop-color="#cc0000" />
      </linearGradient>
    </defs>
    <style>
      .skill-name {
        font-family: 'Share Tech Mono', monospace;
        font-size: 14px;
        fill: #cc6677;
      }
      .skill-pct {
        font-family: 'Share Tech Mono', monospace;
        font-size: 14px;
        fill: #cc0000;
        text-anchor: end;
      }
      .bar-fill {
        animation: fill-grow 1.5s ease-out forwards;
        transform-origin: left;
      }
      @keyframes fill-grow {
        from { transform: scaleX(0); }
        to { transform: scaleX(1); }
      }
    </style>
    <!-- Skill 1: Machine Learning (82%) -->
    <text x="10" y="25" class="skill-name">Machine Learning</text>
    <rect x="180" y="14" width="550" height="12" rx="6" fill="#1a0010" stroke="#2a0015" stroke-width="1"/>
    <rect x="180" y="14" width="451" height="12" rx="6" fill="url(#bar-grad)" class="bar-fill"/>
    <text x="780" y="25" class="skill-pct">82%</text>

    <!-- Skill 2: Python (88%) -->
    <text x="10" y="65" class="skill-name">Python</text>
    <rect x="180" y="54" width="550" height="12" rx="6" fill="#1a0010" stroke="#2a0015" stroke-width="1"/>
    <rect x="180" y="54" width="484" height="12" rx="6" fill="url(#bar-grad)" class="bar-fill"/>
    <text x="780" y="65" class="skill-pct">88%</text>

    <!-- Skill 3: Deep Learning (75%) -->
    <text x="10" y="105" class="skill-name">Deep Learning</text>
    <rect x="180" y="94" width="550" height="12" rx="6" fill="#1a0010" stroke="#2a0015" stroke-width="1"/>
    <rect x="180" y="94" width="412.5" height="12" rx="6" fill="url(#bar-grad)" class="bar-fill"/>
    <text x="780" y="105" class="skill-pct">75%</text>

    <!-- Skill 4: Data Analysis (79%) -->
    <text x="10" y="145" class="skill-name">Data Analysis</text>
    <rect x="180" y="134" width="550" height="12" rx="6" fill="#1a0010" stroke="#2a0015" stroke-width="1"/>
    <rect x="180" y="134" width="434.5" height="12" rx="6" fill="url(#bar-grad)" class="bar-fill"/>
    <text x="780" y="145" class="skill-pct">79%</text>

    <!-- Skill 5: NLP / LLMs (70%) -->
    <text x="10" y="185" class="skill-name">NLP / LLMs</text>
    <rect x="180" y="174" width="550" height="12" rx="6" fill="#1a0010" stroke="#2a0015" stroke-width="1"/>
    <rect x="180" y="174" width="385" height="12" rx="6" fill="url(#bar-grad)" class="bar-fill"/>
    <text x="780" y="185" class="skill-pct">70%</text>

    <!-- Skill 6: Math & Stats (73%) -->
    <text x="10" y="225" class="skill-name">Math & Stats</text>
    <rect x="180" y="214" width="550" height="12" rx="6" fill="#1a0010" stroke="#2a0015" stroke-width="1"/>
    <rect x="180" y="214" width="401.5" height="12" rx="6" fill="url(#bar-grad)" class="bar-fill"/>
    <text x="780" y="225" class="skill-pct">73%</text>
  </svg>
</div>

---

### 〉 GITHUB.STATS

<div align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=ddd047&show_icons=true&theme=dark&bg_color=0a0005&title_color=cc0000&icon_color=cc0000&text_color=e8e0f0&border_color=2a0015&hide_border=false&count_private=true" />
  &nbsp;&nbsp;
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ddd047&layout=compact&theme=dark&bg_color=0a0005&title_color=cc0000&text_color=e8e0f0&border_color=2a0015" />
</div>

<br>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=ddd047&theme=dark&background=0a0005&ring=cc0000&fire=ff4444&currStreakLabel=cc0000&sideLabels=880000&border=2a0015&dates=888888" />
</div>

---

### 〉 LAB.ENVIRONMENT

```python
ddd047 = {
    "role"       : "AI/ML Enthusiast · B.Tech Student",
    "learning"   : ["Deep Learning", "NLP", "LLMs", "Computer Vision"],
    "building"   : "Something that will stick to walls (metaphorically)",
    "ask_me_about": ["Machine Learning", "Python", "AI Research"],
    "spider_sense": "Tingling whenever there's an underfitting model nearby"
}
```

---

### 〉 SOCIALS.WEB (INTERACTIVE)

<div align="center">
  <svg width="100%" height="50" viewBox="0 0 800 50" fill="none" xmlns="http://www.w3.org/2000/svg">
    <style>
      .btn {
        transition: all 0.3s;
        cursor: pointer;
      }
      .btn:hover rect {
        fill: rgba(204, 0, 0, 0.15);
        stroke: #ff4444;
      }
      .btn:hover text {
        fill: #ffffff;
      }
      .btn-text {
        font-family: 'Share Tech Mono', monospace;
        font-size: 13px;
        fill: #cc0000;
      }
    </style>

    <!-- Button 1: GitHub -->
    <a href="https://github.com/ddd047" target="_blank" class="btn">
      <rect x="25" y="7" width="130" height="36" rx="18" stroke="#cc0000" stroke-width="1.5" fill="none"/>
      <text x="90" y="29" text-anchor="middle" class="btn-text">🕸 GitHub</text>
    </a>

    <!-- Button 2: LinkedIn -->
    <a href="https://www.linkedin.com/in/himanshu-dhiman-b30611321/" target="_blank" class="btn">
      <rect x="180" y="7" width="130" height="36" rx="18" stroke="#cc0000" stroke-width="1.5" fill="none"/>
      <text x="245" y="29" text-anchor="middle" class="btn-text">💼 LinkedIn</text>
    </a>

    <!-- Button 3: Twitter/X -->
    <a href="https://twitter.com" target="_blank" class="btn">
      <rect x="335" y="7" width="130" height="36" rx="18" stroke="#cc0000" stroke-width="1.5" fill="none"/>
      <text x="400" y="29" text-anchor="middle" class="btn-text">🐦 Twitter/X</text>
    </a>

    <!-- Button 4: Email -->
    <a href="mailto:himanshu.hry26@gmail.com" class="btn">
      <rect x="490" y="7" width="130" height="36" rx="18" stroke="#cc0000" stroke-width="1.5" fill="none"/>
      <text x="555" y="29" text-anchor="middle" class="btn-text">📧 Email</text>
    </a>

    <!-- Button 5: Blog -->
    <a href="#" class="btn">
      <rect x="645" y="7" width="130" height="36" rx="18" stroke="#cc0000" stroke-width="1.5" fill="none"/>
      <text x="710" y="29" text-anchor="middle" class="btn-text">📝 Blog</text>
    </a>
  </svg>
</div>

---

### 〉 CONTRIBUTION.WEB

<div align="center">
  <a href="https://github.com/ddd047" target="_blank">
    <img src="https://github-readme-activity-graph.vercel.app/graph?username=ddd047&bg_color=0a0005&color=cc0000&line=880000&point=ff4444&area=true&hide_border=false&border_color=2a0015" alt="Activity Graph" />
  </a>
</div>

---

<!-- FOOTER WEB -->
<div align="center">
  <svg width="100%" height="40" viewBox="0 0 800 40" xmlns="http://www.w3.org/2000/svg">
    <g stroke="#cc0000" stroke-width="0.7" fill="none" opacity="0.35">
      <line x1="400" y1="0" x2="0"   y2="40"/>
      <line x1="400" y1="0" x2="150" y2="40"/>
      <line x1="400" y1="0" x2="300" y2="40"/>
      <line x1="400" y1="0" x2="400" y2="40"/>
      <line x1="400" y1="0" x2="500" y2="40"/>
      <line x1="400" y1="0" x2="650" y2="40"/>
      <line x1="400" y1="0" x2="800" y2="40"/>
      <path d="M0 15 Q200 5 400 15 Q600 25 800 15"/>
      <path d="M0 28 Q200 18 400 28 Q600 38 800 28"/>
    </g>
    <circle cx="400" cy="2" r="3" fill="#cc0000" opacity="0.8"/>
  </svg>

  <br>

  <img src="https://readme-typing-svg.demolab.com?font=Share+Tech+Mono&size=12&duration=3000&pause=1000&color=cc0000&center=true&vCenter=true&width=500&lines=🕷+ddd047+·+swinging+through+code+since+day+one+🕷" alt="footer text" />

  <br><br>

  <img src="https://komarev.com/ghpvc/?username=ddd047&style=for-the-badge&color=cc0000&labelColor=0a0005&label=VISITORS" alt="Visitor Count" />
</div>
