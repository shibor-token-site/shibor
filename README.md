<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Shibor Token</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #0d0d1a;
      color: #ffffff;
    }
    header {
      text-align: center;
      padding: 2rem 1rem;
      background-color: #111122;
    }
    .logo {
      width: 150px;
      animation: pulse 2s infinite;
    }
    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.05); }
      100% { transform: scale(1); }
    }
    h1 {
      margin-top: 1rem;
      font-size: 2.5rem;
      color: #ffe680;
    }
    section {
      padding: 2rem;
      max-width: 900px;
      margin: auto;
    }
    .buttons a {
      display: inline-block;
      margin: 1rem 1rem 0 0;
      padding: 0.75rem 1.5rem;
      background-color: #0077ff;
      color: white;
      border-radius: 10px;
      text-decoration: none;
      transition: 0.3s;
    }
    .buttons a:hover {
      background-color: #0055aa;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
    }
    .card {
      background-color: #1a1a2d;
      border-radius: 10px;
      padding: 1rem;
      box-shadow: 0 0 10px rgba(255, 255, 255, 0.05);
    }
    .card h3 {
      margin-top: 0;
      color: #ffcc00;
    }
    .footer {
      text-align: center;
      font-size: 0.85rem;
      color: #888;
      margin: 3rem 0 1rem;
    }
    .highlight {
      color: #00ffaa;
    }
    .scrolling-logos {
      overflow: hidden;
      white-space: nowrap;
      margin-top: 1rem;
    }
    .scrolling-logos span {
      display: inline-block;
      padding: 0 2rem;
      animation: scroll-left 15s linear infinite;
      font-size: 1.1rem;
      color: #00ccff;
    }
    @keyframes scroll-left {
      0% { transform: translateX(100%); }
      100% { transform: translateX(-100%); }
    }
    pre {
      background-color: #111;
      padding: 1rem;
      border-radius: 10px;
      overflow-x: auto;
    }
  </style>
</head>
<body>
  <header>
    <img src="logo_shbr.png" alt="Shibor Token Logo" class="logo" />
    <h1>SHIBOR TOKEN</h1>
    <div class="buttons">
      <a href="#">Join Telegram</a>
      <a href="#">Chat on LINE</a>
      <a href="#">Discord Server</a>
      <a href="#airdrop">Airdrop Signup</a>
    </div>
  </header>

  <section>
    <h2>AI Project Integration</h2>
    <div class="grid">
      <div class="card">
        <h3>Inner Bark AI</h3>
        <p>An emotional-aware AI assistant that interacts with users on LINE, Telegram, and Discord, responding intelligently to facial and voice emotion data via mobile camera consent.</p>
      </div>
      <div class="card">
        <h3>Alpha Companion Bot</h3>
        <p>A lightweight early-release version of the AI assistant, focusing on chat interactions, motivation boosts, and emotional monitoring.</p>
      </div>
      <div class="card">
        <h3>Emotion Token Utility</h3>
        <p>Use Shibor Tokens to unlock premium AI moods, personality traits, or generate digital pets based on your emotional state.</p>
      </div>
    </div>
  </section>

  <section>
    <h2>Partners & Alliances</h2>
    <div class="grid">
      <div class="card">
        <h3>OpenAI</h3>
        <p>Providing core GPT-powered conversational intelligence for the Shibor Token AI system.</p>
      </div>
      <div class="card">
        <h3>Solana Network</h3>
        <p>Chosen as the blockchain infrastructure for its speed, low fees, and developer ecosystem.</p>
      </div>
      <div class="card">
        <h3>Emotion AI Lab</h3>
        <p>Collaboration with emotion recognition researchers for camera-based mood detection via phone.</p>
      </div>
      <div class="card">
        <h3>Artifex Studio</h3>
        <p>2D/3D animation partner responsible for dynamic character rendering and logo animation on-chain.</p>
      </div>
      <div class="card">
        <h3>DEX & Exchange Partners</h3>
        <p>Solona DEX, CoinMarketCap, Sniper, MEXC, WEEk, XT, Bybit — facilitating liquidity, exposure, and market trust for Shibor Token.</p>
        <div class="scrolling-logos">
          <span>Solona DEX</span>
          <span>CoinMarketCap</span>
          <span>Sniper</span>
          <span>MEXC</span>
          <span>WEEk</span>
          <span>XT</span>
          <span>Bybit</span>
        </div>
      </div>
    </div>
  </section>

  <section id="airdrop">
    <h2>Whitepaper Overview</h2>
    <p class="highlight">A philosophical and technological exploration of AI, emotion, and decentralized utility in Shibor Token.</p>
    <div class="card">
      <h3>Shibor Token Philosophy</h3>
      <p>Inspired by Shiba Inu legacy, Shibor Token aims to balance AI with humanity. Using strategic tokenomics and emotional AI, we reflect the essence of being — play, connect, survive, and transcend.</p>
    </div>
    <div class="card">
      <h3>Roadmap</h3>
      <ul>
        <li><strong>Q2 2025:</strong> Alpha Bot release on LINE/Telegram</li>
        <li><strong>Q3 2025:</strong> Inner Bark AI beta with camera-based emotion</li>
        <li><strong>Q4 2025:</strong> Token DEX listings, NFT Pet minting</li>
        <li><strong>2026:</strong> Emotion Intelligence DAO, multilingual expansion</li>
      </ul>
    </div>
    <div class="card">
      <h3>Sample AI Model (Python Snippet)</h3>
      <pre><code>from transformers import pipeline

emotion = pipeline("text-classification", model="j-hartmann/emotion-english-distilroberta-base")

text = "I feel excited and inspired to help others."
result = emotion(text)
print(result)
# Output: [{'label': 'joy', 'score': 0.98}]</code></pre>
    </div>
    <div class="buttons">
      <a href="#">Download Whitepaper (PDF)</a>
      <a href="#">Project Roadmap</a>
    </div>
  </section>

  <div class="footer">
    &copy; 2025 Shibor Token. All rights reserved.
  </div>
</body>
</html>
