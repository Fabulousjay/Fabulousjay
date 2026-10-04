
  <title id="title">Ayo (Fabulous) Adegbulu, Software Engineer</title>
  <defs>
    <linearGradient id="background" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0" stop-color="#04110f"/>
      <stop offset="0.55" stop-color="#0a2e2a"/>
      <stop offset="1" stop-color="#0f766e"/>
    </linearGradient>
    <linearGradient id="sweep" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0" stop-color="#2dd4bf" stop-opacity="0"/>
      <stop offset="0.5" stop-color="#2dd4bf" stop-opacity="0.16"/>
      <stop offset="1" stop-color="#2dd4bf" stop-opacity="0"/>
    </linearGradient>
    <linearGradient id="nameGradient" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0" stop-color="#ffffff"/>
      <stop offset="1" stop-color="#99f6e4"/>
    </linearGradient>
    <radialGradient id="glow" cx="0.5" cy="0.5" r="0.5">
      <stop offset="0" stop-color="#2dd4bf" stop-opacity="0.35"/>
      <stop offset="1" stop-color="#2dd4bf" stop-opacity="0"/>
    </radialGradient>
    <pattern id="dots" width="28" height="28" patternUnits="userSpaceOnUse">
      <circle cx="1.5" cy="1.5" r="1.1" fill="#5eead4" fill-opacity="0.16"/>
    </pattern>
    <clipPath id="frame">
      <rect width="1000" height="240" rx="14"/>
    </clipPath>
    <clipPath id="reveal">
      <rect x="64" y="146" height="34" width="0">
        <animate attributeName="width" from="0" to="580" begin="1.5s" dur="2.4s" fill="freeze"/>
      </rect>
    </clipPath>
    <style>
      .name { animation: rise 1s ease-out 0.2s both; }
      @keyframes rise {
        from { opacity: 0; transform: translateY(16px); }
        to { opacity: 1; transform: translateY(0); }
      }
    </style>
  </defs>

  <g clip-path="url(#frame)">
    <rect width="1000" height="240" fill="url(#background)"/>
    <rect width="1000" height="240" fill="url(#dots)"/>

    <circle cx="880" cy="210" r="190" fill="url(#glow)">
      <animate attributeName="opacity" values="0.55;1;0.55" dur="6s" repeatCount="indefinite"/>
    </circle>

    <g transform="skewX(-20)">
      <rect x="-300" y="0" width="260" height="240" fill="url(#sweep)">
        <animateTransform attributeName="transform" type="translate" from="0 0" to="1500 0" begin="1s" dur="7s" repeatCount="indefinite"/>
      </rect>
    </g>

    <g stroke="#2dd4bf" stroke-opacity="0.55" stroke-width="1.4" stroke-dasharray="4 8" fill="none">
      <line x1="740" y1="150" x2="820" y2="205"><animate attributeName="stroke-dashoffset" from="0" to="-24" dur="1.6s" repeatCount="indefinite"/></line>
      <line x1="820" y1="205" x2="870" y2="125"><animate attributeName="stroke-dashoffset" from="0" to="-24" dur="1.6s" repeatCount="indefinite"/></line>
      <line x1="870" y1="125" x2="790" y2="65"><animate attributeName="stroke-dashoffset" from="0" to="-24" dur="1.6s" repeatCount="indefinite"/></line>
      <line x1="790" y1="65" x2="740" y2="150"><animate attributeName="stroke-dashoffset" from="0" to="-24" dur="1.6s" repeatCount="indefinite"/></line>
      <line x1="870" y1="125" x2="940" y2="70"><animate attributeName="stroke-dashoffset" from="0" to="-24" dur="1.6s" repeatCount="indefinite"/></line>
      <line x1="870" y1="125" x2="950" y2="190"><animate attributeName="stroke-dashoffset" from="0" to="-24" dur="1.6s" repeatCount="indefinite"/></line>
      <line x1="820" y1="205" x2="950" y2="190"><animate attributeName="stroke-dashoffset" from="0" to="-24" dur="1.6s" repeatCount="indefinite"/></line>
    </g>

    <g fill="#5eead4">
      <circle cx="740" cy="150" r="5"><animate attributeName="r" values="4;7;4" dur="3s" begin="0s" repeatCount="indefinite"/></circle>
      <circle cx="820" cy="205" r="5"><animate attributeName="r" values="4;7;4" dur="3s" begin="0.5s" repeatCount="indefinite"/></circle>
      <circle cx="870" cy="125" r="7"><animate attributeName="r" values="6;9;6" dur="3s" begin="1s" repeatCount="indefinite"/></circle>
      <circle cx="790" cy="65" r="5"><animate attributeName="r" values="4;7;4" dur="3s" begin="1.5s" repeatCount="indefinite"/></circle>
      <circle cx="940" cy="70" r="5"><animate attributeName="r" values="4;7;4" dur="3s" begin="2s" repeatCount="indefinite"/></circle>
      <circle cx="950" cy="190" r="5"><animate attributeName="r" values="4;7;4" dur="3s" begin="2.5s" repeatCount="indefinite"/></circle>
    </g>

    <text class="name" x="64" y="112" font-size="48" font-weight="800" fill="url(#nameGradient)" font-family="'Segoe UI', system-ui, -apple-system, Helvetica, Arial, sans-serif">Ayo (Fabulous) Adegbulu</text>

    <rect x="64" y="128" width="0" height="3" rx="1.5" fill="#2dd4bf">
      <animate attributeName="width" from="0" to="96" begin="0.9s" dur="0.6s" fill="freeze"/>
    </rect>

    <g clip-path="url(#reveal)">
      <text x="64" y="168" font-size="20" fill="#ccfbf1" font-family="'SF Mono', 'Fira Code', Consolas, 'Courier New', monospace" textLength="576" lengthAdjust="spacing">Software Engineer | React | Next.js | TypeScript</text>
    </g>

    <rect x="64" y="150" width="9" height="24" rx="1" fill="#2dd4bf" opacity="0">
      <animate attributeName="x" from="64" to="640" begin="1.5s" dur="2.4s" fill="freeze"/>
      <animate attributeName="opacity" values="1;1;0;0" keyTimes="0;0.5;0.5;1" dur="1s" begin="1.5s" repeatCount="indefinite"/>
    </rect>
  </g>
