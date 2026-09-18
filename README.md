<!-- Portfolio profile README for GitHub: sarmad-640 -->

<div align="center">
  <h1>
    <span style="
      background: linear-gradient(90deg,#7c3aed,#22c55e,#38bdf8,#f472b6);
      background-size: 300% 300%;
      -webkit-background-clip: text;
      background-clip: text;
      color: transparent;
      animation: gradientShift 5s ease-in-out infinite;
      font-weight: 800;
      letter-spacing: -0.02em;
    ">
      Hi, I'm Sarmad 👋
    </span>
  </h1>

  <p style="margin-top:-6px;">
    <b>Learning and improving</b><br/>
    <span style="font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, 'Liberation Mono','Courier New', monospace;">
      Frontend • Vibe coder • Tech enthusiast
    </span>
  </p>

  <p>
    <a href="https://github.com/sarmad-640?tab=repositories">Repositories</a>
    ·
    <a href="https://github.com/sarmad-640?tab=stars">Stars</a>
  </p>

  <!-- Inline CSS animations (GitHub usually allows this in README) -->
  <style>
    @keyframes gradientShift {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    @keyframes glowPulse {
      0%, 100% { box-shadow: 0 0 0 rgba(56,189,248,0); }
      50% { box-shadow: 0 0 22px rgba(56,189,248,0.35); }
    }

    @keyframes floaty {
      0%, 100% { transform: translateY(0px); }
      50% { transform: translateY(-6px); }
    }

    @keyframes scan {
      0% { transform: translateX(-120%); opacity: 0; }
      20% { opacity: 1; }
      60% { opacity: 1; }
      100% { transform: translateX(120%); opacity: 0; }
    }

    /* Typing effect */
    .typewrap { display: inline-block; }
    .type {
      display: inline-block;
      vertical-align: bottom;
      overflow: hidden;
      white-space: nowrap;
      border-right: 2px solid rgba(34,197,94,0.9);
      animation: typing 3.2s steps(22) infinite, blink 0.75s step-end infinite;
      width: 22ch; /* adjust if you change the text */
      font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, 'Liberation Mono','Courier New', monospace;
      font-size: 14px;
      color: #e5e7eb;
    }

    @keyframes typing {
      0% { width: 0ch; }
      30% { width: 22ch; }
      70% { width: 22ch; }
      100% { width: 0ch; }
    }

    @keyframes blink {
      50% { border-right-color: transparent; }
    }

    /* Terminal card */
    .term {
      width: min(760px, 95vw);
      margin: 14px auto 0;
      border-radius: 14px;
      background: rgba(17, 24, 39, 0.65);
      border: 1px solid rgba(56,189,248,0.25);
      position: relative;
      overflow: hidden;
      animation: glowPulse 2.4s ease-in-out infinite;
      text-align: left;
    }

    .term::before{
      content:"";
      position:absolute;
      inset:-40%;
      background: radial-gradient(circle at 20% 20%, rgba(34,197,94,0.25), transparent 40%),
                  radial-gradient(circle at 80% 30%, rgba(56,189,248,0.18), transparent 45%),
                  radial-gradient(circle at 40% 90%, rgba(244,114,182,0.16), transparent 50%);
      filter: blur(12px);
      opacity: 0.9;
      pointer-events:none;
      animation: floaty 4.2s ease-in-out infinite;
    }

    .termInner{
      position: relative;
      padding: 18px 18px 16px;
    }

    .termTop{
      display:flex;
      gap:8px;
      margin-bottom:10px;
      opacity:0.95;
    }
    .dot{ width:10px; height:10px; border-radius:50%; display:inline-block; }
    .d1{ background:#ef4444; }
    .d2{ background:#f59e0b; }
    .d3{ background:#22c55e; }

    .scanline{
      position:absolute;
      top:0;
      left:-30%;
      right:-30%;
      height:2px;
      background: linear-gradient(90deg, transparent, rgba(56,189,248,0.85), transparent);
      animation: scan 3s ease-in-out infinite;
      pointer-events:none;
      opacity:0.7;
    }
  </style>

  <div class="term">
    <div class="scanline"></div>
    <div class="termInner">
      <div class="termTop">
        <span class="dot d1"></span>
        <span class="dot d2"></span>
        <span class="dot d3"></span>
      </div>

      <div style="color:#e5e7eb; font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas,'Liberation Mono','Courier New', monospace; font-size:14px;">
        <div>
          <span style="color:#38bdf8;">$</span> status:
          <span style="color:#22c55e;">learning</span>
        </div>
        <div style="margin-top:6px;">
          <span style="color:#38bdf8;">$</span> focus:
          <span style="color:#a78bfa;">frontend</span>
        </div>
        <div style="margin-top:10px; line-height:1.5;">
          <span style="color:#38bdf8;">$</span>
          <span class="typewrap">
            <span class="type">ship → learn → improve</span>
          </span>
        </div>
      </div>

      <div style="margin-top:12px; display:flex; gap:10px; flex-wrap:wrap;">
        <div style="padding:8px 10px; border-radius:999px; border:1px solid rgba(34,197,94,0.35); color:#bbf7d0; background:rgba(34,197,94,0.08);">
          UX-first UI
        </div>
        <div style="padding:8px 10px; border-radius:999px; border:1px solid rgba(56,189,248,0.35); color:#bae6fd; background:rgba(56,189,248,0.08);">
          Component-driven
        </div>
        <div style="padding:8px 10px; border-radius:999px; border:1px solid rgba(244,114,182,0.35); color:#fbcfe8; background:rgba(244,114,182,0.08);">
          Refactor energy
        </div>
      </div>
    </div>
  </div>

</div>

---

## ⚙️ About
I write code to learn fast and build real things.
My focus right now is <b>frontend</b>: clean UI, good UX, and practical features.

- Learning by shipping
- Techy UI details (state, components, interactions)
- Always refactoring with intent

---

## 🚀 Featured Projects
_(Replace placeholders once you pick your 3–6 repos.)_

### 1) <span style="color:#2ea043">Project One</span>
**Stack:** React / Next.js / TypeScript *(edit)*  
One-liner: what it does + impact  
- Repo: `https://github.com/sarmad-640/<repo-name>`
- Notes: components, state, UI/UX *(edit)*

### 2) <span style="color:#2ea043">Project Two</span>
**Stack:** *(edit)*  
- Repo: `https://github.com/sarmad-640/<repo-name>`

### 3) <span style="color:#2ea043">Project Three</span>
**Stack:** *(edit)*  
- Repo: `https://github.com/sarmad-640/<repo-name>`

---

## 🧰 Tech Stack
- **Frontend:** HTML, CSS, JavaScript/TypeScript
- **UI mindset:** component-driven, responsive, polished interactions
- **Tools:** Git, Linux, code reviews

---

## 📌 What I'm working on
- Building small UI projects to improve speed + quality
- Learning frontend patterns (state, rendering, performance)
- Turning ideas into demos
