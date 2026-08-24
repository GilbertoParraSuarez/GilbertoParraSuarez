# AGENTS.md — Configuración de Codex para el perfil de GitHub de Gilberto Parra

## 1. Propósito

Este archivo contiene las instrucciones persistentes que Codex debe seguir al trabajar en este repositorio de perfil de GitHub.

Datos del perfil:

- **Nombre:** Gilberto Rodrigo Parra Suárez
- **Usuario de GitHub:** `GilbertoParraSuarez`
- **Repositorio de perfil:** `GilbertoParraSuarez/GilbertoParraSuarez`
- **Ubicación profesional:** Ecuador
- **Rol principal:** Software Engineer / Full Stack Developer
- **Portafolio:** `https://rodrigoparra.netlify.app/`
- **LinkedIn:** `https://www.linkedin.com/in/gilberto-parra-a5053a314`
- **Correo profesional:** `sprg565@gmail.com`

El repositorio de perfil **ya existe**. No crear otro repositorio.

Codex debe trabajar sobre el repositorio actual, completar o modificar `README.md`, crear o corregir los GitHub Actions necesarios, verificar las referencias y dejar los cambios listos para funcionar en GitHub.

---

# 2. Objetivo final

El repositorio debe mostrar un perfil profesional, moderno, visual y orientado a reclutadores, empleadores y colaboradores técnicos.

La primera pantalla del README debe comunicar rápidamente:

1. Quién es Gilberto.
2. Que es Software Engineer / Full Stack Developer.
3. Que tiene más de 3 años de experiencia profesional.
4. Su stack tecnológico principal.
5. Enlaces de contacto.
6. Estadísticas de GitHub.
7. Actividad de contribuciones mediante Snake Animation.

Más abajo se debe mostrar:

- resumen profesional;
- experiencia relevante;
- principales áreas técnicas;
- intereses y colaboración;
- información de contacto.

El resultado debe verse correctamente tanto en modo claro como oscuro de GitHub y no debe sentirse como un README genérico generado automáticamente.

---

# 3. Reglas obligatorias para Codex

## 3.1 Antes de modificar archivos

Codex debe ejecutar o verificar, según estén disponibles en el entorno:

```bash
git rev-parse --show-toplevel
git status
git remote -v
find . -maxdepth 3 -type f | sort
```

Confirmar, cuando sea posible, que el remote corresponde a:

```text
GilbertoParraSuarez/GilbertoParraSuarez
```

Leer completamente antes de reemplazar:

- `README.md`, si existe;
- `.github/workflows/*.yml`, si existen.

No borrar contenido útil sin revisarlo primero.

## 3.2 Git

Trabajar sobre la rama actual/default.

No crear ramas nuevas salvo que el usuario lo solicite expresamente.

No reescribir historial.

No usar salvo autorización explícita:

```bash
git reset --hard
git push --force
git clean -fd
```

Al terminar ejecutar:

```bash
git diff --check
git status
```

Si el entorno permite commits:

```bash
git add README.md AGENTS.md .github/workflows
git commit -m "feat: configure GitHub profile README"
```

Si existe acceso autenticado al remote y está permitido:

```bash
git push
```

Si no es posible hacer push por autenticación o permisos, no evadir la restricción. Dejar el commit local preparado e informar al usuario el comando que debe ejecutar.

---

# 4. Perfil profesional a representar

No inventar información profesional.

Usar como posicionamiento principal:

> Software Engineer & Full Stack Developer with 3+ years of professional experience building web, mobile and enterprise applications.

Áreas principales:

- Full Stack Web Development
- Cross-platform Mobile Development
- Enterprise Systems & ERP
- REST APIs
- Backend integrations
- Relational Databases
- ORM
- Testing
- Docker
- Git
- CI/CD
- AI-powered integrations and automation

Experiencia profesional válida:

## Mivilsoft — Full Stack Developer

Stack relevante:

- Odoo
- Python
- React
- React Native
- SQLite
- REST APIs
- external API integrations
- AI-powered automation

Responsabilidades que se pueden mencionar:

- desarrollo y mantenimiento de módulos empresariales y ERP;
- aplicaciones móviles multiplataforma;
- integración de APIs externas;
- automatización y generación de reportes con IA;
- migraciones y optimización de consultas;
- pruebas unitarias, funcionales y de integración.

