<style>
  .readme-hero { background: linear-gradient(135deg, #0a0e27 0%, #1a1f3a 100%); padding: 60px 20px; border-radius: 12px; margin: 0 0 40px 0; }
  .readme-hero h1 { font-size: 48px; font-weight: 700; color: #ffffff; margin: 0; font-family: 'Inter', sans-serif; }
  .readme-hero-tag { font-size: 14px; color: #0D9488; font-weight: 600; text-transform: uppercase; letter-spacing: 1px; margin-top: 12px; }
  .readme-hero-desc { font-size: 20px; color: #e0e0e0; margin-top: 16px; line-height: 1.6; max-width: 600px; font-family: 'Inter', sans-serif; }
  
  .card { background: rgba(13, 148, 136, 0.05); border: 1px solid #0D9488; border-radius: 8px; padding: 28px; margin: 20px 0; }
  .card h2 { color: #0D9488; font-size: 24px; margin-top: 0; font-family: 'Inter', sans-serif; font-weight: 700; }
  .card-grid { display: grid; grid-template-columns: repeat(4, 1fr); gap: 16px; margin: 20px 0; }
  .card-item { padding: 20px; background: rgba(20, 184, 166, 0.08); border: 1px solid #0D9488; border-radius: 6px; text-align: center; }
  .card-item h3 { font-size: 16px; color: #0D9488; margin: 0 0 8px 0; font-weight: 700; }
  .card-item p { font-size: 13px; color: #b0b0b0; margin: 0; line-height: 1.4; }
  
  .progress-bar { background: #14b8a6; height: 4px; border-radius: 2px; margin: 12px 0; }
  .stat-item { padding: 16px; text-align: center; border-bottom: 1px solid #0D9488; }
  .stat-item:last-child { border-bottom: none; }
  .stat-value { font-size: 28px; font-weight: 700; color: #0D9488; }
  .stat-label { font-size: 12px; color: #b0b0b0; text-transform: uppercase; }
  
  .workflow { display: flex; align-items: center; justify-content: space-around; margin: 40px 0; gap: 20px; flex-wrap: wrap; }
  .workflow-step { text-align: center; }
  .workflow-icon { width: 56px; height: 56px; background: rgba(13, 148, 136, 0.15); border: 2px solid #0D9488; border-radius: 50%; display: flex; align-items: center; justify-content: center; margin: 0 auto 12px; font-size: 24px; }
  .workflow-label { font-size: 13px; color: #e0e0e0; font-weight: 600; }
  
  .cta-buttons { display: flex; gap: 12px; justify-content: center; flex-wrap: wrap; margin: 28px 0; }
  .cta-btn { background: #0D9488; color: #ffffff; padding: 12px 24px; border-radius: 6px; text-decoration: none; font-weight: 600; font-size: 14px; border: none; cursor: pointer; font-family: 'Inter', sans-serif; transition: all 0.2s; }
  .cta-btn:hover { background: #14b8a6; transform: translateY(-2px); }
  
  .svg-hero { max-width: 100%; height: auto; margin: 20px 0; }
</style>

<div class="readme-hero" align="center">
  <div class="readme-hero-tag">Building Kinderly</div>
  <h1>Hey, I'm Omar 👋</h1>
  <p class="readme-hero-desc">
    I'm building Kinderly because parents deserve <strong style="color: #0D9488;">peace of mind</strong>, 
    and nurseries deserve tools that make communication <strong style="color: #0D9488;">simple</strong>.
  </p>
</div>

<div align="center">
  <p style="font-size: 13px; color: #b0b0b0; text-transform: uppercase; letter-spacing: 0.5px; margin: 0 0 32px 0;">
    👥 HRTech Expert • 🤖 AI Enthusiast • 🎯 Problem Solver • 📚 Lifelong Learner
  </p>
</div>

---

<div class="card">
  <svg viewBox="0 0 800 200" class="svg-hero" xmlns="http://www.w3.org/2000/svg">
    <!-- Background grid -->
    <defs>
      <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
        <path d="M 40 0 L 0 0 0 40" fill="none" stroke="#0D9488" stroke-width="0.5" opacity="0.1"/>
      </pattern>
    </defs>
    <rect width="800" height="200" fill="url(#grid)"/>
    
    <!-- Left circle (Parents) -->
    <circle cx="150" cy="100" r="50" fill="none" stroke="#0D9488" stroke-width="2" opacity="0.8"/>
    <text x="150" y="105" text-anchor="middle" font-size="24">👨‍👩‍👧‍👦</text>
    
    <!-- Right circle (Teachers) -->
    <circle cx="650" cy="100" r="50" fill="none" stroke="#0D9488" stroke-width="2" opacity="0.8"/>
    <text x="650" y="105" text-anchor="middle" font-size="24">👨‍🏫</text>
    
    <!-- Connection lines with glow -->
    <line x1="200" y1="100" x2="600" y2="100" stroke="#0D9488" stroke-width="2" opacity="0.6"/>
    <circle cx="320" cy="100" r="6" fill="#0D9488"/>
    <circle cx="400" cy="100" r="6" fill="#0D9488"/>
    <circle cx="480" cy="100" r="6" fill="#0D9488"/>
    
    <!-- Center badge -->
    <rect x="360" y="70" width="80" height="60" rx="8" fill="#0D9488" opacity="0.15" stroke="#0D9488" stroke-width="1"/>
    <text x="400" y="105" text-anchor="middle" font-size="13" fill="#0D9488" font-weight="bold">KINDERLY</text>
  </svg>

  <h2 style="text-align: center; margin-top: 0;">🌿 Kinderly</h2>
  <p style="text-align: center; font-size: 15px; color: #e0e0e0; margin: 16px 0;">
    Nursery-Parent Communication Platform
  </p>
  
  <div class="card-grid">
    <div class="card-item">
      <h3>⚡ Real-time</h3>
      <p>Instant notifications and live updates</p>
    </div>
    <div class="card-item">
      <h3>📋 Daily Reports</h3>
      <p>Beautiful summaries with photos</p>
    </div>
    <div class="card-item">
      <h3>💬 Messaging</h3>
      <p>Direct communication with teachers</p>
    </div>
    <div class="card-item">
      <h3>🔒 Secure</h3>
      <p>Enterprise-grade privacy</p>
    </div>
  </div>

  <div align="center" style="margin-top: 24px;">
    <a href="https://kinderly.net" class="cta-btn">Visit Kinderly →</a>
  </div>
</div>

---

## 🚀 What I'm Building

<div class="card" style="background: rgba(13, 148, 136, 0.08); border-left: 4px solid #0D9488;">
  <div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 24px; margin: 0;">
    <div>
      <h3 style="color: #0D9488; font-size: 18px; margin-bottom: 12px;">🔬 Deep Research</h3>
      <p style="color: #b0b0b0; font-size: 14px; margin: 0 0 16px 0;">Talking to parents & nurseries daily</p>
      <div class="progress-bar" style="width: 71%;"></div>
      <span style="font-size: 12px; color: #0D9488; font-weight: 700;">71%</span>
    </div>
    <div>
      <h3 style="color: #0D9488; font-size: 18px; margin-bottom: 12px;">⚡ MVP Dev</h3>
      <p style="color: #b0b0b0; font-size: 14px; margin: 0 0 16px 0;">Building core features that matter</p>
      <div class="progress-bar" style="width: 54%;"></div>
      <span style="font-size: 12px; color: #0D9488; font-weight: 700;">54%</span>
    </div>
    <div>
      <h3 style="color: #0D9488; font-size: 18px; margin-bottom: 12px;">📊 Validation</h3>
      <p style="color: #b0b0b0; font-size: 14px; margin: 0 0 16px 0;">Testing with real users</p>
      <div class="progress-bar" style="width: 38%;"></div>
      <span style="font-size: 12px; color: #0D9488; font-weight: 700;">38%</span>
    </div>
  </div>
</div>

---

## 💡 How I Work

<div class="workflow">
  <div class="workflow-step">
    <div class="workflow-icon">👥</div>
    <p class="workflow-label">Talk to users</p>
    <p style="font-size: 11px; color: #808080; max-width: 100px;">Real conversations, not surveys</p>
  </div>
  <svg style="width: 40px; height: 2px; margin-top: 28px;"><line x1="0" y1="1" x2="40" y2="1" stroke="#0D9488" stroke-width="2"/></svg>
  <div class="workflow-step">
    <div class="workflow-icon">📝</div>
    <p class="workflow-label">Write specs</p>
    <p style="font-size: 11px; color: #808080; max-width: 100px;">Good requirements prevent disasters</p>
  </div>
  <svg style="width: 40px; height: 2px; margin-top: 28px;"><line x1="0" y1="1" x2="40" y2="1" stroke="#0D9488" stroke-width="2"/></svg>
  <div class="workflow-step">
    <div class="workflow-icon">⚡</div>
    <p class="workflow-label">Ship fast</p>
    <p style="font-size: 11px; color: #808080; max-width: 100px;">Learning from real usage</p>
  </div>
  <svg style="width: 40px; height: 2px; margin-top: 28px;"><line x1="0" y1="1" x2="40" y2="1" stroke="#0D9488" stroke-width="2"/></svg>
  <div class="workflow-step">
    <div class="workflow-icon">🚀</div>
    <p class="workflow-label">Move quick</p>
    <p style="font-size: 11px; color: #808080; max-width: 100px;">Days, not months</p>
  </div>
</div>

---

## 🛠️ Tech Stack

<div align="center" style="display: grid; grid-template-columns: repeat(4, 1fr); gap: 12px; max-width: 600px; margin: 0 auto;">
  <div style="padding: 16px; background: rgba(13, 148, 136, 0.1); border: 1px solid #0D9488; border-radius: 6px; text-align: center;">
    <div style="font-size: 20px; margin-bottom: 8px;">🧠</div>
    <p style="font-size: 12px; color: #e0e0e0; margin: 0; font-weight: 600;">Claude</p>
  </div>
  <div style="padding: 16px; background: rgba(13, 148, 136, 0.1); border: 1px solid #0D9488; border-radius: 6px; text-align: center;">
    <div style="font-size: 20px; margin-bottom: 8px;">⚡</div>
    <p style="font-size: 12px; color: #e0e0e0; margin: 0; font-weight: 600;">Cursor</p>
  </div>
  <div style="padding: 16px; background: rgba(13, 148, 136, 0.1); border: 1px solid #0D9488; border-radius: 6px; text-align: center;">
    <div style="font-size: 20px; margin-bottom: 8px;">🎨</div>
    <p style="font-size: 12px; color: #e0e0e0; margin: 0; font-weight: 600;">Figma</p>
  </div>
  <div style="padding: 16px; background: rgba(13, 148, 136, 0.1); border: 1px solid #0D9488; border-radius: 6px; text-align: center;">
    <div style="font-size: 20px; margin-bottom: 8px;">📋</div>
    <p style="font-size: 12px; color: #e0e0e0; margin: 0; font-weight: 600;">Notion</p>
  </div>
  <div style="padding: 16px; background: rgba(13, 148, 136, 0.1); border: 1px solid #0D9488; border-radius: 6px; text-align: center;">
    <div style="font-size: 20px; margin-bottom: 8px;">🗄️</div>
    <p style="font-size: 12px; color: #e0e0e0; margin: 0; font-weight: 600;">PostgreSQL</p>
  </div>
  <div style="padding: 16px; background: rgba(13, 148, 136, 0.1); border: 1px solid #0D9488; border-radius: 6px; text-align: center;">
    <div style="font-size: 20px; margin-bottom: 8px;">🐍</div>
    <p style="font-size: 12px; color: #e0e0e0; margin: 0; font-weight: 600;">Python</p>
  </div>
  <div style="padding: 16px; background: rgba(13, 148, 136, 0.1); border: 1px solid #0D9488; border-radius: 6px; text-align: center;">
    <div style="font-size: 20px; margin-bottom: 8px;">📘</div>
    <p style="font-size: 12px; color: #e0e0e0; margin: 0; font-weight: 600;">TypeScript</p>
  </div>
  <div style="padding: 16px; background: rgba(13, 148, 136, 0.1); border: 1px solid #0D9488; border-radius: 6px; text-align: center;">
    <div style="font-size: 20px; margin-bottom: 8px;">🌪️</div>
    <p style="font-size: 12px; color: #e0e0e0; margin: 0; font-weight: 600;">Tailwind</p>
  </div>
</div>

---

## 📊 GitHub Stats

<div style="display: grid; grid-template-columns: 200px 1fr; gap: 24px; align-items: start; margin: 20px 0;">
  <div style="background: rgba(13, 148, 136, 0.08); border: 1px solid #0D9488; border-radius: 8px; padding: 0;">
    <div class="stat-item">
      <div class="stat-value">1</div>
      <div class="stat-label">Total Stars</div>
    </div>
    <div class="stat-item">
      <div class="stat-value">6</div>
      <div class="stat-label">Commits 2024</div>
    </div>
    <div class="stat-item">
      <div class="stat-value">2</div>
      <div class="stat-label">Pull Requests</div>
    </div>
    <div class="stat-item">
      <div class="stat-value">1</div>
      <div class="stat-label">Issues</div>
    </div>
  </div>
  <div>
    <p style="font-size: 13px; color: #b0b0b0; margin: 0 0 12px 0;">Top Languages</p>
    <svg viewBox="0 0 200 120" xmlns="http://www.w3.org/2000/svg" style="width: 100%; height: auto;">
      <!-- Language bars -->
      <rect x="0" y="20" width="140" height="16" fill="#0D9488" opacity="0.8" rx="2"/>
      <text x="150" y="32" font-size="12" fill="#e0e0e0">JavaScript</text>
      
      <rect x="0" y="50" width="80" height="16" fill="#14b8a6" opacity="0.8" rx="2"/>
      <text x="90" y="62" font-size="12" fill="#e0e0e0">HTML</text>
      
      <rect x="0" y="80" width="60" height="16" fill="#0D9488" opacity="0.6" rx="2"/>
      <text x="70" y="92" font-size="12" fill="#e0e0e0">CSS</text>
    </svg>
  </div>
</div>

---

## 💬 Let's Build Together

<div align="center" style="margin: 40px 0;">
  <h3 style="color: #ffffff; font-size: 20px; margin-bottom: 16px;">Interested in:</h3>
  <p style="color: #e0e0e0; font-size: 14px; margin: 8px 0;">
    🏗️ <strong>Founding</strong> • 🎯 <strong>Product</strong> • 👥 <strong>HRTech</strong> • 🤖 <strong>AI</strong>
  </p>
  <div class="cta-buttons">
    <a href="https://linkedin.com/in/omar-wafaey-087b42205/" class="cta-btn">LinkedIn</a>
    <a href="https://twitter.com/OmerWafaey" class="cta-btn">Twitter</a>
    <a href="mailto:omerwafaey@gmail.com" class="cta-btn">Email</a>
    <a href="https://kinderly.net" class="cta-btn" style="background: #14b8a6;">Visit Kinderly</a>
  </div>
</div>

<div align="center" style="border-top: 1px solid #0D9488; padding-top: 24px; margin-top: 40px;">
  <blockquote style="font-size: 15px; color: #b0b0b0; font-style: italic; margin: 0 0 16px 0; padding-left: 16px; border-left: 3px solid #0D9488;">
    The best products come from understanding users deeply and building with intention.
  </blockquote>
  <p style="font-size: 13px; color: #808080; margin: 0;">⭐ Thanks for stopping by. Star some repos if you find them useful.</p>
  <br/>
  <img src="https://komarev.com/ghpvc/?username=OmerWafaey&style=flat-square&color=0D9488" alt="Profile Views"/>
</div>
