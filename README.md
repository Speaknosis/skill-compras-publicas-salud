# Skill: Compras públicas e integridad para startups de salud digital (Chile)

Skill para Claude (Claude Code / Claude.ai) que orienta a startups y empresas de salud digital para relacionarse con el sector público chileno de forma ética y legal, y para vender por **Compras Públicas de Innovación (CPI)**.

Nace de los materiales compartidos por el ecosistema **ECO-SD / CENS** (Jornada del 28-10-2026).

## Contenido

- `SKILL.md`: instrucciones y mapa de situaciones (reuniones por Ley del Lobby, RFI, Contratos para la Innovación, Diálogo Competitivo, pilotos, conflictos de interés).
- `references/`: un resumen fiel y citado de cada documento fuente.
- `templates/`: solicitud de audiencia por Ley del Lobby, respuesta a un RFI de innovación y declaración de conflictos de interés.
- `sources/`: los PDF originales, para verificar.

## Instalación

- **Claude Code:** copiar o clonar esta carpeta en `~/.claude/skills/compras-publicas-salud/` (personal) o en `.claude/skills/compras-publicas-salud/` de un proyecto.
- **Claude.ai:** comprimir la carpeta (sin `sources/` si pesa demasiado) y subirla en Settings → Capabilities → Skills.

## Cómo usarlo en ChatGPT, Gemini u otras IA

El formato `SKILL.md` se activa solo en Claude. Igual el contenido es texto Markdown más PDFs, así que se puede usar en otras herramientas configurándolo a mano:

- **ChatGPT (GPT personalizado):** en *Explorar GPTs → Crear → Configurar*, pegar el contenido de `SKILL.md` (sin el bloque inicial entre `---`) en **Instrucciones**, y subir los archivos de `references/` y `templates/` en **Conocimiento**. Opcional: subir también los PDF de `sources/`.
- **Gemini (Gem):** en *Gems → Nuevo Gem*, pegar `SKILL.md` en las **instrucciones** y adjuntar `references/` y `templates/` como **conocimiento**.
- **NotebookLM:** crear un cuaderno y subir los PDF de `sources/` junto con los archivos de `references/`. Responde con citas a los documentos originales.
- **Otra IA:** usar `SKILL.md` como prompt de sistema y adjuntar las referencias que necesite cada pregunta.

Los nombres de los menús de cada plataforma pueden cambiar. Si alguna no acepta archivos `.md`, se pueden renombrar a `.txt`.

## Pendientes

- Verificar contra el texto oficial los plazos de la Ley 20.730 y su Reglamento (`references/ley-lobby.md`, Parte B).
- Sumar los documentos de las mesas de trabajo de ECO-SD cuando CENS los comparta.

> No constituye asesoría legal. Verificar siempre en las fuentes oficiales.
