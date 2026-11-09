# Estado al 2026-11-08
Agente: OpenAI Codex Desktop. Tarea actual: piloto Apple Music Web CDP autenticado en segundo plano.

## Apple Music Web CDP
El perfil aislado llegó a Apple Music y encontró el resultado exacto Ghost Town (feat. PARTYNEXTDOOR) de Kanye West. La corrección anterior permitió enviar el clic DOM con focus=false y visibility=visible, pero la reproducción no avanzó durante 42 s (currentTime=0, playbackState=none). Se modificó el piloto para pasar el puntero por el arte y enviar un clic de ratón CDP al centro del botón Play observado. Se añadió telemetría segura para estado de carga y error del elemento multimedia, sin imprimir URLs firmadas. node --check pasó. El nuevo gesto no tiene aún validación física. Informe y prueba: Indicaciones/PRUEBA_APPLE_WEB_CDP.md; flujo: Indicaciones/FLUJO_APPLE_WEB_CDP.md.

## Trabajo previo
El coordinador académico conserva un paquete con hashes y bloquea reenvíos inciertos. Se documentaron 44 pruebas y una simulación adicional, sin validar una tarea real completa. El piloto Apple Music confirmó Ghost Town en primer plano; fondo sigue en evaluación. Cider y MusicKit son pilotos separados.

Siguiente paso: ejecutar una sola prueba autenticada del nuevo clic CDP. Se espera focus=false, título correcto, currentTime creciente hasta superar 30 s y sin que Brave recupere el foco. Si no inicia, distinguirlo con paused, readyState, networkState, srcHost y error de la salida. No integrar a Viernes hasta confirmar.

## Recuperación de voz, música y búsqueda pública
OpenAI Codex Desktop verificó Python 3.11.9 y sus dependencias en la ejecución de Windows. Corrigió falsas continuaciones y cancelaciones, agregó atenuación mediante la API local cuando Windows no expone sesión activa del reproductor y confirmó pausa, letras, aleatorio, repetición y volumen. 122 pruebas automatizadas pasaron. La prueba conjunta con música y micrófono completó la frase sintética, redujo y restauró el volumen y conservó el estado inicial. La búsqueda pública funciona en el perfil separado de Brave mediante Playwright cuando el conector personal no responde. La extensión personal sigue agotando su plazo. Apple Music Web por CDP queda pausado, porque el hover recuperó el foco antes del clic.
Pendiente: medir habla natural con música y conversaciones de fondo y mejorar la latencia de la parada confirmada. Informe local en Indicaciones/ENTREGA_RECUPERACION_VOZ_CIDER_BRAVE.md.

## Actualización de música y voz · 2026-11-08
Cider es el reproductor de la ruta principal de música. Pruebas reales de consola confirmaron pista, progreso y conservación de foco con Cider al frente y con Brave al frente. También se verificaron arranque en frío, cola de playlist y panel de letras. Los lanzadores habituales reutilizan la autorización local protegida por Windows. El conector personal Playwright respondió desde Brave. Se verificaron Groq y DeepSeek y se ejecutaron regresiones de voz y música. El comportamiento con voz natural, ruido del cuarto y juego real a pantalla completa queda por medir. Informe local: `Indicaciones/INFORME_CIDER_CONSOLA_Y_VOZ.md`.

## Selección por título y recepción de voz · 2026-11-08
Viernes reproduce una coincidencia musical clara o devuelve opciones numeradas, conserva elecciones tras la interrupción por activación y reconoce títulos confirmados en la sesión. La captura permanece activa entre ciclos en reposo. Se verificaron desde consola selección, avance de cola y volumen de Cider. El micrófono configurado entregó muestras y los casos sintéticos validaron la ruta de voz. Siguiente comprobación: órdenes naturales con música de fondo. Informe local: `Indicaciones/INFORME_TITULOS_Y_RECEPCION_CIDER.md`.

## Interrupción de voz y retroceso · 2026-11-08
Viernes 0.16.1 activa una pausa provisional ante indicios de voz cercana mientras habla. La parada o la nueva llamada se decide después de confirmar la toma. Se redujo la ganancia de la voz sintetizada para reducir eco y se comprobó retroceso de pista y de opción en Cider real. La lógica de voz pasó las pruebas tras el filtro de eco. La entrada previa al filtro presentó detección variable durante la salida, por lo que queda contrastar voz natural en el equipo. Informe local: `Indicaciones/INFORME_INTERRUPCION_VOZ_REAL.md`.

## Seguimiento musical de Cider
OpenAI Codex Desktop · Cider conserva la última lista musical para ordinales consecutivos y corrige variantes de letras y de artista en órdenes musicales. El panel usa UI Automation de Windows. 75 pruebas automáticas correctas. Falta comprobar voz y Cider en sesión interactiva. Informe local: Indicaciones/INFORME_SEGUIMIENTO_CIDER.md.

## Captura de ESPOL hacia Codex
OpenAI Codex Desktop · Orden explícita para adjuntar la captura de una actividad visible de ESPOL y enviar su consigna y materiales verificados a un solo chat de Codex mediante el coordinador existente. 72 pruebas automáticas correctas; falta la comprobación en sesión real. Informe local: Indicaciones/INFORME_CAPTURA_ESPOL_CODEX.md.

## Prueba real de captura académica
OpenAI Codex Desktop · Corregidas variantes del comando de captura ESPOL y añadido el enlace al chat confirmado. El conector guarda PNG temporal sin exponer imágenes en sus respuestas. La prueba real desde Viernes en texto confirmó el turno y dos imágenes en el paquete tras abrir la actividad por el conector. Pendiente adjuntar automáticamente pestañas manuales que el conector no expone. Informe local: Indicaciones/INFORME_CORRECCION_CAPTURA_ESPOL.md.

## Captura de pestaña visible
OpenAI Codex Desktop · Captura ESPOL verifica la URL en Brave al frente mediante accesibilidad de Windows y conserva el PNG de la vista original. Playwright recopila la misma actividad aunque vea otra pestaña. La prueba real en texto guardó la captura y reutilizó el chat existente sin duplicarlo. 73 pruebas automáticas. Falta prueba de micrófono y confirmar el cambio visual al chat. Informe local: Indicaciones/INFORME_PESTANA_VISIBLE_ESPOL.md.

## Captura desde consola
OpenAI Codex Desktop · Captura de ESPOL desde consola recupera la ventana de Brave con una actividad seleccionada y admite encargo por título desde la agenda local. Ambas rutas verificadas en Viernes en texto con la misma actividad y sin chat duplicado. Pasaron 74 pruebas. Informe: Indicaciones/INFORME_CAPTURA_DESDE_CONSOLA.md.

## Captura web para Codex
OpenAI Codex Desktop · Captura general de páginas web de Brave, con recopilación específica para ESPOL. Codex Desktop se localiza mediante AppX si falta en PATH y se verifica la existencia del chat antes de reutilizarlo. Confirmados chat eliminado y captura pública real; 83 pruebas automáticas. Pendiente enviar página general y verificar voz. Informe: Indicaciones/INFORME_CAPTURA_WEB_CODEX.md.

## Apertura del chat original
OpenAI Codex Desktop · Viernes abre el chat de captura después de cerrar el cliente del encargo. Reconoce las órdenes de reapertura y recupera la referencia al reiniciar. Pasaron 83 pruebas y la reapertura se verificó en Codex Desktop. Informe: Indicaciones/INFORME_APERTURA_CHAT_CODEX.md.