## GAD Municipal de Tisaleo — Software Developer

Stack relevante:

- Laravel
- .NET Core
- Blazor
- Oracle
- SQL
- Bootstrap

Responsabilidades válidas:

- levantamiento de requerimientos;
- casos de uso;
- desarrollo de sistemas administrativos;
- servicios backend;
- interfaces Blazor;
- servicios web;
- optimización SQL;
- documentación técnica.

## Sprint Core — Full Stack Developer

Stack relevante:

- Angular
- Blazor
- .NET Core
- Node.js
- Entity Framework
- LINQ
- Oracle
- SQLite
- Firebase
- REST APIs
- CI/CD

Responsabilidades válidas:

- aplicaciones web escalables;
- APIs REST;
- integración entre frontend, backend y aplicaciones móviles;
- persistencia con Entity Framework;
- Firebase y sincronización en tiempo real;
- testing automatizado;
- automatización de despliegues.

---

# 5. Tecnologías que deben aparecer

Usar iconos de Devicon y una estética visual similar a Profile README Generator.

## Frontend / Web

- JavaScript
- TypeScript
- React
- Angular
- Blazor
- HTML5
- CSS3
- Bootstrap

## Mobile

- React Native
- .NET MAUI
- Xamarin solamente si existe un icono confiable; si no, omitirlo.

## Backend

- C#
- .NET / .NET Core
- Laravel
- Node.js
- Python
- Odoo

## Databases

- PostgreSQL
- MySQL
- Oracle
- SQLite

## Engineering / Tools

- Git
- GitHub
- Docker

No añadir tecnologías que no estén justificadas únicamente para llenar espacio.

Mantener aproximadamente 15–20 iconos como máximo en la zona visual principal.

---

# 6. Diseño requerido para README.md

## 6.1 Estética

El README debe seguir una estética parecida a `profile-readme-generator.com`:

- composición limpia;
- predominio visual del contenido;
- iconos Devicon;
- botones Shields.io;
- estadísticas en tarjetas;
- GIF de programación a la derecha;
- Snake Animation cerca del final.

No sobrecargar con:

- demasiados GIFs;
- emojis en cada línea;
- banners gigantes;
- contadores irrelevantes;
- citas motivacionales largas;
- tecnologías redundantes.

El README debe funcionar como una landing profesional.

## 6.2 Idioma

Idioma principal: **inglés**.

Añadir una breve versión en español dentro de un `<details>` únicamente en la sección About Me.

No duplicar todo el README en dos idiomas.

---

# 7. Encabezado obligatorio

Usar un encabezado similar a:

```html
<h2 data-importer="text" align="left">
  Hi 👋! I'm Gilberto Rodrigo Parra Suárez, a Software Engineer & Full Stack Developer from Ecuador 🇪🇨
</h2>
```

---

# 8. GIF principal

Usar **exactamente** este GIF:

```text
https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif
```

Implementarlo con:

```html
<img
  data-importer="image"
  align="right"
  height="150"
  src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif"
  alt="Coding animation"
/>
```

No sustituirlo por otro GIF.

---

# 9. About Me

Crear una sección concisa usando como base:

```markdown
### 👨‍💻 About me

I'm a **Software Engineer and Full Stack Developer with 3+ years of professional experience**, focused on building scalable web, mobile and enterprise applications.

I work across the complete software development lifecycle — from requirements analysis and database modeling to frontend, backend, REST APIs, testing, integrations and deployment.
```

Después incluir entre 5 y 8 puntos breves:

```markdown
- 💻 Full Stack Web Development
- 📱 Cross-platform Mobile Development
- 🏢 Enterprise Systems & ERP
- 🔌 REST APIs & System Integrations
- 🗄️ Relational Databases & ORM
- 🤖 AI-powered integrations & automation
- 🧪 Testing, Git, Docker & CI/CD
```

Añadir debajo:

```html
<details>
<summary><strong>🇪🇨 Sobre mí en español</strong></summary>

<br>

Soy Ingeniero en Software y Desarrollador Full Stack con más de 3 años de experiencia profesional desarrollando aplicaciones web, móviles y sistemas empresariales.

Trabajo en diferentes etapas del ciclo de desarrollo de software, desde análisis de requerimientos y modelado de bases de datos hasta frontend, backend, APIs REST, pruebas, integraciones y despliegue.

</details>
```

