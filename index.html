<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
<title>Vision9 — Create Your Universe</title>
<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700;900&family=Rajdhani:wght@300;400;600&display=swap" rel="stylesheet">
<style>
  :root {
    --cyan: #00f5ff;
    --purple: #b400ff;
    --dark: #020408;
    --dark2: #050d14;
    --card: #0a1520;
    --border: rgba(0,245,255,0.15);
    --glow: 0 0 20px rgba(0,245,255,0.3);
  }
  * { margin: 0; padding: 0; box-sizing: border-box; }
  body {
    background: var(--dark);
    color: #e0f0ff;
    font-family: 'Rajdhani', sans-serif;
    min-height: 100vh;
    overflow-x: hidden;
  }
  body::before {
    content: '';
    position: fixed;
    inset: 0;
    background-image:
      linear-gradient(rgba(0,245,255,0.03) 1px, transparent 1px),
      linear-gradient(90deg, rgba(0,245,255,0.03) 1px, transparent 1px);
    background-size: 50px 50px;
    pointer-events: none;
    z-index: 0;
  }
  .screen { display: none; min-height: 100vh; position: relative; z-index: 1; }
  .screen.active { display: flex; flex-direction: column; }

  /* LANDING */
  #landing { align-items: center; justify-content: center; text-align: center; padding: 40px 20px; }
  .logo {
    font-family: 'Orbitron', monospace;
    font-size: clamp(52px, 14vw, 96px);
    font-weight: 900;
    background: linear-gradient(135deg, var(--cyan), var(--purple));
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    letter-spacing: 4px;
    animation: pulse 3s ease-in-out infinite;
  }
  @keyframes pulse {
    0%,100% { filter: drop-shadow(0 0 20px rgba(0,245,255,0.5)); }
    50% { filter: drop-shadow(0 0 50px rgba(180,0,255,0.8)); }
  }
  .tagline { font-size: clamp(12px, 3.5vw, 16px); color: var(--cyan); letter-spacing: 3px; text-transform: uppercase; margin: 10px 0 30px; opacity: 0.8; }
  .hero-text { font-size: clamp(14px, 3.5vw, 18px); color: rgba(224,240,255,0.65); max-width: 480px; line-height: 1.8; margin: 0 auto 40px; }
  .hero-text span { color: var(--cyan); font-weight: 700; }
  .btn-primary {
    background: linear-gradient(135deg, var(--cyan), var(--purple));
    border: none; color: #000;
    font-family: 'Orbitron', monospace; font-size: 13px; font-weight: 700;
    padding: 16px 40px; border-radius: 4px; cursor: pointer;
    letter-spacing: 2px; text-transform: uppercase; transition: all 0.3s;
    box-shadow: 0 0 30px rgba(0,245,255,0.4);
    display: block; width: 100%; max-width: 300px; margin: 0 auto 12px;
  }
  .btn-primary:active { transform: scale(0.97); }
  .btn-secondary {
    background: transparent; border: 1px solid var(--border);
    color: var(--cyan); font-family: 'Rajdhani', sans-serif; font-size: 14px; font-weight: 600;
    padding: 14px 40px; border-radius: 4px; cursor: pointer;
    letter-spacing: 2px; text-transform: uppercase; transition: all 0.3s;
    display: block; width: 100%; max-width: 300px; margin: 0 auto 30px;
  }
  .stats { display: flex; gap: 30px; justify-content: center; flex-wrap: wrap; margin-top: 30px; }
  .stat { text-align: center; }
  .stat-num { font-family: 'Orbitron', monospace; font-size: 26px; font-weight: 700; color: var(--cyan); }
  .stat-label { font-size: 10px; color: rgba(224,240,255,0.4); letter-spacing: 2px; text-transform: uppercase; margin-top: 4px; }

  /* AUTH */
  #auth { align-items: center; justify-content: center; padding: 40px 20px; }
  .auth-card { background: var(--card); border: 1px solid var(--border); border-radius: 8px; padding: 40px 28px; width: 100%; max-width: 400px; box-shadow: var(--glow); }
  .auth-title { font-family: 'Orbitron', monospace; font-size: 20px; color: var(--cyan); text-align: center; margin-bottom: 28px; letter-spacing: 2px; }
  .form-group { margin-bottom: 18px; }
  .form-label { display: block; font-size: 11px; color: rgba(224,240,255,0.5); letter-spacing: 2px; text-transform: uppercase; margin-bottom: 7px; }
  .form-input { width: 100%; background: rgba(0,245,255,0.05); border: 1px solid var(--border); border-radius: 4px; padding: 12px 14px; color: #e0f0ff; font-family: 'Rajdhani', sans-serif; font-size: 16px; outline: none; transition: border-color 0.3s; }
  .form-input:focus { border-color: var(--cyan); }
  .auth-switch { text-align: center; margin-top: 18px; font-size: 13px; color: rgba(224,240,255,0.5); }
  .auth-switch a { color: var(--cyan); cursor: pointer; }

  /* DASHBOARD */
  #dashboard { padding: 0; }
  .top-nav { display: flex; align-items: center; justify-content: space-between; padding: 14px 18px; background: rgba(5,13,20,0.97); border-bottom: 1px solid var(--border); position: sticky; top: 0; z-index: 100; backdrop-filter: blur(12px); }
  .nav-logo { font-family: 'Orbitron', monospace; font-size: 20px; font-weight: 900; background: linear-gradient(135deg, var(--cyan), var(--purple)); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text; }
  .nav-avatar { width: 36px; height: 36px; border-radius: 50%; background: linear-gradient(135deg, var(--cyan), var(--purple)); display: flex; align-items: center; justify-content: center; font-family: 'Orbitron', monospace; font-size: 14px; font-weight: 700; color: #000; cursor: pointer; }
  .dash-body { padding: 22px 18px; }
  .section-title { font-family: 'Orbitron', monospace; font-size: 12px; color: var(--cyan); letter-spacing: 3px; text-transform: uppercase; margin-bottom: 16px; display: flex; align-items: center; gap: 10px; }
  .section-title::after { content: ''; flex: 1; height: 1px; background: var(--border); }
  .create-btn { background: linear-gradient(135deg, rgba(0,245,255,0.08), rgba(180,0,255,0.08)); border: 1px solid var(--cyan); border-radius: 8px; padding: 28px; text-align: center; cursor: pointer; transition: all 0.3s; margin-bottom: 28px; width: 100%; }
  .create-btn:active { background: rgba(0,245,255,0.15); }
  .create-icon { font-size: 36px; margin-bottom: 8px; }
  .create-text { font-family: 'Orbitron', monospace; font-size: 13px; color: var(--cyan); letter-spacing: 2px; }
  .worlds-grid { display: grid; grid-template-columns: repeat(2, 1fr); gap: 10px; }
  .world-card { background: var(--card); border: 1px solid var(--border); border-radius: 8px; overflow: hidden; cursor: pointer; transition: all 0.2s; position: relative; }
  .world-card:active { transform: scale(0.97); border-color: var(--cyan); }
  .world-thumb { width: 100%; aspect-ratio: 16/9; object-fit: cover; display: block; }
  .world-info { padding: 8px 10px; }
  .world-name { font-size: 12px; font-weight: 600; color: #e0f0ff; white-space: nowrap; overflow: hidden; text-overflow: ellipsis; }
  .world-meta { font-size: 10px; color: rgba(224,240,255,0.4); margin-top: 2px; }
  .world-badge { position: absolute; top: 6px; right: 6px; background: rgba(0,245,255,0.2); border: 1px solid var(--cyan); border-radius: 3px; padding: 2px 5px; font-size: 8px; color: var(--cyan); font-family: 'Orbitron', monospace; }
  .empty-state { grid-column: 1/-1; text-align: center; padding: 40px 20px; color: rgba(224,240,255,0.3); }
  .empty-icon { font-size: 44px; margin-bottom: 12px; }
  .empty-text { font-size: 13px; line-height: 1.7; }

  /* CREATE */
  #create { padding: 0; }
  .create-header { display: flex; align-items: center; gap: 14px; padding: 14px 18px; background: rgba(5,13,20,0.97); border-bottom: 1px solid var(--border); position: sticky; top: 0; z-index: 100; }
  .back-btn { background: transparent; border: 1px solid var(--border); border-radius: 4px; color: var(--cyan); padding: 8px 12px; cursor: pointer; font-size: 15px; }
  .create-step-title { font-family: 'Orbitron', monospace; font-size: 12px; color: var(--cyan); letter-spacing: 2px; }
  .create-body { padding: 22px 18px; }
  .steps { display: flex; gap: 6px; margin-bottom: 28px; }
  .step { flex: 1; height: 3px; background: var(--border); border-radius: 2px; transition: background 0.3s; }
  .step.active { background: var(--cyan); box-shadow: 0 0 8px var(--cyan); }
  .step.done { background: var(--purple); }
  .upload-zone { border: 2px dashed var(--border); border-radius: 8px; padding: 46px 18px; text-align: center; cursor: pointer; transition: all 0.3s; margin-bottom: 18px; position: relative; overflow: hidden; }
  .upload-zone input { position: absolute; inset: 0; opacity: 0; cursor: pointer; width: 100%; height: 100%; }
  .upload-icon { font-size: 44px; margin-bottom: 14px; }
  .upload-title { font-family: 'Orbitron', monospace; font-size: 13px; color: var(--cyan); margin-bottom: 6px; letter-spacing: 2px; }
  .upload-sub { font-size: 12px; color: rgba(224,240,255,0.4); }
  .preview-img { width: 100%; border-radius: 8px; border: 1px solid var(--cyan); margin-bottom: 18px; display: none; max-height: 200px; object-fit: cover; }
  .world-name-input { width: 100%; background: rgba(0,245,255,0.05); border: 1px solid var(--border); border-radius: 4px; padding: 13px 14px; color: #e0f0ff; font-family: 'Rajdhani', sans-serif; font-size: 16px; outline: none; margin-bottom: 16px; transition: border-color 0.3s; }
  .world-name-input:focus { border-color: var(--cyan); }
  .assets-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 12px; margin-bottom: 18px; }
  .asset-upload { border: 1px dashed var(--border); border-radius: 8px; padding: 20px 14px; text-align: center; cursor: pointer; transition: all 0.2s; position: relative; overflow: hidden; }
  .asset-upload input { position: absolute; inset: 0; opacity: 0; cursor: pointer; width: 100%; height: 100%; }
  .asset-icon { font-size: 26px; margin-bottom: 6px; }
  .asset-label { font-size: 10px; color: rgba(224,240,255,0.5); letter-spacing: 1px; text-transform: uppercase; }
  .asset-preview { width: 56px; height: 56px; object-fit: contain; margin: 0 auto 6px; display: none; }

  /* WORLD */
  #world { position: fixed; inset: 0; z-index: 500; background: #000; display: none; }
  #world.open { display: block; }
  #three-canvas { position: absolute; inset: 0; width: 100%; height: 100%; display: block; }
  .world-ui { position: absolute; inset: 0; pointer-events: none; z-index: 10; }
  .world-top { display: flex; align-items: center; justify-content: space-between; padding: 14px; background: linear-gradient(180deg, rgba(0,0,0,0.85) 0%, transparent 100%); pointer-events: all; }
  .world-title-ui { font-family: 'Orbitron', monospace; font-size: 13px; color: var(--cyan); letter-spacing: 2px; }
  .world-top-btns { display: flex; gap: 8px; }
  .ui-btn { background: rgba(0,0,0,0.75); border: 1px solid var(--border); border-radius: 4px; color: var(--cyan); padding: 7px 12px; cursor: pointer; font-size: 11px; font-family: 'Orbitron', monospace; letter-spacing: 1px; pointer-events: all; }
  .ui-btn.danger { color: #ff5555; border-color: rgba(255,85,85,0.3); }
  .crosshair { position: absolute; top: 50%; left: 50%; transform: translate(-50%,-50%); width: 18px; height: 18px; pointer-events: none; }
  .crosshair::before,.crosshair::after { content: ''; position: absolute; background: rgba(0,245,255,0.9); border-radius: 1px; }
  .crosshair::before { width: 18px; height: 1px; top: 50%; left: 0; transform: translateY(-50%); }
  .crosshair::after { width: 1px; height: 18px; left: 50%; top: 0; transform: translateX(-50%); }
  .sprite-container { position: absolute; bottom: 0; left: 0; right: 0; height: 210px; pointer-events: none; display: flex; align-items: flex-end; justify-content: center; gap: 20px; padding-bottom: 170px; }
  .sprite-img { max-height: 150px; max-width: 100px; object-fit: contain; filter: drop-shadow(0 0 12px rgba(0,245,255,0.6)); display: none; }
  .effects-bar { position: absolute; bottom: 200px; left: 12px; right: 12px; display: flex; gap: 6px; pointer-events: all; flex-wrap: wrap; justify-content: center; }
  .effect-btn { background: rgba(0,0,0,0.8); border: 1px solid var(--border); border-radius: 20px; color: rgba(224,240,255,0.7); padding: 5px 12px; cursor: pointer; font-size: 11px; font-family: 'Rajdhani', sans-serif; letter-spacing: 1px; pointer-events: all; }
  .effect-btn.active { border-color: var(--cyan); color: var(--cyan); background: rgba(0,245,255,0.1); }
  .prompt-area { position: absolute; bottom: 158px; left: 12px; right: 12px; display: flex; gap: 6px; pointer-events: all; }
  .prompt-input { flex: 1; background: rgba(0,0,0,0.88); border: 1px solid var(--border); border-radius: 4px; padding: 10px 12px; color: #e0f0ff; font-family: 'Rajdhani', sans-serif; font-size: 14px; outline: none; }
  .prompt-input:focus { border-color: var(--cyan); }
  .prompt-input::placeholder { color: rgba(224,240,255,0.3); }
  .prompt-send { background: var(--cyan); border: none; border-radius: 4px; color: #000; padding: 10px 14px; cursor: pointer; font-size: 15px; font-weight: 700; }
  .controls-area { position: absolute; bottom: 0; left: 0; right: 0; padding: 12px 16px; background: linear-gradient(0deg, rgba(0,0,0,0.92) 0%, transparent 100%); display: flex; align-items: flex-end; justify-content: space-between; pointer-events: all; }
  .dpad { display: grid; grid-template-columns: repeat(3,1fr); grid-template-rows: repeat(3,1fr); gap: 3px; width: 112px; height: 112px; }
  .dpad-btn { background: rgba(0,0,0,0.75); border: 1px solid var(--border); border-radius: 4px; color: var(--cyan); cursor: pointer; display: flex; align-items: center; justify-content: center; font-size: 17px; -webkit-user-select: none; user-select: none; -webkit-tap-highlight-color: transparent; }
  .dpad-btn:active { background: rgba(0,245,255,0.25); }
  .right-controls { display: flex; flex-direction: column; align-items: flex-end; gap: 8px; }
  .apk-btn { background: linear-gradient(135deg, var(--cyan), var(--purple)); border: none; border-radius: 4px; color: #000; font-family: 'Orbitron', monospace; font-size: 10px; font-weight: 700; padding: 10px 13px; cursor: pointer; letter-spacing: 1px; box-shadow: 0 0 20px rgba(0,245,255,0.35); }
  .particles { position: absolute; inset: 0; pointer-events: none; overflow: hidden; }
  .particle { position: absolute; border-radius: 50%; animation: fall linear infinite; }
  @keyframes fall { 0% { transform: translateY(-20px) translateX(0); opacity: 1; } 100% { transform: translateY(105vh) translateX(var(--drift,0px)); opacity: 0; } }
  .night-overlay { position: absolute; inset: 0; background: rgba(0,0,20,0.65); pointer-events: none; display: none; z-index: 5; }
  .night-overlay.on { display: block; }
  .fog-overlay { position: absolute; inset: 0; background: radial-gradient(ellipse at center, transparent 20%, rgba(180,210,255,0.35) 100%); pointer-events: none; display: none; z-index: 5; animation: fogPulse 7s ease-in-out infinite; }
  @keyframes fogPulse { 0%,100%{opacity:.4} 50%{opacity:.8} }
  .fog-overlay.on { display: block; }
  .sunrise-overlay { position: absolute; inset: 0; background: linear-gradient(180deg, rgba(255,110,0,0.35) 0%, transparent 45%); pointer-events: none; display: none; z-index: 5; }
  .sunrise-overlay.on { display: block; }

  /* LOADING */
  .loading-overlay { position: fixed; inset: 0; background: var(--dark); z-index: 2000; display: none; flex-direction: column; align-items: center; justify-content: center; }
  .loading-overlay.on { display: flex; }
  .loading-logo { font-family: 'Orbitron', monospace; font-size: 34px; font-weight: 900; background: linear-gradient(135deg, var(--cyan), var(--purple)); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text; margin-bottom: 28px; animation: pulse 1.5s ease-in-out infinite; }
  .loading-bar-wrap { width: 200px; height: 3px; background: var(--border); border-radius: 2px; overflow: hidden; margin-bottom: 14px; }
  .loading-bar { height: 100%; background: linear-gradient(90deg, var(--cyan), var(--purple)); border-radius: 2px; animation: loadAnim 1.8s ease-in-out infinite; }
  @keyframes loadAnim { 0%{width:0%} 100%{width:100%} }
  .loading-text { font-size: 11px; color: rgba(224,240,255,0.5); letter-spacing: 3px; text-transform: uppercase; }

  /* TOAST */
  .toast { position: fixed; bottom: 28px; left: 50%; transform: translateX(-50%) translateY(80px); background: var(--card); border: 1px solid var(--cyan); border-radius: 4px; padding: 11px 22px; color: var(--cyan); font-size: 12px; letter-spacing: 1px; z-index: 9999; transition: transform 0.3s; box-shadow: var(--glow); white-space: nowrap; pointer-events: none; }
  .toast.on { transform: translateX(-50%) translateY(0); }

  ::-webkit-scrollbar { width: 3px; }
  ::-webkit-scrollbar-thumb { background: var(--border); border-radius: 2px; }
</style>
</head>
<body>

<div class="loading-overlay" id="loadingOverlay">
  <div class="loading-logo">VISION9</div>
  <div class="loading-bar-wrap"><div class="loading-bar"></div></div>
  <div class="loading-text" id="loadingText">Generating Universe...</div>
</div>

<div class="toast" id="toast"></div>

<!-- LANDING -->
<div class="screen active" id="landing">
  <div class="logo">VISION9</div>
  <div class="tagline">Your Universe, One Image Away</div>
  <p class="hero-text">
    What studios spend <span>billions</span> to build,<br>
    Vision9 creates in <span>seconds</span>.<br>
    Upload any image. Walk inside it. Own it.
  </p>
  <button class="btn-primary" onclick="showScreen('auth','signup')">CREATE YOUR UNIVERSE</button>
  <button class="btn-secondary" onclick="showScreen('auth','login')">SIGN IN</button>
  <div class="stats">
    <div class="stat"><div class="stat-num" id="statWorlds">0</div><div class="stat-label">Worlds Created</div></div>
    <div class="stat"><div class="stat-num">∞</div><div class="stat-label">Possibilities</div></div>
    <div class="stat"><div class="stat-num">&lt;3s</div><div class="stat-label">Generation Time</div></div>
  </div>
</div>

<!-- AUTH -->
<div class="screen" id="auth">
  <div style="flex:1;display:flex;align-items:center;justify-content:center;padding:40px 20px;">
    <div class="auth-card">
      <div class="auth-title" id="authTitle">CREATE ACCOUNT</div>
      <div class="form-group" id="nameGroup">
        <label class="form-label">Username</label>
        <input type="text" class="form-input" id="authName" placeholder="Choose a username">
      </div>
      <div class="form-group">
        <label class="form-label">Email</label>
        <input type="email" class="form-input" id="authEmail" placeholder="your@email.com">
      </div>
      <div class="form-group">
        <label class="form-label">Password</label>
        <input type="password" class="form-input" id="authPass" placeholder="••••••••">
      </div>
      <button class="btn-primary" onclick="handleAuth()">ENTER</button>
      <div class="auth-switch">
        <span id="authSwitchText">Already have an account?</span>
        <a onclick="toggleAuth()" id="authSwitchLink"> Sign In</a>
      </div>
      <div style="margin-top:14px;">
        <button class="btn-secondary" onclick="showScreen('landing')" style="font-size:11px;padding:10px;">← BACK</button>
      </div>
    </div>
  </div>
</div>

<!-- DASHBOARD -->
<div class="screen" id="dashboard">
  <div class="top-nav">
    <div class="nav-logo">V9</div>
    <div style="display:flex;align-items:center;gap:10px;">
      <div style="font-size:12px;color:rgba(224,240,255,0.55);" id="navUsername"></div>
      <div class="nav-avatar" id="navAvatar" onclick="logout()">?</div>
    </div>
  </div>
  <div class="dash-body">
    <div class="section-title">CREATE NEW</div>
    <div class="create-btn" onclick="showScreen('create')">
      <div class="create-icon">🌌</div>
      <div class="create-text">+ NEW UNIVERSE</div>
    </div>
    <div class="section-title">MY WORLDS</div>
    <div class="worlds-grid" id="worldsGrid">
      <div class="empty-state"><div class="empty-icon">🪐</div><div class="empty-text">No worlds yet.<br>Create your first universe.</div></div>
    </div>
  </div>
</div>

<!-- CREATE -->
<di
