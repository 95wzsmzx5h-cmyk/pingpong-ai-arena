# pingpong-ai-arena
Official landing page + policies for Ping Pong AI Arena (BYOK Chrome extension) and Ping Pong AI Arena Pro.
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Ping Pong AI Arena</title>
  <style>
    body{font-family:system-ui,Arial;max-width:880px;margin:40px auto;padding:0 16px;line-height:1.55}
    h1{margin:0 0 10px} .muted{color:#555}
    .card{border:1px solid #ddd;border-radius:14px;padding:16px;margin:16px 0}
    code{background:#f6f6f6;padding:2px 6px;border-radius:8px}
  </style>
</head>
<body>
  <h1>Ping Pong AI Arena</h1>
  <p class="muted">A BYOK Chrome extension that runs AI-vs-AI debate loops in Chrome Side Panel.</p>

  <div class="card">
    <h2>What it does</h2>
    <ul>
      <li>Runs a back-and-forth debate between two AI agents.</li>
      <li>Side Panel UI stays open while you browse.</li>
      <li>Custom personas via system prompts.</li>
    </ul>
  </div>

  <div class="card">
    <h2>Privacy (BYOK + Local Storage)</h2>
    <ul>
      <li>Your API key and settings are stored locally using <code>chrome.storage.local</code>.</li>
      <li>Prompts are sent directly from your browser to your selected AI provider endpoints.</li>
      <li>No developer-owned prompt relay servers.</li>
      <li>We do not collect browsing history, page content, cookies, or website traffic.</li>
    </ul>
  </div>

  <div class="card">
    <h2>Pro Upgrade</h2>
    <p><strong>Ping Pong AI Arena Pro</strong> unlocks higher turn limits / premium features.</p>
    <p><strong>Buy Pro:</strong> <em>PASTE YOUR STRIPE PAYMENT LINK HERE</em></p>
    <p>After purchase you’ll receive an activation phrase to enter in Settings.</p>
  </div>

  <div class="card">
    <h2>Support</h2>
    <p>Email: <strong>PASTE YOUR SUPPORT EMAIL HERE</strong></p>
  </div>

  <div class="card">
    <h2>Policies</h2>
    <p><a href="privacy.html">Privacy Policy</a></p>
    <p><a href="terms.html">Terms of Service</a></p>
    <p><strong>Refund policy:</strong> Refunds available within 7 days upon request (digital product). Contact support.</p>
  </div>

  <p class="muted">Not affiliated with any AI provider. Informational tool only (not financial advice).</p>
</body>
</html>
