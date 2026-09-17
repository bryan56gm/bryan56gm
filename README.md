## Hola, soy Bryan 👋

**Full Stack Developer** en Barcelona. Llevo **más de cuatro años** construyendo sistemas de gestión de principio a fin —del modelo de datos al despliegue— y manteniéndolos en producción para empresas de distribución alimentaria, construcción, hostelería y administración pública.

Ahora mismo levanto un **ERP que unifica siete sociedades** en una sola base de datos, con consulta en lenguaje natural para dirección. Antes, Dynamics 365 dentro de un partner de Microsoft.

Lo que más me interesa: **que un sistema siga funcionando cuando nadie lo mira**. Reglas garantizadas en la base de datos, procesos que avisan solo si fallan, y cada decisión de arquitectura escrita con lo que se descartó y por qué.

🔭 &nbsp;Construyendo un ERP para un grupo de 7 sociedades<br>
🌱 &nbsp;Aprendiendo despliegues con agentes de IA gobernados<br>
💬 &nbsp;Pregúntame de Postgres, RLS, offline-first o integraciones con ERPs<br>
📫 &nbsp;[bryann56gm@gmail.com](mailto:bryann56gm@gmail.com) · [linkedin.com/in/bryangm](https://linkedin.com/in/bryangm)<br>
🌍 &nbsp;Castellano y catalán nativos · inglés intermedio

<br>

## Con qué trabajo

| | |
|---|---|
| **A diario** | ![TypeScript](https://img.shields.io/badge/TypeScript-0f5750?style=flat-square&logo=typescript&logoColor=white) ![React](https://img.shields.io/badge/React-0f5750?style=flat-square&logo=react&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-0f5750?style=flat-square&logo=nextdotjs&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-0f5750?style=flat-square&logo=nodedotjs&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0f5750?style=flat-square&logo=postgresql&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-0f5750?style=flat-square&logo=supabase&logoColor=white) |
| **También** | ![Astro](https://img.shields.io/badge/Astro-3a7f78?style=flat-square&logo=astro&logoColor=white) ![Tailwind](https://img.shields.io/badge/Tailwind-3a7f78?style=flat-square&logo=tailwindcss&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-3a7f78?style=flat-square&logo=prisma&logoColor=white) ![Capacitor](https://img.shields.io/badge/Capacitor-3a7f78?style=flat-square&logo=capacitor&logoColor=white) ![PostGIS](https://img.shields.io/badge/PostGIS-3a7f78?style=flat-square&logo=postgresql&logoColor=white) |
| **Calidad** | ![Vitest](https://img.shields.io/badge/Vitest-3a7f78?style=flat-square&logo=vitest&logoColor=white) ![Playwright](https://img.shields.io/badge/Playwright-3a7f78?style=flat-square&logo=playwright&logoColor=white) ![ESLint](https://img.shields.io/badge/ESLint-3a7f78?style=flat-square&logo=eslint&logoColor=white) — tests y linter obligatorios antes de cada commit |
| **Infraestructura** | ![Docker](https://img.shields.io/badge/Docker-3a7f78?style=flat-square&logo=docker&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-3a7f78?style=flat-square&logo=linux&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-3a7f78?style=flat-square&logo=githubactions&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-3a7f78?style=flat-square&logo=vercel&logoColor=white) — VPS propio, CI y copias de seguridad automatizadas |
| **IA aplicada** | Consultas a un ERP en lenguaje natural vía MCP, memoria semántica con pgvector, agentes que no ejecutan nada irreversible sin aprobación |
| **Y antes** | ![Dynamics 365](https://img.shields.io/badge/Dynamics%20365-6d767e?style=flat-square&logo=microsoftdynamics365&logoColor=white) ![Power Platform](https://img.shields.io/badge/Power%20Platform-6d767e?style=flat-square&logo=microsoftpowerplatform&logoColor=white) — X++, Power Apps y Power Automate en implantaciones de pymes a multinacionales |

<br>

## Lo que se puede abrir

<table>
  <tr>
    <td width="33%" valign="top">
      <a href="https://wildkeys.io"><img src="assets/wildkeys.jpg" alt="WildKeys" width="100%"></a>
      <br><br>
      <b><a href="https://wildkeys.io">wildkeys.io</a></b><br>
      Identificación de especies con claves dicotómicas, en tres idiomas. CMS y editor visual propios.<br>
      <sub>Next.js · Supabase · CI con comprobación nocturna</sub>
    </td>
    <td width="33%" valign="top">
      <a href="https://games.wildkeys.io"><img src="assets/games.jpg" alt="WildKeys Games" width="100%"></a>
      <br><br>
      <b><a href="https://games.wildkeys.io">games.wildkeys.io</a></b><br>
      PWA que funciona sin conexión, con el motor de juego separado de React. Estrenada en un evento físico.<br>
      <sub>Vite · React · service worker · marcador con cola offline</sub>
    </td>
    <td width="33%" valign="top">
      <a href="https://kreiselevents.com"><img src="assets/kreisel.jpg" alt="Kreisel Events" width="100%"></a>
      <br><br>
      <b><a href="https://kreiselevents.com">kreiselevents.com</a></b><br>
      Astro con CMS headless propio: el cliente publica al instante sin perder el rendimiento de un sitio estático.<br>
      <sub>Astro · React · Supabase · JSON-LD, hreflang</sub>
    </td>
  </tr>
</table>

<br>

## Código que se puede leer

### [harvis-standards](https://github.com/bryan56gm/harvis-standards) &nbsp;<img alt="versión" src="https://img.shields.io/github/v/tag/bryan56gm/harvis-standards?style=flat-square&color=0f5750&label=">

Mi estándar de ingeniería, convertido en paquete para que no dependa de acordarse. Lo instalan como dependencia todos mis proyectos, así que una regla cambia en un sitio y llega a todos.

- **ESLint flat config por framework** — Next, Vite y Astro, componibles.
- **Una regla propia**: [`no-arbitrary-tailwind`](https://github.com/bryan56gm/harvis-standards/blob/main/rules/no-arbitrary-tailwind.js), que prohíbe los valores arbitrarios de Tailwind para que el sistema de diseño no se erosione a base de `[13px]`.
- **Plantillas** de lefthook, commitlint, knip, renovate y CI — [`templates/`](https://github.com/bryan56gm/harvis-standards/tree/main/templates).
- Versionado con etiquetas y CHANGELOG, con su propia CI y tests.

> El porqué de cada regla vive escrito aparte; aquí está solo lo que una máquina puede hacer cumplir.

<br>

## Cómo trabajo

| | |
|---|---|
| **Decisiones escritas** | Cada decisión de arquitectura queda documentada, con lo que se descartó y por qué. |
| **Garantías en la base de datos** | Las reglas que no pueden fallar viven en RLS y restricciones, no en la convención. |
| **Pruebas antes del commit** | Lo que no pasa, no sale. [Lefthook y commitlint](https://github.com/bryan56gm/harvis-standards/tree/main/templates) como plantilla, no como buena intención. |
| **Silencio por defecto** | Lo que corre solo, avisa solo si falla. |

<br>

<p align="center">
  <sub>La mayoría de mi código es de clientes y vive en repositorios privados. Lo que hay aquí es lo que puedo enseñar.</sub>
</p>