---

# 10. Tecnologías visuales

Utilizar preferentemente iconos desde:

```text
https://cdn.jsdelivr.net/gh/devicons/devicon/
```

Ejemplo:

```html
<div data-importer="techs" align="left">
  <img src="..." height="35" alt="javascript logo" />
  <img width="12" />
  <img src="..." height="35" alt="typescript logo" />
</div>
```

Agrupar las tecnologías en máximo dos filas.

Evitar iconos rotos. Si un icono Devicon no existe o devuelve error, eliminarlo o utilizar un badge confiable de Shields.io.

---

# 11. Redes sociales y contacto

Mostrar solamente canales profesionales.

## Portfolio

```text
https://rodrigoparra.netlify.app/
```

## LinkedIn

```text
https://www.linkedin.com/in/gilberto-parra-a5053a314
```

## Gmail

```text
sprg565@gmail.com
```

Usar botones similares a:

```html
<div data-importer="socials" align="left">

  <a href="https://rodrigoparra.netlify.app/" target="_blank">
    <img
      src="https://img.shields.io/static/v1?message=Portfolio&logo=googlechrome&label=&color=4285F4&logoColor=white&labelColor=&style=for-the-badge"
      height="35"
      alt="portfolio"
    />
  </a>

  <a href="https://www.linkedin.com/in/gilberto-parra-a5053a314" target="_blank">
    <img
      src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge"
      height="35"
      alt="linkedin"
    />
  </a>

  <a href="mailto:sprg565@gmail.com">
    <img
      src="https://img.shields.io/static/v1?message=Gmail&logo=gmail&label=&color=D14836&logoColor=white&labelColor=&style=for-the-badge"
      height="35"
      alt="gmail"
    />
  </a>

</div>
```

No añadir YouTube, Twitch, Discord, Instagram u otras redes sin autorización del usuario.

---

# 12. GitHub Stats

El perfil debe mostrar:

1. GitHub Stats.
2. Most Used Languages.

Username definitivo:

```text
GilbertoParraSuarez
```

No debe quedar ningún placeholder como `YOUR_GITHUB_USERNAME`.

---

# 13. Archivos obligatorios del repositorio

La estructura mínima final debe ser:

```text
GilbertoParraSuarez/
├── AGENTS.md
├── README.md
└── .github/
    └── workflows/
        ├── stats.yml
        ├── languages.yml
        └── snake.yml
```

Si ya existen estos workflows, actualizarlos en vez de duplicarlos.

No crear nombres alternativos como `stats-2.yml`, `snake-new.yml` o `readme-final.md`.

---

# 14. Workflow stats.yml

Crear o corregir:

```text
.github/workflows/stats.yml
```

Usar:

- `actions/checkout@v6`
- `stats-organization/github-readme-stats-action@v2`
- `crazy-max/ghaction-github-pages@v5`

Contenido esperado:

```yaml
name: Generate GitHub Stats

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  generate-stats:
    runs-on: ubuntu-latest

    permissions:
      contents: write

    steps:
      - name: Checkout repository
        uses: actions/checkout@v6

      - name: Generate GitHub Stats
        uses: stats-organization/github-readme-stats-action@v2
        with:
          card: stats
          options: >-
            username=GilbertoParraSuarez
            &show_icons=true
            &include_all_commits=true
            &hide_border=false
            &theme=dracula
          path: dist/stats.svg
          token: ${{ secrets.GITHUB_TOKEN }}

      - name: Publish stats
        uses: crazy-max/ghaction-github-pages@v5
        with:
          build_dir: dist
          target_branch: stats-output
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

Reglas:

- No añadir un PAT hardcodeado.
- No mostrar tokens en logs.
- Usar `GITHUB_TOKEN`.
- No prometer estadísticas de repositorios privados; el token estándar de este workflow puede no tener acceso a otros repositorios privados del usuario.

El README debe consumir:

```text
https://raw.githubusercontent.com/GilbertoParraSuarez/GilbertoParraSuarez/stats-output/stats.svg
```

---

# 15. Workflow languages.yml

Crear o corregir:

```text
.github/workflows/languages.yml
```

Contenido esperado:

```yaml
name: Generate Languages Stats

on:
  schedule:
    - cron: "30 0 * * *"
  workflow_dispatch:

