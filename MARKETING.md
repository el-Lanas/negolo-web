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
| Posts 1080×1080 | `assets/marketing/post-planes.png` · `assets/marketing/post-sinpago.png` |

**Descripción (copiar tal cual):**
> Desarrollo web, apps y chatbots para tu negocio. Landing Page S/299 (2 días), Web Corporativa S/499 (5 días) y Tienda Virtual S/699 (7 días). Sin pago previo: págas recién cuando apruebas tu web. Precios + IGV. Cotización gratis y sin compromiso 👉 WhatsApp 930 227 652

---

## 2. Los 10 posts iniciales (copy listo)

1. **Lanzamiento** — "Nace negolo 🚀 Webs, apps y chatbots para negocios que quieren crecer en internet. Landing Page desde S/299 con dominio .com y hosting. Cotización gratis y sin pago previo."
2. **Oferta Web Corporativa S/499** — "Tu web lista en 5 días: hasta 5 secciones + dominio .com + hosting + 3 correos por 1 año = S/499 (+ IGV). Sin costos sorpresa."
3. **Antes / Después** — carrusel del portafolio (Valencia Visual) con la frase "¿Tu web actual espanta clientes?"
4. **Cuánto cuesta una web** — video corto explicando los planes vigentes: S/299 landing (2 días), S/499 corporativa (5 días) y S/699 tienda (7 días).
5. **Casos: Valencia Visual** — "Sitio corporativo + configurador 3D de stands con marca diseñada desde cero. Hecho 100% con código."
6. **Chatbots** — "Responde de noche, filtra consultas y agenda citas solo. Tu negocio atendiendo mientras duermes. A medida, cotización en el día."
7. **Error común** — "3 errores que hacen que tu web no venda" (tip educativo, sin vender).
8. **Precio .pe y mantenimiento** — "¿Necesitas dominio .pe? Súmalo por +S/199 (todo el año). Mantenimiento opcional por S/150/año."
9. **Testimonio / prueba** — captura real de un demo del portafolio + "todos nuestros proyectos tienen demo navegable".
10. **CTA fuerte** — "Cuéntanos tu idea por WhatsApp y en el día te cotizamos gratis. Sin pago previo: diseñas, corriges y recién ahí pagas."

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
- S/299 **Landing Page** (1 página + dominio .com + hosting, entrega en 2 días)
- **S/499 Web Corporativa** (hasta 5 secciones + dominio .com + hosting + 3 correos por 1 año, entrega en 5 días) ← recomendar (el más elegido)
- S/699 **Tienda Virtual** (catálogo + carrito + pagos y envíos, entrega en 7 días)

Todos los precios son **+ IGV**. Extras: dominio **.pe + S/199**, **mantenimiento S/150/año**. Para chatbots, apps, ERP/CRM o cualquier sistema a medida: **cotización en el día**.

**Cierres:** "Empezamos **sin pago previo**: nos cuentas tu idea, te cotizamos gratis, diseñamos tu web, la corriges y recién ahí pagas." · seguimiento a las 24 h y 48 h.

---

## 4. Plan de promoción

**Semana 1-2 (orgánico, inversión S/0)**
- Publicar los 10 posts (1 cada 2 días) + 1 reel por semana.
- Marketplace: 2 avisos (Landing Page S/299 y Web Corporativa S/499) con CTA al chat. Nunca poner teléfono/correo/URL en la imagen ni en la descripción.
- Grupos de Facebook: emprendedores Perú / Lima, negocios locales, ferias y emprendimiento. 1 aporte útil por día + comentario suave; no spam.

**Semana 2+ (pago, empezar S/15/día)**
- Objetivo: **Mensajes (Click to WhatsApp)** → directo a 51930227652.
- Público: Lima + Callao, 24-55, intereses: pequeña empresa, emprendimiento, marketing digital, gastronomía, belleza.
- 3 creativos A/B (post de los 3 planes con "sin pago previo", antes/después, "cotización gratis").
- Escalar solo si **costo por mensaje < S/8**; apagar lo que no rinda.

**KPIs semanales:** mensajes recibidos · costo por mensaje · % que pide precio · cierres · ticket promedio (meta S/499+).

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
- [x] Portada FB dedicada y piezas gráficas (`assets/marketing/portada-fb.png`, `post-planes.png`, `post-sinpago.png`)
- [ ] Página de Facebook `negolo` creada
- [ ] Posts publicados (pendiente de tu aprobación)
- [ ] Deploy en Vercel + DNS en Namecheap (al final, como acordamos)
