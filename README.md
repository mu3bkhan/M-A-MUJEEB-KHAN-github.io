<h1 align="center">Hi 👋, I'm Mohammed Abdul Mujeeb Khan</h1>
<h3 align="center">Computer Science Engineering student | Data Science • AI/ML • Cybersecurity</h3>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=2F80ED&center=true&vCenter=true&width=600&lines=Aspiring+Data+Scientist;Machine+Learning+%2F+AI+Enthusiast;Cybersecurity+%26+Ethical+Hacking;Python+Developer" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/YOUR-LINKEDIN-HANDLE"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:073mohammedabdulmujeebkhan@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <img src="https://img.shields.io/badge/Location-Hyderabad,%20India-informational?style=for-the-badge"/>
</p>

---

### 🧑‍💻 About me

Motivated and enthusiastic Computer Science Engineering student (4th year, ISL Engineering College) seeking entry-level opportunities to apply technical knowledge, analytical skills, and project experience while continuously growing as a professional.

- 🔭 Currently a final-year B.Tech CSE student
- 🌱 Learning: Data Science, Machine Learning, and applied Cybersecurity
- 💡 Interested in: Data Science, Artificial Intelligence, Machine Learning, Cybersecurity, Python
- 🎯 Career interests: Data Science Analyst, Data Analyst, Python Developer, ML/AI, Cybersecurity, entry-level tech roles
- 📫 Reach me: **073mohammedabdulmujeebkhan@gmail.com** | **9441714826**

---

### 🛠️ Technical skills

**Languages**
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

