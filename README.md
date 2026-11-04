# el-secretario

Estructura inicial para darle contexto estable a Codex, Claude, Gemini u otro harness que pueda trabajar con archivos.

El sistema sirve para:

- capturar notas, reuniones e ideas sin ordenarlas manualmente;
- conservar las fuentes originales;
- separar decisiones, tareas, preguntas e ideas de contenido;
- mantener proyectos y productos actualizados;
- preparar una revisión semanal;
- automatizar borradores sin publicar ni enviar nada por cuenta propia.

## Descargar o clonar

### Opción sencilla

1. Presioná el botón verde **Code**.
2. Elegí **Download ZIP**.
3. Descomprimí la carpeta.
4. Abrila desde Codex, Claude Code, Gemini o la herramienta que uses.

### Usando Git

```bash
git clone https://github.com/belenperaltaaccenture/el-secretario.git
```

## Primer mensaje para la IA

Copiá el contenido de [`PROMPT_MAESTRO_SEGUNDO_CEREBRO.md`](PROMPT_MAESTRO_SEGUNDO_CEREBRO.md) o decile:

> Leé README.md e INSTRUCCIONES_IA.md. Revisá la estructura y explicame cómo usarla. No modifiques archivos todavía.

Después completá [`01_NEGOCIO/CONTEXTO_DEL_NEGOCIO.md`](01_NEGOCIO/CONTEXTO_DEL_NEGOCIO.md) y dejá tu primera nota dentro de `00_ENTRADA`.

## Estructura

```text
00_ENTRADA       Notas sin procesar
01_NEGOCIO       Objetivos y criterios: información funcional
02_CLIENTES      Preguntas y lenguaje real
03_PRODUCTOS     Tableros, Apps y Power Automate
04_CONTENIDOS    Ideas y borradores
05_PROCESOS      Procedimientos repetibles
06_PROYECTOS     Trabajo activo
07_REVISIONES    Resúmenes semanales
99_ARCHIVO       Información inactiva
prompts          Instrucciones reutilizables
```

## Automatización incluida

[`prompts/AUTOMATIZACION_REVISION_SEMANAL.md`](prompts/AUTOMATIZACION_REVISION_SEMANAL.md) define una revisión de los viernes. La IA puede preparar el borrador, pero no publicar, enviar mensajes, borrar fuentes ni cambiar servicios externos.

Si tu herramienta no admite tareas programadas, ejecutá manualmente [`prompts/REVISION_SEMANAL.md`](prompts/REVISION_SEMANAL.md). El sistema sigue funcionando.

## Seguridad y privacidad

Este repositorio es público y contiene solamente plantillas vacías e instrucciones reutilizables.

Cuando lo uses:

- no subas información real de clientes a un repositorio público;
- no guardes contraseñas, claves de API, tarjetas ni documentos personales;
- trabajá localmente o creá un repositorio privado para tu información real;
- revisá siempre los cambios antes de publicar o compartir;
- conservá intervención humana para acciones externas.

## Regla principal

Los archivos guardan la memoria. La IA procesa. Las automatizaciones repiten. La persona decide.
