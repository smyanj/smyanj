<img width="1200" height="360" alt="pokemon-readme-banner" src="https://github.com/user-attachments/assets/db44963b-bd1e-4d36-ab6f-52a14e27c7bb" /><h1 align="center">Hi 👋, I'm Smyan Jaipuriyar</h1>
<h3 align="center">UCSB Alum, Masters in Computer Science @ Georgia Tech! </h3>

![Upload<svg width="1200" height="360" viewBox="0 0 1200 360" fill="none" xmlns="http://www.w3.org/2000/svg" role="img" aria-labelledby="title desc">
  <title id="title">Animated Pokémon-inspired GitHub README banner for Smyan Jaipuriyar</title>
  <desc id="desc">A yellow and blue outlined animated name banner with pixel grass, stars, and a Pokéball-style icon.</desc>
  <style>
    :root {
      --sky1: #84d7ff;
      --sky2: #f8fdff;
      --grass1: #34b233;
      --grass2: #188c2b;
      --poke-yellow: #ffcb05;
      --poke-blue: #2a75bb;
      --deep-blue: #16336d;
      --red: #ee1515;
    }

    .sky {
      fill: url(#skyGradient);
      animation: skyShift 7s ease-in-out infinite alternate;
    }

    .cloud {
      fill: white;
      opacity: 0.78;
      animation: drift 14s linear infinite;
    }

    .cloud.two { animation-duration: 19s; animation-delay: -5s; opacity: 0.55; }
    .cloud.three { animation-duration: 22s; animation-delay: -10s; opacity: 0.62; }

    .grass { fill: url(#grassGradient); }
    .pixel { fill: rgba(255,255,255,0.22); animation: twinkle 1.8s ease-in-out infinite alternate; }
    .pixel:nth-of-type(odd) { animation-delay: .45s; }

    .name-shadow {
      font-family: Impact, "Arial Black", sans-serif;
      font-size: 96px;
      letter-spacing: 5px;
      fill: #0b1d44;
      opacity: 0.28;
      transform: translate(10px, 12px);
    }

    .name-outline {
      font-family: Impact, "Arial Black", sans-serif;
      font-size: 96px;
      letter-spacing: 5px;
      fill: var(--poke-yellow);
      stroke: var(--poke-blue);
      stroke-width: 10px;
      paint-order: stroke fill;
      stroke-linejoin: round;
      stroke-dasharray: 920;
      stroke-dashoffset: 920;
      animation: drawName 3.2s ease-in-out infinite, nameFloat 3s ease-in-out infinite;
      filter: url(#softGlow);
    }

    .name-inner {
      font-family: Impact, "Arial Black", sans-serif;
      font-size: 96px;
      letter-spacing: 5px;
      fill: var(--poke-yellow);
      stroke: #fff2a8;
      stroke-width: 2px;
      paint-order: stroke fill;
      animation: nameFloat 3s ease-in-out infinite;
    }

    .subtitle {
      font-family: "Courier New", monospace;
      font-size: 24px;
      font-weight: 700;
      letter-spacing: 3px;
      fill: #17306d;
      animation: blink 1.4s steps(2, start) infinite;
    }

    .ball {
      transform-origin: 172px 164px;
      animation: bounceBall 1.6s ease-in-out infinite;
    }

    .spark { fill: #fff7aa; animation: sparkle 1.3s ease-in-out infinite alternate; transform-origin: center; }
    .spark.b { animation-delay: .3s; }
    .spark.c { animation-delay: .7s; }
    .spark.d { animation-delay: 1s; }

    @keyframes drawName {
      0% { stroke-dashoffset: 920; }
      38% { stroke-dashoffset: 0; }
      78% { stroke-dashoffset: 0; }
      100% { stroke-dashoffset: 920; }
    }

    @keyframes nameFloat {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-7px); }
    }

    @keyframes bounceBall {
      0%, 100% { transform: translateY(0) rotate(-8deg); }
      50% { transform: translateY(-18px) rotate(8deg); }
    }

    @keyframes sparkle {
      from { opacity: .35; transform: scale(.8); }
      to { opacity: 1; transform: scale(1.25); }
    }

    @keyframes blink {
      0%, 58% { opacity: 1; }
      59%, 100% { opacity: .35; }
    }

    @keyframes drift {
      0% { transform: translateX(-120px); }
      100% { transform: translateX(1320px); }
    }

    @keyframes twinkle {
      from { opacity: .2; }
      to { opacity: .8; }
    }

    @keyframes skyShift {
      from { opacity: .92; }
      to { opacity: 1; }
    }

    @media (prefers-reduced-motion: reduce) {
      * { animation: none !important; }
      .name-outline { stroke-dashoffset: 0; }
    }
  </style>

  <defs>
    <linearGradient id="skyGradient" x1="0" y1="0" x2="0" y2="360" gradientUnits="userSpaceOnUse">
      <stop offset="0" stop-color="#77ceff"/>
      <stop offset="0.62" stop-color="#f8fdff"/>
      <stop offset="1" stop-color="#dff8ff"/>
    </linearGradient>
    <linearGradient id="grassGradient" x1="0" y1="250" x2="0" y2="360" gradientUnits="userSpaceOnUse">
      <stop offset="0" stop-color="#58d450"/>
      <stop offset="1" stop-color="#15862b"/>
    </linearGradient>
    <filter id="softGlow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="3.5" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <rect class="sky" width="1200" height="360" rx="28"/>

  <g class="cloud" transform="translate(80 48)">
    <ellipse cx="40" cy="24" rx="40" ry="22"/>
    <ellipse cx="86" cy="20" rx="48" ry="28"/>
    <ellipse cx="132" cy="28" rx="42" ry="22"/>
  </g>
  <g class="cloud two" transform="translate(380 92)">
    <ellipse cx="38" cy="24" rx="38" ry="20"/>
    <ellipse cx="82" cy="18" rx="46" ry="27"/>
    <ellipse cx="126" cy="28" rx="39" ry="21"/>
  </g>
  <g class="cloud three" transform="translate(760 42)">
    <ellipse cx="44" cy="25" rx="44" ry="22"/>
    <ellipse cx="92" cy="19" rx="50" ry="28"/>
    <ellipse cx="140" cy="30" rx="46" ry="23"/>
  </g>

  <path class="grass" d="M0 252H1200V360H0V252Z"/>
  <path d="M0 252C96 228 178 270 277 246C372 223 481 260 594 242C729 220 801 273 924 247C1034 224 1122 246 1200 229V360H0V252Z" fill="#2faf43" opacity=".75"/>

  <g class="ball">
    <circle cx="172" cy="164" r="52" fill="white" stroke="#17213f" stroke-width="8"/>
    <path d="M124 164a48 48 0 0 1 96 0H124Z" fill="#ee1515"/>
    <path d="M122 164H222" stroke="#17213f" stroke-width="8" stroke-linecap="round"/>
    <circle cx="172" cy="164" r="17" fill="white" stroke="#17213f" stroke-width="7"/>
    <circle cx="172" cy="164" r="7" fill="#f7f7f7"/>
  </g>

  <path class="spark" d="M1015 85l9 23 23 9-23 9-9 23-9-23-23-9 23-9 9-23Z"/>
  <path class="spark b" d="M930 166l6 15 15 6-15 6-6 15-6-15-15-6 15-6 6-15Z"/>
  <path class="spark c" d="M252 78l7 18 18 7-18 7-7 18-7-18-18-7 18-7 7-18Z"/>
  <path class="spark d" d="M1110 210l5 13 13 5-13 5-5 13-5-13-13-5 13-5 5-13Z"/>

  <rect class="pixel" x="68" y="286" width="16" height="16" rx="2"/>
  <rect class="pixel" x="132" y="314" width="14" height="14" rx="2"/>
  <rect class="pixel" x="994" y="293" width="16" height="16" rx="2"/>
  <rect class="pixel" x="1078" y="325" width="14" height="14" rx="2"/>
  <rect class="pixel" x="690" y="310" width="12" height="12" rx="2"/>

  <text class="name-shadow" x="260" y="181">SMYAN</text>
  <text class="name-shadow" x="260" y="274">JAIPURIYAR</text>

  <text class="name-outline" x="260" y="181">SMYAN</text>
  <text class="name-inner" x="260" y="181">SMYAN</text>

  <text class="name-outline" x="260" y="274">JAIPURIYAR</text>
  <text class="name-inner" x="260" y="274">JAIPURIYAR</text>

  <text class="subtitle" x="472" y="326">PRESS START ▶ SOFTWARE ENGINEER</text>
</svg>
ing pokemon-readme-banner.svg…]()

- 🌱 I’m currently focused on learning back-end development, Go, C, C++

- 📫 How to reach me **sjaipuriyar6@gatech.edu**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://linkedin.com/in/https://www.linkedin.com/in/smyan-jaipuriyar/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="https://www.linkedin.com/in/smyan-jaipuriyar/" height="30" width="40" /></a>
