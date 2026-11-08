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
