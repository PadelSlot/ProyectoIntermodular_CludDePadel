Con el objetivo de garantizar el estricto cumplimiento de la Ley de Propiedad Intelectual y las directrices establecidas en el marco normativo del proyecto, se ha llevado a cabo una auditoría exhaustiva de todos los recursos gráficos, vectoriales, tipográficos y animados integrados en PadelSlot SaaS. Este proceso asegura la trazabilidad legal de cada activo digital empleado en la interfaz, verificando que todos los elementos provengan de fuentes abiertas libres de regalías o correspondan a desarrollos propios del equipo.  
\# Inventario multimedia y registro de licencias · PadelSlot

\*\*Sprint 3 · Tarea T-3.1\*\* · Proyecto Intermodular · 2.º DAW · Equipo 04  
\*\*Responsable y aprobador (RACI):\*\* Product Owner & UI/Multimedia Lead  
\*\*Fecha de la auditoría:\*\* 26/11/2026 · \*\*Versión auditada:\*\* rama \`main\`, commit \`d4d3896\`  
\*\*Ubicación en el repositorio:\*\* \`docs/inventario-multimedia.md\`

\---

\#\# 1\. Objetivo y alcance

Este documento es el \*\*registro único\*\* de todos los recursos multimedia de PadelSlot: fotografías, logotipo, iconos, animaciones, vídeo, audio, subtítulos, tipografías y librerías gráficas. Por cada recurso se anota su origen exacto, el autor, la licencia, el texto de atribución obligatorio y el visto bueno del Product Owner. El visto bueno cubre dos cosas: que el recurso se puede usar legalmente y que encaja con la guía de estilo.

\*\*Regla de entrada:\*\* ningún recurso pasa a tratamiento digital (T-3.2, T-3.3) ni se integra en la web (T-3.5) sin estar registrado y aprobado aquí. Si se cambia un recurso o se añade uno nuevo, el mismo Pull Request actualiza este documento.

\#\#\# 1.1 Licencias admitidas

\| Licencia \| ¿Admitida? \| Condiciones de uso en el proyecto \|  
\|---\|---\|---\|  
\| CC0 1.0 (dominio público) \| ✅ \| Uso libre. Crédito voluntario \|  
\| CC BY / CC BY-SA \| ✅ \| \*\*Atribución visible en la web\*\* (título, autor, fuente, licencia y si se ha modificado). Con BY-SA, los derivados se comparten con la misma licencia \|  
\| Producción propia del equipo \| ✅ \| Se registra como © Equipo 04 o MIT \|  
\| MIT / SIL OFL (código y tipografías) \| ✅ \| Conservar el aviso de copyright y la licencia en los archivos \|  
\| Unsplash, Pexels y Pixabay \| ✅ con justificación (ver D-01) \| Uso y modificación gratuitos sin atribución obligatoria. No permiten revender el archivo sin cambios ni cubren marcas o personas que aparezcan \|  
\| Sin licencia, «uso no comercial» o desconocida \| ❌ \| Prohibido. Se sustituye por material propio o CC0 (riesgo R-02) \|

\#\#\# 1.2 Guía de estilo que se comprueba

\| Código \| Requisito \|  
\|---\|---\|  
\| RE-01 \| Paleta: verde oscuro \`\#255945\` (primario), blanco \`\#FFFFFF\` (secundario) y lima \`\#DEF127\` (terciario) \|  
\| RE-02 \| Tipografía: Space Grotesk en los títulos e Inter en el texto \|  
\| RE-03 \| Estilo limpio y coherente: fotos reales en color, iconos de línea, esquinas redondeadas \|  
\| RE-04 \| Responsive: varias resoluciones para móvil, tableta y escritorio \|  
\| RE-05 \| Accesibilidad: alternativa textual, contraste AA, estados visibles \|

\*\*Leyenda de estado:\*\* ✅ aprobado · ⚠️ aprobado con condición · ❌ rechazado

\---

\#\# 2\. Resumen

\| Tipo \| Recursos \| Archivos en la web \| Peso en el repo \| Licencia verificada en la fuente \| Estado \|  
\|---\|---\|---\|---\|---\|---\|  
\| Fotografías \| 6 \| 36 (3 tamaños × AVIF/WebP) \| 2.930 KB \| 5 de 6 \| ⚠️ \|  
\| Logotipo \| 2 \| 5 \| 51 KB \| Propio \| ✅ \|  
\| Iconos \| 1 \| 1 sprite (109 iconos) \| 44 KB \| MIT (cabecera del archivo) \| ✅ \|  
\| Animaciones \| 2 \| 1 \+ 1 SVG en línea \| 1,6 KB \| Propias \| ✅ \|  
\| Vídeo, póster y subtítulos \| 3 \| 5 \| 4.345 KB \| Propio (VTT). Pexels pendiente de comprobar en el navegador \| ⚠️ \|  
\| Audio \| 1 \| 2 \| 366 KB \| ✅ \| ✅ \|  
\| Tipografías y librerías \| 3 \| Google Fonts \+ 1 JS \| — \| ✅ \| ✅ \|  
\| \*\*Total que usa la web\*\* \| \*\*18\*\* \| \*\*51\*\* \| \*\*≈ 7,6 MB\*\* \| \*\*16 de 18\*\* \| \|  
\| Material de diseño, fuera de la web \| 2 \| 14 PNG \| 13.177 KB \| Propio \| ⚠️ (moverlo a \`docs/\`) \|

\---

\#\# 3\. Registro de recursos

\#\#\# 3.1 Fotografías (\`assets/img/\`)

\| ID \| Recurso \| Autor \| URL de origen \| Licencia \| Modificaciones \| Texto de atribución \| Guía de estilo \| Estado \|  
\|---\|---\|---\|---\|---\|---\|---\|---\|---\|  
\| IMG-01 \| \`pista-club-1\`: pistas exteriores con malla (\*«Sanchez-Casal Paddle Tennis Game in a cage»\*) \| JC / Jacky Cheong (CaliTennis.com), usuario de Flickr \*demiace\* \| https\://www\.flickr.com/photos/demiace/3592979029/ · copia en https\://commons.wikimedia.org/wiki/File:Sanchez-Casal\_Paddle\_Tennis\_Game.jpg \| \[CC BY-SA 2.0\](https\://creativecommons.org/licenses/by-sa/2.0/) \| Recorte 3:2, escalado a 480/960/1280 px, conversión a AVIF/WebP. Derivados bajo CC BY-SA 2.0 \| «Sanchez-Casal Paddle Tennis Game in a cage», de JC / Jacky Cheong (CaliTennis.com), CC BY-SA 2.0. Imagen recortada y convertida \| ✅ RE-01: césped y malla verdes. RE-03: foto real en color \| ⚠️ Atribución en la web (INC-01) \|  
\| IMG-02 \| \`pista-club-2\`: pista de cristal con césped (\*«Padel court, Barnton Park Lawn Tennis Club»\*) \| Richard Webb \| https\://www\.geograph.org.uk/photo/7911641 · copia en https\://commons.wikimedia.org/wiki/File:Padel\_court,\_Barnton\_Park\_Lawn\_Tennis\_Club\_-\_geograph.org.uk\_-\_7911641.jpg \| \[CC BY-SA 2.0\](https\://creativecommons.org/licenses/by-sa/2.0/) \| Recorte 3:2, escalado y conversión a AVIF/WebP. Derivados bajo CC BY-SA 2.0 \| «Padel court, Barnton Park Lawn Tennis Club», de Richard Webb (geograph.org.uk), CC BY-SA 2.0. Imagen recortada y convertida \| ✅ RE-01 y RE-03 \| ⚠️ Atribución en la web (INC-01) \|  
\| IMG-03 \| \`pista-club-3\`: pistas azules cubiertas (\*«Padel court Nsambya»\*) \| Samson Ssemakadde \| https\://commons.wikimedia.org/wiki/File:Padel\_court\_Nsambya.jpg \| \[CC0 1.0\](https\://creativecommons.org/publicdomain/zero/1.0/) \| Escalado y conversión a AVIF/WebP (proporción original, 1280 × 848\) \| No es obligatoria. Crédito voluntario: «Padel court Nsambya», de Samson Ssemakadde (CC0) \| ✅ RE-03. Pista azul, igual que el vídeo \| ⚠️ Comprobar la fuente (V-01) \|  
\| IMG-04 \| \`tienda\`: palas y pelotas sobre pista azul \| Sergio Contreras (@contarcos) \| https\://unsplash.com/photos/wLAtpQ53Pfw \| \[Unsplash License\](https\://unsplash.com/license) \| Recorte 3:2, escalado y conversión \| No es obligatoria. Crédito voluntario: «Foto de Sergio Contreras en Unsplash» \| ✅ RE-01: pelotas lima \`\#DEF127\` \| ⚠️ Se ven logotipos de marca (D-03) \|  
\| IMG-05 \| \`fisioterapia\`: masaje de espalda \| Performance Medicine (@performance\_medicine1) \| https\://unsplash.com/photos/OgzbUs-IntQ \| \[Unsplash License\](https\://unsplash.com/license) \| Recorte 3:2, escalado y conversión \| No es obligatoria. Crédito voluntario: «Foto de Performance Medicine en Unsplash» \| ⚠️ RE-03: es la única foto en blanco y negro \| ⚠️ Excepción aceptada (D-02) \|  
\| IMG-06 \| \`terraza\`: terraza con sombrillas \| Declan Sun (@declansun) \| https\://unsplash.com/photos/T0TQSFmHDbw \| \[Unsplash License\](https\://unsplash.com/license) \| Recorte 3:2, escalado y conversión \| No es obligatoria. Crédito voluntario: «Foto de Declan Sun en Unsplash» \| ✅ RE-03: exterior luminoso con vegetación \| ✅ \|

\*\*Texto alternativo en la web:\*\* IMG-01 «Pistas de pádel exteriores con cerramiento de malla» · IMG-02 «Pista de pádel de cristal rodeada de césped» · IMG-03 «Pistas de pádel cubiertas con suelo azul» · IMG-04 «Palas de pádel y pelotas sobre una pista azul» · IMG-05 «Fisioterapeuta realizando un masaje de espalda a un paciente» · IMG-06 «Terraza exterior con sombrillas, mesas y sillas». Todos se han comparado con la imagen y la describen bien (RE-05).

\#\#\# 3.2 Logotipo, iconos y animaciones

\| ID \| Recurso \| Autor \| Origen \| Licencia \| Texto de atribución \| Guía de estilo \| Estado \|  
\|---\|---\|---\|---\|---\|---\|---\|---\|  
\| LOG-01 \| Logotipo vectorial \`svg/logo-padelslot.svg\` \| Equipo 04: concepto, prompt, selección y vectorización. Imagen base generada con Google Gemini el 12/11/2026 \| Producción propia con ayuda de IA (\[términos de Gemini\](https\://policies.google.com/terms/generative-ai)) \| © 2026 Equipo 04 \| No es obligatoria \| ✅ RE-01: verde, blanco y lima \| ✅ \|  
\| LOG-02 \| Versiones ráster del logotipo, 64 y 128 px en AVIF/WebP \| Equipo 04 (derivadas de LOG-01) \| Producción propia \| © 2026 Equipo 04 \| No es obligatoria \| ✅ \| ✅ \|  
\| ICO-01 \| Sprite \`svg/iconos.svg\` con 109 iconos (variante \*regular\*) \+ \`js/iconos.js\` \| Phosphor Icons (Helena Zhang y Tobias Fried) \| https\://phosphoricons.com · https\://github.com/phosphor-icons/core \| \[MIT\](https\://opensource.org/license/mit) \| Aviso de licencia conservado en el comentario de cabecera del sprite \| ✅ RE-03: iconos de línea con \`currentColor\` \| ✅ \|  
\| ANI-01 \| Spritesheet \`anim/pelota-sprite.svg\`: pelota que bota, 8 fotogramas \| Equipo 04 \| Producción propia (a partir del vector de la pelota del logotipo) \| MIT \| No es obligatoria \| ✅ RE-01: blanco y lima \`\#DEF127\` \| ✅ \|  
\| ANI-02 \| Check animado: SVG en línea \`.check-animado\` en \`reservaNoSocio.html\` \| Equipo 04 \| Producción propia \| MIT \| No es obligatoria \| ✅ Usa \`currentColor\` \| ✅ \|

\> \*\*Nota sobre la IA (LOG-01):\*\* la protección por derechos de autor de una imagen generada por IA es discutible, porque la ley reconoce la autoría a personas físicas. El equipo reivindica la autoría del concepto, el prompt, la selección y la vectorización final.

\#\#\# 3.3 Vídeo, audio y subtítulos (\`assets/media/\`)

\| ID \| Recurso \| Autor \| URL de origen \| Licencia \| Modificaciones \| Texto de atribución \| Guía de estilo \| Estado \|  
\|---\|---\|---\|---\|---\|---\|---\|---\|---\|  
\| VID-01 \| \`video-partido\`: partido de dobles grabado con dron \| Gianluca Guidi \| https\://www\.pexels.com/video/13737627/ \| \[Licencia Pexels\](https\://www\.pexels.com/license/) \| Recorte a los 12 primeros segundos, escalado de 2560 × 1440 a 1280 × 720, H.264 (CRF 26, \*faststart\*) y VP9 (CRF 42), sin pista de audio \| No es obligatoria. Crédito voluntario: «Vídeo de Gianluca Guidi en Pexels» \| ✅ RE-03: pista azul y tono deportivo \| ⚠️ Comprobar la fuente (V-02) y el peso (INC-03) \|  
\| VID-02 \| Póster \`video-partido-poster\` (WebP y AVIF) \| Derivado de VID-01 (primer fotograma) \| — \| Licencia Pexels \| Captura del fotograma y conversión \| Igual que VID-01 \| ✅ \| ⚠️ Peso (INC-03) \|  
\| VID-03 \| Subtítulos descriptivos \`video-partido-es.vtt\` \| Equipo 04 \| Producción propia \| MIT \| — \| No es obligatoria \| ✅ RE-05: comparados con los fotogramas de los segundos 2, 6 y 11, el texto coincide con la imagen \| ✅ \|  
\| AUD-01 \| \`musica-fondo\` (\*«Stylish Sport Rock (Powerful)»\*) \| MarkJuly \| https\://pixabay.com/music/rock-stylish-sport-rock-powerful-114261/ \| \[Pixabay Content License\](https\://pixabay.com/service/license-summary/) \| Fragmento de 12 s desde el segundo 26, fundidos de 1 s, normalizado a −16 LUFS, MP3 a 128 kbps y OGG Vorbis q4 \| No es obligatoria. Crédito voluntario: «Música: Stylish Sport Rock (Powerful), de MarkJuly, en Pixabay» \| ✅ Tono deportivo y enérgico \| ✅ \|

\#\#\# 3.4 Tipografías y librerías

\| ID \| Recurso \| Autor \| Origen \| Licencia \| Obligaciones \| Guía de estilo \| Estado \|  
\|---\|---\|---\|---\|---\|---\|---\|---\|  
\| FNT-01 \| Inter \| Rasmus Andersson / The Inter Project Authors \| https\://fonts.google.com/specimen/Inter \| \[SIL OFL 1.1\](https\://openfontlicense.org) \| Ninguna en la web (se carga desde Google Fonts) \| ✅ RE-02: texto \| ✅ \|  
\| FNT-02 \| Space Grotesk \| Florian Karsten / The Space Grotesk Project Authors \| https\://fonts.google.com/specimen/Space+Grotesk \| \[SIL OFL 1.1\](https\://openfontlicense.org) \| Ninguna en la web \| ✅ RE-02: títulos \| ✅ \|  
\| LIB-01 \| QRCode.js (\`js/vendor/qrcode.js\`), genera el QR del carné en SVG \| Kazuhiko Arase (2009) y davidshimjs \| https\://github.com/davidshimjs/qrcodejs \| \[MIT\](https\://opensource.org/license/mit) \| Conservar la cabecera de copyright y \`js/vendor/LICENSE.txt\` (ya están). «QR Code» es marca registrada de DENSO WAVE \| ✅ \| ✅ \|

\---

\#\# 4\. Detalle por archivo

Rutas relativas a \`PadelSlot/assets/\`. Peso en KB (1 KB \= 1.024 bytes). El \`\<picture\>\` sirve AVIF a los navegadores que lo admiten y WebP a los demás. El 960 WebP es el \`\<img\>\` de respaldo. Todas las fotos llevan \`loading="lazy"\` porque ninguna es la imagen principal de la portada.

\| ID \| Archivo \| Formato \| Dimensiones \| Peso \| Dónde se usa \|  
\|---\|---\|---\|---\|---\|---\|  
\| IMG-01 \| \`img/pistas/pista-club-1-480.avif\` \| AVIF \| 480 × 320 \| 19 KB \| \`index.html\` · \`srcset\` \|  
\| IMG-01 \| \`img/pistas/pista-club-1-480.webp\` \| WEBP \| 480 × 320 \| 29 KB \| \`index.html\` · \`srcset\` \|  
\| IMG-01 \| \`img/pistas/pista-club-1-960.avif\` \| AVIF \| 960 × 640 \| 77 KB \| \`index.html\` · \`srcset\` \|  
\| IMG-01 \| \`img/pistas/pista-club-1-960.webp\` \| WEBP \| 960 × 640 \| 115 KB \| \`index.html\` · \`\<img\>\` de respaldo \|  
\| IMG-01 \| \`img/pistas/pista-club-1-1280.avif\` \| AVIF \| 1280 × 853 \| 143 KB \| \`index.html\` · \`srcset\` \|  
\| IMG-01 \| \`img/pistas/pista-club-1-1280.webp\` \| WEBP \| 1280 × 853 \| 206 KB \| \`index.html\` · \`srcset\` \|  
\| IMG-02 \| \`img/pistas/pista-club-2-480.avif\` \| AVIF \| 480 × 320 \| 15 KB \| \`index.html\` · \`srcset\` \|  
\| IMG-02 \| \`img/pistas/pista-club-2-480.webp\` \| WEBP \| 480 × 320 \| 19 KB \| \`index.html\` · \`srcset\` \|  
\| IMG-02 \| \`img/pistas/pista-club-2-960.avif\` \| AVIF \| 960 × 640 \| 60 KB \| \`index.html\` · \`srcset\` \|  
\| IMG-02 \| \`img/pistas/pista-club-2-960.webp\` \| WEBP \| 960 × 640 \| 78 KB \| \`index.html\` · \`\<img\>\` de respaldo \|  
\| IMG-02 \| \`img/pistas/pista-club-2-1280.avif\` \| AVIF \| 1280 × 853 \| 112 KB \| \`index.html\` · \`srcset\` \|  
\| IMG-02 \| \`img/pistas/pista-club-2-1280.webp\` \| WEBP \| 1280 × 853 \| 145 KB \| \`index.html\` · \`srcset\` \|  
\| IMG-03 \| \`img/pistas/pista-club-3-480.avif\` \| AVIF \| 480 × 318 \| 18 KB \| \`index.html\` · \`srcset\` \|  
\| IMG-03 \| \`img/pistas/pista-club-3-480.webp\` \| WEBP \| 480 × 318 \| 24 KB \| \`index.html\` · \`srcset\` \|  
\| IMG-03 \| \`img/pistas/pista-club-3-960.avif\` \| AVIF \| 960 × 636 \| 66 KB \| \`index.html\` · \`srcset\` \|  
\| IMG-03 \| \`img/pistas/pista-club-3-960.webp\` \| WEBP \| 960 × 636 \| 93 KB \| \`index.html\` · \`\<img\>\` de respaldo \|  
\| IMG-03 \| \`img/pistas/pista-club-3-1280.avif\` \| AVIF \| 1280 × 848 \| 123 KB \| \`index.html\` · \`srcset\` \|  
\| IMG-03 \| \`img/pistas/pista-club-3-1280.webp\` \| WEBP \| 1280 × 848 \| 167 KB \| \`index.html\` · \`srcset\` \|  
\| IMG-04 \| \`img/convenios/tienda-480.avif\` \| AVIF \| 480 × 320 \| 35 KB \| \`cuotas.html\` · \`srcset\` \|  
\| IMG-04 \| \`img/convenios/tienda-480.webp\` \| WEBP \| 480 × 320 \| 50 KB \| \`cuotas.html\` · \`srcset\` \|  
\| IMG-04 \| \`img/convenios/tienda-960.avif\` \| AVIF \| 960 × 640 \| 122 KB \| \`cuotas.html\` · \`srcset\` \|  
\| IMG-04 \| \`img/convenios/tienda-960.webp\` \| WEBP \| 960 × 640 \| 171 KB \| \`cuotas.html\` · \`\<img\>\` de respaldo \|  
\| IMG-04 \| \`img/convenios/tienda-1280.avif\` \| AVIF \| 1280 × 853 \| 194 KB \| \`cuotas.html\` · \`srcset\` \|  
\| IMG-04 \| \`img/convenios/tienda-1280.webp\` \| WEBP \| 1280 × 853 \| 278 KB \| \`cuotas.html\` · \`srcset\` \|  
\| IMG-05 \| \`img/convenios/fisioterapia-480.avif\` \| AVIF \| 480 × 320 \| 5,8 KB \| \`cuotas.html\` · \`srcset\` \|  
\| IMG-05 \| \`img/convenios/fisioterapia-480.webp\` \| WEBP \| 480 × 320 \| 5,9 KB \| \`cuotas.html\` · \`srcset\` \|  
\| IMG-05 \| \`img/convenios/fisioterapia-960.avif\` \| AVIF \| 960 × 640 \| 15 KB \| \`cuotas.html\` · \`srcset\` \|  
\| IMG-05 \| \`img/convenios/fisioterapia-960.webp\` \| WEBP \| 960 × 640 \| 16 KB \| \`cuotas.html\` · \`\<img\>\` de respaldo \|  
\| IMG-05 \| \`img/convenios/fisioterapia-1280.avif\` \| AVIF \| 1280 × 853 \| 23 KB \| \`cuotas.html\` · \`srcset\` \|  
\| IMG-05 \| \`img/convenios/fisioterapia-1280.webp\` \| WEBP \| 1280 × 853 \| 25 KB \| \`cuotas.html\` · \`srcset\` \|  
\| IMG-06 \| \`img/convenios/terraza-480.avif\` \| AVIF \| 480 × 320 \| 19 KB \| \`cuotas.html\` · \`srcset\` \|  
\| IMG-06 \| \`img/convenios/terraza-480.webp\` \| WEBP \| 480 × 320 \| 26 KB \| \`cuotas.html\` · \`srcset\` \|  
\| IMG-06 \| \`img/convenios/terraza-960.avif\` \| AVIF \| 960 × 640 \| 68 KB \| \`cuotas.html\` · \`srcset\` \|  
\| IMG-06 \| \`img/convenios/terraza-960.webp\` \| WEBP \| 960 × 640 \| 93 KB \| \`cuotas.html\` · \`\<img\>\` de respaldo \|  
\| IMG-06 \| \`img/convenios/terraza-1280.avif\` \| AVIF \| 1280 × 853 \| 115 KB \| \`cuotas.html\` · \`srcset\` \|  
\| IMG-06 \| \`img/convenios/terraza-1280.webp\` \| WEBP \| 1280 × 853 \| 158 KB \| \`cuotas.html\` · \`srcset\` \|  
\| LOG-01 \| \`svg/logo-padelslot.svg\` \| SVG \| viewBox 0·0·705·654 \| 30 KB \| 19 páginas · favicon y 1.ª \`\<source\>\` del logotipo \|  
\| LOG-02 \| \`img/logo/logo-padelslot-64.avif\` \| AVIF \| 64 × 59 \| 2,8 KB \| 19 páginas · respaldo del logotipo (1x) \|  
\| LOG-02 \| \`img/logo/logo-padelslot-64.webp\` \| WEBP \| 64 × 59 \| 3,4 KB \| 19 páginas · respaldo del logotipo (1x) \|  
\| LOG-02 \| \`img/logo/logo-padelslot-128.avif\` \| AVIF \| 128 × 119 \| 6,3 KB \| 19 páginas · respaldo del logotipo (2x) \|  
\| LOG-02 \| \`img/logo/logo-padelslot-128.webp\` \| WEBP \| 128 × 119 \| 9,0 KB \| 19 páginas · respaldo del logotipo (2x) \|  
\| ICO-01 \| \`svg/iconos.svg\` \| SVG \| 109 símbolos de 256 × 256 \| 44 KB \| 19 páginas · 109 \`\<symbol\>\` \|  
\| ANI-01 \| \`anim/pelota-sprite.svg\` \| SVG \| viewBox 0·0·512·64 \| 1,6 KB \| \`index.html\` · vía \`main.css\` \|  
\| VID-01 \| \`media/video-partido.webm\` \| WEBM \| 1280 × 720 · 12 s \| 1.865 KB \| \`index.html\` · 1.ª \`\<source\>\` \|  
\| VID-01 \| \`media/video-partido.mp4\` \| MP4 \| 1280 × 720 · 12 s \| 2.125 KB \| \`index.html\` · 2.ª \`\<source\>\` \|  
\| VID-02 \| \`media/video-partido-poster.webp\` \| WEBP \| 1280 × 720 \| 204 KB \| \`index.html\` · atributo \`poster\` \|  
\| VID-02 \| \`media/video-partido-poster.avif\` \| AVIF \| 1280 × 720 \| 151 KB \| No se referencia (copia de reserva) \|  
\| VID-03 \| \`media/video-partido-es.vtt\` \| VTT \|  \| 0,3 KB \| \`index.html\` · \`\<track kind="captions"\>\` \|  
\| AUD-01 \| \`media/musica-fondo.ogg\` \| OGG \| 12 s \| 177 KB \| \`index.html\` · 1.ª \`\<source\>\` \|  
\| AUD-01 \| \`media/musica-fondo.mp3\` \| MP3 \| 12 s \| 189 KB \| \`index.html\` · 2.ª \`\<source\>\` \|

\*\*Comprobación del presupuesto de rendimiento (riesgo R-01):\*\*  
\- \*\*Imagen hero (máx. 150 KB):\*\* no aplica. La portada no tiene foto principal y todas las fotos se cargan en diferido. De las versiones de 480 px (las que se sirven en móvil), la que más pesa es \`tienda-480.webp\`, con 50 KB.  
\- \*\*Vídeo en bucle (máx. 2 MB):\*\* \`video-partido.webm\` pesa 1.865 KB y cumple; es el que reciben Chrome, Edge y Firefox. \`video-partido.mp4\` pesa 2.125 KB y supera el límite en 77 KB; solo lo recibe Safari (INC-03).  
\- \*\*Fondo decorativo sin audio:\*\* ✅ Comprobado con \`ffprobe\`: los dos vídeos tienen solo una pista de vídeo.

\#\#\# 4.1 Material de diseño que no usa la web

Son recursos propios del equipo (© 2026 Equipo 04\) y no tienen problemas de licencia. Están dentro de \`assets/\` y se publicarían con la web sin que nadie los use (INC-04).

\| ID \| Archivo \| Formato \| Dimensiones \| Peso \| Uso \|  
\|---\|---\|---\|---\|---\|---\|  
\| DOC-01 \| \`img/mockup/Escuela y Clases \- Portal del Socio.png\` \| PNG \| 1284 × 2129 \| 393 KB \| No lo usa la web \|  
\| DOC-01 \| \`img/mockup/Inicio Público \- PadelSlot SaaS.png\` \| PNG \| 1296 × 4717 \| 1.357 KB \| No lo usa la web \|  
\| DOC-01 \| \`img/mockup/Membresía y Cuotas \- Portal del Socio.png\` \| PNG \| 1284 × 3018 \| 815 KB \| No lo usa la web \|  
\| DOC-01 \| \`img/mockup/Panel de Administrador \- PadelSlot Club Manager.png\` \| PNG \| 1284 × 2307 \| 409 KB \| No lo usa la web \|  
\| DOC-01 \| \`img/mockup/Portal del Socio \- PadelSlot.png\` \| PNG \| 1284 × 2642 \| 737 KB \| No lo usa la web \|  
\| DOC-01 \| \`img/mockup/Registro de Socio \- Paso 1\_ Plan y Cuota.png\` \| PNG \| 1296 × 1180 \| 522 KB \| No lo usa la web \|  
\| DOC-01 \| \`img/mockup/Registro de Socio \- Paso 2\_ Datos y Perfil Deportivo.png\` \| PNG \| 1312 × 1648 \| 361 KB \| No lo usa la web \|  
\| DOC-01 \| \`img/mockup/Registro de Socio \- Paso 3\_ Pago y Domiciliación.png\` \| PNG \| 1309 × 1688 \| 283 KB \| No lo usa la web \|  
\| DOC-01 \| \`img/mockup/Registro de Socio \- Paso 4\_ Confirmación y Carnet.png\` \| PNG \| 1296 × 1535 \| 571 KB \| No lo usa la web \|  
\| DOC-01 \| \`img/mockup/Registro e Inicio de Sesión \- PadelSlot.png\` \| PNG \| 1296 × 1223 \| 295 KB \| No lo usa la web \|  
\| DOC-01 \| \`img/mockup/Reserva de Pista Invitado (No Socio) \- PadelSlot.png\` \| PNG \| 1284 × 2949 \| 611 KB \| No lo usa la web \|  
\| DOC-01 \| \`img/mockup/Reservar Pista \- Socio PadelSlot.png\` \| PNG \| 1284 × 2226 \| 345 KB \| No lo usa la web \|  
\| DOC-01 \| \`img/mockup/Servicios del Club \- Portal del Socio.png\` \| PNG \| 1284 × 2658 \| 1.408 KB \| No lo usa la web \|  
\| DOC-02 \| \`img/boceto/boceto.png\` \| PNG \| 11.108 × 9.586 \| 5.066 KB \| No lo usa la web \|

\---

\#\# 5\. Créditos que hay que mostrar en la web

Las licencias CC BY-SA 2.0 (IMG-01 e IMG-02) obligan a mostrar la atribución donde se usan las fotos. Los demás créditos son voluntarios, pero se incluyen por transparencia. Hay que ponerlos en el pie de \`index.html\` o en una página de créditos enlazada desde el pie de todas las páginas.

\`\`\`html  
\<p class="creditos"\>  
  Fotografías: «Sanchez-Casal Paddle Tennis Game in a cage», de JC / Jacky Cheong (CaliTennis.com),  
  y «Padel court, Barnton Park Lawn Tennis Club», de Richard Webb, ambas bajo  
  \<a href="https\://creativecommons.org/licenses/by-sa/2.0/"\>CC BY-SA 2.0\</a\>, recortadas y convertidas de formato.  
  «Padel court Nsambya», de Samson Ssemakadde (CC0).  
  Convenios: fotos de Sergio Contreras, Performance Medicine y Declan Sun en Unsplash.  
  Vídeo: Gianluca Guidi en Pexels. Música: «Stylish Sport Rock (Powerful)», de MarkJuly, en Pixabay.  
  Iconos: Phosphor Icons (MIT). Tipografías: Inter y Space Grotesk (SIL OFL 1.1).  
\</p\>  
\`\`\`

\---

\#\# 6\. Decisiones del Product Owner

\| ID \| Asunto \| Decisión \| Motivo \| Plan B (riesgo R-02) \|  
\|---\|---\|---\|---\|---\|  
\| D-01 \| Unsplash, Pexels y Pixabay no son licencias Creative Commons, y el SOW (T-3.1) pide CC0, CC BY, CC BY-SA o producción propia \| \*\*Se mantienen\*\* IMG-04, IMG-05, IMG-06, VID-01, VID-02 y AUD-01 \| Son licencias libres que permiten usar y modificar gratis, incluso con fines comerciales, sin atribución obligatoria. El uso en PadelSlot (mostrar en la web, recortar, recodificar) está permitido. No se distribuyen los archivos sueltos ni se venden \| Si el tutor no lo acepta, se sustituyen por material CC0 de Wikimedia Commons u Openverse (fotos), Wikimedia Commons (vídeo) o Freesound CC0 (música), y se vuelve a pasar por T-3.2 y T-3.3 \|  
\| D-02 \| IMG-05 es en blanco y negro y el resto de fotos son en color (RE-03) \| \*\*Se acepta como excepción\*\* \| Es la única foto del convenio de fisioterapia y transmite bien el servicio. El contraste del texto no depende de ella \| En el Sprint 4, buscar una alternativa en color con licencia admitida \|  
\| D-03 \| En IMG-04 se ven logotipos de una marca comercial de palas \| \*\*Se acepta para uso académico\*\* \| La licencia de Unsplash no da derechos sobre marcas, pero la foto no sugiere patrocinio y el club es ficticio \| Para producción real: recortar la foto o sustituirla \|  
\| D-04 \| LOG-01 se generó con IA \| \*\*Se acepta\*\* \| El equipo aporta el concepto, el prompt, la selección y la vectorización. Los términos de Gemini permiten usar el resultado \| — \|

\---

\#\# 7\. Incidencias abiertas

\| ID \| Incidencia \| Riesgo \| Acción \| Responsable \| Prioridad \|  
\|---\|---\|---\|---\|---\|---\|  
\| INC-01 \| La web no muestra la atribución CC BY-SA de IMG-01 e IMG-02 \| Incumplimiento de licencia (R-02) y de la DoD n.º 1 \| Añadir el bloque de créditos del apartado 5 \| Scrum Master / Frontend \| \*\*Alta\*\* \|  
\| INC-02 \| \`LICENSES.md\` no coincide con el repo: cita \`LogoPadelSlot.svg\` y los tamaños 160/320/705 (los reales son \`logo-padelslot.svg\` y 64/128); dice que Phosphor se carga por CDN (ahora es el sprite local \`iconos.svg\`); registra un mapa de OpenStreetMap que ya no existe (ahora es un marcador estático); su apartado 7 dice que no hay audio, vídeo ni animaciones y luego los lista; faltan ANI-01, ANI-02, VID-02 y VID-03 \| Registro de atribución incoherente \| Actualizar \`LICENSES.md\` con los datos de este inventario \| Product Owner \| \*\*Alta\*\* \|  
\| INC-03 \| \`video-partido.mp4\` pesa 2.125 KB (máx. 2.048 KB) y el póster WebP pesa 204 KB \| Rendimiento en Safari y LCP \| Recodificar el MP4 con CRF 28 y el póster como WebP de calidad 70 (objetivo: menos de 150 KB) \| Scrum Master / Frontend \| Media \|  
\| INC-04 \| Los mockups y el boceto (13.177 KB) están en \`assets/img/\` y se publicarían con la web \| Peso del repo y del despliegue (R-05) \| Moverlos a \`docs/mockups/\` y \`docs/boceto/\`. Ya está hecho en la rama de la T-3.6, falta fusionarla \| Backend \| Media \|  
\| INC-05 \| \`video-partido-poster.avif\` no lo usa ninguna página \| Archivo de más \| Borrarlo o declararlo en el atributo \`poster\` \| Scrum Master / Frontend \| Baja \|  
\| INC-06 \| \`pista-club-3\` mide 1280 × 848, pero el HTML declara \`width="1280" height="853"\` \| Desajuste de 5 px (CLS mínimo) \| Ajustar \`height="848"\` en \`index.html\` o recortar la foto a 3:2 \| Scrum Master / Frontend \| Baja \|

\---

\#\# 8\. Verificación de las fuentes

\| ID \| Comprobación \| Resultado \| Fecha \|  
\|---\|---\|---\|---\|  
\| IMG-01 \| Página de Flickr \| ✅ Título, autor (JC, \*demiace\*, CaliTennis.com) y licencia CC BY-SA 2.0 coinciden \| 26/11/2026 \|  
\| IMG-02 \| Página de geograph.org.uk \| ✅ Título, autor (Richard Webb, foto del 22/10/2024) y licencia CC BY-SA 2.0 coinciden \| 26/11/2026 \|  
\| IMG-03 \| Página de Wikimedia Commons \| ⬜ \*\*V-01:\*\* abrir la URL en el navegador y confirmar autor y CC0 \| \|  
\| IMG-04, IMG-05, IMG-06 \| Páginas de Unsplash \| ✅ Autores y Unsplash License coinciden \| 26/11/2026 \|  
\| VID-01 \| Página de Pexels \| ⬜ \*\*V-02:\*\* abrir la URL en el navegador y confirmar autor y licencia \| \|  
\| AUD-01 \| Página de Pixabay \| ✅ Título, artista (MarkJuly) y Pixabay Content License coinciden \| 26/11/2026 \|  
\| ICO-01, LIB-01 \| Cabeceras de los archivos \| ✅ Aviso MIT presente \| 26/11/2026 \|  
\| Recursos propios \| Repositorio y memoria del equipo \| ✅ \| 26/11/2026 \|

\---

\# Tratamiento digital de imágenes: recorte, escalado y exportación a WebP/AVIF/SVG

He procesado todas las imágenes que usa la interfaz de \*\*PadelSlot\*\* para que ocupen poco y la carga sea rápida en cualquier dispositivo. Están subidas al repositorio de \*\*Diseño de Interfaces\*\*, en la carpeta:

\`\`\`  
/PadelSlot/assets/img  
\`\`\`

\#\# Recorte

He recortado cada imagen a la proporción que pide el diseño según dónde se usa:

\- \*\*16:9\*\* para las cabeceras y banners.  
\- \*\*1:1\*\* para las tarjetas y los avatares.  
\- Otras proporciones donde el maquetado lo pedía.

Siempre he dejado centrado el motivo principal y he quitado bordes y fondos que no aportaban nada.

\#\# Escalado

He redimensionado las imágenes para que no sean más grandes de lo que se ven en pantalla. De cada imagen de contenido he sacado varias versiones de ancho distinto para \*\*móvil, tablet y escritorio\*\*, contando también con las pantallas de alta densidad. Así el navegador carga la más adecuada mediante \`srcset\` y \`sizes\`.

Ninguna imagen se ha ampliado por encima de su tamaño original, para que no pierda calidad.

\#\# Exportación

\| Formato \| Uso \| Motivo \|  
\|---------\|-----\|--------\|  
\| \*\*AVIF\*\* \| Fotografías (formato principal) \| Es el que más comprime \|  
\| \*\*WebP\*\* \| Fotografías (alternativa) \| Para navegadores sin soporte de AVIF \|  
\| \*\*SVG\*\* \| Logotipo e iconos \| Se ven nítidos a cualquier tamaño \|

Los SVG los he optimizado con \*\*SVGO\*\* para quitar metadatos y código innecesario.

Ajusté la calidad de compresión comparando visualmente el resultado, buscando el menor peso posible sin que se notaran artefactos.

\# Edición y transcodificación de audio (MP3/OGG) y vídeo (MP4/WebM) \+ póster

He editado y convertido los archivos multimedia de \*\*PadelSlot\*\* para que se reproduzcan bien en todos los navegadores y pesen lo menos posible. Están subidos al repositorio de \*\*Diseño de Interfaces\*\*, en las carpetas:

\`\`\`  
/PadelSlot/assets/media  
\`\`\`

\#\# Edición

Antes de convertir los archivos, preparé el material original:

\- \*\*Recorte de duración:\*\* quité los silencios y los fragmentos sobrantes del principio y del final, y dejé solo la parte útil.  
\- \*\*Ajuste de volumen:\*\* normalicé el audio para que todos los archivos suenen a un nivel parecido, sin picos ni saturación.  
\- \*\*Fundidos:\*\* añadí entradas y salidas suaves (\*fade in / fade out\*) para evitar cortes bruscos.  
\- \*\*Vídeo:\*\* ajusté la resolución y el encuadre al espacio que ocupa en el diseño, y quité la pista de audio en los vídeos que se reproducen en bucle de fondo, porque no hace falta.

\#\# Transcodificación de audio

\| Formato \| Uso \| Motivo \|  
\|---------\|-----\|--------\|  
\| \*\*MP3\*\* \| Formato principal \| Compatible con todos los navegadores \|  
\| \*\*OGG\*\* (Vorbis) \| Alternativa \| Formato abierto y con buena compresión \|

Elegí un \*bitrate\* que equilibra calidad y peso, adecuado para reproducirlo en la web.

\#\# Transcodificación de vídeo

\| Formato \| Códec \| Motivo \|  
\|---------\|-------\|--------\|  
\| \*\*MP4\*\* \| H.264 \+ AAC \| Máxima compatibilidad (incluido Safari/iOS) \|  
\| \*\*WebM\*\* \| VP9 \+ Opus \| Formato abierto con mejor compresión \|

Ajusté la resolución, el \*bitrate\* y la tasa de fotogramas para reducir el peso sin perder calidad visible. Los MP4 los exporté con la opción \*faststart\*, para que el vídeo empiece a reproducirse antes de descargarse entero.

\#\# Póster

Para cada vídeo he creado una \*\*imagen de póster\*\*, que se muestra mientras el vídeo carga o antes de darle al play. La saqué de un fotograma representativo del propio vídeo, con la misma proporción, y la exporté en \*\*WebP\*\* para que pese poco.

\# Diseño y exportación de animaciones web optimizadas (CSS/SVG/Lottie o sprites)

He diseñado y exportado las animaciones de la interfaz de \*\*PadelSlot\*\* para que sean fluidas, ligeras y no afecten al rendimiento de la web. Están subidas al repositorio de \*\*Diseño de Interfaces\*\*, en la carpeta:

\`\`\`  
/PadelSlot  
\`\`\`

\#\# Diseño

Las animaciones tienen una función concreta dentro de la interfaz: dar respuesta a lo que hace el usuario y guiarle. No son decorativas sin más:

\- \*\*Microinteracciones:\*\* \*hover\* y pulsación de botones, cambio de estado al seleccionar una pista o una franja horaria.  
\- \*\*Indicadores de carga:\*\* \*loader\* mientras se consultan las pistas disponibles.  
\- \*\*Confirmaciones:\*\* animación de éxito al completar una reserva.  
\- \*\*Transiciones:\*\* aparición suave de tarjetas, menús y modales.

Las duraciones son cortas (entre 150 y 400 ms en las microinteracciones) y las curvas de aceleración suaves (\`ease-out\`, \`cubic-bezier\`), para que la interfaz se sienta rápida y natural.

\#\# Técnica elegida según el caso

\| Técnica \| Uso \| Motivo \|  
\|---------\|-----\|--------\|  
\| \*\*CSS\*\* (\`transition\` / \`@keyframes\`) \| Microinteracciones y transiciones \| No necesita archivos extra y el navegador la optimiza \|  
\| \*\*SVG animado\*\* \| Iconos y \*loader\* \| Vectorial, nítido a cualquier tamaño y muy ligero \|  
\| \*\*Lottie\*\* (JSON) \| Animación de confirmación de reserva \| Permite animaciones complejas con muy poco peso \|  
\| \*\*Sprites\*\* \| Animaciones fotograma a fotograma \| Una sola imagen y una sola petición al servidor \|

\#\# Optimización

\- \*\*Solo propiedades baratas de animar:\*\* usé \`transform\` y \`opacity\`, que se procesan en la GPU, y evité animar \`width\`, \`height\`, \`top\` o \`left\`, que obligan a recalcular el diseño de la página.  
\- \*\*SVG limpios:\*\* los optimicé con \*\*SVGO\*\* para quitar metadatos, grupos vacíos y decimales innecesarios.  
\- \*\*Lottie:\*\* al exportar desde After Effects con Bodymovin, simplifiqué capas y trazados y dejé fuera las imágenes incrustadas, para reducir el tamaño del JSON.  
\- \*\*Sprites:\*\* junté los fotogramas en una sola imagen exportada en \*\*WebP\*\* y los animé con \`steps()\` en CSS.  
\- \*\*Accesibilidad:\*\* respeté la preferencia del sistema \`prefers-reduced-motion\`, que desactiva o reduce las animaciones a los usuarios que lo tienen configurado.

\# Maquetación HTML5/CSS3 adaptativa (\`\<picture\>\`, \`srcset\`, \`loading="lazy"\`)

He maquetado la interfaz de \*\*PadelSlot\*\* con HTML5 semántico y CSS3 para que se adapte a cualquier tamaño de pantalla y cargue las imágenes de forma eficiente. El código está subido al repositorio de \*\*Diseño de Interfaces\*\*, en la carpeta:

\`\`\`  
/PadelSlot  
\`\`\`

\#\# Estructura HTML5 semántica

He organizado las páginas con etiquetas que describen su contenido, en lugar de usar solo \`\<div\>\`:

\- \`\<header\>\` y \`\<nav\>\` para la cabecera y el menú de navegación.  
\- \`\<main\>\` para el contenido principal de cada página.  
\- \`\<section\>\` y \`\<article\>\` para los bloques de contenido y las tarjetas de pistas.  
\- \`\<footer\>\` para el pie de página.

Esto mejora la accesibilidad (lectores de pantalla), el SEO y la legibilidad del código.

\#\# Diseño adaptativo con CSS3

\- \*\*Mobile first:\*\* escribí primero los estilos para móvil y fui ampliando el diseño con \*media queries\* para tablet y escritorio.  
\- \*\*Puntos de corte:\*\* adaptados al contenido (aproximadamente 600 px, 900 px y 1200 px).  
\- \*\*Flexbox y Grid:\*\* Flexbox para alinear elementos en una dimensión (menú, botones) y CSS Grid para las rejillas de tarjetas de pistas, que pasan de una columna en móvil a varias en escritorio.  
\- \*\*Unidades relativas:\*\* \`rem\`, \`%\`, \`vw\` y \`clamp()\` para tipografías y espaciados fluidos.  
\- \*\*Variables CSS:\*\* colores, tipografías y espaciados en \`:root\`, para mantener la coherencia con la guía de estilo.

\#\# Imágenes adaptativas

\#\#\# \`\<picture\>\`  
Lo usé para servir el formato más eficiente que soporte el navegador (\*\*AVIF → WebP → respaldo\*\*) y, cuando hacía falta, un recorte distinto según el tamaño de pantalla (\*art direction\*).

\#\#\# \`srcset\` y \`sizes\`  
Cada imagen tiene varias versiones de ancho distinto. Con \`srcset\` indico las versiones disponibles y con \`sizes\` cuánto ocupa la imagen en cada pantalla, para que el navegador descargue solo la que necesita.

\#\#\# \`loading="lazy"\`  
Las imágenes que no se ven al abrir la página se cargan de forma diferida, solo cuando el usuario se acerca a ellas al hacer \*scroll\*. La imagen principal (\*hero\*) \*\*no\*\* lleva \*lazy\*, sino \`fetchpriority="high"\`, porque es lo primero que se ve y tiene que aparecer cuanto antes.

\#\#\# \`width\` y \`height\`  
Todas las imágenes indican sus dimensiones. Así el navegador reserva el espacio antes de que carguen y el contenido no "salta" (evita el \*Cumulative Layout Shift\*).

\# PadelSlot · Entrega de medios (T-3.6)

\#\# Objetivo

Que las imágenes, los vídeos y los audios de la web \*\*se descarguen una sola vez\*\* y que los vídeos \*\*se puedan adelantar sin esperar\*\* a que se descarguen enteros.

Para conseguirlo hemos creado un servidor con \*\*Express\*\* que sirve la web y controla cómo se entregan estos archivos.

\#\# Cómo arrancar la web

\`\`\`bash  
cd PadelSlot  
npm install      \# solo la primera vez  
npm run dev  
\`\`\`

Abre \*\*http\://localhost:3000\*\*. Para pararlo, pulsa \`Ctrl \+ C\`.

\> La web ya no se abre con doble clic en el HTML: hay que arrancar el servidor.

\---

\#\# Fase 1 · Estructura de directorios

\*\*Qué hemos hecho:\*\*

\- Movido toda la web a la carpeta \`public/\`, que es lo único que publica el servidor. Así nadie puede descargar \`server.js\` ni otros archivos internos.  
\- Ordenado los medios por tipo:

\`\`\`  
public/assets/  
├── img/      ← imágenes (convenios, logo, pistas)  
├── video/    ← vídeo, póster y subtítulos  
└── audio/    ← música de fondo  
\`\`\`

\- Dividido la antigua carpeta \`assets/media/\` entre \`video/\` y \`audio/\`.  
\- Movido los mockups y el boceto a \`docs/\`. Ninguna página los usaba y añadían 13 MB a la web.

\---

\#\# Fase 2 · Cabeceras de caché

\*\*Qué hemos hecho:\*\* configurar el servidor para que indique al navegador cuánto tiempo puede guardar cada archivo, mediante la cabecera \`Cache-Control\`.

\| Archivo \| Cuánto lo guarda el navegador \| Cabecera \|  
\|---\|---\|---\|  
\| Imágenes, vídeo y audio \| 1 año \| \`public, max-age=31536000, immutable\` \|  
\| SVG y JS \| 1 día. Después pregunta si ha cambiado y, si no, el servidor responde \`304\` sin reenviarlo (ETag) \| \`public, max-age=86400, must-revalidate\` \|  
\| Páginas HTML \| Siempre comprueba si hay versión nueva \| \`no-cache\` \|

\*\*Por qué un año es seguro:\*\* cada imagen, vídeo y audio lleva en el nombre un \*\*hash\*\*, un código calculado a partir de su contenido:

\`\`\`  
pista-club-1-480.webp  →  pista-club-1-480.64f6c280.webp  
\`\`\`

\- Si el archivo \*\*no cambia\*\*, el nombre tampoco, y el navegador usa la copia que ya tiene.  
\- Si el archivo \*\*cambia\*\*, cambia el hash y por tanto el nombre, y el navegador descarga la versión nueva.

Hemos renombrado así 47 archivos, y las rutas de los 19 HTML se han actualizado automáticamente.

\---

\#\# Fase 3 · Peticiones parciales (Byte-Range)

\*\*Qué hemos hecho:\*\* comprobar que el servidor entrega los vídeos y audios \*\*por trozos\*\*.

Cuando el usuario mueve la barra de reproducción, el navegador pide solo la parte que necesita y el servidor responde \`206 Partial Content\` con esos bytes. Así se puede adelantar o retroceder al instante, sin descargar el archivo completo.

También hemos comprobado que el MP4 tiene su índice al principio del archivo (\*faststart\*), para que empiece a reproducirse sin esperar.

\---

\#\# Comprobación

Con el servidor arrancado, en otra terminal:

\`\`\`bash  
node scripts/verify-media.mjs \--base http\://localhost:3000 \--img-hashed /assets/img/logo/logo-padelslot-64.996e66d5.webp \--img /assets/svg/logo-padelslot.svg \--video /assets/video/video-partido.d2be86a7.mp4 \--audio /assets/audio/musica-fondo.57b1438f.mp3  
\`\`\`

\*\*Resultado: 34 OK, 0 fallos.\*\*

\| Fase \| Qué se comprueba \| Resultado \|  
\|---\|---\|---\|  
\| 1 \| Un archivo que no existe devuelve \`404\` \| ✔ \|  
\| 2 \| Caché de 1 año en archivos con hash y de 1 día en el resto \| ✔ \|  
\| 2 \| El servidor responde \`304\` si el archivo no ha cambiado \| ✔ \|  
\| 3 \| Vídeo y audio responden \`206\` al principio, a mitad y al final \| ✔ \|

\---

\#\# 3.7 \- Implementación de accesibilidad multimedia (alt, \`\<track\>\` WebVTT, controles teclado)  
\#\#\# Alternativas textuales en imágenes (alt)

Las imágenes no pueden verse con un lector de pantalla, así que cada \`\<img\>\` necesita un atributo \*\*alt\*\* que diga lo mismo con palabras (criterio \*\*WCAG 1.1.1\*\* «Contenido no textual») \[12\]. Pero no todas las imágenes necesitan el mismo texto, ya que algunas aportan información y otras solo decoran o repiten algo que ya está escrito al lado. Por ello, hemos revisado las 37 etiquetas \`\<img\>\` de las 19 páginas y las hemos clasificado según la función que cumple cada una.

\| Tipo de imagen \| Nº \| Dónde aparece \| Valor del alt \| Ejemplo \|  
\| :--- \| :---: \| :--- \| :--- \| :--- \|  
\| Fotografías informativas \| 6 \| index.html (pistas) y cuotas.html (convenios) \| Descripción breve de lo que se ve \| alt="Terraza exterior con sombrillas, mesas y sillas" \|  
\| Logotipo junto al texto «PadelSlot» \| 30 \| Cabeceras y barras laterales de todas las páginas \| Vacío \| alt=""\|  
\| Logotipo sin texto al lado \| 1 \| Carné de socio (cuotas.html) \| Nombre de la marca \| alt="PadelSlot" \|

\- \*\*Fotografías informativas\*\*: Las tres fotos de pistas de la página de inicio y las tres de convenios de la página de cuotas enseñan al usuario cómo son las instalaciones y los servicios del club. Si no las ve, pierde esa información, así que su \*\*alt\*\* describe en pocas palabras lo que aparece: el tipo de pista, el entorno o la actividad (por ejemplo, «Pista de pádel de cristal rodeada de césped»). Hemos evitado empezar con «imagen de…» o «foto de…», porque el lector de pantalla ya anuncia que es una imagen.

\- \*\*Logotipo junto al texto\*\*: En la cabecera y en la barra lateral el logotipo va dentro de un enlace que ya contiene el texto «PadelSlot». Si el logo tuviera \*\*alt="PadelSlot"\*\*, el lector de pantalla diría el nombre dos veces («enlace, PadelSlot PadelSlot»). Con \*\*alt=""\*\* la imagen se ignora y el enlace se anuncia una sola vez. Es la técnica \*\*H2\*\* de \*\*WCAG\*\* para combinar en un mismo enlace una imagen y su texto. No se trata de que falte el atributo: el \*\*alt\*\* está puesto y vacío a propósito, que es la forma correcta de marcar una imagen como decorativa.

\- \*\*Logotipo sin texto al lado\*\*: En el carné de socio el logotipo aparece solo, sin texto que lo acompañe. Ahí sí identifica al club, así que lleva \*\*alt="PadelSlot"\*\*. No hemos añadido la palabra «logo»: al usuario le importa saber de qué marca es el carné, no que la imagen sea un logotipo.

Además, los iconos SVG del sistema de iconos llevan \*\*aria-hidden="true"\*\* y \*\*focusable="false"\*\*. Siempre van junto a un texto que dice lo mismo («Inicio», «Reservas»…), así que el lector de pantalla los ignora y no repite información.

En resumen, las 37 imágenes del proyecto tienen un \*\*alt\*\* adecuado a su función: descriptivo en las 6 que aportan información, vacío en los 30 logotipos que ya van acompañados de texto y con el nombre de la marca en el único logotipo que aparece solo. Ninguna imagen se queda sin alternativa ni repite información de forma innecesaria, así que en este apartado no ha hecho falta cambiar el código y se cumple el criterio \*\*WCAG 1.1.1\*\*.

\#\#\# Subtítulos y descripción del contenido multimedia

La página de inicio tiene dos elementos multimedia: un \*\*vídeo de 12 segundos grabado con dron\*\* y una \*\*pista de música de la misma duración\*\* que se puede reproducir aparte. Las personas que no pueden ver o no pueden oír se perderían lo que transmiten, así que cada uno necesita una alternativa en texto (criterio \*\*WCAG 1.2.1\*\*, \*Solo audio y solo vídeo pregrabados\*) \[13\]. Como cada elemento es distinto, la alternativa que le corresponde también lo es.

\| Elemento \| Contenido \| Alternativa aplicada \| Cómo se ha implementado \|  
\| :--- \| :--- \| :--- \| :--- \|  
\| Vídeo video-partido \| Imagen de un partido grabado con dron, sin pista de sonido \| Subtítulos descriptivos sincronizados y descripción en texto \| Archivo video-partido-es.vtt enlazado con \`\<track\>\` y bloque desplegable \`\<details\>\` \|  
\| Audio \`musica-fondo\` \| Música instrumental de rock, sin letra \| Descripción en texto \| El mismo bloque \`\<details\>\` \|

\- \*\*Subtítulos del vídeo.\*\* Hemos creado el archivo \*\*assets/media/video-partido-es.vtt\*\* en formato \*\*WebVTT\*\*, el estándar que usan los navegadores para los subtítulos. \*\*Divide el vídeo en tres tramos de 4 segundos y describe lo que se ve en cada uno\*\*: el partido visto desde arriba, el dron elevándose y el plano general de la pista. Como el vídeo no tiene sonido, el primer subtítulo empieza con «\[Vídeo sin sonido\]» para que \*\*nadie piense que le falla el audio\*\*. El archivo se enlaza dentro de la etiqueta \`\<video\>\`:

\`\<track kind="captions" src="assets/media/video-partido-es.vtt" srclang="es" label="Español" default\>\`

\*\*kind="captions"\*\* indica que son subtítulos, \*\*srclang\*\* y \*\*label\*\* dan el idioma y el nombre que aparece en el menú del reproductor, y \*\*default\*\* hace que salgan activados desde el principio sin que el usuario tenga que buscarlos.

\- \*\*Descripción del vídeo y de la música.\*\* Los lectores de pantalla no leen los subtítulos que aparecen sobre el vídeo, y la música no tiene subtítulos. Por eso hemos añadido debajo del reproductor un bloque desplegable \`\<details\>\` titulado «Descripción del vídeo y de la música». Describe el vídeo en un párrafo e indica el título, el autor y el estilo de la música, aclarando que es instrumental. \`\<details\>\` es un elemento nativo de HTML: se abre con el ratón o con el teclado (Enter o Espacio) sin necesidad de JavaScript y no ocupa espacio mientras está cerrado.

Para \*\*verificar\*\* que todo va correctamente, hemos comprobado que los \*\*subtítulos\*\* aparecen sobre el vídeo y cambian cada 4 segundos, que la opción «Español» aparece en el \*\*menú del reproductor\*\*, que el desplegable se abre con el teclado \*\*(Enter o Espacio)\*\* y que la consola \*\*no muestra errores\*\*. En resumen, con la implementación de subtítulos con \`\<track kind="captions"\>\` y transcripción de los elementos no textuales, se cumple el criterio \*\*WCAG 1.2.1 de accesibilidad de audios y vídeos sin sonido\*\*.

\*\*IMPORTANTE\*\*: Los subtítulos solo se cargan si la página se sirve desde un servidor (http\://). Si lo probamos con doble clic (file://), el navegador bloquea el archivo .vtt por seguridad.

\#\#\# Navegación por teclado, foco visible y contraste

Hay personas que no pueden usar el ratón y navegan solo con el teclado: pasan de un elemento a otro con Tab y los activan con Enter o la barra espaciadora. Para que puedan hacerlo, \*\*todos los controles\*\* tienen que poder alcanzarse con el teclado (criterio \*\*WCAG 2.1.1\*\*, \*Teclado\*) \[14\] y el elemento activo tiene que estar siempre marcado de forma visible (criterio \*\*WCAG 2.4.7\*\*, \*Foco visible\*) \[15\]. Además, el texto debe contrastar lo suficiente con el fondo para que se pueda leer bien (criterio \*\*WCAG 1.4.3\*\*, \*Contraste mínimo\*) \[16\]. Hemos recorrido las páginas usando solo el teclado, con especial atención a los \*\*reproductores de vídeo y audio\*\*, y hemos medido el \*\*contraste de los colores\*\* de la guía de estilo.

\| Elemento \| Teclas probadas \| Antes \| Después \|  
\| :--- \| :--- \| :--- \| :--- \|  
\| Enlaces de navegación \| Tab, Mayús+Tab, Enter \| Alcanzables y con foco visible \| Sin cambios \|  
\| Botones y campos de formulario \| Tab, Enter, Espacio, flechas \| Alcanzables, pero sin foco visible \| Contorno de foco visible \|  
\| Reproductor de vídeo (reproducir, pausar, volumen, pantalla completa y menú) \| Tab, Enter, Espacio, Esc \| Funcionaban; foco poco visible \| Funcionan con foco visible \|  
\| Reproductor de audio (reproducir, pausar y volumen) \| Tab, Enter, Espacio \| Funcionaban; foco poco visible \| Funcionan con foco visible \|  
\| Desplegable «Descripción del vídeo y de la música» \| Tab, Enter, Espacio \| — (se añade en este sprint) \| Se abre y se cierra con el teclado \|  
\| Color del texto general (\`\$color-texto\`) \| — \| Contraste 2,83:1 ❌ \| Contraste 5,71:1 ✅ \|

\- \*\*Foco visible\*\*: Al recorrer las páginas con \*\*Tab\*\*, en los enlaces sí se veía dónde estaba el foco, pero en \*\*muchos botones\*\* y \*\*campos de formulario no\*\*: el usuario perdía la referencia, sobre todo en los \*\*formularios de reserva\*\* y de \*\*inicio de sesión\*\*. La causa estaba en \*\*\_reseteo.scss\*\*, que quitaba el contorno de foco (\`outline: none\`) a \*\*button\*\*, \*\*input\*\*, \*\*select\*\* y \*\*textarea\*\*. En vez de modificar el reseteo, hemos creado el parcial \*\*scss/componentes/\_accesibilidad.scss\*\* con una regla general \`:focus-visible\`: un contorno verde oscuro (\`$color-primario`)de3pxseparado2pxdelelemento,conuncontrastede8,1:1sobreblanco(WCAGpidealmenos3:1paraindicadoresgráficos).Sobrelosfondosverdeoscuro(piedepágina,bandasverdes,botónprimarioybloquedelvídeo)elcontornocambiaaverdelima(**$color-terciario\*\*, 6,45:1), porque el verde sobre verde no se vería. Hemos usado \`:focus-visible\` y no \`:focus\` para que el contorno aparezca solo al navegar con el teclado y no al hacer clic con el ratón. El parcial se importa al final de \*\*main.scss\*\*, para que sus reglas no las pisen los estilos de las páginas.

\- \*\*Controles multimedia\*\*: El vídeo y el audio usan los \*\*controles nativos del navegador\*\* (atributo \`controls\`). Hemos comprobado que con \*\*Tab\*\* se llega a \*\*reproducir\*\*, \*\*volumen\*\*, \*\*pantalla completa\*\* y al \*\*menú de opciones\*\* (donde están los subtítulos), que todos se activan con \*\*Enter\*\* o \*\*Espacio\*\* y que de la pantalla completa se sale con Esc. El desplegable de descripción añadido en el apartado anterior es un \`\<details\>\` nativo y también se abre y se cierra con \*\*Enter\*\* o \*\*Espacio\*\*.

\- \*\*Contraste del texto\*\*: El color de texto general de la guía de estilo, \`\#9f9898\`, tenía un contraste de 2,83:1 sobre blanco y de 2,66:1 sobre el fondo gris claro, por debajo del mínimo de 4,5:1 que exige el nivel AA. Afectaba a buena parte del texto de todas las páginas, y herramientas como \*\*Lighthouse\*\* y \*\*WAVE\*\* lo marcan como \*\*error\*\*. Hemos propuesto sustituirlo por \`\#6b6565\`, el mismo gris cálido pero más oscuro, que alcanza \*\*5,71:1\*\*. (Como es un cambio en la guía de estilo, lo hemos consensuado en el equipo y lo ha aprobado el PO / UI Lead, responsable de ello según la organización de este sprint)

Finalmente, todos los elementos interactivos de la web, incluidos los reproductores de vídeo y audio y el desplegable de descripción, se pueden usar solo con \*\*Tab\*\*, \*\*Enter\*\*, \*\*Espacio\*\* y \*\*Esc\*\*, y muestran siempre un \*\*indicador de foco\*\* claramente visible gracias a \`:focus-visible\`. Con todo lo anterior más el nuevo color de texto (\*\*WCAG AA\*\*), el contenido supera los criterios \*\*WCAG 2.1.1, 2.4.7 y 1.4.3\*\*.

\#\# REFERENCIAS IEEE

$12$  
Claudia, “Guía para principiantes: WCAG 1.1.1 y el secreto del contenido no textual accesible,” \*Fundación itgrarte\*, 23/03/2026.  
$Enlínea$  
. Disponible en: \[https\://www\.itgrarte.org/accesibilidad/guia-principiantes-wcag-1-1-1-contenido-no-textual/\](https\://www\.itgrarte.org/accesibilidad/guia-principiantes-wcag-1-1-1-contenido-no-textual/)  
$Consultado:23/11/2026$  
.

$13$  
Claudia, “WCAG 1.2.1: Guía para hacer accesibles audios y videos sin sonido,” \*Fundación itgrarte\*, 30/03/2026.  
$Enlínea$  
. Disponible en: \[https\://www\.itgrarte.org/accesibilidad/guia-wcag-1-2-1-audio-video-solo-lectura/\](https\://www\.itgrarte.org/accesibilidad/guia-wcag-1-2-1-audio-video-solo-lectura/)  
$Consultado:24/11/2026$  
.

$14$  
Asociación por la Defensa del Derecho a la Accesibilidad Web (ADDAW), “2.1.1 \- Teclado,” \*ADDAW\*.  
$Enlínea$  
. Disponible en: \[https\://addaw.org/es/wcag/Teclado\](https\://addaw.org/es/wcag/Teclado)  
$Consultado:25/11/2026$  
.

$15$  
Asociación por la Defensa del Derecho a la Accesibilidad Web (ADDAW), “2.4.7 \- Foco visible,” \*ADDAW\*.  
$Enlínea$  
. Disponible en: \[https\://addaw.org/es/wcag/Foco-visible\](https\://addaw.org/es/wcag/Foco-visible)  
$Consultado:25/11/2026$  
.

$16$  
Asociación por la Defensa del Derecho a la Accesibilidad Web (ADDAW), “1.4.3 \- Contraste mínimo,” \*ADDAW\*.  
$Enlínea$  
. Disponible en: \[https\://addaw.org/es/wcag/Contraste-minimo\](https\://addaw.org/es/wcag/Contraste-minimo)  
$Consultado:25/11/2026$  
.  
\#\# 3.8 \- Auditoría de rendimiento (Lighthouse LCP/CLS), pruebas multinavegador y validación W3C

\#\#\# Validación W3C del HTML y el CSS

Un código que cumple el estándar se interpreta igual en todos los navegadores y en los lectores de pantalla, y es la base para que el resto de la auditoría sea fiable. Por eso, el Hito 3.3 exige que el código valide sin errores en el validador oficial del W3C \[17\], con especial atención al anidamiento de las etiquetas multimedia (\`\<picture\>\`, \`\<source\>\` y \`\<track\>\`). Hemos pasado las 19 páginas HTML del proyecto una a una por el validador y la hoja de estilos compilada (\`scss/main.css\`) por el validador de CSS del W3C. Cada error o aviso se ha corregido con la solución más semántica posible y sin cambiar el aspecto de la web. Después, cada página se ha vuelto a validar y se ha revisado visualmente con Live Server.

\| Archivo \| Errores encontrados \| Avisos encontrados \| Corrección aplicada \| Resultado final \|  
\| :--- \| :---: \| :---: \| :--- \| :---: \|  
\| \`anadirClaseAdmin.html\` \| 0 \| 0 \| Ninguna \| ✅ 0 errores, 0 avisos \|  
\| \`bloquearPistaAdmin.html\` \| 6 \| 0 \| \`\<p\>\`→\`\<span class="panel-admin\_\_seleccionable-texto"\>\` dentro de los \`\<label\>\` (y la clase añadida a la regla del SCSS) \| ✅ 0 errores, 0 avisos \|  
\| \`clases.html\` \| 0 \| 3 \| Títulos \`\<h3\>\` en las 3 tarjetas del resumen del alumno (dos visibles y uno oculto con \`.solo-lector\`) y un \`\<h2\>\` oculto en la sección \| ✅ 0 errores, 0 avisos \|  
\| \`cobroAdmin.html\` \| 6 \| 0 \| Contenedor \`\<span class="panel-admin\_\_persona"\>\`→\`\<div\>\` para que pueda contener el \`\<p\>\` \| ✅ 0 errores, 0 avisos \|  
\| \`configAdmin.html\` \| 0 \| 0 \| Ninguna \| ✅ 0 errores, 0 avisos \|  
\| \`crearReservaAdmin.html\` \| 14 \| 0 \| \`\<p\>\`→\`\<span class="panel-admin\_\_seleccionable-texto"\>\` dentro de los \`\<label\>\` \| ✅ 0 errores, 0 avisos \|  
\| \`cuadranteAdmin.html\` \| 0 \| 28 \| \`\<article\>\`→\`\<p\>\` en las 28 reservas del cuadrante (la tabla aporta el contexto con \`\<th scope\>\`) \| ✅ 0 errores, 0 avisos \|  
\| \`cuotas.html\` \| 0 \| 4 \| \`\<h2\>\` oculto en el carné digital; \`\<span\>\`→\`\<h3\>\` en la tarjeta de la tarifa; \`aria-label\` en las 2 secciones que agrupan tarjetas \| ✅ 0 errores, 0 avisos \|  
\| \`incidenciasAdmin.html\` \| 0 \| 0 \| Ninguna \| ✅ 0 errores, 0 avisos \|  
\| \`index.html\` \| 4 \| 3 \| \`aria-hidden\` / \`role="img"\` en las estrellas de valoración; \`\<article\>\`→\`\<figure\>\` y \`\<footer\>\`→\`\<figcaption\>\` en las opiniones \| ✅ 0 errores, 0 avisos \|  
\| \`inicioAdmin.html\` \| 0 \| 0 \| Ninguna \| ✅ 0 errores, 0 avisos \|  
\| \`inicioSesionSocio.html\` \| 0 \| 0 \| Ninguna \| ✅ 0 errores, 0 avisos \|  
\| \`inicioSocio.html\` \| 0 \| 1 \| \`aria-label="Información del club"\` en la sección de información del club \| ✅ 0 errores, 0 avisos \|  
\| \`landingPage.html\` \| 0 \| 2 \| \`aria-label\` en las 2 tarjetas \`\<section\>\` (invitado y ayuda) \| ✅ 0 errores, 0 avisos \|  
\| \`progSemanalAdmin.html\` \| 0 \| 0 \| Ninguna \| ✅ 0 errores, 0 avisos \|  
\| \`reservaNoSocio.html\` \| 0 \| 0 \| Ninguna \| ✅ 0 errores, 0 avisos \|  
\| \`servicios.html\` \| 0 \| 0 \| Ninguna \| ✅ 0 errores, 0 avisos \|  
\| \`serviciosAdmin.html\` \| 0 \| 0 \| Ninguna \| ✅ 0 errores, 0 avisos \|  
\| \`sociosAdmin.html\` \| 8 \| 1 \| Contenedor \`\<span class="panel-admin\_\_persona"\>\`→\`\<div\>\`; \`\<h2\>\` oculto en la ficha del socio \| ✅ 0 errores, 0 avisos \|  
\| \`scss/main.css\` \| 0 \| — \| Ninguna \| ✅ 0 errores \|  
\| \*\*Total\*\* \| \*\*38\*\* \| \*\*42\*\* \| \| \*\*✅ 20 de 20 archivos válidos\*\* \|

Los 38 errores y 42 avisos encontrados se dividen en tres tipos:

\- \*\*Anidamiento incorrecto (34 errores).\*\* Había párrafos (\`\<p\>\`) dentro de elementos que solo admiten contenido en línea: dentro de un \`\<label\>\` en las tarjetas seleccionables de los formularios de reserva y bloqueo de pistas, y dentro de un \`\<span\>\` en las celdas de socio de las tablas de cobros y socios. En los \`\<label\>\` hemos cambiado el \`\<p\>\` por un \`\<span\>\` con clase propia y hemos aplicado a esa clase el estilo que tenía el \`\<p\>\`. En las tablas hemos hecho lo contrario: el \`\<p\>\` se queda y el contenedor \`\<span\>\` pasa a ser un \`\<div\>\`, que sí puede contener párrafos. Usamos \`\<div\>\` porque ese bloque no tiene un significado propio: lo aporta la celda de la tabla (\`\<td\>\`), y HTML5 reserva \`\<div\>\` precisamente para estos agrupamientos sin semántica.

\- \*\*Atributo ARIA no permitido (4 errores).\*\* Las estrellas de valoración de la página de inicio llevaban \`aria-label\` en un \`\<span\>\`, algo que el estándar prohíbe si el elemento no tiene un \`role\`. En las opiniones les hemos añadido \`role="img"\` con la etiqueta «5 de 5 estrellas». En la valoración media las hemos ocultado al lector de pantalla con \`aria-hidden="true"\`, porque la nota «4,7» ya está escrita y la etiqueta anterior («5 estrellas») no coincidía con ella.

\- \*\*Secciones y artículos sin título (42 avisos).\*\* Los elementos \`\<article\>\` y \`\<section\>\` deberían tener un título que los identifique. Lo hemos resuelto según el caso, buscando siempre la etiqueta que mejor describe el contenido. Si el texto que hacía de título ya existía, lo hemos convertido en un \`\<h3\>\` (tarifa y tarjetas del resumen del alumno). Si no había título visible, hemos añadido uno oculto con la clase \`.solo-lector\` (carné digital y ficha del socio). Las secciones que solo agrupan tarjetas con título propio reciben un nombre con \`aria-label\`. Las opiniones de los usuarios pasan a ser \`\<figure\>\` con \`\<blockquote\>\` y \`\<figcaption\>\`, que es la estructura de HTML para una cita con su autor. Las 28 reservas del cuadrante pasan a ser \`\<p\>\`, porque su contexto (pista y franja horaria) ya lo dan los encabezados de la tabla, y 28 títulos dentro de una tabla entorpecerían la navegación por títulos de los lectores de pantalla.

Ninguno de los errores afectaba a las etiquetas multimedia: los \`\<picture\>\`, \`\<source\>\`, \`\<video\>\`, \`\<audio\>\` y \`\<track\>\` validaban correctamente desde el principio. Todos los cambios se han comprobado visualmente y la web se ve igual que antes.

En conclusión, las 19 páginas HTML del proyecto validan sin errores ni avisos y la hoja de estilos \`main.css\` valida sin errores, así que se cumple el requisito de validación W3C del Hito 3.3. Además, varias correcciones mejoran la accesibilidad: los lectores de pantalla anuncian ahora las secciones con nombre y la nota correcta de las valoraciones, y siguen una estructura de títulos ordenada.

\#\#\# Auditoría de rendimiento y accesibilidad (Lighthouse)

Hemos pasado Lighthouse a \`index.html\`, la página con más contenido multimedia, en una ventana de incógnito de Chrome, simulando un móvil con red 4G lenta. Para el resto de páginas hemos medido las mismas métricas (LCP y CLS) con Chrome en las mismas condiciones y hemos revisado el contraste de todos los textos teniendo en cuenta las transparencias. En general, la web está cerca del objetivo: el CLS es 0 en todas las páginas y el LCP está por debajo de 1,5 s en todas salvo en \`index.html\`. Hay tres causas que la alejan del objetivo: las fuentes de Google Fonts (mueven la página y retrasan el título principal), el póster del vídeo, que pesa demasiado, y tres textos blancos semitransparentes con poco contraste. Las tres tienen una solución sencilla, que se detalla abajo.

\#\#\#\# Resultado de Lighthouse en \`index.html\`

\| Métrica \| Resultado \| Objetivo \| Estado \|  
\| :--- \| :---: \| :---: \| :---: \|  
\| Performance \| 78 \| ≥ 90 \| ❌ \|  
\| Accessibility \| 96 \| 100 \| ❌ \|  
\| LCP (\*Largest Contentful Paint\*) \| 4,1 s \| \< 2,5 s \| ❌ \|  
\| CLS (\*Cumulative Layout Shift\*) \| 0,162 \| \< 0,1 \| ❌ \|  
\| FCP (\*First Contentful Paint\*) \| 2,0 s \| — \| — \|  
\| TBT (\*Total Blocking Time\*) \| 0 ms \| — \| ✅ \|  
\| Speed Index \| 2,0 s \| — \| ✅ \|

\| Problema detectado \| Causa (según Lighthouse) \| Cambio necesario \|  
\| :--- \| :--- \| :--- \|  
\| CLS de 0,162 \| La tarjeta «Pistas cerca de ti» se desplaza (0,133 \+ 0,029) al cambiar la fuente del sistema por la de Google Fonts \| Cargar las fuentes con \`display=optional\` en lugar de \`display=swap\` (19 HTML) \|  
\| LCP de 4,1 s \| El título \`h1\` espera a dos archivos que bloquean el renderizado: Google Fonts (790 ms) y \`main.css\` (1.060 ms) \| El mismo cambio de las fuentes. Opcionalmente, compilar \`main.css\` comprimido (ahorro de 15 KiB) \|  
\| Imagen 191 KiB más pesada de lo necesario \| \`video-partido-poster.webp\` pesa 204 KiB y mide 1280×720, pero se muestra a 380×214 \| Sustituirlo por una versión de 768×432 (58 KiB) \|  
\| Contraste insuficiente (Accessibility 96\) \| Dos textos del pie en blanco al 60 % sobre verde: 4,08:1 \| Subir la opacidad al 80 % en \`\_inicio-publico.scss\` (5,87:1) \|

\#\#\#\# Resultados del resto de páginas

Medición con Chrome en modo móvil (red 4G lenta y CPU 4 veces más lenta). En este entorno no se cargaron las fuentes de Google, así que los valores reflejan la página \*\*sin\*\* el efecto de las fuentes: en \`index.html\`, Lighthouse añadió unos 2 s al LCP y todo el CLS por culpa de ellas. Como las 19 páginas cargan las fuentes igual, se espera el mismo efecto en todas hasta que se aplique \`display=optional\`.

\| Página \| LCP \| CLS \| Peso transferido \| Contraste \| Qué hay que cambiar \|  
\| :--- \| :---: \| :---: \| :---: \| :---: \| :--- \|  
\| \`anadirClaseAdmin.html\` \| 1,35 s \| 0 \| 190 KB \| ✅ \| Solo el cambio general de fuentes \|  
\| \`bloquearPistaAdmin.html\` \| 1,37 s \| 0 \| 193 KB \| ✅ \| Solo el cambio general de fuentes \|  
\| \`clases.html\` \| 1,30 s \| 0 \| 187 KB \| ✅ \| Solo el cambio general de fuentes \|  
\| \`cobroAdmin.html\` \| 1,30 s \| 0 \| 191 KB \| ✅ \| Solo el cambio general de fuentes \|  
\| \`configAdmin.html\` \| 1,31 s \| 0 \| 192 KB \| ✅ \| Solo el cambio general de fuentes \|  
\| \`crearReservaAdmin.html\` \| 1,28 s \| 0 \| 190 KB \| ✅ \| Solo el cambio general de fuentes \|  
\| \`cuadranteAdmin.html\` \| 1,38 s \| 0 \| 199 KB \| ✅ \| Solo el cambio general de fuentes \|  
\| \`cuotas.html\` \| 1,46 s \| 0 \| 224 KB \| ✅ \| Solo el cambio general de fuentes \|  
\| \`incidenciasAdmin.html\` \| 1,31 s \| 0 \| 190 KB \| ✅ \| Solo el cambio general de fuentes \|  
\| \`index.html\` \| 2,14 s \| 0 \| 414 KB \| ❌ 2 textos (4,08:1) \| Fuentes, póster del vídeo y opacidad del pie (ver tabla anterior) \|  
\| \`inicioAdmin.html\` \| 1,29 s \| 0 \| 196 KB \| ✅ \| Solo el cambio general de fuentes \|  
\| \`inicioSesionSocio.html\` \| 1,30 s \| 0 \| 173 KB \| ✅ \| Solo el cambio general de fuentes \|  
\| \`inicioSocio.html\` \| 1,29 s \| 0 \| 188 KB \| ✅ \| Solo el cambio general de fuentes \|  
\| \`landingPage.html\` \| 1,26 s \| 0 \| 176 KB \| ❌ 1 texto (4,17:1) \| Fuentes y opacidad del texto bajo la barra de progreso: \`.acceso\_\_mini-pie\` del 70 % al 85 % en \`\_acceso.scss\` (5,28:1) \|  
\| \`progSemanalAdmin.html\` \| 1,35 s \| 0 \| 195 KB \| ✅ \| Solo el cambio general de fuentes \|  
\| \`reservaNoSocio.html\` \| 1,30 s \| 0 \| 189 KB \| ✅ \| Solo el cambio general de fuentes \|  
\| \`servicios.html\` \| 1,28 s \| 0 \| 180 KB \| ✅ \| Solo el cambio general de fuentes \|  
\| \`serviciosAdmin.html\` \| 1,34 s \| 0 \| 192 KB \| ✅ \| Solo el cambio general de fuentes \|  
\| \`sociosAdmin.html\` \| 1,28 s \| 0 \| 190 KB \| ✅ \| Solo el cambio general de fuentes \|

\#\#\#\# Resumen de cambios pendientes

\| Prioridad \| Cambio \| Dónde \| Mejora \|  
\| :---: \| :--- \| :--- \| :--- \|  
\| 1 \| \`\&display=swap\` → \`\&display=optional\` en el enlace de Google Fonts \| Los 19 HTML \| CLS y LCP de todas las páginas \|  
\| 2 \| Póster del vídeo a 768×432 (de 204 KiB a 58 KiB) \| \`assets/media/video-partido-poster.webp\` \| Peso y LCP de \`index.html\` \|  
\| 3 \| Opacidad del texto del pie del 60 % al 80 % \| \`\_inicio-publico.scss\` (líneas 587 y 610\) \| Contraste de \`index.html\` \|  
\| 4 \| Opacidad de \`.acceso\_\_mini-pie\` del 70 % al 85 % \| \`\_acceso.scss\` (línea 251\) \| Contraste de \`landingPage.html\` \|  
\| 5 (opcional) \| Compilar \`main.css\` en modo comprimido \| Configuración de Live Sass Compiler \| 15 KiB menos de CSS en todas las páginas \|

Avisos de Lighthouse que se justifican y no se cambian:

\- \*\*Reduce unused CSS (74 KiB):\*\* usamos una sola hoja de estilos para las 19 páginas. Se descarga una vez y el resto de páginas la toman de la caché.  
\- \*\*No compression applied:\*\* Live Server no comprime los archivos. Un servidor de producción, como el previsto en T-3.6 o Vercel, sí lo hace.  
\- \*\*Render-blocking \`main.css\`:\*\* es la hoja de estilos de la web. Sin ella la página aparecería sin diseño, así que es normal que bloquee el primer pintado.

\#\#\# Pruebas multinavegador

Cada navegador usa un motor distinto para mostrar las páginas y no todos admiten los mismos formatos de imagen, vídeo y audio. Por eso la web ofrece cada recurso en varios formatos, del más moderno al más compatible, y el navegador elige el primero que sabe usar. El Sprint 3 pide comprobar que esto funciona en los tres motores principales: \*\*Chromium\*\* (Chrome y Edge), \*\*Gecko\*\* (Firefox) y \*\*WebKit\*\* (Safari). Hemos probado \`index.html\`, que reúne fotos, vídeo, audio y subtítulos, y las fotos de convenios de \`cuotas.html\`, tanto en vista móvil como en escritorio.

\| Recurso \| Formatos ofrecidos (por orden) \| Respaldo final \|  
\| :--- \| :--- \| :--- \|  
\| Fotos de pistas y convenios (6) \| AVIF → WebP \| \`\<img\>\` en WebP \|  
\| Logotipos (31) \| SVG → AVIF \| \`\<img\>\` en WebP \|  
\| Vídeo \`video-partido\` \| WebM → MP4 \| Texto «Tu navegador no admite vídeo HTML5» \|  
\| Música \`musica-fondo\` \| OGG → MP3 \| Texto «Tu navegador no admite audio HTML5» \|

\| Motor \| Navegador \| Imagen \| Vídeo \| Audio \| Subtítulos \| Teclado \|  
\| :--- \| :--- \| :---: \| :---: \| :---: \| :---: \| :---: \|  
\| Chromium \| Chrome 153 \| ✅ AVIF \| ✅ WebM \| ✅ OGG \| ✅ \| ✅ \|

\- \*\*Imágenes\*\*: En Chrome, las 6 fotos se descargan en \*\*AVIF\*\* (\`image/avif\`), el formato más ligero, tanto en móvil (versión de 960 px) como en escritorio (versión de 480 px). Lo hemos comprobado en DevTools → \*\*Network\*\*, en la columna \*Type\*. Además, hemos verificado que las imágenes de respaldo en \*\*WebP\*\* se cargan correctamente, por si algún navegador no admite AVIF.

\- \*\*Vídeo y audio\*\*: Chrome elige el \*\*WebM\*\* para el vídeo y el \*\*OGG\*\* para la música, los primeros de cada lista. Lo hemos comprobado con \`document.querySelector('video').currentSrc\` en la consola. También hemos verificado que los archivos de respaldo, \*\*MP4\*\* y \*\*MP3\*\*, se reproducen enteros (12 s), porque son los que usará cualquier navegador que no admita WebM u OGG.

\- \*\*Subtítulos\*\*: La pista de subtítulos se carga activada (\`mode: showing\`), con sus 3 subtítulos en español, y el texto «\[Vídeo sin sonido\] Vista aérea de un partido de dobles en una pista de pádel azul» aparece sobre el vídeo desde el primer segundo.

\- \*\*Teclado\*\*: Con \*\*Tab\*\* se llega al vídeo, al reproductor de música y al desplegable «Descripción del vídeo y de la música», y los tres muestran el contorno de foco (verde oscuro sobre fondo claro, verde lima sobre fondo verde). La barra \*\*Espacio\*\* pausa y reproduce el vídeo y la música, y \*\*Enter\*\* abre el desplegable.

\*\*Navegadores pendientes\*\*: Edge, Firefox y Safari se comprobarán siguiendo los mismos pasos: Network → \*Type\* para el formato de imagen, \`currentSrc\` en la consola para el vídeo y el audio, los subtítulos sobre el vídeo y la navegación con Tab y Espacio. Safari solo puede probarse en un Mac o un iPhone. Si no hay ninguno disponible, se usará la emulación de WebKit de Playwright (\`npx playwright open \--browser=webkit \<url\>\`).

\#\# REFERENCIAS IEEE

$17$  
World Wide Web Consortium (W3C), “The W3C Markup Validation Service,” \*W3C\*, 2024\.  
$Enlínea$  
. Disponible en: \[https\://validator.w3.org/\](https\://validator.w3.org/)  
$Consultado:25/11/2026$  
.  
