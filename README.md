<!--
  README de perfil - Tema: Futurista / Cyberpunk / JARVIS-like
  Autoria: gerado por assistente (base para customização)
  Para instalar: criar repo com nome: Tiago070 (username) -> colar este README.md
-->

<div align="center">

<!-- BANNER PRINCIPAL: SVG com efeito de inicialização do sistema -->
<!-- SVG embutido para máxima compatibilidade e animação via SMIL (suportado como imagem inline) -->
<svg width="100%" height="220" viewBox="0 0 1200 220" preserveAspectRatio="xMidYMid slice" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Iniciando Sistema">
  <defs>
    <linearGradient id="g1" x1="0" x2="1">
      <stop offset="0%" stop-color="#00f5ff"/>
      <stop offset="50%" stop-color="#a020ff"/>
      <stop offset="100%" stop-color="#ff007c"/>
    </linearGradient>
    <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="8" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <mask id="m1">
      <rect x="0" y="0" width="1200" height="220" fill="white"/>
    </mask>
  </defs>

  <rect width="1200" height="220" fill="#0b0f14"/>
  <!-- Grid lines -->
  <g stroke="#08121a" stroke-opacity="0.6">
    <line x1="0" y1="44" x2="1200" y2="44" stroke-width="1"/>
    <line x1="0" y1="88" x2="1200" y2="88" stroke-width="1"/>
    <line x1="0" y1="132" x2="1200" y2="132" stroke-width="1"/>
    <line x1="0" y1="176" x2="1200" y2="176" stroke-width="1"/>
  </g>

  <!-- Título com efeito de máquina -->
  <g transform="translate(48,56)">
    <text x="0" y="36" font-family="Verdana,DejaVu Sans,monospace" font-size="36" fill="url(#g1)" filter="url(#glow)" style="letter-spacing:2px">Tiago Cardoso Ferreira</text>
    <text x="0" y="76" font-family="Courier New,monospace" font-size="14" fill="#8aa1b1" opacity="0.95">Desenvolvedor • Frontend • Mobile • Educador</text>
  </g>

  <!-- Boot progress bar -->
  <g transform="translate(48,120)">
    <rect x="0" y="0" rx="6" ry="6" width="1100" height="26" fill="#071018" stroke="#0c2a36"/>
    <rect x="0" y="0" rx="6" ry="6" width="0" height="26" fill="url(#g1)">
      <animate attributeName="width" from="0" to="1100" dur="2.8s" begin="0.2s" fill="freeze"/>
    </rect>
    <text x="6" y="18" font-family="Courier New,monospace" font-size="12" fill="#0a0a0a" style="font-weight:700">
      <tspan fill="#e6f7ff">Inicializando</tspan>
      <tspan fill="#8aa1b1"> • Sistema: IMERSALAB UI</tspan>
    </text>
  </g>

  <!-- Boot ephemeral indicators -->
  <g transform="translate(48,160)" font-family="Courier New,monospace" font-size="11" fill="#7fb9ff">
    <text x="0" y="12">● network: <tspan fill="#66ffcc">ok</tspan></text>
    <text x="160" y="12">● sensors: <tspan fill="#66ffcc">ok</tspan></text>
    <text x="320" y="12">● ui: <tspan fill="#66ffcc">ok</tspan></text>
    <text x="480" y="12">● modules: <tspan fill="#ffd966">loading</tspan></text>
  </g>
</svg>

</div>

