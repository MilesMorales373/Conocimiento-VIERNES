# Estado al 2026-11-15

## 2026-11-24 · Preguntas sin número y captura sin panel
OpenAI Codex Desktop admitió diapositivas sin número en la lectura visual y excluyó temporalmente el panel propio de la captura. Gemma respondió la captura de prueba, el panel real desapareció solo durante la captura y pasaron 35 regresiones. Pendiente repetir por voz. Informe: Indicaciones/INFORME_PREGUNTAS_VISUALES_SIN_NUMERO.md.

## 2026-11-24 · Pantallas y código rojo
OpenAI Codex Desktop agregó selección de monitor por menú y voz para la isla y el panel. También agregó «código rojo» para cerrar Viernes y los procesos de ChatGPT, Codex y Ollama de la cuenta. La prueba detectó dos monitores, verificó la geometría en el segundo, cerró el panel y ocho procesos de prueba y preservó un proceso ajeno. Pendientes cierre de instancias personales y prueba oral. Informe local: Indicaciones/INFORME_PANTALLAS_Y_CODIGO_ROJO.md.

## 2026-11-22 · Cierre del cuestionario visual
OpenAI Codex Desktop agregó «terminamos el cuestionario» como cierre explícito del seguimiento visual. Borra el punto guardado para empezar de nuevo desde lo visible sin capturar la pantalla. Se conserva el alias anterior. Informe local: Indicaciones/INFORME_CIERRE_CUESTIONARIO_VISUAL.md.

## 2026-11-22 · Continuidad visual de cuestionarios
OpenAI Codex Desktop añadió continuidad visual numerada a la lectura de cuestionarios. Las órdenes de continuación solicitan una captura nueva del mismo monitor y exigen el próximo número, sin avanzar si falta. Gemma leyó la captura de la pregunta 12 y la secuencia 9–12 pasó con capturas simuladas. Pasaron 35 pruebas dirigidas. Pendiente desplazamiento y voz en la sesión habitual. Informe: Indicaciones/INFORME_CONTINUIDAD_CUESTIONARIO_VISUAL.md.

## 2026-11-22 · Lectura de preguntas sin grupo visible
OpenAI Codex Desktop amplió la lectura directa de cuestionarios en Brave a grupos accesibles sin nombre, encabezados y enunciados interrogativos próximos a opciones. En Brave real aislado se verificaron 3 selecciones en el mismo documento con respuestas de referencia. Falta inspeccionar el cuestionario específico. Informe local: Indicaciones/INFORME_LECTURA_CUESTIONARIOS_BRAVE.md.

## 2026-11-22 · Cuestionario directo sin extensión
OpenAI Codex Desktop corrigió resuelve/resuelva y sustituyó Playwright para este comando por accesibilidad de Windows en la pestaña activa de Brave. En Brave real de práctica se verificaron 3/3 selecciones con respuestas de referencia y se conservó la identidad de la pestaña. Gemma no se cargó en esa sesión por RAM disponible insuficiente. Pasaron 57 pruebas. Pendiente confirmar el flujo completo con Gemma y la página habitual. Informe local: Indicaciones/INFORME_CUESTIONARIO_BRAVE_DIRECTO.md.

## 2026-11-22 · Cuestionario en Brave
OpenAI Codex Desktop implementó un modo de cuestionario para leer las preguntas detectadas en una pestaña de Brave y marcar radios y casillas con Gemma local. Verifica el documento antes de cada selección. En Brave real aislado, un cuestionario web servido localmente obtuvo 3/3 sin crear pestañas ni enviar el formulario. Un cambio de pregunta bloqueó la selección. Pasaron 54 regresiones. Pendiente repetir con el perfil habitual de Brave y por voz. Informe local: Indicaciones/INFORME_CUESTIONARIO_BRAVE.md.

## 2026-11-15 · Búsqueda documental recuperable
Se añadió búsqueda local por contenido y proyecto con índice incremental y respaldo E5 para coincidencias estimadas. Telegram consulta, cancela y retoma la búsqueda con estado persistente. Pasaron 86 pruebas Python y 12 del Worker; el codificador real acertó en un ensayo controlado. Pendientes cliente web, configuración de carpetas y ensayo real del bot. Informe: Indicaciones/INFORME_INDICE_DOCUMENTAL_MOVIL.md.

