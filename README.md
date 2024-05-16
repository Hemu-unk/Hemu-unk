<!-- Embedding SVG -->
<svg width="200%" height="200%" xmlns="http://www.w3.org/2000/svg">
  <!-- Define the clipping path for rain effect area -->
  <defs>
    <clipPath id="rainClip">
      <rect x="10" y="10" width="180" height="80"/>
    </clipPath>
  </defs>

  <!-- Define the gradient for the raindrops -->
  <defs>
    <linearGradient id="rainGradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#c300ff"/>
      <stop offset="100%" stop-color="blue"/>
    </linearGradient>
  </defs>
  
  <!-- Apply the clipping path to the raindrops group -->
  <g id="raindrops" clip-path="url(#rainClip)">
    <!-- Main raindrop -->
    <circle cx="20" cy="-20" r="3" fill="url(#rainGradient)">
      <!-- Animate the falling motion -->
      <animate attributeName="cy" values="-20; 200;" dur="2.8s" repeatCount="indefinite"/>
      <animate attributeName="cx" values="20; 260;" dur="2.8s" repeatCount="indefinite"/>
    </circle>
    <!-- Secondary raindrops -->
    <circle cx="50" cy="-30" r="2.5" fill="url(#rainGradient)">
      <animate attributeName="cy" values="-30; 200;" dur="2.2s" repeatCount="indefinite" />
      <animate attributeName="cx" values="50; 290;" dur="2.2s" repeatCount="indefinite"/>
    </circle>
    <circle cx="80" cy="-25" r="3" fill="url(#rainGradient)">
      <animate attributeName="cy" values="-25; 200;" dur="2.1s" repeatCount="indefinite" />
      <animate attributeName="cx" values="80; 320;" dur="2.1s" repeatCount="indefinite"/>
    </circle>
    <!-- Add more raindrops -->
    <circle cx="110" cy="-35" r="2.8" fill="url(#rainGradient)">
      <animate attributeName="cy" values="-35; 200;" dur="2.3s" repeatCount="indefinite" />
      <animate attributeName="cx" values="110; 350;" dur="2.3s" repeatCount="indefinite"/>
    </circle>
    <circle cx="140" cy="-40" r="3.2" fill="url(#rainGradient)">
      <animate attributeName="cy" values="-40; 250;" dur="2.4s" repeatCount="indefinite" />
      <animate attributeName="cx" values="140; 380;" dur="2.4s" repeatCount="indefinite"/>
    </circle>
    <!-- Add more raindrops -->
    <circle cx="170" cy="-15" r="2.7" fill="url(#rainGradient)">
      <animate attributeName="cy" values="-15; 200;" dur="2.2s" repeatCount="indefinite" />
      <animate attributeName="cx" values="170; 410;" dur="2.2s" repeatCount="indefinite"/>
    </circle>
    <circle cx="200" cy="-22" r="2.9" fill="url(#rainGradient)">
      <animate attributeName="cy" values="-22; 200;" dur="2.3s" repeatCount="indefinite" />
      <animate attributeName="cx" values="200; 440;" dur="2.3s" repeatCount="indefinite"/>
    </circle>
    <circle cx="230" cy="-18" r="3.1" fill="url(#rainGradient)">
      <animate attributeName="cy" values="-18; 200;" dur="2.4s" repeatCount="indefinite" />
      <animate attributeName="cx" values="230; 470;" dur="2.4s" repeatCount="indefinite"/>
    </circle>
    <!-- Add even more raindrops -->
    <circle cx="260" cy="-28" r="2.6" fill="url(#rainGradient)">
      <animate attributeName="cy" values="-28; 200;" dur="2.1s" repeatCount="indefinite" />
      <animate attributeName="cx" values="260; 500;" dur="2.1s" repeatCount="indefinite"/>
    </circle>
    <circle cx="290" cy="-32" r="2.4" fill="url(#rainGradient)">
      <animate attributeName="cy" values="-32; 200;" dur="2.2s" repeatCount="indefinite" />
      <animate attributeName="cx" values="290; 530;" dur="2.2s" repeatCount="indefinite"/>
    </circle>
    <circle cx="320" cy="-26" r="2.8" fill="url(#rainGradient)">
      <animate attributeName="cy" values="-26; 200;" dur="2.3s" repeatCount="indefinite" />
      <animate attributeName="cx" values="320; 560;" dur="2.3s" repeatCount="indefinite"/>
    </circle>
    <circle cx="350" cy="-38" r="3.3" fill="url(#rainGradient)">
      <animate attributeName="cy" values="-38; 200;" dur="2.4s" repeatCount="indefinite" />
      <animate attributeName="cx" values="350; 590;" dur="2.4s" repeatCount="indefinite"/>
    </circle>
    <!-- Additional raindrops to the left of the box -->
    <circle cx="-10" cy="-18" r="2.9" fill="url(#rainGradient)">
      <animate attributeName="cy" values="-18; 200;" dur="2.3s" repeatCount="indefinite" />
      <animate attributeName="cx" values="-10; 230;" dur="2.3s" repeatCount="indefinite"/>
    </circle>
    <circle cx="-40" cy="-22" r="2.7" fill="url(#rainGradient)">
      <animate attributeName="cy" values="-22; 200;" dur="2.2s" repeatCount="indefinite" />
      <animate attributeName="cx" values="-40; 200;" dur="2.2s" repeatCount="indefinite"/>
    </circle>
    <circle cx="-70" cy="-15" r="3.1" fill="url(#rainGradient)">
      <animate attributeName="cy" values="-15; 200;" dur="2.4s" repeatCount="indefinite" />
      <animate attributeName="cx" values="-70; 170;" dur="2.4s" repeatCount="indefinite"/>
    </circle>
  </g>

   <!-- Rectangle -->
  <svg width="200" height="100" xmlns="http://www.w3.org/2000/svg">
    <!-- Linear gradient definition -->
    <defs>
      <linearGradient id="borderGradient" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#c300ff"/>
        <stop offset="100%" stop-color="blue"/>
      </linearGradient>
    </defs>
    <rect x="10" y="10" width="180" height="80" fill="none" stroke="url(#borderGradient)" stroke-width="2" rx="10" ry="10"/>
  </svg>
</svg>
