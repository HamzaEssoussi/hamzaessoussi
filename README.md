<svg viewBox="0 0 1000 600" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="glassFill" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#ffffff" stop-opacity="0.14"/>
      <stop offset="100%" stop-color="#ffffff" stop-opacity="0.04"/>
    </linearGradient>
    <linearGradient id="sheen" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#ffffff" stop-opacity="0.35"/>
      <stop offset="45%" stop-color="#ffffff" stop-opacity="0"/>
    </linearGradient>
    <filter id="cardShadow" x="-40%" y="-40%" width="180%" height="180%">
      <feDropShadow dx="0" dy="10" stdDeviation="14" flood-color="#000000" flood-opacity="0.35"/>
    </filter>
  </defs>

  <!-- fond transparent : la carte se fond dans le fond de la page -->

  <!-- ============ ROW 1 ============ -->
  <!-- Card 1 : IA générative -->
  <g transform="translate(40,60)" filter="url(#cardShadow)">
    <rect width="200" height="200" rx="26" fill="url(#glassFill)" stroke="#ffffff" stroke-opacity="0.28" stroke-width="1.4"/>
    <path d="M26 26 Q100 10 174 26" stroke="url(#sheen)" stroke-width="40" fill="none" opacity="0.5"/>
    <text x="100" y="72" font-size="38" text-anchor="middle">🧠</text>
    <text x="100" y="118" font-family="Segoe UI, Arial, sans-serif" font-size="13" fill="#EAF2FF" text-anchor="middle" font-weight="600">IA générative</text>
    <text x="100" y="138" font-family="Segoe UI, Arial, sans-serif" font-size="12" fill="#B9C7DD" text-anchor="middle">(RAG, LLM) &amp;</text>
    <text x="100" y="156" font-family="Segoe UI, Arial, sans-serif" font-size="12" fill="#B9C7DD" text-anchor="middle">Machine Learning</text>
  </g>

  <!-- Card 2 : Systèmes IA -->
  <g transform="translate(266,60)" filter="url(#cardShadow)">
    <rect width="200" height="200" rx="26" fill="url(#glassFill)" stroke="#ffffff" stroke-opacity="0.28" stroke-width="1.4"/>
    <path d="M26 26 Q100 10 174 26" stroke="url(#sheen)" stroke-width="40" fill="none" opacity="0.5"/>
    <text x="100" y="72" font-size="38" text-anchor="middle">🏗️</text>
    <text x="100" y="118" font-family="Segoe UI, Arial, sans-serif" font-size="13" fill="#EAF2FF" text-anchor="middle" font-weight="600">Systèmes IA</text>
    <text x="100" y="138" font-family="Segoe UI, Arial, sans-serif" font-size="12" fill="#B9C7DD" text-anchor="middle">end-to-end</text>
    <text x="100" y="156" font-family="Segoe UI, Arial, sans-serif" font-size="12" fill="#B9C7DD" text-anchor="middle">Python · FastAPI · Docker</text>
  </g>

  <!-- Card 3 : Stage IA @ Axe Finance -- alterne texte / logo -->
  <g transform="translate(492,60)" filter="url(#cardShadow)">
    <rect width="200" height="200" rx="26" fill="url(#glassFill)" stroke="#ffffff" stroke-opacity="0.28" stroke-width="1.4"/>
    <path d="M26 26 Q100 10 174 26" stroke="url(#sheen)" stroke-width="40" fill="none" opacity="0.5"/>
    <g>
      <animate attributeName="opacity" values="1;1;0;0;1" keyTimes="0;0.55;0.65;0.95;1" dur="6s" repeatCount="indefinite"/>
      <text x="100" y="72" font-size="38" text-anchor="middle">💼</text>
      <text x="100" y="118" font-family="Segoe UI, Arial, sans-serif" font-size="13" fill="#EAF2FF" text-anchor="middle" font-weight="600">Stage IA</text>
      <text x="100" y="138" font-family="Segoe UI, Arial, sans-serif" font-size="12" fill="#B9C7DD" text-anchor="middle">LLM (Ollama/Qwen)</text>
      <text x="100" y="156" font-family="Segoe UI, Arial, sans-serif" font-size="12" fill="#B9C7DD" text-anchor="middle">+ RAG ChromaDB</text>
    </g>
    <g>
      <animate attributeName="opacity" values="0;0;1;1;0" keyTimes="0;0.55;0.65;0.95;1" dur="6s" repeatCount="indefinite"/>
      <circle cx="100" cy="88" r="34" fill="#ffffff" fill-opacity="0.10" stroke="#ffffff" stroke-opacity="0.3"/>
      <text x="100" y="98" font-family="Segoe UI, Arial, sans-serif" font-size="20" font-weight="700" fill="#4FC3F7" text-anchor="middle">AF</text>
      <text x="100" y="150" font-family="Segoe UI, Arial, sans-serif" font-size="14" fill="#EAF2FF" text-anchor="middle" font-weight="600">Axe Finance</text>
      <text x="100" y="168" font-family="Segoe UI, Arial, sans-serif" font-size="11" fill="#B9C7DD" text-anchor="middle">Été 2026</text>
    </g>
  </g>

  <!-- Card 4 : Test Automation @ Sagemcom -- alterne texte / logo -->
  <g transform="translate(718,60)" filter="url(#cardShadow)">
    <rect width="200" height="200" rx="26" fill="url(#glassFill)" stroke="#ffffff" stroke-opacity="0.28" stroke-width="1.4"/>
    <path d="M26 26 Q100 10 174 26" stroke="url(#sheen)" stroke-width="40" fill="none" opacity="0.5"/>
    <g>
      <animate attributeName="opacity" values="1;1;0;0;1" keyTimes="0;0.55;0.65;0.95;1" dur="6.4s" begin="0.8s" repeatCount="indefinite"/>
      <text x="100" y="72" font-size="38" text-anchor="middle">🧪</text>
      <text x="100" y="118" font-family="Segoe UI, Arial, sans-serif" font-size="13" fill="#EAF2FF" text-anchor="middle" font-weight="600">Test Automation</text>
      <text x="100" y="138" font-family="Segoe UI, Arial, sans-serif" font-size="12" fill="#B9C7DD" text-anchor="middle">Compteurs</text>
      <text x="100" y="156" font-family="Segoe UI, Arial, sans-serif" font-size="12" fill="#B9C7DD" text-anchor="middle">intelligents (Python)</text>
    </g>
    <g>
      <animate attributeName="opacity" values="0;0;1;1;0" keyTimes="0;0.55;0.65;0.95;1" dur="6.4s" begin="0.8s" repeatCount="indefinite"/>
      <circle cx="100" cy="88" r="34" fill="#ffffff" fill-opacity="0.10" stroke="#ffffff" stroke-opacity="0.3"/>
      <text x="100" y="96" font-family="Segoe UI, Arial, sans-serif" font-size="15" font-weight="700" fill="#4FC3F7" text-anchor="middle">SGC</text>
      <text x="100" y="150" font-family="Segoe UI, Arial, sans-serif" font-size="14" fill="#EAF2FF" text-anchor="middle" font-weight="600">Sagemcom</text>
      <text x="100" y="168" font-family="Segoe UI, Arial, sans-serif" font-size="11" fill="#B9C7DD" text-anchor="middle">Été 2025</text>
    </g>
  </g>

  <!-- ============ ROW 2 ============ -->
  <!-- Card 5 : Membre G2FOSS -- alterne texte / logo -->
  <g transform="translate(160,310)" filter="url(#cardShadow)">
    <rect width="200" height="200" rx="26" fill="url(#glassFill)" stroke="#ffffff" stroke-opacity="0.28" stroke-width="1.4"/>
    <path d="M26 26 Q100 10 174 26" stroke="url(#sheen)" stroke-width="40" fill="none" opacity="0.5"/>
    <g>
      <animate attributeName="opacity" values="1;1;0;0;1" keyTimes="0;0.55;0.65;0.95;1" dur="5.8s" begin="1.6s" repeatCount="indefinite"/>
      <text x="100" y="72" font-size="38" text-anchor="middle">🎓</text>
      <text x="100" y="118" font-family="Segoe UI, Arial, sans-serif" font-size="13" fill="#EAF2FF" text-anchor="middle" font-weight="600">Membre Club</text>
      <text x="100" y="138" font-family="Segoe UI, Arial, sans-serif" font-size="12" fill="#B9C7DD" text-anchor="middle">G2FOSS ENIT</text>
    </g>
    <g>
      <animate attributeName="opacity" values="0;0;1;1;0" keyTimes="0;0.55;0.65;0.95;1" dur="5.8s" begin="1.6s" repeatCount="indefinite"/>
      <circle cx="100" cy="88" r="34" fill="#ffffff" fill-opacity="0.10" stroke="#ffffff" stroke-opacity="0.3"/>
      <text x="100" y="96" font-family="Segoe UI, Arial, sans-serif" font-size="16" font-weight="700" fill="#4FC3F7" text-anchor="middle">G2F</text>
      <text x="100" y="150" font-family="Segoe UI, Arial, sans-serif" font-size="14" fill="#EAF2FF" text-anchor="middle" font-weight="600">G2FOSS</text>
      <text x="100" y="168" font-family="Segoe UI, Arial, sans-serif" font-size="11" fill="#B9C7DD" text-anchor="middle">Club ENIT</text>
    </g>
  </g>

  <!-- Card 6 : PFE -->
  <g transform="translate(386,310)" filter="url(#cardShadow)">
    <rect width="200" height="200" rx="26" fill="url(#glassFill)" stroke="#ffffff" stroke-opacity="0.28" stroke-width="1.4"/>
    <path d="M26 26 Q100 10 174 26" stroke="url(#sheen)" stroke-width="40" fill="none" opacity="0.5"/>
    <text x="100" y="72" font-size="38" text-anchor="middle">🚀</text>
    <text x="100" y="118" font-family="Segoe UI, Arial, sans-serif" font-size="13" fill="#EAF2FF" text-anchor="middle" font-weight="600">Recherche PFE</text>
    <text x="100" y="138" font-family="Segoe UI, Arial, sans-serif" font-size="12" fill="#B9C7DD" text-anchor="middle">6 mois</text>
    <text x="100" y="156" font-family="Segoe UI, Arial, sans-serif" font-size="12" fill="#B9C7DD" text-anchor="middle">Fév → Août 2027</text>
  </g>

  <!-- Card 7 : Langues -->
  <g transform="translate(612,310)" filter="url(#cardShadow)">
    <rect width="200" height="200" rx="26" fill="url(#glassFill)" stroke="#ffffff" stroke-opacity="0.28" stroke-width="1.4"/>
    <path d="M26 26 Q100 10 174 26" stroke="url(#sheen)" stroke-width="40" fill="none" opacity="0.5"/>
    <text x="100" y="72" font-size="38" text-anchor="middle">🌍</text>
    <text x="100" y="118" font-family="Segoe UI, Arial, sans-serif" font-size="13" fill="#EAF2FF" text-anchor="middle" font-weight="600">Langues</text>
    <text x="100" y="138" font-family="Segoe UI, Arial, sans-serif" font-size="12" fill="#B9C7DD" text-anchor="middle">AR · FR · EN</text>
    <text x="100" y="156" font-family="Segoe UI, Arial, sans-serif" font-size="12" fill="#B9C7DD" text-anchor="middle">DE (notions)</text>
  </g>
</svg>