## 2026-11-15 · Primera etapa de Viernes móvil
OpenAI Codex Desktop conectó una búsqueda local por nombre en carpetas configuradas con selección y envío por Telegram al propietario vinculado. Se definió una ruta de web privada instalable en iPhone. Pasaron 31 pruebas Python y 12 del Worker en local. El próximo bloque es la búsqueda por contenido y proyecto. Queda pendiente verificar Telegram desde un iPhone con el receptor real y aplicar el cambio del Worker donde esté desplegado. Informe local: Indicaciones/INFORME_MEJORA_MOVIL_ARCHIVOS.md.

## 2026-11-15 · Búsqueda HTTP y variantes de lyrics
OpenAI Codex Desktop añadió variantes de lyrics al MiniPlayer y priorizó consultas HTTP de Yahoo, luego DuckDuckGo y Mojeek, con Brave sin ventana como último respaldo. Consultas de clasificación y de concierto recuperaron fuentes sin iniciar Brave. Se comprobó también la respuesta completa de clasificación con el modelo rápido y pasaron 117 pruebas seleccionadas. Pendiente comprobación de pronunciaciones al micrófono. Informe local: Indicaciones/INFORME_BUSQUEDA_EN_SEGUNDO_PLANO_Y_LYRICS.md.

## 2026-11-15 · Minirreproductor, cierre y redacción
OpenAI Codex Desktop actualizó la orden de letras para abrir el MiniPlayer de Cider, preservó primer plano y aplicaciones protegidas en el cierre masivo, y añadió estilo académico con seguimiento de revisiones y comprobación de extensión en foros. Se probaron la apertura real del minirreproductor y la repetición de la orden desde Viernes, dos respuestas de foro con el modelo rápido y 111 pruebas seleccionadas. El cierre se verificó con ventanas simuladas; los iconos sin ventana identificable quedan fuera. Pendiente prueba por micrófono y otras escalas. Informe local: Indicaciones/INFORME_MINIPLAYER_CIERRE_Y_REDACCION.md.

## 2026-11-15 · Continuidad de voz
OpenAI Codex Desktop añadió una conversación de voz opcional con «Viernes, conversemos», ventana de seguimiento de 15 s y pausa de 1,35 s por frase en esa modalidad. La escucha y el contexto reutilizan los motores actuales. Durante la voz sintetizada o con audio de fondo se conserva la activación habitual. Pasaron 115 pruebas seleccionadas, 10 nuevas, con transcripción y respuesta simuladas en el bucle. Pendiente comprobar habla real y comparar detectores locales de final de turno. Informe local: Indicaciones/INFORME_CONTINUIDAD_DE_VOZ.md.

## 2026-11-15 · Limpieza de almacenamiento
OpenAI Codex Desktop retiró respaldos antiguos, los pilotos exclusivos de Apple Music y MusicKit, el entorno de Browser Use y archivos descartados de evaluación NPU. Se eliminaron duplicados del modelo semántico por SHA-256 y cachés regenerables. Tamaño lógico retirado: aproximadamente 2,14 GB. Pasaron 132 pruebas antes y después. Se verificaron la inferencia semántica CPU, Chromium local y la disponibilidad de Cider y Whisper Turbo. Informe local: Indicaciones/INFORME_LIMPIEZA_ALMACENAMIENTO.md.

## 2026-11-15 · Captura de PowerPoint y recuperación de la extensión
OpenAI Codex Desktop implementó lectura de PPTX y un reintento acotado de captura tras recuperar la extensión de Playwright. Se verificaron texto, imágenes y SHA-256 en un adjunto real previamente descargado. El perfil oculto necesita renovar su sesión. Falta comprobar el interruptor en Brave y el envío completo a Codex. Informe local: Indicaciones/INFORME_PPTX_Y_RECUPERACION_PLAYWRIGHT.md.

El piloto Apple Music Web CDP se retiró de la instalación. A continuación se conserva únicamente la historia de sus pruebas.

## Apple Music Web CDP
El perfil aislado llegó a Apple Music y encontró el resultado exacto Ghost Town (feat. PARTYNEXTDOOR) de Kanye West. La corrección anterior permitió enviar el clic DOM con focus=false y visibility=visible, pero la reproducción no avanzó durante 42 s (currentTime=0, playbackState=none). Se modificó el piloto para pasar el puntero por el arte y enviar un clic de ratón CDP al centro del botón Play observado. Se añadió telemetría segura para estado de carga y error del elemento multimedia, sin imprimir URLs firmadas. node --check pasó. El nuevo gesto no tiene aún validación física. Los archivos locales de este piloto se retiraron en la limpieza del 15 de noviembre.

