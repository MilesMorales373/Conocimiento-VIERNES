# Estado al 2026-11-08
Agente: OpenAI Codex Desktop. Tarea actual: piloto Apple Music Web CDP autenticado en segundo plano.

## Apple Music Web CDP
El perfil aislado llegó a Apple Music y encontró el resultado exacto Ghost Town (feat. PARTYNEXTDOOR) de Kanye West. La corrección anterior permitió enviar el clic DOM con focus=false y visibility=visible, pero la reproducción no avanzó durante 42 s (currentTime=0, playbackState=none). Se modificó el piloto para pasar el puntero por el arte y enviar un clic de ratón CDP al centro del botón Play observado. Se añadió telemetría segura para estado de carga y error del elemento multimedia, sin imprimir URLs firmadas. node --check pasó. El nuevo gesto no tiene aún validación física. Informe y prueba: Indicaciones/PRUEBA_APPLE_WEB_CDP.md; flujo: Indicaciones/FLUJO_APPLE_WEB_CDP.md.

## Trabajo previo
El coordinador académico conserva un paquete con hashes y bloquea reenvíos inciertos. Se documentaron 44 pruebas y una simulación adicional, sin validar una tarea real completa. El piloto Apple Music confirmó Ghost Town en primer plano; fondo sigue en evaluación. Cider y MusicKit son pilotos separados.

Siguiente paso: ejecutar una sola prueba autenticada del nuevo clic CDP. Se espera focus=false, título correcto, currentTime creciente hasta superar 30 s y sin que Brave recupere el foco. Si no inicia, distinguirlo con paused, readyState, networkState, srcHost y error de la salida. No integrar a Viernes hasta confirmar.