jobs:
  generate-languages:
    runs-on: ubuntu-latest

    permissions:
      contents: write

    steps:
      - name: Checkout repository
        uses: actions/checkout@v6

      - name: Generate Languages Card
        uses: stats-organization/github-readme-stats-action@v2
        with:
          card: top-langs
          options: >-
            username=GilbertoParraSuarez
            &layout=compact
            &langs_count=8
            &hide_border=false
            &theme=dracula
          path: dist/languages.svg
          token: ${{ secrets.GITHUB_TOKEN }}

      - name: Publish languages
        uses: crazy-max/ghaction-github-pages@v5
        with:
          build_dir: dist
          target_branch: languages-output
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

El README debe consumir:

```text
https://raw.githubusercontent.com/GilbertoParraSuarez/GilbertoParraSuarez/languages-output/languages.svg
```

---

# 16. Workflow snake.yml

Crear o corregir:

```text
.github/workflows/snake.yml
```

Usar:

- `Platane/snk/svg-only@v3`
- `crazy-max/ghaction-github-pages@v5`

Contenido esperado:

```yaml
name: Generate Snake Animation

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:

jobs:
  generate:
    runs-on: ubuntu-latest

    permissions:
      contents: write

    steps:
      - name: Generate contribution snake
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: GilbertoParraSuarez
          outputs: |
            dist/snake.svg
            dist/snake-dark.svg?palette=github-dark

      - name: Publish snake
        uses: crazy-max/ghaction-github-pages@v5
        with:
          build_dir: dist
          target_branch: snake-output
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

---

# 17. Snake Animation en README

Debe soportar modo claro y oscuro:

```html
<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/GilbertoParraSuarez/GilbertoParraSuarez/snake-output/snake-dark.svg"
  />

  <source
    media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/GilbertoParraSuarez/GilbertoParraSuarez/snake-output/snake.svg"
  />

  <img
    data-importer="snake"
    src="https://raw.githubusercontent.com/GilbertoParraSuarez/GilbertoParraSuarez/snake-output/snake.svg"
    alt="GitHub contribution snake"
  />
</picture>
```

---

# 18. GitHub Stats en README

Usar una composición centrada:

```html
<div data-importer="stats" align="center">

  <img
    src="https://raw.githubusercontent.com/GilbertoParraSuarez/GilbertoParraSuarez/stats-output/stats.svg"
    height="165"
    alt="GitHub stats"
  />

  <img
    src="https://raw.githubusercontent.com/GilbertoParraSuarez/GilbertoParraSuarez/languages-output/languages.svg"
    height="165"
    alt="Most used languages"
  />

</div>
```

No utilizar usernames de ejemplo como:

- `maurodesouza`
- `octocat`
- `YOUR_GITHUB_USERNAME`

---

# 19. Experiencia profesional en README

Después de las estadísticas añadir:

```markdown
## 💼 Professional Experience
```

Mostrar experiencia relevante de forma concisa.

Ejemplo:

```markdown
### Full Stack Developer — Mivilsoft

`Odoo` · `Python` · `React` · `React Native` · `SQLite` · `REST APIs` · `AI`

- Developed and maintained enterprise and ERP modules.
- Built cross-platform mobile applications for iOS and Android.
- Integrated external APIs and AI-powered solutions.
- Implemented database migrations and optimized queries.
- Performed unit, functional and integration testing.
```

Repetir el mismo estilo para:

- GAD Municipal de Tisaleo.
- Sprint Core.

Evitar párrafos demasiado largos.

---

# 20. Intereses y colaboración

Añadir una sección:

```markdown
## 🎯 What I'm currently interested in
```

Incluir:

- Full Stack / Software Engineering opportunities
- Web and mobile application development
- Enterprise software and ERP systems
- Backend services and REST API architectures
- AI integrations and business process automation
- Open-source projects
- Technical collaborations

No escribir que el usuario está desempleado.

No escribir “actively looking for work” salvo que el usuario lo pida expresamente.

---

# 21. Restricciones de contenido

## No inventar métricas

No escribir datos como:

```text
Improved performance by 60%
10,000+ users
Reduced costs by 40%
99.9% uptime
```

a menos que exista evidencia real o el usuario la proporcione explícitamente.

## No inventar certificaciones

No añadir certificaciones AWS, Azure, Google, Scrum u otras no proporcionadas.

## No añadir información privada innecesaria

No mostrar:

- números telefónicos;
- referencias laborales;
- direcciones físicas;
- documentos de identidad.

## No dejar placeholders visibles

Comprobar antes de finalizar:

```bash
grep -RInE \
  'YOUR_GITHUB_USERNAME|PROJECT_URL|TODO|FIXME|maurodesouza|octocat' \
  README.md .github/workflows \
  || true
