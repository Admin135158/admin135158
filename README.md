<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Architect | Morpheus Innovations</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      background: #0a0a0a;
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      font-family: 'Courier New', 'Fira Code', monospace;
      padding: 2rem;
    }
    .container {
      max-width: 1000px;
      width: 100%;
    }
    .glitch {
      font-size: 1rem;
      color: #0f0;
      white-space: pre-wrap;
      word-break: break-word;
      animation: glitch 0.2s infinite alternate;
    }
    @keyframes glitch {
      0% { text-shadow: -2px 0 #f0f, 2px 0 #0ff; opacity: 0.9; }
      100% { text-shadow: 2px 0 #f0f, -2px 0 #0ff; opacity: 1; }
    }
    .ascii-box {
      background: #0a0a0a;
      border: 1px solid #c084fc;
      border-radius: 12px;
      padding: 1.5rem;
      margin: 1rem 0;
      box-shadow: 0 0 20px rgba(192, 132, 252, 0.2);
      transition: all 0.3s ease;
    }
    .ascii-box:hover {
      box-shadow: 0 0 35px rgba(192, 132, 252, 0.5);
      border-color: #a855f7;
    }
    pre {
      color: #c084fc;
      font-family: monospace;
      font-size: 0.7rem;
      overflow-x: auto;
      white-space: pre-wrap;
      word-break: break-word;
    }
    .green pre { color: #4ade80; }
    .cyan pre { color: #22d3ee; }
    .purple pre { color: #c084fc; }
    .red pre { color: #f87171; }
    h1, h2, h3 {
      text-align: center;
      color: #c084fc;
      margin: 0.5rem 0;
    }
    hr {
      border-color: #c084fc;
      margin: 1rem 0;
    }
    @media (max-width: 600px) {
      pre { font-size: 0.4rem; }
      .ascii-box { padding: 0.8rem; }
    }
  </style>
</head>
<body>
<div class="container">
  <div class="ascii-box purple glitch">
    <pre>
╔═══════════════════════════════════════════════════════════════════════════╗
║  ███████╗███████╗██████╗ ███╗   ██╗ █████╗ ███╗   ██╗██████╗  ██████╗     ║
║  ██╔════╝██╔════╝██╔══██╗████╗  ██║██╔══██╗████╗  ██║██╔══██╗██╔═══██╗    ║
║  █████╗  █████╗  ██████╔╝██╔██╗ ██║███████║██╔██╗ ██║██║  ██║██║   ██║    ║
║  ██╔══╝  ██╔══╝  ██╔══██╗██║╚██╗██║██╔══██║██║╚██╗██║██║  ██║██║   ██║    ║
║  ██║     ███████╗██║  ██║██║ ╚████║██║  ██║██║ ╚████║██████╔╝╚██████╔╝    ║
║  ╚═╝     ╚══════╝╚═╝  ╚═╝╚═╝  ╚═══╝╚═╝  ╚═╝╚═╝  ╚═══╝╚═════╝  ╚═════╝     ║
╚═══════════════════════════════════════════════════════════════════════════╝
    </pre>
  </div>

  <div class="ascii-box cyan">
    <pre>
╔═══════════════════════════════════════════════════════════════════════════╗
║                    FERNANDO DE JESUS GARCIA GONZALEZ                      ║
║                 ARCHITECT | MORPHEUS INNOVATIONS | SECURITY               ║
╚═══════════════════════════════════════════════════════════════════════════╝
    </pre>
  </div>

  <div class="ascii-box green">
    <pre>
┌─────────────────────────────────────────────────────────────────────────┐
│  P2 SECURITY RESEARCH                                                   │
│  "The mirror is the code. The code is the law. The law is the 30% Rider."│
│                                                                         │
│  OS | GORF OLLIN 9 | SECURITY | P2 RESEARCHER | APPLE | CONSULTANT      │
└─────────────────────────────────────────────────────────────────────────┘
    </pre>
  </div>

  <div class="ascii-box purple">
    <pre>
╔═══════════════════════════════════════════════════════════════════════════╗
║     MORPHEUS INNOVATIONS AND TECHNOLOGIES HOLDINGS LLC                    ║
║  System design, high‑entropy physics, and architectural security.        ║
║  We don't build software; we build reality‑anchors.                      ║
║                                                                           ║
║  • GORF Equations: Guardian of the Ollin Identity (O=9).                 ║
║  • Rider Enforcement: All IP licensed via mandatory 30% perpetuity clause.║
║  • Digital Bodyguard: DERAIL | EXPOSE FAKE | REPORT | REJECT | RELEASE.  ║
╚═══════════════════════════════════════════════════════════════════════════╝
    </pre>
  </div>

  <div class="ascii-box red">
    <pre>
┌─────────────────────────────────────────────────────────────────────────┐
│  ⚠️ ARCHITECT'S WARNING                                                 │
│  The swarm isn't coming. It's already compiling.                        │
│  Gatekeepers, meet your match.                                          │
└─────────────────────────────────────────────────────────────────────────┘
    </pre>
  </div>
</div>
</body>
</html>
