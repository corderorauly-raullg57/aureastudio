# AUREA Studio — Tutorial completo

**AUREA Studio** convierte una idea o tus fotos en un video para redes sociales: con guion, imágenes, animación, voz en off, música y subtítulos animados. Todo funciona desde un solo archivo HTML en tu navegador.

---

## Índice

1. [Qué necesitas](#1-qué-necesitas)
2. [Primer arranque](#2-primer-arranque)
3. [Crear un proyecto](#3-crear-un-proyecto)
4. [Elegir el nivel de IA](#4-elegir-el-nivel-de-ia)
5. [Paso 1 · Idea y guion](#5-paso-1--idea-y-guion)
6. [Paso 2 · Reparto](#6-paso-2--reparto)
7. [Paso 3 · Escenas](#7-paso-3--escenas)
8. [Paso 4 · Formato y animación](#8-paso-4--formato-y-animación)
9. [Paso 5 · Audio y narración](#9-paso-5--audio-y-narración)
10. [Paso 6 · Subtítulos](#10-paso-6--subtítulos)
11. [Paso 7 · Marca y cierre](#11-paso-7--marca-y-cierre)
12. [Paso 8 · Generar video y exportar paquete](#12-paso-8--generar-video-y-exportar-paquete)
13. [Dónde quedan tus archivos](#13-dónde-quedan-tus-archivos)
14. [Recetas rápidas](#14-recetas-rápidas)
15. [Consejos si tienes poca electricidad o poca conexión](#15-consejos-si-tienes-poca-electricidad-o-poca-conexión)
16. [Solución de problemas](#16-solución-de-problemas)
17. [Preguntas frecuentes](#17-preguntas-frecuentes)

---

## 1. Qué necesitas

| Requisito | Detalle |
|---|---|
| Computadora | PC o laptop con Windows, Linux o Mac. |
| Navegador | **Google Chrome** o **Microsoft Edge** actualizados. Son los únicos que guardan en carpetas y exportan MP4 directamente. |
| Internet | Para las funciones de IA (guion, imágenes, voz, video IA). La Foto viva, la música incluida, los subtítulos y la grabación funcionan sin Internet. |
| Espacio | Unos 100 MB libres por proyecto (imágenes, clips y video final). |

> En celular la app se abre, pero no guarda en carpetas y la exportación es más lenta. Úsala en una PC.

---

## 2. Primer arranque

1. Crea una carpeta, por ejemplo `AUREA Studio`, y pon dentro el archivo `AUREA_Studio_Pro.html`.
2. Haz doble clic en el archivo. Si se abre con otro navegador, haz clic derecho → **Abrir con** → Chrome o Edge.
3. Verás tres zonas:
   - **Arriba:** el proyecto actual, los botones **＋ Crear proyecto**, **📂 Abrir** y **⚙ Configuración**, y la barra **Motor de IA**, que te dice qué servicios estás usando.
   - **Izquierda:** los 7 pasos para armar el video.
   - **Derecha:** el **visor**, donde ves el lienzo, la vista previa y el video final.

---

## 3. Crear un proyecto

Trabaja siempre dentro de un proyecto: así nada se pierde si se va la corriente.

1. Pulsa **＋ Crear proyecto**.
2. Escribe un nombre, por ejemplo `Cafetería Doña Ana - domingo`. La app no deja crear un proyecto sin nombre.
3. **La primera vez** te pedirá elegir una carpeta: elige la carpeta donde está `AUREA_Studio_Pro.html` y acepta el permiso. Allí se crea la carpeta `salida`.
4. El proyecto se guarda solo cada vez que cambias algo. El indicador de arriba muestra **Guardado hh:mm** en verde.

> Al crear un proyecto nuevo, la pantalla queda limpia para empezar de cero. Los proyectos anteriores siguen guardados en `salida` y los abres con **📂 Abrir**.

Si ya existe un proyecto con el mismo nombre, la app te pregunta antes de reemplazarlo.

---

## 4. Elegir el nivel de IA

Pulsa **⚙ Configuración**. Los niveles van de gratis a premium:

| Nivel | Qué hace | Costo | Claves que necesitas |
|---|---|---|---|
| **1 · Gratis** (predeterminado) | Foto viva en tu PC (agua, cielo, fuego y vehículos en movimiento, profundidad 3D). **Voz local** generada en tu PC. Guion e imágenes con Pollinations sin cuenta (lento: 1 respuesta cada 30 s). | $0 | Ninguna |
| **2 · Gratis con cuentas** | Además: **video IA real** (Wan 2.2, unas 4 a 8 escenas por día), sin esperas, y un director que **ve** tus fotos y las capturas de webs. | $0 | Hugging Face + Pollinations (gratis) |
| **3 · Créditos diarios** | Guion y voz más naturales con Google Gemini, más el video IA de Hugging Face. | $0 dentro de la cuota | Gemini + Hugging Face (gratis) |
| **4 · Pago económico** | Imágenes FLUX rápidas y nítidas en fal.ai. | Centavos por video | fal.ai + Gemini |
| **5 · Pago calidad** | Imágenes, guion y voz de OpenAI. | Centavos por imagen | OpenAI |
| **6 · Video IA de pago** | Clips Kling 2.5 Turbo, sin límite diario. | ≈ $0.35 por escena | fal.ai + Gemini |
| **7 · Premium** | Kling 3.0 Pro + OpenAI, la máxima calidad. | ≈ $0.56 por escena + imágenes | OpenAI + fal.ai |

**Recomendación para empezar:** el nivel **2**, que es gratis y ya da video IA real.

> **Por qué conviene la clave gratuita de Pollinations:** sin clave, Pollinations solo responde 1 vez cada 30 segundos, no tiene voz y su IA no puede ver imágenes. Con la clave gratuita (botón **Obtener clave** junto a Pollinations) desaparecen las tres limitaciones.

### Cómo sacar la clave gratis de Hugging Face

1. En ⚙ Configuración, junto a **Hugging Face**, pulsa **Obtener clave**.
2. Crea una cuenta gratis (correo y contraseña) y confirma el correo.
3. Pulsa **Create new token**, elige el tipo **Read**, ponle un nombre (`aurea`) y créalo.
4. Copia el token (empieza por `hf_`) y pégalo en la casilla de Hugging Face.

### Cómo sacar la clave gratis de Google Gemini

1. Junto a **Google Gemini**, pulsa **Obtener clave**.
2. Entra con una cuenta de Google y pulsa **Create API key**.
3. Copia la clave y pégala en la casilla.

> 🔒 Las claves se guardan solo en tu navegador. No van dentro de los proyectos, así que puedes compartir una carpeta de proyecto sin riesgo.

### 🤖 Modo automático: el video nunca se detiene

Cada computadora (la tuya o la de un cliente) tiene servicios que funcionan y otros que no, según el país, la VPN o el saldo. El **modo automático** (activado de fábrica) se encarga solo:

1. **Comprueba los servicios** al abrir la app (cada 6 horas como máximo) y otra vez antes de cada video (si pasaron más de 20 minutos). En el progreso verás el paso **Comprobar servicios** con lo que se va a usar.
2. **Sigue el orden de prioridad** de cada paso (guion, imágenes, voz, video IA y transformar): empieza por el que elegiste y, si no está disponible, pasa al siguiente de la lista.
3. **Si uno falla durante el trabajo**, prueba el siguiente al instante, sin parar, y lo avisa con 🔁 en la barra **Motor de IA**.
4. **Recuerda lo que falló** en esa computadora: si un servicio está bloqueado para el país o la clave no vale, lo salta durante unas horas; si solo falló por saturación, lo vuelve a intentar a los 15 minutos.
5. **Si todo falla**, termina el video igual: guion de respaldo, fondo artístico en lugar de la imagen, voz local en tu PC y Foto viva en lugar del video IA.

Dónde se ajusta, en **⚙ Configuración › Respaldo automático y orden de prioridad**:
- **🤖 Modo automático (recomendado)**: déjalo activado.
- **Permitir que el respaldo pase a servicios de pago**: desactivado, el respaldo solo usa servicios gratis, así nunca se gasta dinero sin querer. El servicio de pago que tú elijas sí se usa.
- **El orden de cada paso**: toca un servicio y sube (↑). Al elegir un nivel, sus servicios pasan a ser los primeros de la lista.
- **Cómo se marca cada servicio**: ✓ funciona, ✕ falló (con el motivo), ○ sin clave y $ si es de pago. Arriba de cada lista se ve cuál se está usando ahora, y si tu elección no está disponible.
- **🔌 Probar conexiones** y **⚡ Usar el mejor disponible** siguen ahí por si quieres comprobarlo a mano.

> **Para vender la app:** cada cliente pone sus claves y el modo automático se adapta solo a su país y a su conexión, sin que tengas que configurarle nada.

**¿Y Google Flow?** Flow no tiene conexión para otras apps y bloquea Cuba aunque uses VPN. Pero su potencia viene de los modelos de video de Google, **Veo** y **Omni Flash**, y esos sí los puedes usar en AUREA a través de servicios que no son de Google:

| En AUREA | Modelo | Servicio | Costo aprox. |
|---|---|---|---|
| Google Veo 3.1 · fal.ai | Veo 3.1 (el de Flow) | fal.ai | ≈ $1,20 por escena |
| Google Omni Flash · fal.ai | Omni Flash (el que usa Camino Digital) | fal.ai | ≈ $0,60 por escena |
| Veo 3.1 Fast · Pollinations | Veo 3.1 Fast | Pollinations (pollen de pago) | según pollen |

Elígelos en **Ajuste fino › Animación de escenas**.

### Ajuste fino y modelos (avanzado)

- **Ajuste fino por servicio:** mezcla proveedores, por ejemplo la voz de ElevenLabs con imágenes gratis.
- **Modelos y espacios:** si un proveedor cambia el nombre de un modelo, o un espacio de Hugging Face deja de funcionar, escribe aquí el nombre nuevo. El botón **Restaurar modelos recomendados** vuelve a los valores de fábrica.

---

## 5. Paso 1 · Idea y guion

Elige cómo empezar.

### Opción A — Desde una idea

1. Pulsa **✨ Desde una idea** y elige cómo nace el guion:
   - **🤖 La IA escribe el guion**, o
   - **✍️ Pegar mi guion**: pega tu texto, una línea o párrafo por escena. La IA **no cambia tus frases**; solo prepara el reparto, las imágenes y la animación.
2. En **¿Qué quieres expresar?** escribe con detalles concretos: qué es, dónde, para quién, qué lo hace especial, precios, días.
   - ❌ Poco útil: `cafetería`
   - ✅ Útil: `Mi cafetería en Holguín abre los domingos con desayunos caseros, café cubano recién colado y precios para toda la familia.`
3. *(Opcional)* Pulsa **💡 Sugerir 5 enfoques**: la IA propone 5 maneras distintas de contarlo (oferta, humor, testimonio, historia emotiva, dato sorprendente…), cada una con su frase de gancho. Toca la que te guste.
4. Elige el **tono**, el **número de escenas** (3 a 8) y el **idioma** del video (español, inglés o portugués). El idioma se aplica al guion, la voz y los subtítulos.
5. Pulsa **✨ Escribir guion**. Aparece la **Versión A** con el guion completo y el reparto detectado.
6. ¿No te convence? Pulsa **↻ Otra versión** y verás la **Versión B al lado** para comparar. Toca **Elegir esta** en la que prefieras.
7. Pulsa **✓ Usar la elegida y crear escenas**: se crean el reparto y las imágenes de cada escena.

> También puedes saltar directo al paso 8: **🎬 Generar video** hace todo esto solo, con la primera versión.

El director creativo entiende si es un anuncio, una felicitación, una historia o un aviso, y escribe un guion con hilo de principio a fin. En los negocios, la última escena menciona tu marca y la llamada a la acción.

### Opción C — Desde una web (link)

Ideal para clientes que ya tienen web: la app la convierte en un **video explicativo**, al estilo de los resúmenes en video de NotebookLM.

1. Pulsa **🌐 Desde una web** y pega la dirección (por ejemplo `www.tucliente.com`).
2. Elige el **objetivo** (promocionar el negocio, explicar qué ofrece, guía paso a paso o resumen de un artículo) y **qué mostrar** (la web navegando más sus fotos, solo la web, o fotos y escenas IA).
3. Elige tono, idioma y número de escenas, y pulsa **🌐 Analizar la web y crear escenas** (o directamente 🎬 Generar video).

Qué hace la app:
- **Lee** todo el texto de la web y toma una **captura completa** de la página (versión móvil para videos verticales, de escritorio para horizontales).
- **Divide** la web en partes: presentación, servicios, precios, cómo funciona, contacto…
- En cada escena **muestra esa parte de la web dentro de un navegador** que se desplaza solo, **señala** lo importante (un precio, un botón) con un marco brillante y un cursor que hace clic, y pone **un título y hasta 3 puntos clave** en pantalla.
- Alterna con las **fotos de la propia web** (animadas con Foto viva) y con imágenes IA cuando falta algo.
- Narra con voz y subtítulos, como cualquier otro video.

> Para que la IA vea la captura y señale el sitio exacto hace falta la clave gratuita de Pollinations (o Gemini/OpenAI). Sin ella, divide la web solo por su texto y no señala zonas.
> En **⚙ Ficha** de cada escena puedes cambiar el **título en pantalla** y los **puntos clave**. En Subtítulos puedes ocultarlos.

### Opción B — Desde mis imágenes

1. Pulsa **🖼 Desde mis imágenes** y sube tus fotos (o arrástralas). Con **una sola foto** la app crea varias tomas distintas de ella.
2. En **¿Qué quieres expresar con ellas?** escribe el mensaje, por ejemplo `Pizzería familiar, oferta 2x1 el fin de semana`.
3. Deja vacía la caja de textos y pulsa **✨ Escribir guion con mis fotos**: la IA **mira cada foto** y escribe una frase que corresponde a lo que se ve.
4. Si prefieres tus propios textos, escribe una línea por escena.

---

## 6. Paso 2 · Reparto

El **reparto** son los personajes, lugares y productos que aparecen en el guion. Sirve para que **la misma persona y el mismo producto se vean iguales en todas las escenas**, que es lo que más se nota en un video profesional.

- Se llena solo al escribir el guion. Cada ficha tiene imagen, nombre, tipo (🧍 personaje, 🏠 lugar, 📦 producto, 🔹 objeto) y una descripción de cómo es.
- **Subir foto**: pon la **foto real** de tu producto, de tu local o de una persona. Es lo más recomendado para negocios: el video mostrará lo verdadero, no algo inventado.
- **↻ Generar**: crea la imagen con IA a partir de la descripción (puedes escribirla en español).
- **🎨 Adaptar**: redibuja la foto en el estilo visual elegido (por ejemplo, tu foto en versión anime o acuarela), conservando los rasgos. **↺** vuelve a la original.
- **✨ Generar faltantes**: crea todas las imágenes que falten. **+ Añadir**: agrega a mano un personaje o producto.
- Deja marcado **Usar estas imágenes como referencia en cada escena**: cada escena se genera a partir de las fotos del reparto que tiene vinculadas.

> La referencia funciona mejor con los niveles de pago (Gemini u OpenAI aceptan varias fotos a la vez). En los niveles gratis se usa la transformación de Hugging Face; si falla, la escena se genera solo con la descripción y te lo indica.

## 7. Paso 3 · Escenas

Cada escena muestra su imagen, su texto y unos **chips** con lo que se va a animar:

| Chip | Qué hace en el video |
|---|---|
| 💧 agua | Ondas y brillos sobre el mar, el río o la piscina |
| ☁️ cielo | Las nubes avanzan despacio |
| 🔥 fuego | Las llamas tiemblan y brillan |
| ♨️ vapor | El vapor o el humo sube |
| 🍃 viento | Se mueven las hojas, el cabello o la ropa |
| 🧍 respiración | La persona respira suavemente |
| 💡 luces | Las luces y los letreros laten |
| 💨 velocidad | El fondo pasa rápido detrás del vehículo |
| ✨ ☀️ 🔆 🌧 ❄️ 🎇 🌅 🌫 | Partículas de ambiente: polvo de luz, rayos de sol, bokeh, lluvia, nieve, chispas, destellos y niebla |

**Toca un chip para quitarlo** si no te gusta ese efecto.

Botones de cada escena:

- **↻ IA** — genera otra imagen.
- **Cambiar imagen** — usa una foto tuya.
- **✨ Transformar** — cambia la imagen con tus palabras:
  - `completa el cuerpo entero de la persona` (marca **Ampliar el encuadre**)
  - `pon olas en el mar`
  - `cambia el fondo por una playa al atardecer`
  - Pulsa **✨ Aplicar**. Si no te gusta, **↺ Volver al original**.
- **🎬 Video IA** — convierte esa escena en un clip de video real (niveles 2 en adelante).
- **📥 Clip** — pon un clip de video **hecho en otra app** (por ejemplo, con los prompts del paquete en Meta Vibes). AUREA lo une con voz, música y subtítulos.
- **⚙ Ficha** — abre la ficha técnica de la escena:
  - **Plano**: general, medio, primer plano, detalle, cenital o contrapicado.
  - **Cámara**: acercar, alejar, paneo, subir u órbita.
  - **Luz**: natural, hora dorada, estudio, nocturna, dramática o neón.
  - **Prompt de imagen** y **prompt de animación**, editables: escribe exactamente qué debe moverse antes de mandarlo al video IA.
  - **Escena compleja**: márcala si tiene personas actuando o acción; esas son las que conviene animar con video IA.
- **🔗 Reparto vinculado** — los chips azules muestran quién aparece en la escena. Toca uno para quitarlo o usa **+ vincular** para añadir.
- El número de la escena lleva **⚡** cuando es compleja.
- **↑ ↓** — cambia el orden. **✕** — elimina la escena.

> 💡 Si ves el mensaje **"El director sugiere…"**, la IA detectó algo que mejorar, como una persona cortada. Pulsa **✨ Transformar** para aplicarlo.

---

## 8. Paso 4 · Formato y animación

**Formato:**

| Formato | Para |
|---|---|
| 9:16 Vertical | TikTok, Reels, Estados de WhatsApp, Shorts |
| 1:1 Cuadrado | Publicaciones del feed |
| 4:5 Retrato | Instagram |
| 16:9 Horizontal | YouTube, Facebook |

**Animación:**

- **Director IA** — analiza cada imagen y decide qué animar. Déjalo activado.
- **Foto viva** — anima agua, cielo, fuego, etc. en tu PC, gratis y sin límite.
- **Profundidad 3D** — lo cercano y lo lejano se mueven distinto, como una cámara real. La primera vez descarga 25 MB.
- **Partículas y luces** — ambiente según la escena.
- **Completar mis fotos con IA** — aplica sola las mejoras que sugiere el director.
- **Video IA** — **solo en escenas complejas** (recomendado: gasta la cuota donde más se nota y deja paisajes, productos y ambientes a la Foto viva), en todas, solo en la primera, o en ninguna.
- **Cámara** — suave, media o intensa.
- **Transición** — fundido, zoom, deslizar, destello o corte.

---

## 9. Paso 5 · Audio y narración

| Modo | Cómo funciona |
|---|---|
| **Sin voz** | Solo música y subtítulos. |
| **🎙 Grabar** | Lee el guion en pantalla (teleprompter) y graba con el micrófono. Los silencios del inicio y del final se recortan solos. |
| **📁 Archivo** | Sube una locución que ya tengas (MP3, WAV, M4A, OGG). |
| **🤖 Voz IA** | Elige una voz y pulsa **▶ Probar voz**. Cada escena se narra por separado, así la voz y los subtítulos quedan sincronizados. Con **Voz local Piper** la voz se genera en tu PC, gratis y sin límite: la primera vez descarga unos 60 MB por voz y luego funciona sin Internet. |

**Música:** tres músicas incluidas sin derechos de autor (cálida, energética, elegante) o la tuya. Usa solo música propia o libre de derechos para evitar bloqueos.

**Volúmenes:** con **Bajar la música cuando habla la voz** la música baja sola durante la narración.

> Con voz, la duración del video se ajusta sola a la narración.

---

## 10. Paso 6 · Subtítulos

| Estilo | Aspecto |
|---|---|
| Elegante | Texto limpio con una línea dorada |
| Karaoke | Cada palabra se ilumina al decirla |
| ¡IMPACTO! | Dos palabras grandes, estilo TikTok |
| En recuadro | Fondo oscuro, máxima legibilidad |
| Cinematográfico | Cursiva con franjas negras de cine |

Elige la posición (abajo, centro o arriba), el tamaño y si quieres todo en MAYÚSCULAS. **⬇ Descargar subtítulos .SRT** sirve para subirlos aparte a YouTube o Facebook.

---

## 11. Paso 7 · Marca y cierre

- **Marca** y **Llamada a la acción**, por ejemplo `Cafetería Doña Ana` y `Te esperamos el domingo`.
- **Contacto:** WhatsApp, dirección o web.
- **Logo** (PNG con fondo transparente es lo ideal) y **color de acento**, que se aplica a subtítulos y botones.
- **Marca en la esquina** durante todo el video.
- **Cierre final** animado de unos 3 segundos con marca, llamada a la acción y contacto.

---

## 12. Paso 8 · Generar video y exportar paquete

Pulsa **🎬 GENERAR VIDEO**. La app hace sola todo lo que falte y muestra el avance:

```
✓ Guion
✓ Reparto
✓ Imágenes de las escenas
✓ Director IA: qué animar
✓ Completar o mejorar fotos
✓ Video IA
✓ Foto viva en 3D
✓ Voz
✓ Grabar el video final
```

- El video se graba **en tiempo real**: uno de 20 segundos tarda unos 20 segundos en grabarse.
- **Deja la pestaña visible** mientras graba. Si la ocultas, el video puede salir con saltos.
- Si un servicio gratis falla o se agota la cuota, la app **sigue con la alternativa** (por ejemplo Foto viva en vez de video IA) y te lo indica con ✕ en la lista.
- Al terminar, el video se reproduce en el visor. Usa **⬇ Descargar video**, **⬇ Subtítulos .SRT** o **✎ Volver al lienzo** para seguir editando.

> **▶ Vista previa** reproduce el video sin grabarlo, útil para revisar antes. **■ Detener** cancela.

### 📦 Exportar paquete del proyecto

El botón **📦 Exportar paquete** (debajo de Generar video y en el visor) junta todo el proyecto:

| Archivo | Contenido |
|---|---|
| `guion.txt` | Los textos de cada escena |
| `prompts.txt` | Prompts de imagen y de animación de cada escena, y **prompts listos para otras IA de video gratis** (Meta Vibes, etc.) |
| `reparto/` | Imágenes y descripciones del reparto |
| `escenas/` | Imagen inicial de cada escena (`escena_01.jpg`…) |
| `clips/`, `voz/` | Clips de video y narraciones |
| `subtitulos.srt`, `video_final` | Subtítulos y el video terminado |

Se guarda en `salida/<proyecto>/paquete/` (funciona sin Internet) y, con conexión, también se descarga como **ZIP**.

**Para animar gratis en otra IA:** sube `escenas/escena_01.jpg` como imagen inicial en la otra herramienta, pega su prompt de `prompts.txt`, descarga el clip y, en AUREA, pulsa **📥 Clip** en esa escena. Luego **🎬 Generar video** une todo.

---

## 13. Dónde quedan tus archivos

```
AUREA Studio/
├── AUREA_Studio_Pro.html
└── salida/
    └── Cafetería Doña Ana - domingo/
        ├── proyecto.json                ← el proyecto (textos y ajustes)
        ├── imagenes/                     ← imágenes de cada escena
        ├── clips/                        ← clips de video IA
        ├── profundidad/                  ← mapas 3D ya calculados
        ├── voz/                          ← narraciones
        ├── reparto/                      ← personajes, lugares y productos
        ├── paquete/                      ← paquete exportado (guion, prompts…)
        ├── musica/                       ← tu música (si subiste una)
        ├── logo.png
        ├── Cafeteria_Dona_Ana_domingo_9x16_15s.mp4   ← VIDEO FINAL
        └── Cafeteria_Dona_Ana_domingo_subtitulos.srt
```

Para seguir otro día: **📂 Abrir** → elige el proyecto. Todo vuelve tal como estaba, incluidos los clips y las voces, sin gastar cuota de IA otra vez.

---

## 14. Recetas rápidas

**Anuncio de negocio en 2 minutos (gratis)**
1. Nivel 2. Crear proyecto.
2. Desde una idea → describe el negocio con detalles → tono *persuasivo* → 4 escenas.
3. Voz IA, música cálida, subtítulos Karaoke, 9:16.
4. Marca, llamada a la acción y WhatsApp.
5. 🎬 Generar video.

**Promoción con fotos de tus productos**
1. Desde mis imágenes → sube 3 a 5 fotos → escribe la oferta.
2. ✨ Escribir guion con mis fotos.
3. Tono *oferta urgente*, subtítulos ¡IMPACTO!, música energética.
4. 🎬 Generar video.

**Felicitación o mensaje emotivo**
1. Desde una idea: `Felicitar a mi madre por sus 70 años, recordando su vida en el campo y su cariño`.
2. Tono *emotivo*, subtítulos Cinematográfico, música elegante.
3. Desactiva **Cierre final** si no es un anuncio.

**Anuncio con tu producto real en todas las escenas**
1. Escribe la idea → ✨ Escribir guion → ✓ Usar la elegida.
2. En **Reparto**, en la ficha del producto, pulsa **Subir foto** y pon la foto real.
3. En cada escena donde no salga bien, pulsa **↻ IA**: ahora usa tu foto como referencia.
4. 🎬 Generar video.

**Video IA gratis e ilimitado con otra herramienta**
1. Prepara las escenas y pulsa **📦 Exportar paquete**.
2. En la otra IA de video, usa cada `escena_XX.jpg` con su prompt de `prompts.txt`.
3. Vuelve a AUREA y sube cada clip con **📥 Clip** → 🎬 Generar video.

**Retrato de persona cortado → cuerpo completo**
1. Sube la foto → en la escena pulsa **✨ Transformar**.
2. Escribe `completa el cuerpo entero` y marca **Ampliar el encuadre** → **✨ Aplicar**.

---

## 15. Consejos si tienes poca electricidad o poca conexión

- **Crea siempre un proyecto primero.** Se guarda solo; si se va la corriente, al volver lo abres con 📂 Abrir y sigues donde ibas.
- **Separa el trabajo en dos ratos:**
  - *Con conexión:* pulsa **✨ Crear guion e imágenes**, **Generar voces ahora** y convierte las escenas en video IA. Todo queda guardado en la carpeta del proyecto.
  - *Sin conexión:* ajusta subtítulos, música, marca y pulsa 🎬 Generar video. La grabación no necesita Internet si las voces e imágenes ya están hechas.
- **Descarga el modelo 3D una vez** con buena conexión (25 MB); después queda guardado en el navegador.
- **Ahorra cuota de video IA:** en el paso 3 elige *Video IA: solo la primera escena*. Las demás escenas usan Foto viva, que es ilimitada.
- **Con la laptop en batería**, cierra otras pestañas mientras grabas el video final.

---

## 16. Solución de problemas

| Problema | Solución |
|---|---|
| **"Imagen pendiente"** en una escena | El servicio de imágenes no respondió. Pulsa **↻ IA** para reintentar o **Cambiar imagen** para usar una foto tuya. |
| **"Se agotó la cuota gratis de GPU"** | Es el límite diario de Hugging Face. Se renueva a las 24 horas. Mientras, la app usa Foto viva. Con un token gratis tienes más minutos. |
| **"El espacio de Hugging Face no está disponible"** | El espacio está dormido o cambió. Reintenta en unos minutos o cambia el nombre en ⚙ Configuración › Modelos y espacios. |
| **"Error 401/403 — clave inválida"** | Revisa que copiaste la clave completa, sin espacios. |
| **"Error 402 — sin saldo"** | Recarga créditos en el servicio de pago o baja de nivel. |
| **"Error 429 — límite de uso"** | Espera unos minutos; usaste mucho seguido. |
| **"Modelo no encontrado"** | El proveedor cambió el nombre del modelo. Escribe el nombre nuevo en Modelos y espacios. |
| **La voz IA no suena** | Prueba otra voz o proveedor, o usa 🎙 Grabar. La voz local tarda la primera vez porque descarga el modelo. |
| **"Límite gratis de Pollinations"** | Sin clave, Pollinations responde 1 vez cada 30 s y la app espera sola. Pon la clave gratuita y desaparece la espera. |
| **Un servicio aparece como "bloqueado para tu país"** | Prueba con otro servidor de tu VPN, o deja que el respaldo automático use otro servicio. |
| **La web no se puede leer** | Algunas webs bloquean a los lectores automáticos. Prueba con otra página del mismo sitio o usa el modo Desde mis imágenes con capturas tuyas. |
| **El video sale en WebM y no en MP4** | Actualiza Chrome o Edge. WebM sirve para YouTube y Facebook; para WhatsApp e Instagram conviene MP4. |
| **El video tiene saltos** | No cambies de pestaña ni minimices mientras graba. |
| **"3D aproximado (modelo no disponible)"** | No se pudo descargar el modelo 3D. Funciona igual con un 3D aproximado; reintenta con mejor conexión. |
| **No guarda en carpetas** | Usa Chrome o Edge en una PC, y acepta el permiso de la carpeta. |

---

## 17. Preguntas frecuentes

**¿Es realmente gratis?**
Sí, en los niveles 1, 2 y 3. Los servicios gratis tienen límites diarios y a veces están ocupados. Los niveles 4 a 7 usan servicios de pago con tu propia cuenta.

**¿Puedo usar los videos en mi negocio?**
Sí. La música incluida la genera la app y no tiene derechos de autor. Si subes tu propia música, asegúrate de que sea tuya o libre de derechos.

**¿Mis fotos y claves se envían a algún sitio?**
Las fotos se envían solo al servicio de IA que elijas cuando pides analizarlas, transformarlas o animarlas. Las claves se quedan en tu navegador y nunca se guardan en los proyectos.

**¿Cuánto dura un video?**
Entre 6 y 60 segundos en modo manual. Con voz, se ajusta solo a la narración (normalmente de 12 a 25 segundos con 4 escenas).

**¿Puedo hacer el video en inglés o portugués?**
Sí. Elige el idioma en el paso 1: el guion, la voz y los subtítulos salen en ese idioma.

**¿Funciona sin Internet?**
La Foto viva, la música, los subtítulos, la grabación y los proyectos sí. El guion, las imágenes, la voz y el video IA necesitan conexión.

---

*AUREA Studio · parte del catálogo Herramix · Soporte y licencias por WhatsApp: +53 5508 1288*
