# Company Brain Starter

**Ayuda a tu IA a entender tu trabajo. Empieza con un solo prompt.**

[English](README.md)

Una plantilla abierta para construir tu **Brain de trabajo privado**: rol,
colaboradores, proyectos, decisiones y fuentes. El asistente te entrevista y lo
organiza contigo. Para probar la conversación no necesitas rellenar plantillas,
instalar nada ni conectar tus aplicaciones.

**Versión preliminar: la estructura inicial está en revisión.**

## Empieza aquí

Abre Claude, Codex u otro asistente y pega esto:

```text
Ayúdame a configurar mi Brain de trabajo privado: una referencia pequeña y mantenida
sobre mi trabajo. Si puedes abrirlo, usa la guía de
https://github.com/andreu-alegre/company-brain-starter
Si no puedes, continúa con estas instrucciones; no finjas haberlo leído ni me hagas
instalar nada para empezar.

Usa mi idioma. Hazme una pregunta clara cada vez y espera mi respuesta.
Entiende mi empresa, rol, responsabilidades, colaboradores, proyectos, prioridades
y qué ayuda espero de ti. No los presupongas ni me hagas repetir lo que ya te conté.
Cuando ayude, ofréceme explicártelo o analizar una fuente concreta que yo elija.
Acuerda la fuente y el alcance antes de leer información externa. Podemos empezar
sin conectores. No me pidas contraseñas, tokens ni exports completos de mis cuentas.

Cuando sepas suficiente, enséñame un resumen breve con las dudas pendientes y pide
mi confirmación antes de guardarlo. Empieza con un único MY_BRAIN.md que contenga
mi perfil, colaboración, proyectos, decisiones, preguntas abiertas y fuentes con fechas.
Los datos reales van en mi propio espacio privado, nunca en el starter público.
Si no puedes guardar archivos, entrégame el documento y explícame cómo conservarlo.
No cambies ajustes, publiques, envíes mensajes ni conectes cuentas por este setup.
Al terminar propón una tarea pequeña que me resulte útil. Empieza por la primera pregunta.
```

Ya puedes empezar. Puedes saltar preguntas, decir que no lo sabes o pedir una versión
de cinco preguntas. No tienes que completar un formulario interminable.

## Qué ocurrirá

El asistente entiende tu trabajo, te muestra lo que ha entendido y prepara tu
`MY_BRAIN.md`. Si puede escribir y le das permiso, lo guarda en tu espacio privado;
si no, te entrega el documento. Después probáis una tarea: preparar una reunión,
ordenar un proyecto o conservar una decisión.

El prompt sirve para conversar sin acceso al repo. La escritura, memoria, skills y
conectores dependen de tu aplicación y cuenta. Si quieres usar una carpeta, tienes
[notas opcionales para Claude y Codex](docs/assistant-setup.md).

## La estructura crece cuando la necesitas

Empieza con [un documento](templates/MY_BRAIN.md). Cuando se quede grande, pide al
asistente que distribuya el contenido en `context/`, `projects/`, `decisions/`,
`inbox/` y `sources/`. Al migrar, el documento inicial debe quedar como índice;
mantener dos copias distintas del contexto crea contradicciones.

**La plantilla es pública. Tu Brain completo debe ser privado.** Puedes descargar
el ZIP o usar **Use this template**, cuando esté disponible, y elegir un repo nuevo
**privado**. No subas contexto real a un fork, issue o PR públicos.

Incluye [setup guiado](SETUP.md), [tres flujos](skills/README.md),
[plantillas](templates/README.md) y un [ejemplo ficticio](examples/meeting.md).
Las instrucciones de los flujos están en inglés; el asistente debe responder en tu idioma.

El Brain no se actualiza solo, no conecta cuentas ni activa automatizaciones.

[Privacidad](PRIVACY.md) · [Contribuir](CONTRIBUTING.md) ·
[Fuentes](docs/sources.md) · [Licencia MIT](LICENSE)