## Trabajo previo
El coordinador académico conserva un paquete con hashes y bloquea reenvíos inciertos. Se documentaron 44 pruebas y una simulación adicional, sin validar una tarea real completa. El piloto Apple Music confirmó Ghost Town en primer plano; fondo sigue en evaluación. Cider y MusicKit son pilotos separados.

Paso que quedó pendiente antes de retirar el piloto: probar un clic CDP autenticado. Se espera focus=false, título correcto, currentTime creciente hasta superar 30 s y sin que Brave recupere el foco. Si no inicia, distinguirlo con paused, readyState, networkState, srcHost y error de la salida. No integrar a Viernes hasta confirmar.

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

## Panel Umbral
OpenAI Codex Desktop · Panel Umbral local con isla, conversación compartida por voz y texto, cámara, Gaming, control de plano e inicio con Windows opcional. Se verificaron dimensiones, repliegue y controles Enviar y Corregir con el motor real. Pasaron 132 pruebas automáticas. Pendiente comprobar micrófono, arranque y cámara con dos pestañas. Informe: Indicaciones/INFORME_PANEL_UMBRAL.md.

## Umbral como aplicación · 2026-11-09
Umbral incorpora un lanzador Windows gráfico sin consola, isla compacta animada y panel expandido con conversación, compositor fijo y tarjeta de Codex al completar el encargo. Pasaron 132 regresiones y pruebas gráficas en Windows con datos de ejemplo y arranque real del ejecutable en modo texto. Falta verificar voz natural y un envío real desde la cámara. Informe local en Indicaciones/INFORME_UMBRAL_APP.md.

## Ajuste visual de Umbral · 2026-11-09
Umbral se compactó a 356 × 274 y la isla a 172 × 31. Se alineó la composición con las referencias y se suavizó la onda con interpolación temporal y un intervalo de 16 ms. Prueba gráfica con eventos de ejemplo y 132 regresiones satisfactorias. Informe local: Indicaciones/INFORME_UMBRAL_COMPACTO.md.

## Umbral y opciones musicales · 2026-11-09
Umbral amplió legibilidad, edición y copia, añadió bandeja musical por lista vigente y fijado por voz. La captura de voz separa paradas y elecciones fusionadas. Pasaron 73 pruebas y verificaciones gráficas con datos de ejemplo. Quedan pruebas de voz natural y reproducción real. Informe: Indicaciones/INFORME_UMBRAL_OPCIONES.md.

## Legibilidad y copia de Umbral · 2026-11-09
Umbral calcula el ancho de la isla según su contenido, adopta la tipografía de Windows, incorpora iconos suavizados y menú oscuro, y permite copiar texto o enlaces mediante el portapapeles Unicode. Pasaron 145 pruebas y una verificación gráfica en Windows con datos de ejemplo. Informe: Indicaciones/INFORME_UMBRAL_COPIA.md.

## Tarjetas laterales y consulta del Barcelona · 2026-11-09
Umbral muestra las opciones musicales a la derecha y reduce los iconos de cámara y envío. La consulta simple del próximo partido del FC Barcelona usa el calendario oficial y convierte a la zona local. Ante 403/429, el respaldo general usa otros motores. Se verificaron la consulta real, la geometría con datos de ejemplo y 52 regresiones. Informe: Indicaciones/INFORME_UMBRAL_LATERAL.md.

## Diseño Pulso · 2026-11-09
Pulso se aplicó a Umbral en Windows con paleta carbón y coral, onda centrada y tarjetas laterales con título y artista separados. Se verificaron la ventana real con datos de ejemplo y 75 pruebas. Informe: Indicaciones/INFORME_UMBRAL_PULSO.md.

## Refinamiento de Pulso · 2026-11-09
Pulso refina la cabecera en una sola fila, integra Escuchando al final del chat y separa la rueda del chat y las tarjetas. Se oscureció el borde y se solicitó redondeo nativo para el panel. Pasaron 75 pruebas y una verificación gráfica. Informe: Indicaciones/INFORME_PULSO_REFINADO.md.

## Teams y carga de aplicaciones · 2026-11-12
OpenAI Codex Desktop incorporó espera por ventana y controles, expansión y desplazamiento de canales, verificación de fecha y señal de clase activa y comprobación del micrófono y la cámara antes de Join now. La espera común se conectó también a los puntos de arranque de Zoom, Cider y Apple Music descritos en Indicaciones/INFORME_TEAMS_Y_CARGA_DE_APPS.md. Pasaron 92 pruebas. Se verificó OCR sobre capturas. Siguiente paso: validar el recorrido desde Teams cerrado y la unión en una clase real activa.

