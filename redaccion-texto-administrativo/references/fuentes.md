# Fuentes y decisiones

## Fuentes usadas

| Fuente | Qué aporta | Qué se tomó |
|---|---|---|
| **Decreto 336/2017**, *Lineamientos para la redacción y producción de documentos administrativos* (B.O. 16/05/2017) | Definiciones de tipos de documento; reglas mínimas de estilo; trámite en GDE; proyectos de actos | Definiciones e identificación inequívoca. El trámite va al skill de GDE; los proyectos de actos, a `labor-normativa-senasa`. |
| **Curso INAP *Producción de textos administrativos*** (Unidades 1 a 3, entrevista, infografía, hoja de ruta, ficha "Cómo construir un texto") | Método: niveles y parámetros del texto, funciones, proceso de escritura, preguntas centrales, coherencia y cohesión, errores frecuentes | Los tres ejes, la ficha de situación, el catálogo de errores. Se dejó afuera la teoría (Bajtín, Navarro, Montolío) y la remisión a normas APA. |
| **Nuevo Manual de Estilo de la Procuración del Tesoro de la Nación** (365 págs.) | Pautas generales de redacción, gramática, organización, diccionario de dudas, géneros de la PTN | Págs. 13–23 (pautas generales), 108–114 (organización, resumida), gramática selectiva (244–284) y una selección del diccionario (285–340). |
| **Memorándum ME-2026-99051774-APN-DPYESA#SENASA** (DPyESA, 9/10/2026) | Ejemplo real de solicitud entre áreas en GDE | Orden de la solicitud, formas de cortesía, ofrecimiento de colaboración, bloque de contacto del programa. Las fórmulas propias del género (encabezado, "De mi mayor consideración", cifras en letras) quedan para `redaccion-senasa`. |

Del Manual de la PTN quedaron **para otros skills**: nombres de organismos y cargos, siglas y mayúsculas (págs. 23–39 y 200–228), citas de normas (60–92) y estructura de notas, memos, providencias y resoluciones (142–162). Se **descartaron**: escritos judiciales, oficios judiciales, informes de auditoría, citas de fallos y de libros, acentuación y ortografía básica, números y gráficos.

## Jerarquía

1. Normativa vigente (Dto. 336/2017).
2. RAE y Asociación de Academias.
3. Lenguaje claro y no sexista.
4. Manual de Estilo de la PTN, donde no contradiga lo anterior.
5. Curso INAP, como método.

## Contradicciones resueltas

| Conflicto | Decisión |
|---|---|
| La PTN da por incorrectas formas que la RAE admite ("en mi opinión", "a mi criterio", "diferente a", "más cercano a", "con ocasión de") | Prevalece la RAE. Esas entradas no se usan como error. |
| La PTN prefiere "la Presidente", "la juez", "la Intendente" | Prevalece el lenguaje no sexista: "la presidenta", "la jueza", "la intendenta". |
| La PTN y el curso aceptan fórmulas como "Me dirijo a usted a fin de…", "Saludo a usted atentamente", "Esperando una respuesta…, lo saludo atentamente" | Prevalece el lenguaje claro: apertura breve que enuncia el propósito y cierre simple. Se elimina el relleno y el gerundio de cierre. |
| La PTN lista conectores arcaicos (*ergo*, *empero*, *va de suyo*, *habida cuenta de que*) | Se filtran: tabla de conectores de uso actual en `construccion-textual.md`. |
| La PTN impone la primera del singular en notas y memos y prohíbe la primera del plural | La voz depende del lugar de enunciación (a título personal, en representación, firma conjunta). Lo obligatorio es una sola voz en todo el texto. |
| Cifras: el Dto. 336 pone letras y número entre paréntesis ("TREINTA (30)"); la PTN, número y letras entre paréntesis, y prohíbe el orden inverso | No lo decide este skill: depende del género y del organismo (skill `redaccion-senasa` y `labor-normativa-senasa`). |
| Mayúsculas en organismos y cargos: el Dto. 336 permite mayúsculas sostenidas; la PTN usa iniciales mayúsculas; la RAE recomienda minúscula para cargos | No lo decide este skill: va al skill del organismo. |
| La PTN escribe "éstos", "sólo" con tilde en algunos casos | Prevalece la Ortografía de 2010: sin tilde en demostrativos y en "solo". |
| El curso propone como estructura del informe "hipótesis" y "metodología" | Se tomó el esquema introducción, desarrollo, conclusión. La hipótesis y la metodología solo si el informe es un estudio. |
| Lenguaje claro frente a cortesía institucional (iteración 1: los pedidos salieron imperativos y el contacto, personal) | Claridad y cortesía no se oponen. Se eliminan el relleno y los rodeos, pero los pedidos se formulan con formas respetuosas ("se solicita", "se agradecerá"), se ofrece colaboración y el contacto es del área, con canales completos. |
| Lenguaje claro frente a formalidad (iteración 2) | Lo escrito no tiene metamensaje: la consideración hacia el receptor (competencia, contexto, limitaciones) debe estar explícita. Primera oración con el objetivo, breve y concisa; desarrollo completo en los párrafos siguientes. |
| "Tenga a bien": el curso la da como relleno ("Solicito tenga a bien enviarme" → "Solicito que me envíe") | Prevalece la práctica validada por la DNSA (iteración 3): es fórmula de cortesía en el pedido principal, no relleno. Una vez por texto. |
| Texto explicativo (iteración 3) | Cada párrafo de desarrollo anuncia su función y los datos se presentan con su lectura para el receptor. Modelo en `construccion-textual.md`, punto 12. |
| Objetivo primero frente a contexto necesario (iteración 4) | El primer párrafo es contexto mínimo + objetivo. Si el receptor no entiende el pedido sin un antecedente, ese antecedente va antes, en una oración, enlazado con "En este sentido, me dirijo…". |
| Firma en GDE | El cuerpo del documento termina en la fórmula de cierre; firma, número, fecha y lugar los agrega el sistema. |

## Pendientes

- Resuelto (octubre de 2026): el detalle del lenguaje no sexista está en `identidad-senasa` (`references/redaccion.md`); este skill conserva un resumen para funcionar solo. Formato de porcentajes: con espacio ("62 %"), en los dos skills.
- Definir con el skill `redaccion-senasa` las convenciones de cifras, mayúsculas y fórmulas de cada género.
