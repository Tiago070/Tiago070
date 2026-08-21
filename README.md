<!--
  README de perfil — Tema: JARVIS / Cyberpunk / IA
  Autor: Gerado por assistente (personalize seus links / projetos / textos)
-->

<!-- Banner principal (SVG animado - efeito "booting") -->
<p align="center">
  <!-- Fundo escuro com efeito de inicialização -->
  <svg width="100%" height="220" viewBox="0 0 1200 220" preserveAspectRatio="xMidYMid slice" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Banner">
    <defs>
      <linearGradient id="g1" x1="0" x2="1">
        <stop offset="0%" stop-color="#00ff9c"/>
        <stop offset="50%" stop-color="#7b61ff"/>
        <stop offset="100%" stop-color="#ff4dff"/>
      </linearGradient>
      <filter id="flicker">
        <feTurbulence baseFrequency="0.9" numOctaves="1" seed="2" result="t"/>
        <feColorMatrix in="t" type="matrix" values="0 0 0 0 0
                                                   0 0 0 0 0
                                                   0 0 0 0 0
                                                   0 0 0 0.8" result="m"/>
        <feBlend in="SourceGraphic" in2="m"/>
      </filter>
    </defs>

    <!-- background -->
    <rect width="1200" height="220" rx="12" fill="#0b0f13"/>
    <rect x="0" y="0" width="1200" height="220" rx="12" fill="url(#g1)" opacity="0.04"/>

    <!-- circuit lines -->
    <g stroke="rgba(123,97,255,0.08)" stroke-width="1" fill="none">
      <path d="M40 180 H1160" />
      <path d="M40 160 H1160" />
      <path d="M40 140 H1160" />
    </g>

    <!-- Title with boot typing effect (animated reveals) -->
    <g font-family="Segoe UI, Roboto, Helvetica, Arial, sans-serif" fill="#cbd5e1" font-weight="600">
      <text x="48" y="80" font-size="32" fill="#9be7d7">Olá, eu sou</text>

      <!-- Main name (glowing gradient + flicker) -->
      <text x="48" y="124" font-size="42" fill="url(#g1)" style="filter: url(#flicker);">
        <tspan>Tiago Cardoso Ferreira</tspan>
      </text>

      <!-- subtitle -->
      <text x="48" y="160" font-size="16" fill="#7f8a93">
        <tspan>Desenvolvedor · Experiências Web & Mobile · UI Interativa</tspan>
      </text>
    </g>

    <!-- boot dots (simulated "initializing" pulse) -->
    <g transform="translate(1040,160)">
      <circle cx="0" cy="0" r="6" fill="#00ff9c">
        <animate attributeName="r" values="6;10;6" dur="1.6s" repeatCount="indefinite" begin="0s"/>
        <animate attributeName="opacity" values="1;0.2;1" dur="1.6s" repeatCount="indefinite" begin="0s"/>
      </circle>
      <circle cx="24" cy="0" r="6" fill="#7b61ff">
        <animate attributeName="r" values="6;10;6" dur="1.6s" repeatCount="indefinite" begin="0.3s"/>
        <animate attributeName="opacity" values="1;0.2;1" dur="1.6s" repeatCount="indefinite" begin="0.3s"/>
      </circle>
      <circle cx="48" cy="0" r="6" fill="#ff4dff">
        <animate attributeName="r" values="6;10;6" dur="1.6s" repeatCount="indefinite" begin="0.6s"/>
        <animate attributeName="opacity" values="1;0.2;1" dur="1.6s" repeatCount="indefinite" begin="0.6s"/>
      </circle>
    </g>

  </svg>
</p>

<!-- Quick badges -->
<p align="center">
  <img alt="profile views" src="https://komarev.com/ghpvc/?username=Tiago070&label=👁+Visitas&color=0e7490&style=flat-square" />
  <img alt="followers" src="https://img.shields.io/github/followers/Tiago070?label=👥+Seguidores&style=flat-square&color=7b61ff" />
  <img alt="visitors" src="https://img.shields.io/badge/⚡-Disponibilidade%3A+Open-00ff9c?style=flat-square" />
</p>