<!-- Typing Animation (SVG) -->
<div align="center" markdown="1">
  <img alt="typing" src='data:image/svg+xml;utf8,
  <svg xmlns="http://www.w3.org/2000/svg" width="820" height="60" viewBox="0 0 820 60">
    <style>
      .t { font: 600 20px/1 "Segoe UI", Roboto, "Helvetica Neue", Arial; fill:#cfeeff; }
      .d { fill:#8aa1b1; font: 14px/1 "Courier New", monospace; }
    </style>
    <rect width="100%" height="100%" fill="#071018"/>
    <text class="t" x="18" y="28">Olá — eu sou <tspan fill="#a76dff">Tiago</tspan>, </text>
    <text class="d" x="18" y="50">Construindo interfaces, experiências imersivas e material didático.</text>

    <!-- typing simulation via animate: reveals text progressively -->
    <text x="240" y="28" font-family="Courier New, monospace" font-size="20" fill="#8fffe6">
      <tspan id="type">▌</tspan>
      <animate attributeName="opacity" values="1;0;1" dur="1s" repeatCount="indefinite" />
    </text>
  </svg>'/>
</div>

---

<!-- SOBRE MIM -->
## 💡 Sobre Mim
Sou Tiago — desenvolvedor focado em experiências visuais para web e mobile, apaixonado por ensino, prototipagem e interfaces que dialogam com usuários. Gosto de protótipos 3D/VR leves, automação educativa e transformar conceitos complexos em material didático acessível.

- 📍 Local: Brasil
- 💬 Contato: [tiagocardoso1357@gmail.com](mailto:tiagocardoso1357@gmail.com)
- 🔭 Atualmente: desenvolvendo e mantendo projetos web e mobile para Imersalab
- 🌱 Aprendendo: melhores práticas em Flutter / acessibilidade web / otimização de assets

---

<!-- TECH STACK + TOOLS -->
## ⚙️ Tech Stack & Ferramentas

<div align="center">
<!-- Tech badges (shields.io) -->
<img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
<img alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
<img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
<img alt="Dart" src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white">
<img alt="Flutter" src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white">
<img alt="Java" src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white">
</div>

### Ferramentas
<div align="center">
<img alt="VSCode" src="https://img.shields.io/badge/VS%20Code-0078D7?style=for-the-badge&logo=visual-studio-code&logoColor=white">
<img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white">
<img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white">
<img alt="Figma" src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white">
<img alt="Chrome DevTools" src="https://img.shields.io/badge/DevTools-4A90E2?style=for-the-badge&logo=googlechrome&logoColor=white">
</div>

---

<!-- PROJECT CARDS -->
## 📦 Projetos selecionados

<div align="center">

<table>
  <tr>
    <td align="center" width="360" valign="top">
      <a href="https://github.com/Tiago070/imersalab" target="_blank">
        <img src="https://img.shields.io/badge/IMERSALAB-Project-8A2BE2?style=for-the-badge&logo=github" alt="imersalab" />
      </a>
      <p><b>Imersalab</b> — SPA interativa, visualizações web e viewer para ambientes 360°. GitHub Pages ativo.</p>
      <p><a href="https://tiago070.github.io/imersalab/" target="_blank">🔗 Demo</a> · <a href="https://github.com/Tiago070/imersalab" target="_blank">📂 Repositório</a></p>
    </td>
    <td align="center" width="360" valign="top">
      <a href="https://github.com/Tiago070/dispositivos-moveis" target="_blank">
        <img src="https://img.shields.io/badge/DART--EXERCISES-0175C2?style=for-the-badge&logo=dart" alt="dispositivos-moveis" />
      </a>
      <p><b>Dispositivos Móveis</b> — coleção de exercícios e exemplos em Dart (material didático para aula).</p>
      <p><a href="https://github.com/Tiago070/dispositivos-moveis" target="_blank">📂 Repositório</a></p>
    </td>
  </tr>

  <tr>
    <td align="center" width="360" valign="top">
      <a href="https://github.com/Tiago070/jardinsdasflores" target="_blank">
        <img src="https://img.shields.io/badge/JARDINS-Portfolio-00C897?style=for-the-badge" alt="jardinsdasflores" />
      </a>
      <p><b>Jardins das Flores</b> — site com foco visual e assets (imagens/galeria).</p>
      <p><a href="https://github.com/Tiago070/jardinsdasflores" target="_blank">📂 Repositório</a></p>
    </td>
    <td align="center" width="360" valign="top">
      <a href="https://github.com/Tiago070/integrador2022" target="_blank">
        <img src="https://img.shields.io/badge/Integrador-Game-JS-F7DF1E?style=for-the-badge&logo=javascript" alt="integrador" />
      </a>
      <p><b>Integrador2022</b> — jogo de escolhas com tema histórico (setup educacional).</p>
      <p><a href="https://github.com/Tiago070/integrador2022" target="_blank">📂 Repositório</a></p>
    </td>
  </tr>
</table>

</div>

---

<!-- OBJETIVOS ATUAIS EM FORMATO TERMINAL -->
## 🎯 Objetivos atuais (terminal)

```bash
# status - objetivos em execução
$ sysctl --whoami
user: Tiago070
role: dev, educator, tinkerer

$ goals --list
[1] melhorar desempenho de jardinsdasflores (compress, lfs, cdn)
[2] migrar exemplos Dart -> Flutter multiplataforma
[3] pipeline CI: lint -> test -> deploy (GitHub Actions)
[4] documentar repositórios: README, LICENSE, CONTRIBUTING

# modo: ativo — iniciando tarefas em background...
$ run --bg "optimize-assets && add-ci-workflows && tidy-issues"

<!-- STATS, LANGS, STREAK, ACTIVITY GRAPH, TROPHIES -->
📊 Métricas & Atividade
<div align="center"> <!-- GitHub Readme Stats (dark theme) --> <img align="center" src="https://github-readme-stats.vercel.app/api?username=Tiago070&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Estatísticas do GitHub" /> <!-- Top Languages --> <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Tiago070&layout=compact&theme=tokyonight&hide_border=true" alt="Linguagens principais" /> <!-- Streak --> <img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=Tiago070&theme=dark&hide_border=true" alt="GitHub Streak" /> <!-- Activity Graph --> <br/> <img src="https://activity-graph.herokuapp.com/graph?username=Tiago070&theme=react-dark&hide_border=true" alt="Activity Graph" /> <!-- Trophies --> <br/> <img src="https://github-profile-trophy.vercel.app/?username=Tiago070&theme=darkhub&row=1&margin-w=8" alt="Trophies" /> </div>
<!-- SNAKE CONTRIBUTION ANIMATION -->
🐍 Snake Contribution (fun)
<div align="center"> <!-- Snake animation (rendered via raw.githack to allow query params) --> <img alt="snake" src="https://raw.githack.com/Platane/snk/master/snk.svg?user=Tiago070&theme=dark&snake=amoled" /> </div>
<!-- SOCIALS -->
🔗 Me acompanhe
<div align="center"> <a href="mailto:tiagocardoso1357@gmail.com"><img alt="email" src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a> <a href="https://www.linkedin.com/in/tiago-cardoso-ferreira-6236b8208" target="_blank"><img alt="linkedin" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a> <a href="https://tiago070.github.io" target="_blank"><img alt="site" src="https://img.shields.io/badge/Portfolio-00BFA6?style=for-the-badge&logo=html5&logoColor=white"></a> <a href="https://github.com/Tiago070"><img alt="github" src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"></a> </div>
<!-- RODAPÉ ELEGANTE --> <p align="center"> <sub> <i>Feito com ♥ — estilo futurista • tema escuro • pronto para demonstração.</i> </sub> </p>
<div align="center"> <small style="color:#8aa1b1">© Tiago Cardoso Ferreira — <span style="color:#a76dff">Tiago070</span></small> </div> ```
