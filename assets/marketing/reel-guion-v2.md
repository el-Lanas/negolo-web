# GUION — Cortometraje negolo v2
**"De una web a clientes reales"** · 40s · 9:16 (1080×1920) · 30fps

> Reemplaza al reel anterior (b-roll de IA abstracto). Este se construye con **UI real animada** (webs del portafolio + mockups pixel-perfect), tipografía **Nunito** y **logo en oro sobre ciruela** — la identidad completa de negolo.

---

## Concepto
La cámara vive dentro de las pantallas. Vemos nacer una web, la vemos publicada, la vemos trabajando (clientes que escriben por WhatsApp, pedidos que llegan) y cerramos con los planes y precios. Ritmo de aviso de producto moderno (estilo Linear/Stripe/Apple), música electrónica moderna.

**Tono:** seguro, moderno, limpio. Sin caras generadas por IA, sin b-roll abstracto.

## Especificaciones de marca
- **Tipografía:** Nunito (400/700/800/900) — la del sitio. Display en ExtraBold/Black.
- **Paleta:** ciruela `#2D1B36` y `#3A2447` · oro `#E8B84B` · lavanda `#F5F0F7` · muted `#C9BBD6`.
- **Logo:** wordmark ORO sobre ciruela (modo oscuro, según BRAND.md).
- **Regla:** nada de texto en zonas tapadas por la UI de TikTok/Reels (14% arriba, 35% abajo).

---

## Guión escena por escena

### ESCENA 1 — "El negocio invisible" (0:00–0:04)
**Visual:** Mockup real de un buscador (Google-like, Nunito). Se escribe: *"café de especialidad en Barranco"*. Carga resultados y **el negocio del cliente no está** — solo competencia. Un micro-texto gris: "Tu competencia sí aparece."
**Texto en pantalla:** **"¿Te buscan… y no apareces?"** (Nunito Black, lavanda)
**Animación:** tecleo letra a letra (28 ms/letra) · resultados con stagger 60 ms · la lupa "late" una vez.
**Audio:** pad electrónico entra (Lyria) · un tick por tecla.

### ESCENA 2 — "Manos a la obra" (0:04–0:10)
**Visual:** Transición wipe. Fondo ciruela. Una ventana de navegador vacía se **construye sola**: navbar → hero (título grande + botón oro) → 3 tarjetas de servicios → footer. Grid de guías visible que se desvanece. Barra de "Publicar" → clic → **"✓ En línea"**.
**Texto:** **"La diseñamos a medida"**
**Animación:** cada bloque entra con spring (250 ms) · glow en el botón Publicar.
**Audio:** whooshes + clicks · la música sube un escalón.

### ESCENA 3 — "Webs espectaculares" (0:10–0:18) ← generadas por VEO
**Visual:** 3 tomas cinematográficas de **webs espectaculares** generadas por Veo (modelo de máxima calidad, prompt ultra-detallado): pantallas/monitores grandes en estudios oscuros y elegantes, UI premium en ciruela + oro, luz cinematográfica, cámara con movimiento lento y suave. Sin texto legible en pantalla (la marca y los mensajes los pone el overlay).
**Texto por caso:** **"Landing · 2 días"** / **"Web corporativa · 5 días"** / **"Tienda online · 7 días"**
**Animación:** cortes al ritmo de la música · transición con swish.
**Audio:** punto alto de la música.

### ESCENA 4 — "Empiezan a escribirte" (0:18–0:26) ← el corazón del video
**Visual:** Móvil (mockup iPhone pixel-perfect) con **WhatsApp Business** abierto. Los mensajes entran uno a uno:
- "Hola, vi su web, ¿me pasas precios?" *(entrante)*
- "¿Tienen el combo de 2 disponible?" *(entrante)*
- Push: **"Nuevo pedido #1042 · S/180"**
- Push: "3 nuevas visitas a tu perfil de Google"
**Contador animado:** **"+12 conversaciones hoy"** (count-up)
**Texto:** **"Y empiezan a llegar los clientes"**
**Animación:** burbujas con pop (0.6→1, 180 ms) · vibración del móvil · notificaciones que caen desde arriba.
**Audio:** pings de notificación · la música sostiene.

### ESCENA 5 — "Precios claros" (0:26–0:34) ← planes y precios
**Visual:** Fondo ciruela con glow dorado. Las **3 tarjetas de planes reales** del sitio entran en cascada:
| Plan | Precio (count-up) | Badge |
|---|---|---|
| Landing Page | **S/399** | IGV incluido |
| Web Corporativa ⭐ Más elegido | **S/599** | IGV incluido |
| Tienda Virtual | **S/799** | IGV incluido |
**Texto:** **"Todo incluido: dominio, hosting y correos"**
**Animación:** tarjetas con stagger · precios de 0 → valor final · la del medio se eleva con glow.
**Audio:** un impacto suave por tarjeta.

### ESCENA 6 — "Cierre de marca" (0:34–0:40)
**Visual:** Wordmark **negolo en ORO** sobre ciruela, grande, centrado. Debajo: **"Páginas web que venden"**. Pill dorada: **"Sin pago previo"**. Botón WhatsApp: "Cotiza gratis".
**Animación:** logo con slide-up + glow · pills con spring · el botón "late" una vez.
**Audio:** la música resuelve · ding final.

---

## Producción técnica
| Parte | Cómo se hace |
|---|---|
| Escena 3 | **Veo 3.1** (máxima calidad disponible) — tomas de webs espectaculares |
| Escenas 1, 2, 4, 5, 6 | **Mockups HTML/CSS/JS reales** (pixel-perfect, Nunito) animados y capturados a 30fps |
| Música | **Lyria 3.5** — electrónica moderna, build + drop suave (el vibe del video anterior que sí gustó) |
| Voz en off | **Sí** — TTS español (Perú), voz masculina joven, cálida y segura |
| SFX | Ticks, whooshes, pops, pings (sintetizados) |

## Voz en off (guion literal)
1. *(0:01)* "¿Te buscan en Google… y no apareces?"
2. *(0:05)* "En negolo diseñamos tu página web a medida."
3. *(0:12)* "Landings, webs corporativas y tiendas online, listas en días."
4. *(0:19)* "Y empiezas a recibir clientes por WhatsApp."
5. *(0:27)* "Landing desde trescientos noventa y nueve soles, todo incluido."
6. *(0:35)* "Sin pago previo. Cotiza gratis hoy."
