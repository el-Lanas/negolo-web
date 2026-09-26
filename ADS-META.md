# Campaña Meta Ads — negolo · S/5 diarios → conversaciones de WhatsApp

## 1. La publicación que vamos a usar

**Publicación base: “Landing Pro — S/500 todo incluido”.**

Por qué esa y no otra:
- Es la que **comunica el valor completo en 2 segundos**: dominio .com + hosting + 3 correos + soporte por 1 año. La de S/300 obliga a explicar lo que NO incluye (más fricción).
- **Ancla el precio**: quien no pueda con S/500 pedirá la de S/300 o una cotización personalizada → igual gana la conversación.
- Se puede **promocionar directamente desde la Page** (“Promocionar publicación”), que es el camino más simple y barato para empezar.

**Creativo recomendado**: `assets/marketing/portada-fb.png` (el mismo diseño de la portada) o un creativo hermano con la misma estructura:
- Titular: **Tu negocio, sin vueltas en internet**
- Oferta grande: **Landing Pro S/500** · “dominio .com + hosting + 3 correos incluidos (1 año)”
- Prueba: **15+ proyectos entregados · respuesta en minutos**
- CTA visual: **Cotización gratis**

**Copy de la publicación (pegar tal cual):**
> ¿Tu negocio todavía no tiene web? Esta semana la dejamos lista.
> Landing Pro **S/500** con **dominio .com + hosting + 3 correos por 1 año**.
> Diseño a medida, adaptado a celular y con botón de WhatsApp para que te escriban.
> También hay plan básico desde S/300 y cotización personalizada: cuéntanos tu proyecto y lo ajustamos a tu presupuesto.
> Cotización gratis, sin compromiso y negociable.
> Escríbenos por WhatsApp: 930 227 652

**Segundo anuncio (A/B, mismo conjunto)**: carrusel del portafolio (Valencia Visual → Convalt → ClubMap) con el copy: *“Esto es lo que podemos hacer por tu negocio. Landings desde S/300. Cotización gratis por WhatsApp.”*

---

## 2. Configuración exacta en Ads Manager

| Campo | Valor |
|---|---|
| Objetivo | **Interacción** (Engagement) |
| Ubicación de conversión | **Mensajes** → **WhatsApp** |
| Cuenta de WhatsApp | WhatsApp Business **+51 930 227 652** (vinculada a la Page Negolo) |
| Mensaje prellenado | “Hola, vi su anuncio y quiero cotizar mi página web” |
| Presupuesto | **S/5 diarios**, continuo (sin fecha de fin) |
| Puja | Automática (maximizar conversaciones) |
| Ventana de atribución | 7 días clic / 1 día vista |
| Estructura | **1 campaña · 1 conjunto · 2 anuncios** (no fragmentar con este presupuesto) |

### Público
- **Ubicación:** Lima Metropolitana + Callao (radio 25 km desde Lima Centro).
- **Edad:** 25–55 · todos los géneros.
- **Intereses (2-3 capas, no más):** pequeña empresa / emprendimiento · marketing digital / publicidad · diseño web / páginas web.
- **Público Advantage+ activado** (deja que Meta busque; con S/5/día conviene no encajonar).
- Excluir: ninguna audiencia todavía (recién empezamos).

### Ubicaciones
Automáticas (Advantage+ placements). Si hay que elegir: Facebook Feed, Instagram Feed, Instagram Reels/Stories y WhatsApp Status.

---

## 3. Plan de 14 días

| Días | Acción |
|---|---|
| 1–3 | **No tocar nada.** Dejar que Meta reparta y aprenda. Responder cada mensaje en menos de 5 minutos. |
| 4 | Revisar: conversaciones iniciadas y **costo por conversación**. Apagar solo si un anuncio tiene CTR < 0,6% y 0 conversaciones. |
| 7 | Comparar los 2 anuncios: pausar el peor, subir el presupuesto del ganador a **S/6–7** (máx. +20%/día). |
| 10 | Si el costo por conversación ≤ S/5 y hay cierres: subir a **S/10/día** y añadir un tercer creativo (caso real del portafolio). |
| 14 | Balance: si hay 1 cierre de S/500, la campaña ya es rentable (S/70 invertidos). Renovar creativos cada 2 semanas para no saturar. |

**Esperado con S/5/día (realista, sin prometer):** ~400–800 impresiones/día, 5–15 clics/día y **2–6 conversaciones por semana** en las primeras semanas. El costo por conversación suele arrancar alto (S/8–15) y bajar al estabilizarse (S/3–7).

---

## 4. Reglas de oro
1. **Responder en menos de 5 minutos**: es el factor que más sube el cierre (y Meta premia la respuesta rápida con mejor entrega).
2. **Nunca poner teléfono, correo ni URL en la imagen del anuncio** (Meta penaliza contacto fuera de su plataforma en el creativo). El contacto va en el botón de WhatsApp.
3. **Sin promesas de resultados** (“más clientes garantizados”): mejora la aprobación y evita rechazos.
4. Un solo mensaje de bienvenida con 3 preguntas de calificación (negocio, si tiene web, urgencia) y enviar los 3 paquetes + enlace al portafolio.
5. Seguimiento a las 24 h y 48 h si no responde. Cerrar con “50% para iniciar, 50% contra entrega”.

## 5. Medición semanal
- Conversaciones iniciadas · **costo por conversación** · % que pide precio · cierres · ticket promedio.
- Meta: ≤ S/6 por conversación · cierre ≥ 20% de las conversaciones.

---

## 6. Pendiente de 2 clics (para tener todo listo)
1. GitHub ya tiene el repo: **el-Lanas/negolo-web**.
2. En **vercel.com/new** → buscar `negolo-web` → **Import** → **Deploy** (framework: Other). Queda una URL `negolo-web.vercel.app`.
3. Luego (al final, como acordamos): dominio en Namecheap (`A @ → 76.76.21.21`, `CNAME www → cname.vercel-dns.com`) y añadir el dominio en Vercel.