```

El resultado ideal es vacío.

---

# 22. Validación de YAML

Antes de finalizar comprobar que los workflows son parseables.

Si Python y PyYAML están disponibles:

```bash
python - <<'PY'
from pathlib import Path
import yaml

for path in sorted(Path('.github/workflows').glob('*.yml')):
    with path.open('r', encoding='utf-8') as f:
        yaml.safe_load(f)
    print(f'OK: {path}')
PY
```

Si PyYAML no está instalado, no instalar dependencias globales solamente para esta validación. Usar una herramienta ya disponible o revisar manualmente la sintaxis e indentación.

---

# 23. Validación de URLs

Si el entorno tiene acceso de red, comprobar al menos:

```bash
curl -I -L --max-time 20 \
  https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif
```

También revisar que las URLs públicas utilizadas en README no tengan errores tipográficos.

No considerar error que las siguientes URLs todavía devuelvan 404 **antes de ejecutar por primera vez sus workflows**:

```text
.../stats-output/stats.svg
.../languages-output/languages.svg
.../snake-output/snake.svg
```

Las ramas y archivos se crean cuando los Actions terminan correctamente.

---

# 24. Integración con GitHub CLI

Si `gh` está instalado:

```bash
gh --version
gh auth status
```

Si está autenticado con acceso al repositorio, después del push intentar ejecutar manualmente:

```bash
gh workflow run stats.yml
gh workflow run languages.yml
gh workflow run snake.yml
```

Después revisar:

```bash
gh run list --limit 10
```

Cuando sea posible, inspeccionar la ejecución con:

```bash
gh run view <RUN_ID>
```

No asumir que un workflow funciona únicamente porque el YAML es válido.

---

# 25. Si GitHub Actions devuelve 403

Si un Action no puede publicar en `stats-output`, `languages-output` o `snake-output`:

1. Revisar el log exacto.
2. Confirmar que el job tenga:

   ```yaml
   permissions:
     contents: write
   ```

3. No crear un token personal automáticamente.
4. No solicitar ni almacenar contraseñas.
5. Informar al usuario si una política de GitHub está bloqueando la escritura.

Si se requiere una configuración manual, indicar revisar:

```text
Repository
→ Settings
→ Actions
→ General
→ Workflow permissions
```

No cambiar configuraciones sensibles mediante API sin autorización explícita.

---

# 26. Seguridad

Nunca:

- imprimir tokens;
- escribir tokens en archivos;
- subir `.env`;
- crear un Personal Access Token;
- copiar credenciales al README;
- almacenar secretos directamente dentro de YAML.

Usar:

```yaml
${{ secrets.GITHUB_TOKEN }}
```

para los workflows de este repositorio.

---

# 27. Control de calidad visual

Antes de terminar revisar `README.md` como documento completo y confirmar:

- El GIF está a la derecha y usa `height="150"`.
- No existe un banner excesivamente grande.
- El encabezado cabe razonablemente en GitHub desktop.
- About Me se entiende rápidamente.
- Las tecnologías están agrupadas.
- Portfolio, LinkedIn y Gmail están visibles antes de las estadísticas.
- Stats y Languages están centrados.
- Professional Experience aparece después de los elementos visuales.
- Snake Animation está cerca del final.
- No hay HTML sin cerrar.
- No hay tablas innecesariamente anchas.
- No existe contenido duplicado.
- El README funciona conceptualmente en light/dark mode.

---

# 28. Orden final recomendado de README.md

```text
1. Header
2. Coding GIF
3. About Me
4. Spanish About Me (<details>)
5. Languages & Technologies
6. Professional links
7. GitHub Stats
8. Professional Experience
9. Current Interests / Collaboration
10. Contribution Snake
11. Closing message
```

Mensaje final sugerido:

```markdown
### Thanks for visiting my profile! 👋