## Mejoras integrales · 2026-11-13
OpenAI Codex Desktop · Cancelación de entrega, continuidad de agenda, espera de ventana, gestión de recuerdos, búsqueda textual y encargo por actividad. Tarea diaria de Windows verificada a las 20:00. Pasaron 94 pruebas dirigidas. La batería completa sigue con fallos preexistentes. Pendientes: voz física, clase en vivo, encargo hasta Telegram, índice personal de PDF/DOCX y ampliación de conversación y herramientas. Informe: Indicaciones/INFORME_MEJORAS_INTEGRALES.md.

## Continuidad · 2026-11-13
OpenAI Codex Desktop incorporó contexto extractivo desde el historial persistente, caché local de PDF/DOCX, selección acotada de consultas y entrega opcional con /resolver N por Telegram. Pasaron 78 pruebas dirigidas. Pendientes: validación física y con cuentas reales, OCR documental y ampliación del selector. Informe: Indicaciones/INFORME_CONTINUIDAD_VIERNES.md.

## Integración de escritorio
OpenAI Codex Desktop · Entrega desde escritorio a Telegram con recuperación del chat y registro por archivo, reconexión acotada de Brave, contexto de acuerdos explícitos, OCR local y estados de ejecución. Pasaron 82 pruebas dirigidas y OCR real sintético. La batería repitió 26 fallos y 26 errores previos. Pruebas físicas y con cuentas reales pendientes. Guía: Indicaciones/GUIA_PRUEBAS_INTEGRACION_VIERNES.md.

## Reparación de voz y Cider
OpenAI Codex Desktop corrigió «Cambie canción», añadió respaldo multimedia de Windows y recuperación de escucha y conectó el cierre normal de ventanas. Micrófono capturó señal real. Cider agotó el plazo HTTP y no confirmó cambio con el respaldo, incluso tras reapertura normal. Pasaron 68 pruebas dirigidas. La batería general mantuvo los fallos anteriores. Informe: Indicaciones/INFORME_REPARACION_VOZ_CIDER_CIERRE.md.

## Pausa de Cider y corrección de órdenes · 2026-11-14
OpenAI Codex Desktop añadió pausa temporal de Cider durante la interacción de voz, reanudación condicionada a la misma pista y posición de cola, y prioridad para órdenes explícitas de transporte. Integró variantes de repetición, Outlook, Calculadora, Settings y Gaming. Cider real confirmó pausa, reanudación y repetición. Windows confirmó la minimización de Calculadora y la apertura y el cierre de Outlook. Pasaron 75 pruebas dirigidas. Queda validar el recorrido con voz humana y música de fondo. Informe: Indicaciones/INFORME_PAUSA_CIDER_Y_ORDENES.md.

## Transporte y aplicaciones generales · 2026-11-14
OpenAI Codex Desktop · Viernes 0.16.2 distingue la atenuación preliminar de la pausa confirmada, conserva respaldo por sesión y comprueba el avance de Cider también por posición de cola. La resolución de ventanas usa el catálogo y los identificadores de Windows para aplicaciones registradas. Prueba real de pausa, reanudación, salto y ciclo abrir/minimizar/mostrar/cerrar Paint. Pasaron 79 pruebas dirigidas. Pendiente: recorrido completo con voz humana y altavoces. Informe: Indicaciones/INFORME_TRANSPORTE_Y_APPS_GENERALES.md.

## Prioridad de voz sobre Cider · 2026-11-14
OpenAI Codex Desktop · Viernes 0.16.3 atenúa sesiones en las salidas activas de Windows, conserva la atenuación al solicitar pausa en Cider y comprueba la protección antes de iniciar Kokoro. Medición real de Cider al 4 % de su nivel anterior y restauración. El flujo real de voz confirmó pausa antes de Kokoro, 6,51 s escritos en los altavoces y reanudación de la misma pista. Pasaron 64 pruebas dirigidas. La activación hablada por una persona queda pendiente de comprobación. Informe: Indicaciones/INFORME_PRIORIDAD_VOZ_CIDER.md.

## Actualización · 2026-11-14
OpenAI Codex Desktop · 0.16.4 · La captura conserva la referencia del intento actual y confirma la recepción antes de vincular el chat. Las preguntas sociales llegan al modelo sin una consulta web. Apertura local de carpetas por nombre o ruta. 60 pruebas seleccionadas satisfactorias. Pendiente confirmar el flujo real desde Brave y voz. Informe local: Indicaciones/INFORME_CAPTURA_Y_CONVERSACION.md.