<!-- Typing animation (SVG) -->
<p align="center">
  <svg width="min(900px,100%)" height="70" viewBox="0 0 900 70" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Typing">
    <rect width="100%" height="100%" rx="8" fill="#071018"/>
    <g font-family="ui-monospace, SFMono-Regular, Menlo, Monaco, 'Roboto Mono', 'Courier New', monospace" font-size="18" fill="#a0f0d2">
      <!-- static prompt -->
      <text x="18" y="42" fill="#7b9db6">> </text>

      <!-- dynamic phrases (appear sequentially) -->
      <text x="36" y="42">
        <tspan id="p1" visibility="hidden">Construindo interfaces imersivas...</tspan>
        <tspan id="p2" visibility="hidden">Explorando Dart & Flutter...</tspan>
        <tspan id="p3" visibility="hidden">Otimizando desempenho e UX...</tspan>
      </text>

      <!-- sequence control -->
      <set xlink:href="#p1" attributeName="visibility" to="visible" begin="0s" dur="2.8s" fill="freeze" />
      <set xlink:href="#p1" attributeName="visibility" to="hidden" begin="2.8s" />
      <set xlink:href="#p2" attributeName="visibility" to="visible" begin="3.2s" dur="2.8s" fill="freeze" />
      <set xlink:href="#p2" attributeName="visibility" to="hidden" begin="6s" />
      <set xlink:href="#p3" attributeName="visibility" to="visible" begin="6.4s" dur="2.8s" fill="freeze" />
      <set xlink:href="#p3" attributeName="visibility" to="hidden" begin="9.2s" />
      <!-- loop: jump back to p1 -->
      <set xlink:href="#p1" attributeName="visibility" to="visible" begin="9.6s" dur="2.8s" fill="freeze" />
    </g>

    <!-- cursor blink -->
    <rect x="36" y="24" width="8" height="18" fill="#00ff9c">
      <animate attributeName="opacity" values="1;0;1" dur="1s" repeatCount="indefinite"/>
    </rect>
  </svg>
</p>

---

## Sobre Mim
Olá — sou Tiago, um desenvolvedor apaixonado por criar experiências interativas e educativas para web e dispositivos móveis. Gosto de combinar estética, performance e acessibilidade, usando tanto tecnologias clássicas (HTML/CSS/JS) quanto stacks modernas (Dart/Flutter, Java). Trabalho com foco em projetos que ensinem, envolvam e impressionem.

