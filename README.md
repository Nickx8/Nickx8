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
