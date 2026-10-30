---
name: compras-publicas-salud
description: Guía para que startups y empresas de salud digital en Chile se relacionen con el sector público de forma ética y legal, y vendan por Compras Públicas de Innovación (CPI). Usar cuando el usuario quiera pedir una reunión a un hospital, servicio de salud, Minsal u otro organismo público (Ley del Lobby 20.730), responder una consulta al mercado o RFI en Mercado Público, postular a un Contrato para la Innovación o Diálogo Competitivo, preparar un piloto con una institución pública, declarar conflictos de interés o aplicar el Marco Ético de Relacionamiento de ECO-SD/CENS. También para preguntas como "¿puedo juntarme con el director del hospital?", "¿cómo le vendo al Estado?" o "¿qué es la CPI?".
---

# Compras públicas e integridad para startups de salud digital (Chile)

Esta skill reúne en un solo lugar la normativa y las guías oficiales que necesita un proveedor de salud digital para **relacionarse con el Estado chileno y venderle innovación** sin poner en riesgo la probidad. Está pensada para startups del ecosistema ECO-SD (CENS).

> **No es asesoría legal.** Resume documentos oficiales con fechas de corte. Antes de decidir, verifica en la fuente (los links están en cada referencia) y, si hay montos, plazos o sanciones en juego, consulta con un abogado.

## Fuentes incluidas (en `references/`)

| Archivo | Documento | Úsalo para |
|---|---|---|
| `marco-etico-cens.md` | Marco Ético de Relacionamiento para Ecosistemas de Innovación en Salud Digital, ECO-SD/CENS (ene-2026) | Principios, conflictos de interés, pilotos, privacidad, la matriz de acciones |
| `ley-lobby.md` | Código de ética y buenas prácticas sobre lobby y gestión de intereses (Comisión de Integridad, nov-2023) + Ley 20.730 del Lobby | Pedir reuniones, sujetos pasivos, las 12 buenas prácticas y un checklist |
| `politica-cpi-ds523.md` | Política de Compra Pública de Innovación, Decreto exento N°523 Hacienda (30-dic-2024, DO 12-mar-2025; algunos documentos lo citan como "DS 53") | Definiciones legales, Contratos para la Innovación vs Diálogo Competitivo, art. 35 ter |
| `orientaciones-cpi-compradores.md` | Orientaciones en CPI para compradores del Estado, ChileCompra (22-ago-2025) | Cómo parte una CPI en el organismo, RFI (formato y 17 preguntas), plazos |
| `manual-contratos-innovacion.md` | Manual Comprador: Contratos para la Innovación, ChileCompra v1 (19-dic-2025) | Etapas y operación en Mercado Público, qué debe presentar el proveedor |
| `informe-comite-cpi-2025.md` | Informe del Comité de Compra Pública de Innovación y Sustentabilidad 2025 | Estado real de la CPI, organismos activos, metas 2026 |

Plantillas en `templates/`: solicitud de audiencia por Ley del Lobby, respuesta a un RFI de innovación y declaración de conflictos de interés.

Lee solo las referencias que necesite la pregunta. Cita el documento y la página o artículo cuando des una respuesta normativa.

## Mapa rápido: ¿qué situación es?

1. **"Quiero reunirme con alguien de un hospital, servicio o ministerio."**
   → Si la persona es **sujeto pasivo** y el objetivo es influir en una decisión (incluida una compra), la reunión va **por Ley del Lobby** (`references/ley-lobby.md`, `templates/solicitud-audiencia-lobby.md`).
   → Si el funcionario relevante **no es sujeto pasivo**, no lo busques por fuera: pide al organismo que lo incorpore como sujeto pasivo (Código de buenas prácticas, BP 4).
   → Ojo con el equipo: quien trabaje o preste servicios a honorarios en esa institución, o sea familiar o amigo de la autoridad, no participa en la gestión (BP 2 y 5). En salud es frecuente que un médico asesor también trabaje en el hospital.
   → Si hay una **licitación o procedimiento de compra en curso** sobre esa materia, **no hay contacto directo** con quienes participan en la adjudicación (prohibición de contactos, art. 35 ter Ley 19.886). Las dudas se canalizan por el foro de Mercado Público. La única excepción es *dentro* de un Diálogo Competitivo de Innovación (`politica-cpi-ds523.md` §4.2).

2. **"Salió una consulta al mercado / RFI que calza con lo que hacemos."**
   → Respóndela; **no es lobby**. Usa `templates/respuesta-rfi-innovacion.md` y el formato de `orientaciones-cpi-compradores.md` §6. Responde **al problema** del organismo, con costos en CLP desglosados, riesgos con mitigación e indicadores medibles. Las respuestas al RFI alimentan el diseño de las bases.