**Let's build software that solves real problems.**
```

---

# 29. Ejecución completa de la tarea

## Fase A — Inspección

- localizar root;
- revisar `git status`;
- revisar remote;
- leer README;
- leer workflows existentes.

## Fase B — Implementación

- actualizar `README.md`;
- crear o corregir `stats.yml`;
- crear o corregir `languages.yml`;
- crear o corregir `snake.yml`.

## Fase C — Revisión estática

- comprobar placeholders;
- comprobar nombres;
- revisar URLs;
- validar YAML;
- ejecutar `git diff --check`.

## Fase D — Git

- revisar `git diff`;
- añadir archivos;
- realizar commit si el entorno lo permite;
- hacer push si existe acceso autenticado.

## Fase E — GitHub Actions

Si existe GitHub CLI autenticado:

- ejecutar los tres workflows;
- revisar los runs;
- diagnosticar cualquier error;
- corregirlo si proviene del código o configuración del repositorio;
- volver a ejecutar el workflow afectado.

## Fase F — Verificación final

Comprobar, después de workflows exitosos, la existencia de:

```text
stats-output/stats.svg
languages-output/languages.svg
snake-output/snake.svg
snake-output/snake-dark.svg
```

mediante GitHub, API o remote cuando el entorno lo permita.

---

# 30. Criterios de aceptación

La tarea solo se considera terminada cuando se cumpla todo lo aplicable:

- [ ] `README.md` existe y está personalizado para Gilberto.
- [ ] No hay `YOUR_GITHUB_USERNAME`.
- [ ] El usuario utilizado es `GilbertoParraSuarez`.
- [ ] El GIF correcto está configurado.
- [ ] El portfolio correcto está configurado.
- [ ] LinkedIn correcto está configurado.
- [ ] Gmail correcto está configurado.
- [ ] Stack tecnológico coherente con el perfil profesional.
- [ ] Experiencia en Mivilsoft presente.
- [ ] Experiencia en GAD Municipal de Tisaleo presente.
- [ ] Experiencia en Sprint Core presente.
- [ ] `stats.yml` existe.
- [ ] `languages.yml` existe.
- [ ] `snake.yml` existe.
- [ ] Los workflows tienen `contents: write`.
- [ ] Los workflows tienen `workflow_dispatch`.
- [ ] Los workflows tienen `schedule`.
- [ ] Stats genera `stats.svg`.
- [ ] Languages genera `languages.svg`.
- [ ] Snake genera SVG light y dark.
- [ ] README referencia correctamente las ramas output.
- [ ] No hay secretos hardcodeados.
- [ ] YAML revisado o validado.
- [ ] `git diff --check` pasa.
- [ ] Los cambios quedan committeados si el entorno lo permite.
- [ ] Los cambios quedan pusheados si el entorno tiene autenticación.
- [ ] Los workflows se ejecutan o se deja una explicación precisa de cualquier bloqueo externo.

---

# 31. Respuesta final esperada de Codex

Al terminar, Codex debe responder de forma breve pero concreta indicando:

1. Qué archivos modificó o creó.
2. Qué validaciones ejecutó.
3. Si hizo commit.
4. Si hizo push.
5. Estado de cada GitHub Action.
6. Si queda alguna acción manual pendiente.

Formato sugerido:

```text
Completed:
- Updated README.md
- Created/updated stats.yml
- Created/updated languages.yml
- Created/updated snake.yml
- Verified no placeholders remain
- Validated YAML
- git diff --check passed
- Commit: <hash>
- Push: successful

GitHub Actions:
- GitHub Stats: success
- Languages: success
- Snake: success

No manual steps remaining.
```

Si una operación no pudo completarse por autenticación:

```text
Implementation is complete locally.

Pending:
- Push could not be performed because GitHub authentication is unavailable.
- Run: git push
- Then execute the workflows from GitHub Actions or with:
  gh workflow run stats.yml
  gh workflow run languages.yml
  gh workflow run snake.yml
```

No ocultar fallos y no declarar éxito de una acción que no se verificó.

---

# 32. Prioridad de estas instrucciones

Estas instrucciones aplican a todo el repositorio de perfil.

Si aparece otro `AGENTS.md` en un subdirectorio, respetar su ámbito para los archivos contenidos en ese subdirectorio.

Las solicitudes directas del usuario tienen prioridad sobre este documento.

El objetivo siempre es preservar un perfil profesional, verificable, limpio y fácil de mantener.