</svg>

<p align="center">
  <a href="https://fabulous-jay-portfolio.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-0f766e?style=for-the-badge" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/adegbulu-ayo/"><img src="https://img.shields.io/badge/LinkedIn-115e59?style=for-the-badge" alt="LinkedIn" /></a>
</p>

Software engineer with a frontend focus, building production web applications such as role based dashboards, complex workflows and data heavy interfaces. I work comfortably across the stack with Laravel and Node.js.

My background is in Applied Geophysics, which is where my interest in data modelling and programming started.

<br />

## Recent work

<table width="100%">
  <tr>
    <td valign="top">
      <h3>Zenthom</h3>
      <p>Facility maintenance platform. I was the sole frontend engineer and built the HQ, facility manager and customer dashboards from Figma to production, integrating 140+ APIs. That included the service request, invoice and payment flows, with wallet payments and card payments confirmed by webhook.</p>
      <p><sub><b>React, TypeScript, Redux Toolkit, React Query, Tailwind CSS</b></sub></p>
      <a href="https://www.zenthom.com/"><img src="https://img.shields.io/badge/Visit_Zenthom-0f766e?style=flat-square" alt="Visit Zenthom" /></a>
    </td>
  </tr>
</table>

<br />

## How I work

I care about what happens between the API and the screen. When I get an API, I check what it actually returns before building around it: valid and invalid IDs, empty responses, missing data and different states. I'm also spending more time on automated testing, especially Cypress.

<br />

## Tech

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=js%2Cts%2Cphp%2Chtml%2Ccss%2Creact%2Cnextjs%2Credux%2Ctailwind%2Cnodejs%2Claravel%2Cpostgres%2Cmysql%2Cgit%2Cdocker%2Cfigma&theme=dark&perline=16" />
  <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=js%2Cts%2Cphp%2Chtml%2Ccss%2Creact%2Cnextjs%2Credux%2Ctailwind%2Cnodejs%2Claravel%2Cpostgres%2Cmysql%2Cgit%2Cdocker%2Cfigma&theme=light&perline=16" />
  <img src="https://skillicons.dev/icons?i=js,ts,php,html,css,react,nextjs,redux,tailwind,nodejs,laravel,postgres,mysql,git,docker,figma&perline=16" width="100%" alt="JavaScript, TypeScript, PHP, HTML, CSS, React, Next.js, Redux, Tailwind, Node.js, Laravel, PostgreSQL, MySQL, Git, Docker and Figma" />
</picture>

<br />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=Fabulousjay&layout=compact&langs_count=8&card_width=850&hide_border=true&border_radius=8&custom_title=Most%20Used%20Languages&bg_color=0d1117&title_color=2dd4bf&text_color=c9d1d9" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=Fabulousjay&layout=compact&langs_count=8&card_width=850&hide_border=true&border_radius=8&custom_title=Most%20Used%20Languages&bg_color=ffffff&title_color=0f766e&text_color=24292f" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Fabulousjay&layout=compact&langs_count=8&card_width=850&hide_border=true&border_radius=8&custom_title=Most%20Used%20Languages&title_color=0f766e" width="100%" alt="Most used languages" />
</picture>

<img src="https://komarev.com/ghpvc/?username=Fabulousjay&label=&color=0f766e&style=flat" width="1" height="1" alt="" />