3. **"¿Cómo le vendo innovación al Estado?" / "¿Qué es la CPI?"**
   → La CPI tiene dos procedimientos especiales (Ley 19.886 art. 7 d) N°4 y N°5, vigentes desde jun-2025):
   - **Contratos para la Innovación:** cuando el problema requiere I+D+i y no existe una solución en el mercado. Va por fases (exploratoria, convocatoria y selección, desarrollo por fases y evaluación). El Estado paga el desarrollo y los prototipos de los seleccionados aunque no ganen el contrato final, salvo decisión fundada en contrario. El RFI es **obligatorio**.
   - **Diálogo Competitivo de Innovación:** cuando existen soluciones dispares que deben adaptarse. Hay diálogo directo con los participantes dentro del procedimiento y termina en bases "a firme".
   - Si ya existen soluciones similares en el mercado, **no corresponde CPI**: va por licitación, convenio marco u otro mecanismo de la Ley 19.886.
   → En Mercado Público, un Contrato para la Innovación tiene dos etapas. **CI1** es la convocatoria y preselección: queda vinculada al ID del RFI, se presenta solo oferta técnica (sin oferta económica) y esas ofertas no son públicas. Los preseleccionados reciben cofinanciamiento por fase mediante OC parciales. **CI2** es cerrada, solo para quienes llegan al final, y puede declararse desierta. Ver `manual-contratos-innovacion.md`.
   → **Quien inicia la CPI es el organismo**, no el proveedor (escribe a cpi@chilecompra.cl). Ver `orientaciones-cpi-compradores.md` §3 y `manual-contratos-innovacion.md`.
   → Expectativas realistas: una CPI toma **en general 10 meses o más** desde la exploración hasta la adjudicación. Al 31-12-2025 no se había publicado ningún Contrato para la Innovación ni Diálogo Competitivo, solo RFI (`informe-comite-cpi-2025.md`). Considéralo para el pipeline y la caja.

4. **"Un hospital nos propone un piloto o convenio."**
   → Aplica el Marco Ético: acuerdo **escrito, exacto y publicable**; roles y riesgos compartidos; umbrales de riesgo clínico definidos de antemano; indicadores de éxito; política de privacidad y ciberseguridad (Leyes 19.628 y 20.584); cláusulas sobre uso de información; plan para compartir aprendizajes. Declara conflictos (`templates/declaracion-conflictos-interes.md`).
   → Ojo: un piloto gratuito no debe convertirse en ventaja para una compra futura. Si después habrá compra, debe pasar por el procedimiento que corresponda.

5. **"¿Podemos invitar, regalar o patrocinar algo?"**
   → Por defecto, **no** a funcionarios que deciden. Los donativos a sujetos pasivos son públicos y la normativa de probidad los restringe. Si es un evento abierto del ecosistema, transparenta quién financia qué (`marco-etico-cens.md`, principio de Transparencia).

6. **"Dónde posicionar la solución."**
   → La política CPI 2025-2026 prioriza las áreas de **transformación digital**, **experiencia usuaria** y **medio ambiente**. Si el problema está fuera de esas áreas, debe cumplir al menos 3 variables de priorización (valor público, desarrollo de startups y Pymes, escalabilidad, etc.). Ver `orientaciones-cpi-compradores.md` §1.4 y `politica-cpi-ds523.md` §2.

## Reglas de comportamiento de la skill

- **Pacientes primero.** Si una táctica comercial tensiona la seguridad, la privacidad o la autonomía clínica, dilo explícitamente.
- No sugieras atajos: reuniones "informales" con evaluadores, redactarle el RFI o las bases al organismo para que calcen con el producto, o pilotos condicionados a una compra.
- Distingue siempre entre **lo que dice el documento** (con cita) y **tu interpretación**.
- Si la pregunta requiere algo que no está en estas fuentes (montos y umbrales de la Ley 19.886 y su Reglamento DS 661/2024, convenio marco, trato directo, garantías), dilo y remite a ChileCompra o al texto legal en bcn.cl.
- Responde en español de Chile, en lenguaje claro.

## Links oficiales

- Ley del Lobby: https://www.leylobby.gob.cl/ · Registros: https://www.infolobby.cl
- Código de buenas prácticas de lobby: https://www.leylobby.gob.cl/files/buenas_practicas_lobby.pdf
- Compra Pública de Innovación (ChileCompra): https://www.chilecompra.cl/cpi/ · cpi@chilecompra.cl
- Mercado Público: https://www.mercadopublico.cl
- Marco Ético ECO-SD/CENS: https://eco-sd.cl/static/ecosistema_salud/files/2026_Marco%20%C3%89tico%20de%20Relacionamiento.pdf
