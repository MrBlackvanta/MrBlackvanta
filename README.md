<div align="center">
  <img src="assets/header.svg" alt="Abdelrhman Abdelaal, Senior Frontend Engineer. Every shipped build scores 100 in all four Lighthouse categories." width="100%" />
</div>

<p align="center">
  <a href="https://abdelaal.dev"><img src="https://img.shields.io/badge/abdelaal.dev-portfolio-0d1117?style=for-the-badge&logo=googlechrome&logoColor=5eead4" alt="Portfolio" /></a>
  <a href="https://abdelaal.dev/portfolio"><img src="https://img.shields.io/badge/38-case_studies-0d1117?style=for-the-badge&logo=readme&logoColor=a78bfa" alt="Case studies" /></a>
  <a href="https://www.linkedin.com/in/YOUR-LINKEDIN-HANDLE"><img src="https://img.shields.io/badge/LinkedIn-connect-0d1117?style=for-the-badge&logo=linkedin&logoColor=7dd3fc" alt="LinkedIn" /></a>
  <a href="https://abdelaal.dev/contact"><img src="https://img.shields.io/badge/say_hi-contact-0d1117?style=for-the-badge&logo=minutemailer&logoColor=f0f6fc" alt="Contact" /></a>
</p>

<br />

Senior frontend engineer at Appswave, building government digital platforms for clients across the UAE and Saudi Arabia. React, Next.js and TypeScript on the front, bilingual Arabic / English interfaces where right-to-left is the default and not an afterthought. Going deeper on .NET so I can own a feature end to end.

- **Every build I ship scores 100 / 100 / 100 / 100 in Lighthouse**, mobile and desktop. Nothing is done below that.
- **I audit the supplied design for WCAG AA contrast before it reaches users**, and each README lists what failed and the smallest colour step that fixed it.
- **Top-ranked code reviewer on Frontend Mentor**: Mentor of the Week, twice in first place, voted by the developers whose code I reviewed.

<br />

## Featured work

Full-stack builds first. Every link is live.

<table>
  <tr>
    <th align="left">Project</th>
    <th align="left">What it proves</th>
    <th align="left">Stack</th>
    <th align="left">Links</th>
  </tr>
  <tr>
    <td><b>todo</b></td>
    <td>Offline-first task list synced across devices. localStorage is the source of truth and the app works with no backend; a .NET API replaces the snapshot per list, rate-limited 60/min, RFC 7807 errors, health probe with a DB check. Drag, touch and keyboard reordering.</td>
    <td>Next.js · .NET 9 minimal API · EF Core · PostgreSQL · Docker · Cloudflare + Render</td>
    <td><a href="https://todo-app.abdelrhman-ahmed8881.workers.dev">Live</a> · <a href="https://github.com/MrBlackvanta/todo-app">Code</a></td>
  </tr>
  <tr>
    <td><b>devjobs</b></td>
    <td>Job board where search, filtering and paging run in the database query, not in the browser. Filters survive a reload, load-more paging, light and dark, view transitions.</td>
    <td>Next.js (OpenNext) · .NET minimal API · EF Core · SQLite · Cloudflare + Render</td>
    <td><a href="https://devjobs-web-app.abdelrhman-ahmed8881.workers.dev">Live</a> · <a href="https://github.com/MrBlackvanta/devjobs-web-app">Code</a></td>
  </tr>
  <tr>
    <td><b>rest-countries</b></td>
    <td>Server-rendered Next.js on Cloudflare's edge over an ASP.NET Core API I built instead of the public one. Search, region filter, detail pages, theme switcher.</td>
    <td>Next.js SSR · ASP.NET Core · EF Core · Cloudflare Workers</td>
    <td><a href="https://rest-countries-api-with-color-theme-switcher.abdelrhman-ahmed8881.workers.dev">Live</a> · <a href="https://github.com/MrBlackvanta/rest-countries-api-with-color-theme-switcher">Code</a></td>
  </tr>
  <tr>
    <td><b>ip-address-tracker</b></td>
    <td>Geolocation lookup proxied through a same-origin Worker, so the API key never ships to the browser. Rate-limited, and a plain visit is resolved at the edge for free so only typed queries spend from the monthly quota.</td>
    <td>TypeScript · Cloudflare Workers · Leaflet</td>
    <td><a href="https://ip-address-tracker.abdelrhman-ahmed8881.workers.dev">Live</a> · <a href="https://github.com/MrBlackvanta/ip-address-tracker">Code</a></td>
  </tr>
  <tr>
    <td><b>abdelaal.dev</b></td>
    <td>The portfolio itself. Static export served by a Worker that also owns the contact endpoint: shared validation, email through Resend, a honeypot that answers 200 so bots never learn they were caught, origin check, body-size cap.</td>
    <td>Next.js · Cloudflare Workers · Resend</td>
    <td><a href="https://abdelaal.dev">Live</a> · <a href="https://github.com/MrBlackvanta/minimalist-portfolio-website">Code</a></td>
  </tr>
</table>

<p align="right"><a href="https://abdelaal.dev/portfolio">All 38 case studies →</a></p>

<br />

## Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=react,nextjs,ts,js,html,css,tailwind,sass,dotnet,cs,postgres,sqlite,docker,cloudflare,git,figma&theme=dark&perline=8" alt="React, Next.js, TypeScript, JavaScript, HTML, CSS, Tailwind, Sass, .NET, C#, PostgreSQL, SQLite, Docker, Cloudflare, Git, Figma" />
</p>

<p align="center"><sub>Also in daily use: Liferay DXP (client extensions, React widgets), OpenNext, EF Core, Render.</sub></p>

<br />

<!--
  Activity cards are hidden on purpose. The public github-readme-stats.vercel.app deployment is PAUSED
  (returns 503 DEPLOYMENT_PAUSED as of 2026-09-19), which is why the old README showed no stats card.
  To turn this section on: fork https://github.com/anuraghazra/github-readme-stats, click its "Deploy to Vercel"
  button (free), then replace YOUR-STATS-INSTANCE below with your Vercel host and remove this comment block.

## Activity

<p align="center">
  <img src="https://YOUR-STATS-INSTANCE.vercel.app/api?username=mrblackvanta&theme=transparent&hide_border=true&include_all_commits=true&count_private=true&title_color=a78bfa&icon_color=5eead4&text_color=8b949e" alt="GitHub stats" height="165" />
  <img src="https://YOUR-STATS-INSTANCE.vercel.app/api/top-langs/?username=mrblackvanta&layout=compact&theme=transparent&hide_border=true&langs_count=8&title_color=a78bfa&text_color=8b949e" alt="Top languages" height="165" />
</p>
-->
