<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>AI Tools Mastermind - Beat the Clock</title>
  <style>
    :root {
      --navy: #0d2f66;
      --red: #e11d1d;
      --bg: #f5f8fc;
      --text: #13213c;
      --muted: #5e6b84;
      --line: #d9e3f2;
      --shadow: 0 18px 40px rgba(13, 47, 102, 0.12);
      --radius: 22px;
    }
    * { box-sizing: border-box; }
    html, body { height: 100%; }
    body {
      margin: 0;
      font-family: Inter, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Arial, sans-serif;
      color: var(--text);
      background:
        radial-gradient(circle at top left, rgba(224,233,246,0.95), transparent 34%),
        radial-gradient(circle at top right, rgba(255,228,228,0.85), transparent 32%),
        linear-gradient(180deg, #f9fbff 0%, var(--bg) 100%);
      overflow: hidden;
    }
    .app {
      width: 100%;
      height: 100vh;
      max-width: 1320px;
      margin: 0 auto;
      padding: 16px 18px 18px;
      display: flex;
      flex-direction: column;
      gap: 12px;
    }
    .topbar {
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 16px;
      flex-wrap: wrap;
      flex: none;
    }
    .brand {
      display: flex;
      align-items: center;
      gap: 14px;
      min-width: 0;
    }
    .brand-badge {
      width: 54px;
      height: 54px;
      border-radius: 16px;
      background: linear-gradient(135deg, var(--navy), #1e5db0);
      display: grid;
      place-items: center;
      color: #fff;
      font-weight: 900;
      letter-spacing: 0.5px;
      box-shadow: var(--shadow);
      flex: none;
    }
    .brand h1 {
      margin: 0;
      font-size: clamp(1.05rem, 2vw, 1.7rem);
      line-height: 1.1;
      color: var(--navy);
    }
    .brand p {
      margin: 4px 0 0;
      color: var(--muted);
      font-size: 0.92rem;
    }
    .top-actions {
      display: flex;
      gap: 10px;
      align-items: center;
      flex-wrap: wrap;
      justify-content: flex-end;
    }
    .pill {
      background: rgba(255,255,255,0.84);
      border: 1px solid var(--line);
      border-radius: 999px;
      padding: 10px 14px;
      box-shadow: 0 8px 24px rgba(16, 29, 64, 0.05);
      color: var(--navy);
      font-weight: 800;
      display: inline-flex;
      align-items: center;
      gap: 8px;
      backdrop-filter: blur(5px);
      white-space: nowrap;
    }
    .hero {
      background: rgba(255,255,255,0.86);
      border: 1px solid rgba(13, 47, 102, 0.12);
      border-radius: 26px;
      box-shadow: var(--shadow);
      padding: 14px 16px 12px;
      flex: none;
    }
    .hero-header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 14px;
      flex-wrap: wrap;
      margin-bottom: 12px;
    }
    .title-block h2 {
      margin: 0;
      font-size: clamp(1.2rem, 2.6vw, 2.15rem);
      letter-spacing: 0.2px;
      line-height: 1.06;
      color: var(--navy);
    }
    .title-block h2 .accent { color: var(--red); }
    .title-block .subtitle {
      margin: 6px 0 0;
      color: var(--muted);
      font-size: 0.94rem;
      max-width: 900px;
    }
    .scoreboard {
      display: grid;
      grid-template-columns: repeat(3, minmax(120px, 1fr));
      gap: 10px;
      min-width: min(470px, 100%);
    }
    .metric {
      background: linear-gradient(180deg, #fff, #f7fbff);
      border: 1px solid var(--line);
      border-radius: 16px;
      padding: 10px 12px;
      text-align: center;
      min-height: 76px;
      display: grid;
      place-items: center;
    }
    .metric .label {
      display: block;
      color: var(--muted);
      font-size: 0.74rem;
      text-transform: uppercase;
      letter-spacing: 0.08em;
      margin-bottom: 4px;
      font-weight: 800;
    }
    .metric .value {
      font-size: 1.3rem;
      font-weight: 1000;
      color: var(--navy);
      line-height: 1;
    }
    .progress-wrap {
      margin-top: 10px;
      background: #edf2fb;
      border: 1px solid #dce7f9;
      border-radius: 999px;
      overflow: hidden;
      height: 14px;
    }
    .progress-bar {
      width: 0%;
      height: 100%;
      background: linear-gradient(90deg, var(--red), #ff6363);
      border-radius: 999px;
      transition: width 0.18s linear;
    }
    .main {
      flex: 1;
      min-height: 0;
      display: grid;
      grid-template-columns: 1fr;
    }
    .panel {
      border-radius: 26px;
      border: 1px solid rgba(13, 47, 102, 0.12);
      background: rgba(255,255,255,0.92);
      box-shadow: var(--shadow);
      padding: 14px;
      min-height: 0;
      display: flex;
      flex-direction: column;
      gap: 12px;
    }
    .panel-title {
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 12px;
    }
    .panel-title h3 {
      margin: 0;
      color: var(--navy);
      font-size: 1rem;
    }
    .panel-title span {
      color: var(--muted);
      font-size: 0.9rem;
      white-space: nowrap;
    }
    .game-shell {
      flex: 1;
      min-height: 0;
      display: grid;
      grid-template-rows: auto 1.3fr 1.2fr auto;
      gap: 12px;
    }
    .game-stage {
      border-radius: 24px;
      border: 1px dashed rgba(13, 47, 102, 0.25);
      background:
        radial-gradient(circle at top left, rgba(13, 47, 102, 0.05), transparent 28%),
        linear-gradient(180deg, #ffffff, #fbfcff);
      padding: 14px;
      display: grid;
      align-items: center;
      min-height: 0;
    }
    .stage-inner {
      display: grid;
      grid-template-columns: 1.2fr 0.8fr;
      gap: 14px;
      align-items: stretch;
    }
    .tool-card {
      border-radius: 24px;
      background: linear-gradient(135deg, var(--navy), #1850a5);
      color: white;
      padding: 18px;
      box-shadow: inset 0 0 0 1px rgba(255,255,255,0.08);
      display: flex;
      flex-direction: column;
      justify-content: center;
      text-align: center;
      min-height: 140px;
    }
    .tool-card .tag {
      text-transform: uppercase;
      letter-spacing: 0.11em;
      font-size: 0.75rem;
      color: rgba(255,255,255,0.84);
      font-weight: 900;
      margin-bottom: 8px;
    }
    .tool-card .tool {
      font-size: clamp(2rem, 4.6vw, 3.4rem);
      line-height: 1.05;
      font-weight: 1000;
      letter-spacing: 0.01em;
      padding: 8px 0;
    }
    .countdown-box {
      border-radius: 24px;
      border: 1px solid var(--line);
      background: linear-gradient(180deg, #fff, #f8fbff);
      padding: 14px;
      min-height: 140px;
      display: grid;
      align-items: center;
      text-align: center;
    }
    .countdown-box .label {
      color: var(--muted);
      text-transform: uppercase;
      letter-spacing: 0.08em;
      font-size: 0.74rem;
      font-weight: 800;
      margin-bottom: 8px;
    }
    .countdown-box .time {
      font-size: clamp(2.2rem, 4.8vw, 4rem);
      font-weight: 1000;
      color: var(--navy);
      line-height: 1;
    }
    .countdown-box .hint {
      margin-top: 6px;
      color: var(--muted);
      line-height: 1.45;
      font-size: 0.88rem;
    }
    .answers-wrap {
      border-radius: 24px;
      border: 1px solid var(--line);
      background: linear-gradient(180deg, #ffffff, #f9fbff);
      padding: 12px;
      display: flex;
      flex-direction: column;
      gap: 10px;
      min-height: 0;
    }
    .categories {
      display: grid;
      grid-template-columns: repeat(5, minmax(0, 1fr));
      gap: 12px;
      align-items: stretch;
    }
    .cat-btn {
      border: 1px solid var(--line);
      border-radius: 18px;
      background: white;
      padding: 18px 14px;
      cursor: pointer;
      color: var(--navy);
      font-weight: 900;
      min-height: 126px;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      line-height: 1.15;
      box-shadow: 0 8px 18px rgba(13, 47, 102, 0.05);
      transition: transform .14s ease, box-shadow .14s ease, border-color .14s ease, background .14s ease;
      position: relative;
      padding-top: 26px;
      font-size: clamp(1rem, 1.5vw, 1.15rem);
      min-width: 0;
    }
    .cat-btn:hover { transform: translateY(-2px); box-shadow: 0 14px 26px rgba(13, 47, 102, 0.08); }
    .cat-btn:disabled { cursor: not-allowed; opacity: 0.7; transform: none; }
    .cat-btn .small {
      position: absolute;
      top: 10px;
      left: 12px;
      width: 26px;
      height: 26px;
      border-radius: 50%;
      background: var(--navy);
      color: white;
      display: grid;
      place-items: center;
      font-size: 0.74rem;
      font-weight: 1000;
    }
    .cat-btn.correct {
      border-color: rgba(10, 143, 73, 0.35);
      background: linear-gradient(180deg, #eefdf4, #e9fff1);
      color: #0a7139;
    }
    .cat-btn.wrong {
      border-color: rgba(224, 24, 24, 0.35);
      background: linear-gradient(180deg, #fff2f2, #fff);
      color: #b11717;
    }
    .feedback {
      display: none;
      border-radius: 18px;
      padding: 12px 14px;
      font-weight: 800;
      align-items: center;
      justify-content: space-between;
      gap: 12px;
      min-height: 50px;
    }
    .feedback.show { display: flex; }
    .feedback.ok { background: #ecfff4; border: 1px solid rgba(10,143,73,0.28); color: #0a7139; }
    .feedback.no { background: #fff2f2; border: 1px solid rgba(224,24,24,0.24); color: #b11717; }
    .controls {
      display: flex;
      gap: 10px;
      flex-wrap: wrap;
      justify-content: flex-end;
      align-items: center;
      margin-top: 2px;
      flex: none;
    }
    .btn {
      border: 0;
      border-radius: 999px;
      padding: 12px 18px;
      font-weight: 1000;
      cursor: pointer;
      transition: transform .14s ease, box-shadow .14s ease, opacity .14s ease;
    }
    .btn:hover { transform: translateY(-1px); }
    .btn.primary { background: linear-gradient(135deg, var(--navy), #1b57af); color: white; box-shadow: 0 12px 24px rgba(16,51,110,0.14); }
    .btn.secondary { background: white; color: var(--navy); border: 1px solid var(--line); }
    
    .start-screen, .end-screen {
      position: fixed;
      inset: 0;
      display: grid;
      place-items: center;
      background: rgba(245, 248, 252, 0.94);
      backdrop-filter: blur(8px);
      z-index: 30;
      padding: 16px;
    }
    .dialog {
      width: min(920px, 96vw);
      background: white;
      border-radius: 30px;
      box-shadow: 0 32px 80px rgba(16,51,110,0.18);
      border: 1px solid rgba(16, 51, 110, 0.12);
      overflow: hidden;
    }
    .dialog-head {
      background: linear-gradient(135deg, var(--navy), #164a95);
      color: white;
      padding: 20px 22px;
    }
    .dialog-head h2 { margin: 0; font-size: clamp(1.35rem, 3vw, 2.2rem); }
    .dialog-head p { margin: 8px 0 0; color: rgba(255,255,255,0.88); line-height: 1.6; }
    .dialog-body {
      padding: 20px 22px 22px;
      display: flex;
      flex-direction: column;
      gap: 16px;
    }

    /* Start Screen Visual Grid & Options Styles */
    .visual-banner {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 12px;
    }
    .visual-card {
      background: linear-gradient(135deg, #102347, #1d4b8f);
      border-radius: 16px;
      padding: 16px;
      color: white;
      text-align: center;
      box-shadow: 0 8px 20px rgba(13, 47, 102, 0.15);
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      gap: 8px;
    }
    .visual-card .icon-graphic {
      width: 48px;
      height: 48px;
      border-radius: 12px;
      background: rgba(255, 255, 255, 0.12);
      display: grid;
      place-items: center;
      font-size: 1.5rem;
      border: 1px solid rgba(255,255,255,0.2);
    }
    .visual-card span {
      font-weight: 800;
      font-size: 0.9rem;
      letter-spacing: 0.02em;
    }
    .options-title {
      font-size: 1rem;
      font-weight: 900;
      color: var(--navy);
      margin-top: 4px;
      text-align: center;
    }
    .mode-options {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 12px;
    }
    .option-card {
      border: 2px solid var(--line);
      border-radius: 20px;
      padding: 16px;
      text-align: center;
      cursor: pointer;
      background: linear-gradient(180deg, #ffffff, #f7fafe);
      transition: all 0.2s ease;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      gap: 8px;
    }
    .option-card:hover {
      border-color: var(--navy);
      transform: translateY(-3px);
      box-shadow: 0 12px 24px rgba(13, 47, 102, 0.1);
    }
    .option-card h4 {
      margin: 0;
      color: var(--navy);
      font-size: 1.1rem;
    }
    .option-card p {
      margin: 0;
      color: var(--muted);
      font-size: 0.82rem;
      line-height: 1.35;
    }
    .option-card .badge-time {
      display: inline-block;
      margin-top: 6px;
      background: rgba(13, 47, 102, 0.08);
      color: var(--navy);
      padding: 4px 10px;
      border-radius: 999px;
      font-weight: 800;
      font-size: 0.76rem;
    }

    .dialog-footer {
      padding: 0 22px 22px;
      display: flex;
      justify-content: flex-end;
      gap: 10px;
      flex-wrap: wrap;
    }
    .results-panel {
      display: none;
      border-radius: 22px;
      border: 1px solid var(--line);
      background: linear-gradient(180deg, #fff, #f8fbff);
      padding: 14px;
      margin-top: 12px;
    }
    .results-panel.show { display: block; }
    .results-panel h3 { margin: 0 0 10px; color: var(--navy); }
    .results-grid {
      display: grid;
      grid-template-columns: repeat(4, minmax(0, 1fr));
      gap: 10px;
    }
    .results-tile {
      text-align: center;
      border-radius: 18px;
      padding: 12px 10px;
      border: 1px solid var(--line);
      background: white;
    }
    .results-tile .label { display: block; color: var(--muted); font-size: 0.76rem; text-transform: uppercase; letter-spacing: 0.08em; }
    .results-tile .value { display: block; color: var(--navy); font-size: 1.35rem; font-weight: 1000; margin-top: 4px; }
    .footer-note {
      color: var(--muted);
      font-size: 0.9rem;
      line-height: 1.5;
      flex: none;
      opacity: 0.9;
    }

    @media (max-width: 1100px) {
      .hero-header { grid-template-columns: 1fr; }
      .scoreboard { min-width: 100%; }
      .categories { grid-template-columns: repeat(2, minmax(0, 1fr)); }
      .results-grid { grid-template-columns: repeat(2, minmax(0, 1fr)); }
      .stage-inner { grid-template-columns: 1fr; }
    }
    @media (max-width: 640px) {
      body { overflow: auto; }
      .app { height: auto; min-height: 100vh; padding: 12px; }
      .hero, .panel { border-radius: 22px; }
      .scoreboard { grid-template-columns: 1fr; }
      .categories { grid-template-columns: 1fr; }
      .mode-options, .visual-banner { grid-template-columns: 1fr; }
      .results-grid { grid-template-columns: 1fr; }
      .brand { align-items: flex-start; }
      .topbar { align-items: flex-start; }
      .top-actions { justify-content: flex-start; }
      .controls { justify-content: flex-start; }
      .dialog-body, .dialog-footer { padding-left: 16px; padding-right: 16px; }
      .dialog-head { padding-left: 16px; padding-right: 16px; }
      .cat-btn { min-height: 110px; }
    }
  </style>
</head>
<body>
  <!-- START SCREEN -->
  <div class="start-screen" id="startScreen">
    <div class="dialog">
      <div class="dialog-head">
        <h2>AI Tools Mastermind</h2>
        <p>Choose a game mode option to test your knowledge with 5 randomly assigned AI tool questions covering different purposes.</p>
      </div>
      <div class="dialog-body">
        <!-- Digital AI Visuals Banner -->
        <div class="visual-banner">
          <div class="visual-card">
            <div class="icon-graphic">⚡</div>
            <span>Neural Engine</span>
          </div>
          <div class="visual-card">
            <div class="icon-graphic">🤖</div>
            <span>Generative AI</span>
          </div>
          <div class="visual-card">
            <div class="icon-graphic">📊</div>
            <span>Smart Analytics</span>
          </div>
        </div>

        <div class="options-title">Select a Game Challenge Option:</div>

        <!-- 3 Game Mode Options -->
        <div class="mode-options">
          <div class="option-card" onclick="selectOption(10, 45)">
            <div>
              <h4>Option A: Speed Blitz</h4>
              <p>5 Random Questions across categories. Quick decisions!</p>
            </div>
            <div><span class="badge-time">10s / Tool • 45s Total</span></div>
          </div>
          <div class="option-card" onclick="selectOption(15, 60)">
            <div>
              <h4>Option B: Standard</h4>
              <p>5 Random Questions across categories. Balanced pace.</p>
            </div>
            <div><span class="badge-time">15s / Tool • 60s Total</span></div>
          </div>
          <div class="option-card" onclick="selectOption(20, 90)">
            <div>
              <h4>Option C: Precision</h4>
              <p>5 Random Questions across categories. Relaxed timing.</p>
            </div>
            <div><span class="badge-time">20s / Tool • 90s Total</span></div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- END SCREEN -->
  <div class="end-screen" id="endScreen" style="display:none;">
    <div class="dialog">
      <div class="dialog-head">
        <h2>Round Complete</h2>
        <p id="endSub">Well played.</p>
      </div>
      <div class="dialog-body" style="grid-template-columns: 1fr;">
        <div class="results-panel show">
          <h3>Final Scorecard</h3>
          <div class="results-grid">
            <div class="results-tile"><span class="label">Score</span><span class="value" id="finalScore">0</span></div>
            <div class="results-tile"><span class="label">Correct</span><span class="value" id="finalCorrect">0</span></div>
            <div class="results-tile"><span class="label">Wrong</span><span class="value" id="finalWrong">0</span></div>
            <div class="results-tile"><span class="label">Accuracy</span><span class="value" id="finalAccuracy">0%</span></div>
          </div>
        </div>
        <div class="footer-note">
          Use this game to help participants quickly associate AI tools with the right use cases.
        </div>
      </div>
      <div class="dialog-footer">
        <button class="btn secondary" id="reviewBtn">Review Game</button>
        <button class="btn primary" id="restartBtn">Play Again</button>
      </div>
    </div>
  </div>

  <!-- MAIN APP -->
  <div class="app" id="appShell">
    <div class="topbar">
      <div class="brand">
        <div class="brand-badge">DNA</div>
        <div>
          <h1>AI Tools Mastermind</h1>
          <p>One AI platform appears at a time. Select the best category before the next one shows up.</p>
        </div>
      </div>
      <div class="top-actions">
        <div class="pill">⏱️ <span id="timeStat">60s</span></div>
        <div class="pill">🏆 Score: <span id="scoreStat">0</span></div>
        <div class="pill">🧠 Correct: <span id="correctStat">0</span></div>
      </div>
    </div>
    <div class="hero">
      <div class="hero-header">
        <div class="title-block">
          <h2><span class="accent">AI</span> MATCHMAKING CHALLENGE</h2>
          <p class="subtitle">Click the category that best fits the platform shown in the center.</p>
        </div>
        <div class="scoreboard">
          <div class="metric"><span class="label">Current Tool</span><span class="value" id="toolCount">1 / 5</span></div>
          <div class="metric"><span class="label">Time Left</span><span class="value" id="timeLeft">60</span></div>
          <div class="metric"><span class="label">Decision Window</span><span class="value" id="decisionTimerTop">10</span></div>
        </div>
      </div>
      <div class="progress-wrap"><div class="progress-bar" id="progressBar"></div></div>
    </div>
    <div class="main">
      <section class="panel game-shell">
        <div class="panel-title">
          <h3>Live Challenge</h3>
          <span id="questionLabel">Waiting to start</span>
        </div>
        <div class="game-stage">
          <div class="stage-inner">
            <div class="tool-card">
              <div class="tag">AI Platform</div>
              <div class="tool" id="currentTool">—</div>
            </div>
            <div class="countdown-box">
              <div class="label">Decision Window</div>
              <div class="time" id="decisionTimerLarge">10</div>
              <div class="hint">Choose the best category before the next tool appears.</div>
            </div>
          </div>
        </div>
        <div class="answers-wrap">
          <div class="panel-title" style="margin-bottom: 10px;">
            <h3>Pick the category</h3>
            <span>Only one is correct</span>
          </div>
          <div class="categories" id="categories"></div>
          <div class="feedback" id="feedback"></div>
        </div>
        <div class="controls">
          <button class="btn secondary" id="skipBtn">Skip</button>
          <button class="btn primary" id="restartBtnSide">Restart Game</button>
        </div>
      </section>
    </div>
  </div>

  <script>
    // 5 Categories
    const categories = [
      "Text Writing",
      "Image / Creative",
      "PPT / Presentation",
      "Data Analysis",
      "Coding Assistance"
    ];

    // The 15 AI Tools organized by Category
    const questionRepository = {
      "Text Writing": [
        { tool: "Jasper", category: "Text Writing" },
        { tool: "Copy.AI", category: "Text Writing" },
        { tool: "Writer", category: "Text Writing" }
      ],
      "Image / Creative": [
        { tool: "Midjourney", category: "Image / Creative" },
        { tool: "Adobe Firefly", category: "Image / Creative" },
        { tool: "Dall-E", category: "Image / Creative" }
      ],
      "PPT / Presentation": [
        { tool: "Gamma", category: "PPT / Presentation" },
        { tool: "Beautiful.ai", category: "PPT / Presentation" },
        { tool: "Tome", category: "PPT / Presentation" }
      ],
      "Data Analysis": [
        { tool: "DataRobot", category: "Data Analysis" },
        { tool: "Tableau", category: "Data Analysis" },
        { tool: "ThoughtSpot", category: "Data Analysis" }
      ],
      "Coding Assistance": [
        { tool: "GitHub Copilot", category: "Coding Assistance" },
        { tool: "Cursor", category: "Coding Assistance" },
        { tool: "Windsurf", category: "Coding Assistance" }
      ]
    };

    const els = {
      startScreen: document.getElementById('startScreen'),
      endScreen: document.getElementById('endScreen'),
      restartBtn: document.getElementById('restartBtn'),
      restartBtnSide: document.getElementById('restartBtnSide'),
      reviewBtn: document.getElementById('reviewBtn'),
      skipBtn: document.getElementById('skipBtn'),
      categories: document.getElementById('categories'),
      currentTool: document.getElementById('currentTool'),
      questionLabel: document.getElementById('questionLabel'),
      toolCount: document.getElementById('toolCount'),
      timeLeft: document.getElementById('timeLeft'),
      timeStat: document.getElementById('timeStat'),
      scoreStat: document.getElementById('scoreStat'),
      correctStat: document.getElementById('correctStat'),
      decisionTimerTop: document.getElementById('decisionTimerTop'),
      decisionTimerLarge: document.getElementById('decisionTimerLarge'),
      progressBar: document.getElementById('progressBar'),
      feedback: document.getElementById('feedback'),
      finalScore: document.getElementById('finalScore'),
      finalCorrect: document.getElementById('finalCorrect'),
      finalWrong: document.getElementById('finalWrong'),
      finalAccuracy: document.getElementById('finalAccuracy'),
      endSub: document.getElementById('endSub')
    };

    let deck = [];
    let current = 0;
    let score = 0;
    let correct = 0;
    let wrong = 0;
    let answered = false;
    let active = false;
    let totalSeconds = 60;
    let remaining = totalSeconds;
    let decisionSeconds = 10;
    let decisionTimer = decisionSeconds;
    let globalTick = null;
    let toolTick = null;

    function shuffle(arr) {
      const copy = [...arr];
      for (let i = copy.length - 1; i > 0; i--) {
        const j = Math.floor(Math.random() * (i + 1));
        [copy[i], copy[j]] = [copy[j], copy[i]];
      }
      return copy;
    }

    // Select 5 questions ensuring 1 question per category purpose
    function generate5RandomQuestions() {
      const selected = [];
      for (const cat in questionRepository) {
        const catQuestions = questionRepository[cat];
        const randomQ = catQuestions[Math.floor(Math.random() * catQuestions.length)];
        selected.push(randomQ);
      }
      return shuffle(selected);
    }

    function buildCategoryButtons() {
      els.categories.innerHTML = '';
      categories.forEach((cat, idx) => {
        const btn = document.createElement('button');
        btn.type = 'button';
        btn.className = 'cat-btn';
        btn.innerHTML = `<span class="small">${idx + 1}</span><span>${cat}</span>`;
        btn.addEventListener('click', () => submitAnswer(cat, btn));
        els.categories.appendChild(btn);
      });
    }

    function resetUI() {
      els.feedback.className = 'feedback';
      els.feedback.style.display = 'none';
      document.querySelectorAll('.cat-btn').forEach(btn => {
        btn.disabled = false;
        btn.classList.remove('correct', 'wrong');
      });
    }

    function updateStats() {
      els.timeLeft.textContent = remaining;
      els.timeStat.textContent = `${remaining}s`;
      els.scoreStat.textContent = score;
      els.correctStat.textContent = correct;
      els.toolCount.textContent = `${Math.min(current + 1, 5)} / 5`;
      els.questionLabel.textContent = active ? `Question ${Math.min(current + 1, 5)} of 5` : 'Waiting to start';
      const pct = Math.min((current / 5) * 100, 100);
      els.progressBar.style.width = `${pct}%`;
      els.decisionTimerTop.textContent = decisionTimer;
      els.decisionTimerLarge.textContent = decisionTimer;
    }

    function loadQuestion() {
      if (current >= deck.length) {
        finishGame();
        return;
      }
      resetUI();
      const q = deck[current];
      answered = false;
      decisionTimer = decisionSeconds;
      els.currentTool.textContent = q.tool;
      updateStats();
    }

    function tickGlobal() {
      if (!active) return;
      remaining -= 1;
      if (remaining < 0) remaining = 0;
      updateStats();
      if (remaining <= 0) finishGame();
    }

    function tickTool() {
      if (!active || answered) return;
      decisionTimer -= 1;
      if (decisionTimer < 0) decisionTimer = 0;
      updateStats();
      if (decisionTimer <= 0) autoMiss();
    }

    function selectOption(perToolTime, globalTime) {
      decisionSeconds = perToolTime;
      totalSeconds = globalTime;
      startGame();
    }

    function startGame() {
      deck = generate5RandomQuestions();
      current = 0;
      score = 0;
      correct = 0;
      wrong = 0;
      answered = false;
      active = true;
      remaining = totalSeconds;
      decisionTimer = decisionSeconds;
      document.body.style.overflow = 'hidden';
      els.startScreen.style.display = 'none';
      els.endScreen.style.display = 'none';
      buildCategoryButtons();
      loadQuestion();
      clearInterval(globalTick);
      clearInterval(toolTick);
      globalTick = setInterval(tickGlobal, 1000);
      toolTick = setInterval(tickTool, 1000);
    }

    function submitAnswer(selected, button) {
      if (!active || answered) return;
      answered = true;
      const q = deck[current];
      const buttons = [...document.querySelectorAll('.cat-btn')];
      buttons.forEach(b => b.disabled = true);
      const correctBtn = buttons.find(b => b.textContent.includes(q.category));
      const isCorrect = selected === q.category;
      if (isCorrect) {
        correct += 1;
        score += 10;
        button.classList.add('correct');
        showFeedback(`Correct! ${q.tool} belongs to ${q.category}.`, true);
      } else {
        wrong += 1;
        button.classList.add('wrong');
        if (correctBtn) correctBtn.classList.add('correct');
        showFeedback(`Incorrect. ${q.tool} is best matched to ${q.category}.`, false);
      }
      current += 1;
      updateStats();
      setTimeout(() => {
        if (!active) return;
        if (current >= deck.length) finishGame();
        else loadQuestion();
      }, 900);
    }

    function autoMiss() {
      if (!active || answered) return;
      answered = true;
      wrong += 1;
      const q = deck[current];
      const buttons = [...document.querySelectorAll('.cat-btn')];
      const correctBtn = buttons.find(b => b.textContent.includes(q.category));
      if (correctBtn) correctBtn.classList.add('correct');
      buttons.forEach(b => b.disabled = true);
      showFeedback(`Time's up. ${q.tool} belongs to ${q.category}.`, false);
      current += 1;
      updateStats();
      setTimeout(() => {
        if (!active) return;
        if (current >= deck.length) finishGame();
        else loadQuestion();
      }, 850);
    }

    function skipQuestion() {
      if (!active || answered) return;
      answered = true;
      wrong += 1;
      const q = deck[current];
      const buttons = [...document.querySelectorAll('.cat-btn')];
      const correctBtn = buttons.find(b => b.textContent.includes(q.category));
      if (correctBtn) correctBtn.classList.add('correct');
      buttons.forEach(b => b.disabled = true);
      showFeedback(`Skipped. ${q.tool} belongs to ${q.category}.`, false);
      current += 1;
      updateStats();
      setTimeout(() => {
        if (!active) return;
        if (current >= deck.length) finishGame();
        else loadQuestion();
      }, 650);
    }

    function showFeedback(message, ok) {
      els.feedback.textContent = message;
      els.feedback.className = `feedback show ${ok ? 'ok' : 'no'}`;
      els.feedback.style.display = 'flex';
    }

    function finishGame() {
      if (!active) return;
      active = false;
      clearInterval(globalTick);
      clearInterval(toolTick);
      score += Math.max(0, remaining);
      els.progressBar.style.width = '100%';
      const attempts = correct + wrong;
      const accuracy = attempts ? Math.round((correct / attempts) * 100) : 0;
      els.finalScore.textContent = score;
      els.finalCorrect.textContent = correct;
      els.finalWrong.textContent = wrong;
      els.finalAccuracy.textContent = `${accuracy}%`;
      let msg = 'Good game!';
      if (accuracy === 100) msg = 'Perfect round — a true AI Matchmaker!';
      else if (accuracy >= 80) msg = 'Excellent performance — strong AI awareness.';
      else if (accuracy >= 60) msg = 'Solid performance — a little more practice will raise the score.';
      else msg = 'Keep practicing — your next round will improve quickly.';
      msg += remaining > 0 ? ` You earned ${remaining} bonus points from remaining time.` : ' Time expired.';
      els.endSub.textContent = msg;
      els.endScreen.style.display = 'grid';
      document.body.style.overflow = 'hidden';
      updateStats();
    }

    function resetToStartScreen() {
      active = false;
      clearInterval(globalTick);
      clearInterval(toolTick);
      els.endScreen.style.display = 'none';
      els.startScreen.style.display = 'grid';
      els.currentTool.textContent = '—';
      current = 0;
      updateStats();
    }

    els.restartBtn.addEventListener('click', resetToStartScreen);
    els.restartBtnSide.addEventListener('click', resetToStartScreen);
    els.reviewBtn.addEventListener('click', () => {
      els.endScreen.style.display = 'none';
      document.body.style.overflow = 'hidden';
    });
    els.skipBtn.addEventListener('click', skipQuestion);

    buildCategoryButtons();
    updateStats();
    els.currentTool.textContent = '—';
  </script>
</body>
</html>
