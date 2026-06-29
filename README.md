<style>
@import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Share+Tech+Mono&family=Rajdhani:wght@400;600&display=swap');
*{margin:0;padding:0;box-sizing:border-box}
.sp-wrap{background:#0a0005;font-family:'Rajdhani',sans-serif;color:#e8e0f0;border-radius:12px;padding:2rem 1.5rem;position:relative;overflow:hidden;border:1px solid #2a0a20}
.web-corner{position:absolute;opacity:0.18;pointer-events:none}
.web-tl{top:0;left:0}
.web-tr{top:0;right:0;transform:scaleX(-1)}
.sp-header{text-align:center;padding:1.5rem 0 1rem;position:relative}
.sp-eyebrow{font-family:'Share Tech Mono',monospace;font-size:0.72rem;color:#cc0000;letter-spacing:5px;text-transform:uppercase;margin-bottom:0.8rem}
.sp-title{font-family:'Bebas Neue',cursive;font-size:3.2rem;letter-spacing:3px;line-height:1;color:#e8e0f0;animation:spShine 2.5s ease-in-out infinite}
@keyframes spShine{0%,100%{color:#ffffff;text-shadow:0 0 8px #cc0000,0 0 20px #880000}50%{color:#ff4444;text-shadow:0 0 12px #ff0000,0 0 30px #cc0000}}
.sp-sub{font-family:'Share Tech Mono',monospace;font-size:0.75rem;color:#880000;letter-spacing:4px;margin-top:4px;text-transform:uppercase}
.sp-divider{width:100%;height:1px;background:#1a0010;margin:1.2rem 0;position:relative;display:flex;align-items:center;justify-content:center}
.sp-divider::before,.sp-divider::after{content:'';flex:1;height:1px;background:linear-gradient(90deg,transparent,#cc0000)}
.sp-divider::before{margin-right:10px}
.sp-divider::after{margin-left:10px}
.sp-diamond{width:8px;height:8px;background:#cc0000;transform:rotate(45deg);flex-shrink:0}
.sp-section-label{font-family:'Share Tech Mono',monospace;font-size:0.7rem;color:#cc0000;letter-spacing:4px;text-transform:uppercase;margin-bottom:0.8rem;display:flex;align-items:center;gap:8px}
.sp-section-label::after{content:'';flex:1;height:1px;background:linear-gradient(90deg,#cc000033,transparent)}
.sp-terminal{background:#0f0008;border:1px solid #2a0015;border-radius:10px;padding:1.2rem;min-height:130px;position:relative}
.sp-terminal::before{content:'';position:absolute;top:0;left:0;right:0;height:2px;background:linear-gradient(90deg,#440000,#cc0000,#440000);animation:scanR 3s linear infinite}
@keyframes scanR{0%,100%{opacity:0.5}50%{opacity:1}}
.sp-prompt{font-family:'Share Tech Mono',monospace;font-size:0.75rem;color:#880000;margin-bottom:0.6rem}
.sp-prompt span{color:#cc0000}
#sp-type{font-size:0.95rem;color:#e8e0f0;line-height:1.7;min-height:3.2rem}
.sp-cursor{display:inline-block;width:2px;height:1em;background:#cc0000;vertical-align:text-bottom;margin-left:1px;animation:blink 0.7s infinite}
@keyframes blink{0%,100%{opacity:1}50%{opacity:0}}
.sp-dots{display:flex;gap:5px;margin-top:0.8rem;justify-content:flex-end}
.sp-dot{width:7px;height:7px;border-radius:50%;background:#2a0015;cursor:pointer;transition:background 0.3s}
.sp-dot.active{background:#cc0000}
.sp-stats{display:grid;grid-template-columns:repeat(3,1fr);gap:10px;margin:1.2rem 0}
.sp-stat{background:#0f0008;border:1px solid #2a0015;border-radius:10px;padding:0.9rem;text-align:center;cursor:pointer;transition:border-color 0.3s,transform 0.2s;position:relative;overflow:hidden}
.sp-stat:hover{border-color:#cc0000;transform:translateY(-3px)}
.sp-stat-ico{font-size:22px;margin-bottom:5px}
.sp-stat-val{font-family:'Bebas Neue',cursive;font-size:1.5rem;color:#cc0000;line-height:1}
.sp-stat-lbl{font-family:'Share Tech Mono',monospace;font-size:0.65rem;color:#660022;letter-spacing:2px;text-transform:uppercase}
.sp-stat-tip{position:absolute;bottom:0;left:0;right:0;background:rgba(204,0,0,0.15);color:#ff7777;font-size:0.68rem;padding:5px;opacity:0;transform:translateY(5px);transition:all 0.3s;font-family:'Share Tech Mono',monospace}
.sp-stat:hover .sp-stat-tip{opacity:1;transform:translateY(0)}
.sp-skills{margin:1.2rem 0}
.sp-skill-row{display:flex;align-items:center;gap:10px;margin-bottom:8px}
.sp-skill-name{font-family:'Share Tech Mono',monospace;font-size:0.75rem;color:#cc6677;width:120px;flex-shrink:0}
.sp-bar-bg{flex:1;height:7px;background:#1a0010;border-radius:4px;overflow:hidden;border:1px solid #2a0015}
.sp-bar-fill{height:100%;border-radius:4px;background:linear-gradient(90deg,#440000,#cc0000);width:0;transition:width 1.2s ease}
.sp-pct{font-family:'Share Tech Mono',monospace;font-size:0.72rem;color:#cc0000;width:30px;text-align:right}
.sp-socials{display:flex;gap:8px;flex-wrap:wrap;margin-top:1.2rem;justify-content:center}
.sp-btn{padding:6px 16px;border-radius:20px;font-family:'Share Tech Mono',monospace;font-size:0.73rem;letter-spacing:1px;cursor:pointer;border:1px solid #cc0000;color:#cc0000;background:transparent;text-decoration:none;transition:all 0.3s}
.sp-btn:hover{background:#cc000022}
.sp-footer{text-align:center;margin-top:1.5rem;padding-top:0.8rem;border-top:1px solid #1a0010;font-family:'Share Tech Mono',monospace;font-size:0.68rem;color:#440022;letter-spacing:2px}
</style>

<div class="sp-wrap">
  <svg class="web-corner web-tl" width="120" height="120" viewBox="0 0 120 120">
    <g stroke="#cc0000" stroke-width="0.8" fill="none">
      <line x1="0" y1="0" x2="120" y2="120"/><line x1="0" y1="0" x2="80" y2="120"/><line x1="0" y1="0" x2="40" y2="120"/><line x1="0" y1="0" x2="0" y2="120"/><line x1="0" y1="0" x2="120" y2="80"/><line x1="0" y1="0" x2="120" y2="40"/>
      <path d="M0 20 Q10 10 20 0"/><path d="M0 40 Q20 20 40 0"/><path d="M0 60 Q30 30 60 0"/><path d="M0 80 Q40 40 80 0"/><path d="M0 100 Q50 50 100 0"/><path d="M0 120 Q60 60 120 0"/><path d="M20 120 Q70 70 120 20"/><path d="M40 120 Q80 80 120 40"/><path d="M60 120 Q90 90 120 60"/><path d="M80 120 Q100 100 120 80"/>
    </g>
  </svg>
  <svg class="web-corner web-tr" width="120" height="120" viewBox="0 0 120 120">
    <g stroke="#cc0000" stroke-width="0.8" fill="none">
      <line x1="0" y1="0" x2="120" y2="120"/><line x1="0" y1="0" x2="80" y2="120"/><line x1="0" y1="0" x2="40" y2="120"/><line x1="0" y1="0" x2="0" y2="120"/><line x1="0" y1="0" x2="120" y2="80"/><line x1="0" y1="0" x2="120" y2="40"/>
      <path d="M0 20 Q10 10 20 0"/><path d="M0 40 Q20 20 40 0"/><path d="M0 60 Q30 30 60 0"/><path d="M0 80 Q40 40 80 0"/><path d="M0 100 Q50 50 100 0"/><path d="M0 120 Q60 60 120 0"/><path d="M20 120 Q70 70 120 20"/><path d="M40 120 Q80 80 120 40"/><path d="M60 120 Q90 90 120 60"/><path d="M80 120 Q100 100 120 80"/>
    </g>
  </svg>

  <div class="sp-header">
    <div class="sp-eyebrow">⬡ your friendly neighborhood dev ⬡</div>
    <div class="sp-title">Welcome to My GitHub</div>
    <div class="sp-sub">// ddd047 · with great code comes great responsibility //</div>
  </div>

  <div class="sp-divider"><div class="sp-diamond"></div></div>

  <div class="sp-section-label">〉 about.me</div>
  <div class="sp-terminal">
    <div class="sp-prompt"><span>ddd047</span>@spidey-lab:~$ ./bio.sh</div>
    <div id="sp-type"><span class="sp-cursor"></span></div>
    <div class="sp-dots" id="sp-dots"></div>
  </div>

  <div style="margin-top:1.2rem">
    <div class="sp-section-label">〉 profile.stats</div>
    <div class="sp-stats">
      <div class="sp-stat"><div class="sp-stat-ico">🤖</div><div class="sp-stat-val">AI/ML</div><div class="sp-stat-lbl">Enthusiast</div><div class="sp-stat-tip">Spinning neural webs</div></div>
      <div class="sp-stat"><div class="sp-stat-ico">🎓</div><div class="sp-stat-val">B.Tech</div><div class="sp-stat-lbl">Student</div><div class="sp-stat-tip">Climbing the academic wall</div></div>
      <div class="sp-stat"><div class="sp-stat-ico">🔴</div><div class="sp-stat-val">100%</div><div class="sp-stat-lbl">Dedication</div><div class="sp-stat-tip">Spider-sense for bugs</div></div>
    </div>
  </div>

  <div class="sp-skills">
    <div class="sp-section-label">〉 skills.web</div>
    <div id="sp-skills-container"></div>
  </div>

  <div class="sp-socials">
    <a class="sp-btn" href="#">🕸 GitHub</a>
    <a class="sp-btn" href="#">💼 LinkedIn</a>
    <a class="sp-btn" href="#">🐦 Twitter/X</a>
    <a class="sp-btn" href="#">📧 Email</a>
    <a class="sp-btn" href="#">📝 Blog</a>
  </div>

  <div class="sp-footer">🕷 ddd047 · swinging through code since day one 🕷</div>
</div>

<script>
const stmts = [
  "🤖 AI/ML enthusiast — I spin neural networks the way Spidey spins webs. Data goes in, intelligence comes out.",
  "🎓 B.Tech student with a sixth sense for machine learning. When the model predicts wrong, my spider-sense tingles.",
  "🧠 Sharp instincts for patterns in chaotic data. From raw datasets to deployable models — I swing through the whole pipeline.",
  "🔬 Deep diving into NLP, computer vision, and deep learning. My GitHub is the lab; every commit is a web shot.",
  "🌆 By day a student, by night training models on my laptop. The city never sleeps, and neither does my training loop."
];
let cur=0,ci=0,del=false;
const tel=document.getElementById('sp-type');
const dnel=document.getElementById('sp-dots');
stmts.forEach((_,i)=>{const d=document.createElement('div');d.className='sp-dot'+(i===0?' active':'');d.onclick=()=>{cur=i;ci=0;del=false;updateD()};dnel.appendChild(d)});
function updateD(){document.querySelectorAll('.sp-dot').forEach((d,i)=>d.classList.toggle('active',i===cur))}
function type(){const f=stmts[cur];tel.innerHTML=f.slice(0,ci)+'<span class="sp-cursor"></span>';if(!del&&ci<f.length){ci++;setTimeout(type,38)}else if(!del&&ci===f.length){setTimeout(()=>{del=true;type()},2600)}else if(del&&ci>0){ci--;setTimeout(type,16)}else{del=false;cur=(cur+1)%stmts.length;updateD();setTimeout(type,400)}}
type();
const skills=[{n:'Machine Learning',p:82},{n:'Python',p:88},{n:'Deep Learning',p:75},{n:'Data Analysis',p:79},{n:'NLP / LLMs',p:70},{n:'Math & Stats',p:73}];
const sc=document.getElementById('sp-skills-container');
skills.forEach(s=>{const r=document.createElement('div');r.className='sp-skill-row';r.innerHTML=`<div class="sp-skill-name">${s.n}</div><div class="sp-bar-bg"><div class="sp-bar-fill" data-p="${s.p}"></div></div><div class="sp-pct">${s.p}%</div>`;sc.appendChild(r)});
setTimeout(()=>document.querySelectorAll('.sp-bar-fill').forEach(b=>b.style.width=b.dataset.p+'%'),500);
</script>
