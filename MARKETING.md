# negolo — Plan de lanzamiento y promoción

> Generado el 26-sep-2026. Todo lo de este documento está listo para ejecutar.
> Contacto: WhatsApp **930 227 652** · correo **atencionalcliente@negolo.com** · web **negolo.com**

---

## 1. Facebook Page

| Campo | Valor |
|---|---|
| Nombre | negolo |
| Categoría | Software company / Diseño de sitios web |
| Usuario | @negolo (si está libre) |
| Botón CTA | **WhatsApp** → wa.me/51930227652 |
| Avatar | `assets/brand/icon-1024.png` (ícono "olo" sobre ciruela) |
| Portada | `assets/marketing/portada-fb.png` (1640×856) |

**Descripción (copiar tal cual):**
> Desarrollo web, apps y chatbots para tu negocio. Landings desde S/300 con dominio .com, hosting y 3 correos incluidos. Diseño a medida, entrega rápida y precios claros. Cotización gratis y sin compromiso 👉 WhatsApp 930 227 652

---

## 2. Los 10 posts iniciales (copy listo)

1. **Lanzamiento** — "Nace negolo 🚀 Webs, apps y chatbots para negocios que quieren crecer en internet. Cotización gratis y sin compromiso. Landings desde S/300 con dominio, hosting y correos."
2. **Oferta S/500** — "Tu web lista este mes: landing + dominio .com + hosting + 3 correos por 1 año = S/500. Sin costos sorpresa."
3. **Antes / Después** — carrusel del portafolio (Valencia Visual) con la frase "¿Tu web actual espanta clientes?"
4. **Cuánto cuesta una web** — video corto explicando por qué cobramos desde S/300 y qué incluye cada plan.
5. **Casos: Valencia Visual** — "Sitio corporativo + configurador 3D de stands con marca diseñada desde cero. Hecho 100% con código."
6. **Chatbots** — "Responde de noche, filtra consultas y agenda citas solo. Tu negocio atendiendo mientras duermes."
7. **Error común** — "3 errores que hacen que tu web no venda" (tip educativo, sin vender).
8. **Precio .pe** — "¿Necesitas .pe? Súmalo por +S/199 (incluye todo el año)."
9. **Testimonio / prueba** — captura real de un demo del portafolio + "todos nuestros proyectos tienen demo navegable".
10. **CTA fuerte** — "Cuéntanos tu idea por WhatsApp y en minutos te decimos cuánto cuesta. Cotización gratis, negociable y sin miedo."

**3 Reels (guiones de 20-30 s)**
- R1: scroll rápido por 3 demos del portafolio + texto "Esto es lo que podemos hacer por tu negocio".
- R2: pantalla del configurador 3D de Valencia Visual girando + "esto hicimos para una empresa de stands".
- R3: "Cómo pedir tu cotización": abrir WhatsApp, escribir "quiero mi web", responder 3 preguntas.

---

## 3. Embudo de WhatsApp (guion de respuesta)

**Mensaje automático bienvenida:**
> ¡Hola! 👋 Soy Piero de negolo. Para darte un precio exacto cuéntame:
> 1️⃣ ¿Qué hace tu negocio?
> 2️⃣ ¿Ya tienes web o red social?
> 3️⃣ ¿Para cuándo la necesitas?
> Mientras tanto, mira nuestros proyectos: negolo.com/portafolio

**Calificación interna:** negocio · si tiene web · urgencia · presupuesto · si decide él o alguien más.

**Propuesta (3 opciones siempre):**
- S/300 Básico (landing, sin dominio/correo/hosting)
- **S/500 Landing Pro** (dominio .com + hosting + 3 correos por 1 año) ← recomendar
- S/900 corporativa / S/1,500 tienda-app-chatbot / cotización personalizada

**Cierres:** "¿Empezamos hoy? Con S/250 aseguramos el dominio y arrancamos el diseño." · seguimiento a las 24 h y 48 h.

---

## 4. Plan de promoción

**Semana 1-2 (orgánico, inversión S/0)**
- Publicar los 10 posts (1 cada 2 días) + 1 reel por semana.
- Marketplace: 2 avisos (Landing S/300 y Landing Pro S/500) con CTA al chat. Nunca poner teléfono/correo/URL en la imagen ni en la descripción.
- Grupos de Facebook: emprendedores Perú / Lima, negocios locales, ferias y emprendimiento. 1 aporte útil por día + comentario suave; no spam.

**Semana 2+ (pago, empezar S/15/día)**
- Objetivo: **Mensajes (Click to WhatsApp)** → directo a 51930227652.
- Público: Lima + Callao, 24-55, intereses: pequeña empresa, emprendimiento, marketing digital, gastronomía, belleza.
- 3 creativos A/B (oferta S/500, antes/después, "cotización gratis").
- Escalar solo si **costo por mensaje < S/8**; apagar lo que no rinda.

**KPIs semanales:** mensajes recibidos · costo por mensaje · % que pide precio · cierres · ticket promedio (meta S/500+).

---

## 5. Despliegue (Vercel + Namecheap)

1. **Repo**: subir esta carpeta a GitHub como `negolo-web`.
2. **Vercel**: tu cuenta ya vinculada a GitHub → *Add New Project* → importar `negolo-web` → framework: **Other** → Deploy. Da una URL `negolo-web.vercel.app`.
3. **Dominio** (Namecheap → negolo.com → Advanced DNS):
   - `A` · `@` · `76.76.21.21`
   - `CNAME` · `www` · `cname.vercel-dns.com`
   - ⚠️ **Antes de tocar nada**: si negolo.com tiene correo activo, NO borrar los registros MX.
4. En Vercel → Settings → Domains → añadir `negolo.com` y `www.negolo.com`.
5. **Correo**: crear `atencionalcliente@negolo.com` (Zoho Mail gratis o el correo del hosting) y configurar MX según el proveedor.

---

## 6. Estado de avance

- [x] Sitio web completo (escritorio y móvil) — `negolo-web/index.html`
- [x] 15 proyectos del portafolio con demo navegable — `negolo-web/portafolio/`
- [x] Marca aplicada (oro/ciruela/lavanda, Nunito, logo oficial)
- [x] Documento de marketing, posts, guiones y plan de anuncios
- [ ] Portada FB dedicada (en generación)
- [ ] Página de Facebook `negolo` creada
- [ ] Posts publicados (pendiente de tu aprobación)
- [ ] Deploy en Vercel + DNS en Namecheap (al final, como acordamos)
