<img width="900" height="230" alt="hacker_banner_v2" src="https://github.com/user-attachments/assets/5d31de9a-10ea-400b-9c98-f6ccc60ecbc6" />
<svg width="900" height="230" viewBox="0 0 900 230" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg2" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#050810"/>
      <stop offset="50%" stop-color="#0a0f1a"/>
      <stop offset="100%" stop-color="#050810"/>
    </linearGradient>
    <linearGradient id="edge" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#00fff2"/>
      <stop offset="50%" stop-color="#ff00c8"/>
      <stop offset="100%" stop-color="#00fff2"/>
      <animateTransform attributeName="gradientTransform" type="translate" from="-1 0" to="1 0" dur="4s" repeatCount="indefinite"/>
    </linearGradient>
    <filter id="glow2">
      <feGaussianBlur stdDeviation="2" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <clipPath id="frame"><rect x="2" y="2" width="896" height="226" rx="14"/></clipPath>
    <style>
      .mono { font-family: 'Courier New', Consolas, monospace; }
      .cyan { fill: #00fff2; }
      .pink { fill: #ff00c8; }
      .faint { fill: #24405a; }
    </style>
  </defs>

  <rect width="900" height="230" rx="14" fill="url(#bg2)"/>
  <rect x="1.5" y="1.5" width="897" height="227" rx="14" fill="none" stroke="url(#edge)" stroke-width="2"/>

  <g clip-path="url(#frame)">
    <!-- circuit-line grid, faint -->
    <g stroke="#123047" stroke-width="1" opacity="0.6">
      <line x1="0" y1="40" x2="900" y2="40"/>
      <line x1="0" y1="190" x2="900" y2="190"/>
      <line x1="150" y1="0" x2="150" y2="230"/>
      <line x1="750" y1="0" x2="750" y2="230"/>
    </g>
    <g fill="#0d2136">
      <circle cx="150" cy="40" r="3"/>
      <circle cx="750" cy="40" r="3"/>
      <circle cx="150" cy="190" r="3"/>
      <circle cx="750" cy="190" r="3"/>
    </g>

    <!-- scrolling hex noise strip, top -->
    <g class="mono faint" font-size="12">
      <text x="0" y="24">
        4A 6F 1F 0E 9B C3 22 7D FF 01 55 AE 90 3C DE 12 88 4B 6A 71 2E 0F BB CC 44 19 A0 5D E7 F2 09 33
        <animate attributeName="x" from="0" to="-400" dur="9s" repeatCount="indefinite"/>
      </text>
    </g>
    <g class="mono faint" font-size="12">
      <text x="900" y="212">
        01 10 11 00 A5 5A F0 0F 3E C2 91 6D 7C 88 2B DA 4F 60 15 EE 33 09 C7 D1 8A 02 5F B4 71 3D 90 AC
        <animate attributeName="x" from="900" to="500" dur="11s" repeatCount="indefinite"/>
      </text>
    </g>

    <!-- decrypting name: glyph scramble settling into clean text -->
    <text x="450" y="105" text-anchor="middle" class="mono cyan" font-size="34" font-weight="bold" filter="url(#glow2)">
      <tspan>N¡k#¡L</tspan>
      <animate attributeName="opacity" values="1;1;0" keyTimes="0;0.15;0.18" dur="5s" begin="0s" fill="freeze"/>
    </text>
    <text x="450" y="105" text-anchor="middle" class="mono cyan" font-size="34" font-weight="bold" filter="url(#glow2)" opacity="0">
      <tspan>NIKHIL KALOKHE</tspan>
      <animate attributeName="opacity" values="0;0;1" keyTimes="0;0.18;0.22" dur="5s" begin="0s" fill="freeze"/>
    </text>

    <!-- decrypting tagline -->
    <text x="450" y="140" text-anchor="middle" class="mono pink" font-size="15" opacity="0">
      <tspan>[ decrypting_profile.sh ] --status=OK</tspan>
      <animate attributeName="opacity" values="0;0;1;1;0" keyTimes="0;0.3;0.35;0.55;0.6" dur="5s" begin="0s" fill="freeze"/>
    </text>
    <text x="450" y="140" text-anchor="middle" class="mono cyan" font-size="16" opacity="0">
      <tspan>Cybersecurity | Defending systems, breaking assumptions</tspan>
      <animate attributeName="opacity" values="0;0;1" keyTimes="0;0.62;0.7" dur="5s" begin="0s" fill="freeze"/>
    </text>

    <!-- footer status bar -->
    <text x="450" y="205" text-anchor="middle" class="mono faint" font-size="12" opacity="0">
      <tspan>ACCESS GRANTED :: SESSION ESTABLISHED</tspan>
      <animate attributeName="opacity" values="0;0;1;0.4;1" keyTimes="0;0.78;0.85;0.9;1" dur="5s" begin="0s" fill="freeze"/>
    </text>

    <!-- horizontal scanline sweep -->
    <rect x="0" y="0" width="900" height="6" fill="#00fff2" opacity="0.15">
      <animate attributeName="y" values="0;230;0" dur="6s" repeatCount="indefinite"/>
    </rect>
  </g>
</svg>