**Focus areas**
![Data Science](https://img.shields.io/badge/Data%20Science-blue?style=flat-square)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-orange?style=flat-square)
![Artificial Intelligence](https://img.shields.io/badge/Artificial%20Intelligence-green?style=flat-square)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-red?style=flat-square)
![Cybersecurity](https://img.shields.io/badge/Cybersecurity-black?style=flat-square)
![Ethical Hacking](https://img.shields.io/badge/Ethical%20Hacking-purple?style=flat-square)

---

### 🎓 Education

| Institution | Qualification | Details |
|---|---|---|
| ISL Engineering College | B.Tech – Computer Science and Engineering | 4th Year, Hyderabad |
| Sri Chaitanya Junior College | Intermediate | GPA: 7.5 |
| Nirmala High School | SSC | GPA: 9.7 |

---

### 🚀 Featured project

**Generating Chest X-Ray Progression of Pneumonia Using Conditional Cycle Generative Adversarial Networks**

- Designed a GAN / Conditional GAN framework to perform domain adaptation between normal and pneumonia chest X-ray images.
- Used a ResNet152-based classifier to evaluate domain change and generate intermediate images depicting pneumonia progression.
- Applied conditional vectors to the generator to simulate different stages of disease progression.
- Guided by **Heena Yasmin**, Assistant Professor, Dept. of CSE, ISL Engineering College.
- Team: Mohammed Abdul Mujeeb Khan, Syed Abdur Rahman Shafeeq, Muzammil Ali Mahmood Razi.

---

### 🏆 Internships & certifications

| Program | Provider | Duration |
|---|---|---|
| AI in Cyber Security – Virtual Internship | EduSkills Academy (AICTE / Ministry of Education) | 8 weeks, Jun–Aug 2026 |
| Ethical Hacking – Virtual Internship | EduSkills Academy (AICTE / Ministry of Education) | 8 weeks, Apr–Jun 2026 |
| Data Science Analyst Course | — | Data Science & Analytics fundamentals |

**AI in Cyber Security** covered machine learning for cybersecurity, ethical AI, data preprocessing, feature engineering, cyber attack vectors, Explainable AI (XAI), Generative AI, AI-powered intrusion detection, threat intelligence, SIEM, SOAR, cloud security, and vulnerability management.

**Ethical Hacking** covered fundamentals of ethical hacking, social engineering and human security risks, malware, network security, Kali Linux tools, vulnerability assessment, and basic web application penetration testing.

---

### 💪 Core strengths

Problem-solving · Analytical thinking · Willingness to learn · Teamwork and collaboration · Adaptability · Technical curiosity

---

### 📫 Get in touch

<p align="left">
  <a href="mailto:073mohammedabdulmujeebkhan@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/YOUR-LINKEDIN-HANDLE"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
</p>

<p align="center"><i>Thanks for stopping by — always open to connecting on Data Science, AI/ML, and Cybersecurity projects.</i></p>
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Circuit Background</title>
<style>
  :root{
    --bg-0:#080b10;
    --bg-1:#0d131c;
    --trace-dim:#1c2836;
    --trace-mid:#2c4a5e;
    --cyan:#4fd8c4;
    --cyan-bright:#9ff5e6;
    --amber:#e8a33d;
    --grid:#121a24;
  }
  *{margin:0;padding:0;box-sizing:border-box;}
  html,body{
    width:100%;height:100%;
    background:var(--bg-0);
    overflow:hidden;
    font-family:'SF Mono','JetBrains Mono',monospace;
  }
  .stage{
    position:relative;
    width:100vw;height:100vh;
    background:
      radial-gradient(ellipse 60% 50% at 22% 28%, rgba(79,216,196,0.10), transparent 60%),
      radial-gradient(ellipse 50% 45% at 82% 75%, rgba(232,163,61,0.07), transparent 60%),
      radial-gradient(ellipse 90% 90% at 50% 50%, var(--bg-1) 0%, var(--bg-0) 75%);
  }

  /* fine PCB grid */
  .grid-layer{
    position:absolute; inset:0;
    background-image:
      linear-gradient(var(--grid) 1px, transparent 1px),
      linear-gradient(90deg, var(--grid) 1px, transparent 1px);
    background-size: 42px 42px;
    opacity:0.35;
    mask-image: radial-gradient(ellipse 80% 80% at 50% 50%, black 40%, transparent 90%);
  }

  svg{position:absolute; inset:0; width:100%; height:100%;}

  .trace-dim{ stroke:var(--trace-dim); stroke-width:1.4; fill:none; }
  .trace-mid{ stroke:var(--trace-mid); stroke-width:1.6; fill:none; }
  .trace-glow{
    stroke:var(--cyan); stroke-width:1.8; fill:none;
    filter: drop-shadow(0 0 3px rgba(79,216,196,0.55));
    opacity:0.85;
  }
  .trace-amber{
    stroke:var(--amber); stroke-width:1.6; fill:none;
    filter: drop-shadow(0 0 3px rgba(232,163,61,0.5));
    opacity:0.7;
  }

  .pulse{
    stroke:var(--cyan-bright);
    stroke-width:2.4;
    fill:none;
    filter: drop-shadow(0 0 6px rgba(159,245,230,0.9));
    stroke-dasharray: 6 900;
    animation: travel 7s linear infinite;
  }
  .pulse.p2{ animation-duration: 9s; animation-delay: -3s; stroke:var(--amber); filter: drop-shadow(0 0 6px rgba(232,163,61,0.9));}
  .pulse.p3{ animation-duration: 11s; animation-delay: -6s; }

  @keyframes travel{
    0%{ stroke-dashoffset: 0; opacity:0; }
    5%{ opacity:1; }
    92%{ opacity:1; }
    100%{ stroke-dashoffset: -1400; opacity:0; }
  }

  .pad{ fill:var(--trace-mid); }
  .pad.lit{
    fill:var(--cyan);
    filter: drop-shadow(0 0 5px rgba(79,216,196,0.85));
    animation: blink 3.6s ease-in-out infinite;
  }
  .pad.lit.amber{ fill:var(--amber); filter: drop-shadow(0 0 5px rgba(232,163,61,0.85)); animation-duration:4.4s; }
  .pad.lit.slow{ animation-duration:5.2s; animation-delay:-1.5s; }

  @keyframes blink{
    0%,100%{ opacity:0.45; }
    50%{ opacity:1; }
  }

  .chip{
    fill:#0f161f;
    stroke:var(--trace-mid);
    stroke-width:1;
  }
  .chip-label{
    fill:#3a4d5c;
    font-size:8px;
    letter-spacing:1px;
  }

  .glyphs text{
    fill:var(--trace-dim);
    font-size:11px;
    opacity:0.5;
  }

  .vignette{
    position:absolute; inset:0;
    background: radial-gradient(ellipse 100% 100% at 50% 50%, transparent 55%, rgba(0,0,0,0.55) 100%);
    pointer-events:none;
  }

  .grain{
    position:absolute; inset:0;
    opacity:0.05;
    pointer-events:none;
    background-image:url("data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='120' height='120'><filter id='n'><feTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='2' stitchTiles='stitch'/></filter><rect width='100%25' height='100%25' filter='url(%23n)'/></svg>");
  }
</style>
</head>
<body>
<div class="stage">
  <div class="grid-layer"></div>

  <svg viewBox="0 0 1600 900" preserveAspectRatio="xMidYMid slice">
    <!-- === background dim trace network === -->
    <g class="trace-dim">
      <path d="M0,120 H260 V220 H520 V80 H900 V300 H1600" />
      <path d="M0,420 H180 V560 H460 V420 H760 V680 H1140 V500 H1600" />
      <path d="M0,760 H320 V860 H700 V760 H1050 V820 H1600" />
      <path d="M120,0 V180 H340 V0" />
      <path d="M520,900 V740 H700 V620" />
      <path d="M1220,0 V140 H1400 V0" />
      <path d="M1600,600 H1460 V400 H1300 V520" />
    </g>

    <!-- === mid detail traces === -->
    <g class="trace-mid">
      <path d="M60,60 H260 V140 H420" />
      <path d="M420,140 V300 H600" />
      <path d="M600,300 V220 H820 V340" />
      <path d="M980,60 V220 H1180 V80" />
      <path d="M1180,80 H1360" />
      <path d="M60,500 H240 V620 H400" />
      <path d="M400,620 V760 H620" />
      <path d="M820,560 H1020 V680 H1240" />
      <path d="M1240,680 V820 H1440" />
      <path d="M1440,820 V740" />
      <path d="M1520,300 V460 H1360 V560" />
    </g>

    <!-- === chips === -->
    <g>
      <rect class="chip" x="560" y="180" width="80" height="80" rx="6"/>
      <text class="chip-label" x="574" y="224">AI·CORE</text>

      <rect class="chip" x="1140" y="440" width="70" height="70" rx="6"/>
      <text class="chip-label" x="1152" y="480">SEC</text>

      <rect class="chip" x="240" y="620" width="70" height="70" rx="6"/>
      <text class="chip-label" x="252" y="660">ML</text>

      <rect class="chip" x="960" y="620" width="60" height="60" rx="6"/>
      <text class="chip-label" x="968" y="655">DB</text>
    </g>

    <!-- === glowing accent traces (cyan/amber, static) === -->
    <g class="trace-glow">
      <path d="M0,120 H260 V220 H520 V80 H900 V300 H1600" />
      <path d="M820,340 V500 H1140" />
    </g>
    <g class="trace-amber">
      <path d="M0,760 H320 V860 H700 V760 H1050 V820 H1600" />
      <path d="M240,690 V760 H400" />
    </g>

    <!-- === animated pulses traveling along the glowing paths === -->
    <path class="pulse p1" d="M0,120 H260 V220 H520 V80 H900 V300 H1600" />
    <path class="pulse p2" d="M0,760 H320 V860 H700 V760 H1050 V820 H1600" />
    <path class="pulse p3" d="M60,60 H260 V140 H420 V300 H600 V220 H820 V340" />

    <!-- === solder pads / nodes === -->
    <g>
      <circle class="pad lit" cx="260" cy="120" r="5"/>
      <circle class="pad lit slow" cx="520" cy="220" r="5"/>
      <circle class="pad" cx="900" cy="80" r="4"/>
      <circle class="pad lit amber" cx="320" cy="760" r="5"/>
      <circle class="pad" cx="700" cy="860" r="4"/>
      <circle class="pad lit amber slow" cx="1050" cy="760" r="5"/>
      <circle class="pad" cx="1240" cy="680" r="4"/>
      <circle class="pad lit" cx="820" cy="340" r="5"/>
      <circle class="pad" cx="1180" cy="80" r="4"/>
      <circle class="pad lit slow" cx="1360" cy="460" r="5"/>
      <circle class="pad" cx="400" cy="620" r="4"/>
      <circle class="pad lit" cx="600" cy="300" r="4.5"/>
    </g>

    <!-- === faint hex/binary glyphs near a couple of nodes, quiet detail === -->
    <g class="glyphs">
      <text x="540" y="255">0x2F</text>
      <text x="835" y="375">1011</text>
      <text x="1065" y="795">0xA4</text>
      <text x="270" y="105">0x9C</text>
    </g>
 <!-- =========================================================
  ANIMATED BACKGROUND — particle network (canvas)
  Paste this block near the TOP of your README.md
  (works because GitHub Pages/Jekyll renders raw HTML/JS;
  it just won't animate on github.com itself, only on your
  live *.github.io page)
========================================================== -->

<!-- =========================================================
  CINEMATIC ANIMATED BACKGROUND
  Layers: drifting nebula glow  →  parallax starfield  →  glowing particle network
  Paste this block near the TOP of your README.md.
  (Animates on your live *.github.io Pages URL — github.com
  sanitizes scripts, so it stays static there.)
========================================================== -->
<p align="center">
  <img src="assets/messi_and_ronaldo_wallpaper_4k_chess.jpg" alt="Chess match" width="800">
</p>
  requestAnimationFrame(loop);
  if (reduceMotion) { drawNebula(0); drawStars(0); drawParticles(); } // one static frame
})();
</script>