## Atajos para Codex
OpenAI Codex Desktop · Atajos para enviar la página visible a Codex. «Pasa esta página a Codex» y «pásale esta página a Codex» usan la ruta de captura existente. Clasificación local comprobada; pendiente el envío real. Informe: Indicaciones/INFORME_CAPTURA_Y_CONVERSACION.md.

## Captura y agenda en segundo plano
OpenAI Codex Desktop · Captura y agenda de ESPOL usan un perfil de Brave sin ventana. La captura fija la URL y el chat queda disponible bajo petición. 57 pruebas dirigidas satisfactorias y foco de Windows conservado en una captura real con página de ejemplo. Pendiente autenticar el perfil de trabajo y validar ESPOL. Informe: Indicaciones/INFORME_BRAVE_SEGUNDO_PLANO.md.

## Pausa al llamar a Viernes
OpenAI Codex Desktop · Cider recibe la orden de pausa al detectar el nombre de activación. 61 pruebas dirigidas satisfactorias. RealtimeSTT abrió la entrada Bluetooth predeterminada; reconocimiento físico pendiente. Informe: Indicaciones/INFORME_PAUSA_AL_LLAMAR_Y_AIRPODS.md.

## Captura de ESPOL y parada
OpenAI Codex Desktop · Corregidas las variantes de envío a Codex, la espera de la entrada autenticada de ESPOL y la descarga de adjuntos en segundo plano. El respaldo solo lee una pestaña existente de URL coincidente. El trabajador real confirmó tablero, consigna y materiales con foco conservado, sin enviar a Codex. «Para» y «cancele» interrumpieron TTS con voz sintética; pendiente voz natural. Informe: Indicaciones/INFORME_CAPTURA_ESPOL_Y_PARADA.md.


## 2026-11-16 · Recuperación web y revisión de parada
OpenAI Codex Desktop corrigió la reserva de contexto para fuentes e incorporó Bing RSS y la API pública de Wikipedia, además de los respaldos previos. Filtra resultados irrelevantes y adapta la extensión de la respuesta a la petición. Gemma respondió consultas reales de Semana Santa, fotosíntesis y PWM; energía solar recuperó evidencia. Pasaron 114 pruebas. Para y cancela interrumpieron síntesis con STT/TTS reales y audio sintético (sin hardware). Próximo paso: voz del usuario con música/ruido y reproducción separada de la cancelación al entrar en clase. Informe: Indicaciones/INFORME_CORRECCION_WEB_Y_PARADA_20261116.md.

## 2026-11-20 · Tarjeta de batería

El panel expandido incluye una tarjeta opcional en el menú, con lectura bajo demanda en segundo plano. La apertura, actualización y cierre pasaron en Tk con datos de ejemplo y la aplicación se reinició. Se verificó la detección de un ratón por USB; falta validar su porcentaje y probar auriculares físicamente. Informe local: Indicaciones/INFORME_TARJETA_BATERIA.md.

### Ajuste del porcentaje de batería

Se habilitó la lectura directa USB HID. En hardware se recibió una trama de batería del receptor y se confirmó que el valor se conserva como última lectura al conectar el cable. Falta verificar actualizaciones desde el cable. Los detalles locales están en Indicaciones/INFORME_TARJETA_BATERIA.md.

## 2026-11-20 · Objetivos de escritorio

OpenAI Codex Desktop integró encargos locales reanudables, tarjetas de selección, acciones de accesibilidad en la pestaña activa, ajustes de continuidad de voz, recuperación de Codex por comprobante y preferencias versionadas por proyecto. La búsqueda añadió descubrimiento temporal, fuentes institucionales y síntesis de respaldo. Se corrigió la cesión de Cider y el salto por índice verificado. Pendientes: voz física y recuperación autenticada de extremo a extremo. Alcance y pruebas: Indicaciones/INFORME_OBJETIVOS_ESCRITORIO_20261120.md.

## 2026-11-20 · Destinos y entrada de audio

Se rutearon encargos locales a chats fijos por materia y subcarpeta. Tres chats admitieron reanudación y un cuarto mantuvo el bloqueo normal de escritura. Se corrigió la selección de micrófono según roles de Windows, la búsqueda por pistas locales y el desplazamiento de la interfaz. Pendiente la prueba física con el auricular disponible. Informe: Indicaciones/INFORME_MATERIAS_MICROFONO_BUSQUEDA_20261120.md.

