# Usar con OpenAI / ChatGPT / Codex

Son las mismas cinco habilidades educativas, en el formato abierto SKILL.md. No son productos oficiales de OpenAI ni herramientas clínicas validadas. OpenAI tiene distintas aplicaciones: no todas ofrecen la misma instalación.

## ChatGPT: la vía sencilla
1. Escanea el QR de OpenAI. Elige una skill y abre “Instrucciones para copiar”.
2. Copia todo su contenido, pégalo en un chat nuevo y pide: “Sigue estas instrucciones para revisar el ejemplo ficticio que te adjunto”.
3. Aporta los datos solicitados. Si quieres conservar el flujo y tu cuenta ofrece Proyectos, usa un proyecto propio para esa tarea y guarda allí las instrucciones.
4. Esto es un prompt reutilizable o un proyecto con instrucciones: NO es una instalación nativa de una skill.

## Si tu aplicación permite skills nativas
La documentación oficial describe skills independientes en la app de escritorio de ChatGPT, Codex CLI y la extensión IDE; en web y móvil también existen skills distribuidas mediante plugins. La disponibilidad y la interfaz dependen del producto, versión y permisos.
- En la app de escritorio, abre Skills. Si tu versión ofrece crear/subir desde el ordenador, revisa el paquete y usa el formato que solicite esa interfaz. No asumas que subir un ZIP a cualquier conversación lo instala.
- Si aparece la skill, en ChatGPT puedes seleccionarla con @ y una petición explícita.
- Si no hay opción de importar, usa la vía sencilla de arriba. Este pack no es un plugin publicado en el directorio de OpenAI.

## Codex: instalación local documentada
1. Descarga y descomprime el pack OpenAI.
2. Copia las cinco carpetas incluidas en skills/ dentro de ~/.agents/skills/ en tu ordenador. Cada carpeta debe conservar su SKILL.md, EJEMPLO.md y agents/openai.yaml. No reemplaces carpetas preexistentes con el mismo nombre sin revisar sus diferencias.
3. Codex detecta los cambios; si no aparecen, reinicia la aplicación.
4. Invoca una skill con $lab-ordenes, o usa /skills. Las instrucciones son educativas y no incluyen scripts ejecutables ni autorizan acceso a sistemas del laboratorio.
5. Prueba primero los ejemplos ficticios y compara sus criterios esperados. La metadata exige invocación explícita para estas skills.

## Seguridad y compatibilidad
Cada persona usa su propia cuenta. No introducir datos identificables ni archivos confidenciales sin la evaluación correspondiente. No se ha probado la importación en todas las cuentas o clientes. La descarga y el formato son verificables; no equivalen a validación del rendimiento del modelo ni de un proceso clínico.

## Fuentes
https://learn.chatgpt.com/docs/build-skills
https://help.openai.com/en/articles/20001066-skills-in-chatgpt
Se leyó íntegramente la documentación de construcción de skills. La ayuda de ChatGPT solo pudo contrastarse mediante extractos indexados; sus controles de interfaz deben reconfirmarse en la cuenta. No se requiere comprar una API para la alternativa de copiar instrucciones; el uso depende del plan y los límites de la cuenta.
