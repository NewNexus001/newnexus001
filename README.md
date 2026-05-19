<!-- VENOM HEADER: Glitchy name reveal + blinking cursor -->
<p align="center">
  <svg width="100%" height="150" viewBox="0 0 800 150" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <filter id="neonGlow">
        <feGaussianBlur stdDeviation="4" result="blur" />
        <feMerge>
          <feMergeNode in="blur" />
          <feMergeNode in="blur" />
          <feMergeNode in="SourceGraphic" />
        </feMerge>
      </filter>
      <clipPath id="nameClip">
        <rect x="0" y="0" width="0" height="150">
          <animate attributeName="width" from="0" to="800" dur="2s" fill="freeze" />
        </rect>
      </clipPath>
      <style>
        .name-text {
          font-family: 'Courier New', monospace;
          font-size: 60px;
          font-weight: bold;
          fill: #00ff41;
          filter: url(#neonGlow);
        }
        .cursor {
          font-family: 'Courier New', monospace;
          font-size: 60px;
          fill: #00ff41;
          animation: blink 1s step-end infinite;
        }
        @keyframes blink {
          50% { opacity: 0; }
        }
      </style>
    </defs>
    <!-- Dark background to make neon pop -->
    <rect width="800" height="150" fill="#0d1117" />
    <!-- Name revealed from left to right -->
    <text class="name-text" x="10" y="90" clip-path="url(#nameClip)">IJEOMA JANE OKOJIE</text>
    <!-- Blinking cursor after the name -->
    <text class="cursor" x="805" y="90">_</text>
  </svg>
</p>

<!-- SUBTITLE & TYPEWRITER SKILLS -->
<p align="center">
  <svg width="100%" height="70" viewBox="0 0 800 70" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <style>
        .skill {
          font-family: 'Courier New', monospace;
          font-size: 20px;
          fill: #00ff41;
        }
        /* Each skill has its own animation to cycle opacity */
        .s0  { animation: a0 60s infinite; }
        .s1  { animation: a1 60s infinite; }
        .s2  { animation: a2 60s infinite; }
        .s3  { animation: a3 60s infinite; }
        .s4  { animation: a4 60s infinite; }
        .s5  { animation: a5 60s infinite; }
        .s6  { animation: a6 60s infinite; }
        .s7  { animation: a7 60s infinite; }
        .s8  { animation: a8 60s infinite; }
        .s9  { animation: a9 60s infinite; }
        .s10 { animation: a10 60s infinite; }
        .s11 { animation: a11 60s infinite; }
        .s12 { animation: a12 60s infinite; }
        .s13 { animation: a13 60s infinite; }
        .s14 { animation: a14 60s infinite; }
        .s15 { animation: a15 60s infinite; }
        .s16 { animation: a16 60s infinite; }
        .s17 { animation: a17 60s infinite; }
        .s18 { animation: a18 60s infinite; }
        .s19 { animation: a19 60s infinite; }
        /* Keyframes for 20 skills (each visible ~3s, total cycle 60s) */
        @keyframes a0  { 0%,4.16% {opacity:0} 4.17%,8.32% {opacity:1} 8.33%,100% {opacity:0} }
        @keyframes a1  { 0%,4.16% {opacity:0} 4.17%,8.33% {opacity:0} 8.34%,12.5% {opacity:1} 12.51%,100% {opacity:0} }
        @keyframes a2  { 0%,8.33% {opacity:0} 8.34%,12.5% {opacity:0} 12.51%,16.67% {opacity:1} 16.68%,100% {opacity:0} }
        @keyframes a3  { 0%,12.5% {opacity:0} 12.51%,16.67% {opacity:0} 16.68%,20.83% {opacity:1} 20.84%,100% {opacity:0} }
        @keyframes a4  { 0%,16.67% {opacity:0} 16.68%,20.83% {opacity:0} 20.84%,25% {opacity:1} 25.01%,100% {opacity:0} }
        @keyframes a5  { 0%,20.83% {opacity:0} 20.84%,25% {opacity:0} 25.01%,29.16% {opacity:1} 29.17%,100% {opacity:0} }
        @keyframes a6  { 0%,25% {opacity:0} 25.01%,29.16% {opacity:0} 29.17%,33.33% {opacity:1} 33.34%,100% {opacity:0} }
        @keyframes a7  { 0%,29.16% {opacity:0} 29.17%,33.33% {opacity:0} 33.34%,37.5% {opacity:1} 37.51%,100% {opacity:0} }
        @keyframes a8  { 0%,33.33% {opacity:0} 33.34%,37.5% {opacity:0} 37.51%,41.66% {opacity:1} 41.67%,100% {opacity:0} }
        @keyframes a9  { 0%,37.5% {opacity:0} 37.51%,41.66% {opacity:0} 41.67%,45.83% {opacity:1} 45.84%,100% {opacity:0} }
        @keyframes a10 { 0%,41.66% {opacity:0} 41.67%,45.83% {opacity:0} 45.84%,50% {opacity:1} 50.01%,100% {opacity:0} }
        @keyframes a11 { 0%,45.83% {opacity:0} 45.84%,50% {opacity:0} 50.01%,54.16% {opacity:1} 54.17%,100% {opacity:0} }
        @keyframes a12 { 0%,50% {opacity:0} 50.01%,54.16% {opacity:0} 54.17%,58.33% {opacity:1} 58.34%,100% {opacity:0} }
        @keyframes a13 { 0%,54.16% {opacity:0} 54.17%,58.33% {opacity:0} 58.34%,62.5% {opacity:1} 62.51%,100% {opacity:0} }
        @keyframes a14 { 0%,58.33% {opacity:0} 58.34%,62.5% {opacity:0} 62.51%,66.66% {opacity:1} 66.67%,100% {opacity:0} }
        @keyframes a15 { 0%,62.5% {opacity:0} 62.51%,66.66% {opacity:0} 66.67%,70.83% {opacity:1} 70.84%,100% {opacity:0} }
        @keyframes a16 { 0%,66.66% {opacity:0} 66.67%,70.83% {opacity:0} 70.84%,75% {opacity:1} 75.01%,100% {opacity:0} }
        @keyframes a17 { 0%,70.83% {opacity:0} 70.84%,75% {opacity:0} 75.01%,79.16% {opacity:1} 79.17%,100% {opacity:0} }
        @keyframes a18 { 0%,75% {opacity:0} 75.01%,79.16% {opacity:0} 79.17%,83.33% {opacity:1} 83.34%,100% {opacity:0} }
        @keyframes a19 { 0%,79.16% {opacity:0} 79.17%,83.33% {opacity:0} 83.34%,87.5% {opacity:1} 87.51%,100% {opacity:0} }
      </style>
    </defs>
    <rect width="800" height="70" fill="#0d1117" />
    <!-- All skill texts overlap at the same position, only one visible at a time -->
    <text x="20" y="45">
      <tspan class="skill s0">Upscale Video to 8K AI Pipeline</tspan>
      <tspan class="skill s1">Image Upscaling &amp; Restoration</tspan>
      <tspan class="skill s2">Game Development (Unity, Unreal)</tspan>
      <tspan class="skill s3">Desktop &amp; Mobile App Development</tspan>
      <tspan class="skill s4">Full-Stack Web (React, Node)</tspan>
      <tspan class="skill s5">HTML5, CSS3, JS, TypeScript</tspan>
      <tspan class="skill s6">Rust &amp; Systems Programming</tspan>
      <tspan class="skill s7">Python &amp; AI/Data Science</tspan>
      <tspan class="skill s8">C, C++, C# (.NET)</tspan>
      <tspan class="skill s9">Ruby, PHP, Go, Solidity</tspan>
      <tspan class="skill s10">Cybersecurity &amp; Ethical Hacking</tspan>
      <tspan class="skill s11">Data Scraping &amp; Mining</tspan>
      <tspan class="skill s12">Animation &amp; Motion Graphics</tspan>
      <tspan class="skill s13">Graphic Design (Flyers, Posters)</tspan>
      <tspan class="skill s14">Video Editing &amp; Ad Creation</tspan>
      <tspan class="skill s15">Hex Editing &amp; Qualcomm Bits</tspan>
      <tspan class="skill s16">Web3 &amp; Blockchain</tspan>
      <tspan class="skill s17">DevOps &amp; Cloud</tspan>
      <tspan class="skill s18">Meeting &amp; Project Management</tspan>
      <tspan class="skill s19">Can Code Any Language Fluently</tspan>
    </text>
  </svg>
</p>

<!-- BADGES: Nigeria, Web3, Status -->
<p align="center">
  <img src="https://img.shields.io/badge/Nigeria-%F0%9F%87%B3%F0%9F%87%AC-brightgreen?style=flat-square" alt="Nigerian" />
  <img src="https://img.shields.io/badge/Web3-Enabled-blue?style=flat-square&logo=ethereum" alt="Web3" />
  <img src="https://img.shields.io/badge/Status-Available%20for%20Hire-brightgreen?style=flat-square" alt="Available" />
  <img src="https://img.shields.io/badge/Building-Something%20Epic-orange?style=flat-square" alt="Building" />
</p>

<!-- LANGUAGE & TECH LOGOS with hover scale + glow -->
<p align="center">
  <svg width="480" height="320" viewBox="0 0 480 320" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <style>
        .icon {
          transition: transform 0.2s ease;
          transform-origin: 24px 24px;
        }
        .icon:hover {
          transform: scale(1.35);
          filter: drop-shadow(0 0 8px #00ff41);
        }
      </style>
    </defs>
    <!-- Row 1 -->
    <g class="icon" transform="translate(10, 10)">
      <title>Python</title>
      <image href="https://cdn.simpleicons.org/python/00ff41" width="48" height="48" />
    </g>
    <g class="icon" transform="translate(80, 10)">
      <title>Rust</title>
      <image href="https://cdn.simpleicons.org/rust/00ff41" width="48" height="48" />
    </g>
    <g class="icon" transform="translate(150, 10)">
      <title>C</title>
      <image href="https://cdn.simpleicons.org/c/00ff41" width="48" height="48" />
    </g>
    <g class="icon" transform="translate(220, 10)">
      <title>C++</title>
      <image href="https://cdn.simpleicons.org/cplusplus/00ff41" width="48" height="48" />
    </g>
    <g class="icon" transform="translate(290, 10)">
      <title>C#</title>
      <image href="https://cdn.simpleicons.org/csharp/00ff41" width="48" height="48" />
    </g>
    <g class="icon" transform="translate(360, 10)">
      <title>Ruby</title>
      <image href="https://cdn.simpleicons.org/ruby/00ff41" width="48" height="48" />
    </g>
    <!-- Row 2 -->
    <g class="icon" transform="translate(10, 80)">
      <title>JavaScript</title>
      <image href="https://cdn.simpleicons.org/javascript/00ff41" width="48" height="48" />
    </g>
    <g class="icon" transform="translate(80, 80)">
      <title>TypeScript</title>
      <image href="https://cdn.simpleicons.org/typescript/00ff41" width="48" height="48" />
    </g>
    <g class="icon" transform="translate(150, 80)">
      <title>Go</title>
      <image href="https://cdn.simpleicons.org/go/00ff41" width="48" height="48" />
    </g>
    <g class="icon" transform="translate(220, 80)">
      <title>Solidity</title>
      <image href="https://cdn.simpleicons.org/solidity/00ff41" width="48" height="48" />
    </g>
    <g class="icon" transform="translate(290, 80)">
      <title>Java</title>
      <image href="https://cdn.simpleicons.org/java/00ff41" width="48" height="48" />
    </g>
    <g class="icon" transform="translate(360, 80)">
      <title>Kotlin</title>
      <image href="https://cdn.simpleicons.org/kotlin/00ff41" width="48" height="48" />
    </g>
    <!-- Row 3 -->
    <g class="icon" transform="translate(10, 150)">
      <title>Swift</title>
      <image href="https://cdn.simpleicons.org/swift/00ff41" width="48" height="48" />
    </g>
    <g class="icon" transform="translate(80, 150)">
      <title>Dart</title>
      <image href="https://cdn.simpleicons.org/dart/00ff41" width="48" height="48" />
    </g>
    <g class="icon" transform="translate(150, 150)">
      <title>PHP</title>
      <image href="https://cdn.simpleicons.org/php/00ff41" width="48" height="48" />
    </g>
    <g class="icon" transform="translate(220, 150)">
      <title>HTML5</title>
      <image href="https://cdn.simpleicons.org/html5/00ff41" width="48" height="48" />
    </g>
    <g class="icon" transform="translate(290, 150)">
      <title>CSS3</title>
      <image href="https://cdn.simpleicons.org/css3/00ff41" width="48" height="48" />
    </g>
    <g class="icon" transform="translate(360, 150)">
      <title>Node.js</title>
      <image href="https://cdn.simpleicons.org/nodedotjs/00ff41" width="48" height="48" />
    </g>
    <!-- Row 4 -->
    <g class="icon" transform="translate(10, 220)">
      <title>React</title>
      <image href="https://cdn.simpleicons.org/react/00ff41" width="48" height="48" />
    </g>
    <g class="icon" transform="translate(80, 220)">
      <title>Git</title>
      <image href="https://cdn.simpleicons.org/git/00ff41" width="48" height="48" />
    </g>
    <g class="icon" transform="translate(150, 220)">
      <title>Docker</title>
      <image href="https://cdn.simpleicons.org/docker/00ff41" width="48" height="48" />
    </g>
    <g class="icon" transform="translate(220, 220)">
      <title>Linux</title>
      <image href="https://cdn.simpleicons.org/linux/00ff41" width="48" height="48" />
    </g>
    <g class="icon" transform="translate(290, 220)">
      <title>PostgreSQL</title>
      <image href="https://cdn.simpleicons.org/postgresql/00ff41" width="48" height="48" />
    </g>
    <g class="icon" transform="translate(360, 220)">
      <title>GitHub</title>
      <image href="https://cdn.simpleicons.org/github/00ff41" width="48" height="48" />
    </g>
  </svg>
</p>

<!-- LIVE GITHUB STATS -->
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=NewNexus001&show_icons=true&theme=merko" alt="GitHub Stats" width="48%" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=NewNexus001&theme=merko" alt="Streak" width="48%" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=NewNexus001&layout=compact&theme=merko" alt="Top Languages" />
</p>

<!-- SNAKE EATING CONTRIBUTIONS (Animated SVG from a GitHub Action) -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github.com/NewNexus001/NewNexus001/blob/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://github.com/NewNexus001/NewNexus001/blob/output/github-contribution-grid-snake.svg" />
    <img alt="github contribution grid snake animation" src="https://github.com/NewNexus001/NewNexus001/blob/output/github-contribution-grid-snake.svg" />
  </picture>
</p>

<!-- TROPHY CASE -->
<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=NewNexus001&theme=algolia&margin-w=15" alt="Trophies" />
</p>

<!-- ACTIVITY GRAPH (neon green) -->
<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=NewNexus001&bg_color=0d1117&color=00ff41&line=00ff41&point=00ff41&area=true&hide_border=true" alt="Activity Graph" />
</p>

<!-- DRAMATIC CLOSING STATEMENT – animated reveal + pulse -->
<p align="center">
  <svg width="100%" height="180" viewBox="0 0 800 180" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <filter id="closingGlow">
        <feGaussianBlur stdDeviation="3" result="blur" />
        <feMerge>
          <feMergeNode in="blur" />
          <feMergeNode in="blur" />
          <feMergeNode in="SourceGraphic" />
        </feMerge>
      </filter>
      <clipPath id="revealClose">
        <rect x="0" y="0" width="0" height="180">
          <animate attributeName="width" from="0" to="800" dur="2s" fill="freeze" />
        </rect>
      </clipPath>
      <style>
        .closing-text {
          font-family: 'Courier New', monospace;
          font-weight: bold;
          font-size: 22px;
          fill: #00ff41;
          filter: url(#closingGlow);
        }
        .pulse-text {
          font-family: 'Courier New', monospace;
          font-weight: bold;
          font-size: 22px;
          fill: #00ff41;
          animation: fadeIn 0.5s 2s forwards, pulseGlow 2s 2.5s infinite alternate;
          opacity: 0;
        }
        @keyframes fadeIn {
          to { opacity: 1; }
        }
        @keyframes pulseGlow {
          0% { filter: url(#closingGlow) drop-shadow(0 0 2px #00ff41); }
          100% { filter: url(#closingGlow) drop-shadow(0 0 18px #00ff41); }
        }
      </style>
    </defs>
    <rect width="800" height="180" fill="#0d1117" />
    <!-- Revealed text (once) -->
    <text class="closing-text" x="15" y="50" clip-path="url(#revealClose)">
      <tspan x="15" dy="0">THE SHORT ANSWER IS ANYTHING</tspan>
      <tspan x="15" dy="35">THAT INVOLVES PC AND DESKTOP</tspan>
      <tspan x="15" dy="35">I CAN DO IT</tspan>
    </text>
    <!-- Layered pulsing copy that fades in after reveal -->
    <text class="pulse-text" x="15" y="50">
      <tspan x="15" dy="0">THE SHORT ANSWER IS ANYTHING</tspan>
      <tspan x="15" dy="35">THAT INVOLVES PC AND DESKTOP</tspan>
      <tspan x="15" dy="35">I CAN DO IT</tspan>
    </text>
  </svg>
</p>

<!-- LIVE VISITOR COUNTER -->
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=NewNexus001&color=green" alt="visitors" />
</p>