- Local: Brasil
- Contato: [✉️ tiagocardoso1357@gmail.com](mailto:tiagocardoso1357@gmail.com) • [LinkedIn](http://linkedin.com/in/tiago-cardoso-ferreira-6236b8208) • [Lattes](http://lattes.cnpq.br/3050600083414822)

---

## Tech Stack
<p align="center">
  <!-- Use shields como ícones -->
  <img alt="Dart" src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" />
  <img alt="Flutter" src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" />
  <img alt="Java" src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white" />
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
</p>

---

## Ferramentas & Plataformas
<p align="center">
  <img alt="VSCode" src="https://img.shields.io/badge/VSCode-0078d4?style=for-the-badge&logo=visual-studio-code&logoColor=white" />
  <img alt="GitHub" src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img alt="Figma" src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" />
  <img alt="Linux" src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
</p>

---

## Projetos em Destaque
> Clique no card para abrir o repositório ou demo

<table width="100%">
  <tr>
    <td width="33%" valign="top">
      <a href="https://github.com/Tiago070/imersalab" target="_blank" rel="noopener">
        <img src="https://raw.githubusercontent.com/Tiago070/imersalab/main/vista-site-inicial.png" alt="imersalab" style="width:100%;border-radius:8px;"/>
      </a>
      <strong>imersalab</strong><br/>
      Página interativa / PWA — demo: <a href="https://tiago070.github.io/imersalab/">GitHub Pages</a><br/>
      <sub><a href="https://github.com/Tiago070/imersalab">Ver repositório</a> • <a href="https://tiago070.github.io/imersalab/">Demo</a></sub>
    </td>
    <td width="33%" valign="top">
      <a href="https://github.com/Tiago070/dispositivos-moveis" target="_blank" rel="noopener">
        <img src="https://img.shields.io/badge/Exerc%C3%ADcios-Dart-blue?style=for-the-badge" alt="dispositivos-moveis" style="width:100%;border-radius:8px;"/>
      </a>
      <strong>dispositivos-moveis</strong><br/>
      Coleção de exercícios e exemplos em Dart (mobile) — ideal para ensino.<br/>
      <sub><a href="https://github.com/Tiago070/dispositivos-moveis">Ver repositório</a></sub>
    </td>
    <td width="33%" valign="top">
      <a href="https://github.com/Tiago070/jardinsdasflores" target="_blank" rel="noopener">
        <img src="https://raw.githubusercontent.com/Tiago070/jardinsdasflores/main/index.html" alt="jardinsdasflores" style="width:100%;border-radius:8px;display:none;" />
        <img src="https://img.shields.io/badge/Site-Visual-ff69b4?style=for-the-badge" alt="jardinsdasflores" style="width:100%;border-radius:8px;"/>
      </a>
      <strong>jardinsdasflores</strong><br/>
      Site visual com foco em assets e performance de imagens.<br/>
      <sub><a href="https://github.com/Tiago070/jardinsdasflores">Ver repositório</a></sub>
    </td>
  </tr>
</table>

---

## Objetivos atuais (estilo terminal)
<pre style="background:#071018;color:#9be7d7;border-radius:8px;padding:16px;font-family:ui-monospace, SFMono-Regular, Menlo, Monaco, 'Roboto Mono', 'Courier New', monospace;">
$ uptime
System: TiagoOS 𐄂 boot: 2026-08

$ goals list --priority high
[1] Melhorar performance do <imersalab> (PWA & image optimization)
[2] Construir uma demo Flutter -> integração com sensores mobile
[3] Automatizar CI/CD: lint, build e deploy automático do GitHub Pages

$ goals list --priority medium
[ ] Criar template padrão README para aulas e exercícios
[ ] Migrar assets pesados para Git LFS / CDN

$ commit --message "ship the future"
</pre>

---

## GitHub Stats & Activity

<p align="center">
  <!-- GitHub Readme Stats -->
  <img align="center" src="https://github-readme-stats.vercel.app/api?username=Tiago070&show_icons=true&theme=dark&hide_border=true&count_private=true" alt="Tiago070's GitHub Stats" />

  <!-- Top Languages -->
  <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Tiago070&layout=compact&theme=dark&hide_border=true" alt="Top Languages" />
</p>

<p align="center">
  <!-- Streak -->
  <img alt="GitHub Streak" src="https://github-readme-streak-stats.herokuapp.com/?user=Tiago070&theme=dark&hide_border=true" />

  <!-- Contribution Activity Graph -->
  <br/>
  <img alt="Activity Graph" src="https://activity-graph.herokuapp.com/graph?username=Tiago070&area=true&bg_color=0b1116&color=00FF9C&line_color=00FF9C&point_color=00FF9C" />
</p>

<!-- GitHub Trophies -->
<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Tiago070&theme=darkhub&row=1" alt="Trophies" />
</p>

<!-- Snake commit animation (Platane's "snake") -->
<p align="center">
  <!-- Obs: se não carregar, é por limite do raw.githubusercontent ou do serviço -->
  <img alt="snake" src="https://raw.githubusercontent.com/Platane/snk/master/snk.svg?user=Tiago070" />
</p>

---

## Contribuição — gráfico de contribuições
<p align="center">
  <!-- GitHub contribution calendar já aparece no perfil; aqui adicionamos um link rápido -->
  <a href="https://github.com/Tiago070">
    <img alt="contribuições" src="https://ghchart.rshah.org/Tiago070" />
  </a>
</p>

---

## Redes Sociais & Contato
<p align="center">
  <a href="mailto:tiagocardoso1357@gmail.com"><img src="https://img.shields.io/badge/Email-%20tiagocardoso1357@gmail.com-00ff9c?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="http://linkedin.com/in/tiago-cardoso-ferreira-6236b8208"><img src="https://img.shields.io/badge/LinkedIn-Tiago%20Cardoso-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="http://lattes.cnpq.br/3050600083414822"><img src="https://img.shields.io/badge/Lattes-Curr%C3%ADculo-0e7490?style=for-the-badge&logo=researchgate&logoColor=white" alt="Lattes" /></a>
  <a href="https://github.com/Tiago070"><img src="https://img.shields.io/badge/GitHub-Tiago070-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
</p>

---

<!-- Elegant footer -->
<p align="center">
  <svg width="240" height="24" viewBox="0 0 240 24" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="divider">
    <defs>
      <linearGradient id="fg" x1="0" x2="1">
        <stop offset="0%" stop-color="#00ff9c" />
        <stop offset="100%" stop-color="#7b61ff" />
      </linearGradient>
    </defs>
    <rect rx="12" width="240" height="24" fill="#071018"/>
    <g fill="url(#fg)" font-family="Segoe UI, Roboto, Helvetica, Arial, sans-serif" font-size="11">
      <text x="12" y="15">— Construído com · foco em design, performance e ensino</text>
    </g>
  </svg>
</p>

<p align="center">
  <sub style="color:#7f8a93">✨ Se gostou do visual, posso personalizar as cores, texto e projetos. Posso também commitar automaticamente este README no seu repositório de perfil (crie um repo chamado <code>Tiago070</code> se ainda não existir).</sub>
</p>
