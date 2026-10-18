# Redacción de texto administrativo — guía de instalación y uso

Skill: `redaccion-texto-administrativo` · Versión 1.0 · Octubre de 2026

## Qué hace

Redacta desde cero o revisa comunicaciones oficiales de la Administración Pública (notas, memorandos, informes, providencias, circulares, dictámenes, correos con valor de comunicación oficial) con lenguaje claro y cortesía institucional.

Trabaja en tres ejes antes de escribir:

1. **Situación comunicativa**: quién escribe y desde qué lugar, a quién, para qué. Si no lo puede inferir, lo pregunta.
2. **Proceso de escritura**: las preguntas centrales y el plan del texto (primer párrafo con contexto mínimo y objetivo; párrafos que anuncian su función).
3. **Construcción textual**: coherencia, cohesión, léxico y 34 errores frecuentes.

No se aplica a textos que no son comunicación oficial (artículos científicos, posteos, mensajes privados).

## Cuándo se usa

Claude lo aplica solo cuando el pedido lo necesita; no hace falta nombrarlo. Ejemplos de pedidos:

- "Redactame una nota a la Dirección de Laboratorio Animal pidiendo prioridad para procesar unas muestras."

- "Revisá este memo antes de mandarlo a firmar: […]"

- "Este informe quedó largo y confuso, ¿lo podés pulir?"

## Cómo instalarlo

1. Descargá el archivo `redaccion-texto-administrativo.zip` de este repositorio (botón *Download raw file*). No uses "Code → Download ZIP": agrega una carpeta extra y Claude no lo reconoce. No lo descomprimas.
2. En Claude (web o escritorio), entrá a **Customize > Skills** (en español, **Personalizar > Skills**), o directamente a claude.ai/customize/skills.
3. Tocá **+**, después **Create skill** y elegí **Upload a skill** (subir un skill). Seleccioná el ZIP.
4. Verificá que quede activado con el interruptor al lado del nombre.

**Requisitos**: cualquier plan de Claude (Free, Pro, Max, Team o Enterprise) con **Code execution and file creation** (ejecución de código y creación de archivos) activado en **Settings > Capabilities**. En planes Team o Enterprise depende de que la organización lo habilite.

**Actualizar**: borrá o desactivá la versión anterior y subí el ZIP nuevo.

## Cómo se relaciona con los otros skills

Funciona solo, pero rinde más junto con **Redacción Senasa** (que va primero: perspectiva, género y público), **GDE Senasa** (carga y firma) e **Identidad Senasa** (lenguaje no sexista y diseño). El orden completo está en la guía general del ecosistema.

## Para tener en cuenta

- Revisá siempre el resultado antes de firmar o publicar: el skill propone, la responsabilidad es de quien firma.

- Los datos que no estén en tu pedido (cifras, normas, nombres, números de GDE) quedan marcados como `[completar: …]`; no se inventan.

- Si algo de la estructura del Senasa cambió (organigrama, códigos, nomenclatura), avisá para actualizar el skill.

## Fuentes

Las instrucciones de este skill salen de:

- Curso *Producción de textos administrativos* (INAP): unidades 1 a 3, hoja de ruta, infografía y entrevista.

- Decreto 336/2017, *Lineamientos para la redacción y producción de documentos administrativos*.

- *Manual de Estilo* de la Procuración del Tesoro de la Nación (PTN).

- Real Academia Española (DPD y Ortografía) y recursos de lenguaje claro de argentina.gob.ar.

- Comunicaciones oficiales reales de la DPyESA (2026), usadas como modelo y validadas por el Programa de Sanidad Porcina.

- Guía oficial de uso de skills en Claude: support.claude.com/en/articles/12512180-use-skills-in-claude.

Elaborado por Alejandro E. Pérez (Programa de Sanidad Porcina, DPyESA – DNSA – SENASA) con Claude, octubre de 2026. Consultas y sugerencias: a quien te compartió esta carpeta.