## 2026-11-20 - Reconocimiento de voz en auriculares Bluetooth

OpenAI Codex Desktop ajustó la captura cuando entrada y salida se emparejan en los AirPods y recuperó el nombre omitido solo con confirmación acústica de la misma toma. La cancelación de eco continúa durante la voz de Viernes. Pasaron 91 pruebas automáticas y la prueba sintética aceptó llamadas completas y rechazó la frase sin nombre. La parada breve se vuelve a comprobar en español si la detección de idioma falla; la prueba sintética detuvo ambas respuestas de Gaming. Se verificaron micrófono activo y reinicio del ejecutable. Pendiente reconocimiento con la voz del usuario. Informe local: Indicaciones/INFORME_RECONOCIMIENTO_AIRPODS_20261120.md.

### Segunda comprobación de la entrada Bluetooth

OpenAI Codex Desktop recibió confirmación de que la prueba con los auriculares Bluetooth no produjo respuesta en el chat. El diagnóstico en la app encontró actividad de entrada y ninguna activación confirmada, incluso al pausar el reproductor. La comparación de interfaces locales no confirmó una alternativa. Se restauró el ejecutable habitual, sin modificar código ni configuración. Pendiente comprobar que la misma voz llegue inteligible a otra aplicación con ese micrófono. Actualizado el informe local INFORME_RECONOCIMIENTO_AIRPODS_20261120.md.

## 2026-11-21 · Perfil de audio Bluetooth

OpenAI Codex Desktop corrigió la prioridad automática de captura: Viernes sigue la entrada multimedia principal de Windows, con el rol de comunicaciones solo si falta la principal. La selección por índice se conserva. Se confirmó que antes abría el micrófono Bluetooth aunque Windows seleccionaba el interno. Tras reiniciar, Viernes capturó por el micrófono integrado, Windows mantuvo los auriculares de salida y el micrófono Bluetooth quedó libre y disponible para elegirlo. Pasaron 92 pruebas dirigidas. La calidad audible y el reconocimiento por el micrófono de los auriculares requieren prueba física. Informe: Indicaciones/INFORME_PERFIL_BLUETOOTH_20261121.md.

### 2026-11-21 · Recuperación de captura

OpenAI Codex Desktop añadió comprobación de señal al abrir la entrada, descartando ceros y bloques repetidos al elegir una interfaz del mismo micrófono. Pasaron 93 pruebas y se verificó el arranque con captura integrada tras reiniciar el servicio de audio. El usuario indicó que el reconocimiento seguía fallando. La prueba directa no confirmó la orden; falta verificar voz inteligible con la Grabadora de Windows. Informe: Indicaciones/INFORME_RECUPERACION_CAPTURA_20261121.md.

### 2026-11-21 · Procesamiento y activación de voz

OpenAI Codex Desktop desactivó las mejoras de procesamiento del micrófono integrado para comprobar la captura. La señal se volvió continua durante la medición y se reconoció la pregunta de prueba sin el nombre. Se extendió la recuperación de «Viernes» por confirmación acústica de la misma toma a la entrada integrada. Pasaron 93 pruebas. Se reinició el ejecutable. Pendiente confirmar la respuesta a una orden completa con voz real. Informe: Indicaciones/INFORME_RECUPERACION_CAPTURA_20261121.md.

### 2026-11-21 · Reversión de captura y confirmación real

OpenAI Codex Desktop revirtió las modificaciones recientes de voz y restauró la apertura de micrófono anterior mediante RealtimeSTT. Se comprobó la configuración original de procesamiento del micrófono, la sesión de captura integrada y la transcripción después de reiniciar. Pasaron 90 pruebas. El usuario confirmó que Viernes volvió a responder a su llamada. Informe: Indicaciones/INFORME_RECUPERACION_CAPTURA_20261121.md.

### Adelantos y recomendaciones de Cider

OpenAI Codex Desktop implementó una sugerencia proactiva de agenda que requiere confirmación explícita para preparar un borrador en el chat académico asignado. Añadió elección de una pista vía Cider según biblioteca, género, contexto y preferencias locales. La reproducción directa requiere delegación o una orden de poner música. Pasaron 151 pruebas y la integración de solo lectura con Cider y una copia de la agenda. Pendientes el borrador con una actividad real aceptada y la aceptación por voz. Informe: Indicaciones/INFORME_ADELANTOS_Y_RECOMENDACIONES.md.
