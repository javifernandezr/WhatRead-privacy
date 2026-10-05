# Web de privacidad de WhatRead

Preparada el 05/10/2026 para publicación manual por el propietario.

## Archivo que debes subir

Sube **solo `index.html`** a la raíz del repositorio o alojamiento que utilizarás para esta web. No necesita instalar dependencias, compilar, subir imágenes ni incluir este README: el estilo y el icono están dentro del HTML. También puedes abrirlo directamente en un navegador para revisarlo antes de subirlo.

Una vez publicada, utiliza:

- La URL principal de la página para la política de privacidad.
- Esa misma URL seguida de `#eliminar-cuenta` para la solicitud de eliminación de cuenta y datos.
- `#condiciones` y `#contacto` para enlazar las otras secciones, si lo necesitas.

La página debe poder leerse sin iniciar sesión. Después de publicarla, facilitar la URL definitiva para incorporarla en la app y Play Console; no se ha supuesto ni registrado un dominio futuro.

## Contenido y funcionamiento

Mantiene la tarjeta, fondo suave y estructura de la referencia New Year World, con verde `#426339`, negro `#141817` y fondo claro `#F4F2EA` de WhatRead. Incluye privacidad, cuenta/biblioteca, consultas a catálogos, cámara/galería, ML Kit, MiniLM, consentimientos Analytics/Crashlytics, conservación, derechos, condiciones de uso y contacto.

Por instrucción del propietario, el responsable figura como «desarrollador/publicador de WhatRead». El correo de contacto público es `whatread.info@gmail.com`.

El enlace de solicitud de borrado abre el programa de correo con destinatario, asunto y texto preparados; la persona debe enviar el mensaje. No existe un formulario ni borrado automático en esta web. El publicador debe atender ese buzón, verificar la titularidad y tramitar la eliminación de Firebase Authentication y de los documentos/subcolecciones asociados al UID en Firestore. Eliminar solamente el usuario de Authentication no elimina por sí solo sus datos de Firestore. No se ha ejecutado ningún borrado real ni enviado correos durante la preparación.

La app actual ofrece «Vaciar mi biblioteca», que no elimina la cuenta. Falta incorporar un acceso visible a la solicitud de borrado y a la URL pública desde la app y validar la tramitación completa. También falta confirmar la retención de observabilidad en los servicios configurados (punto 8); el HTML no inventa un plazo concreto de consola. **El punto 6 del checklist permanece pendiente** hasta publicar la página y completar esos pasos. La preparación de los textos no acredita por sí sola aceptación por Google Play ni una revisión jurídica integral.

## Revisión ejecutada

HTML autocontenido y sin scripts, formularios, recursos externos ni cookies propios. Enlaces internos y correo preparados correctamente; se inspeccionan capturas de escritorio, borrado y móvil a 390/320 px, sin desbordamiento horizontal. Evidencia: `artifacts/validation/privacy-web-review.json` y `artifacts/ui/privacy_web/`. No se modifica ni compila la app Flutter por esta entrega.

Referencias revisadas: [página del propietario](https://javifernandezr.github.io/newyearworld-privacy/), [eliminación de cuentas en Play](https://support.google.com/googleplay/android-developer/answer/13327111?hl=es), [Firebase](https://firebase.google.com/support/privacy), [ML Kit](https://developers.google.com/ml-kit/terms), [GitHub](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement) y [derecho de información — AEPD](https://www.aepd.es/derechos-y-deberes/conoce-tus-derechos/derecho-de-informacion).
