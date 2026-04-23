# Propuesta PROSAM — Contexto del Proyecto

> Propuesta comercial + futuro desarrollo de web para **Centro Médico PROSAM**.
> Clínica de salud mental (psiquiatría, psicología, neuropsicología) — CABA, Argentina.
> 30+ años operando. Sitio actual: `cmprosam.com.ar` (offline / mala visibilidad).

---

## 1. ESTADO ACTUAL

**Lo que hay hoy:** propuesta comercial interactiva (HTML único, 85KB) con portfolio embebido.
**Lo que viene si cierra:** redesign completo del sitio + branding + SEO/GEO + landings por servicio + blog + CMS.

---

## 2. STACK ACTUAL (PROPUESTA)

| Archivo | Descripción |
|---|---|
| `index.html` | Single-page pitch con CSS y JS inline |
| `img/` | Screenshots portfolio (Antoá, FabrIQ, GymApp) |

**Tecnologías:** HTML5 + CSS custom (glass-morphism, variables CSS) + vanilla JS. Google Fonts: Inter + Playfair Display.
**Sin build step.** Editar `index.html` directo.

---

## 3. DELIVERABLES OFRECIDOS (SI CIERRA)

| Área | Detalle |
|---|---|
| Web | Home + 4 páginas principales + 7 landings por servicio + blog |
| Branding | Logo nuevo + paleta + guía tipográfica |
| SEO | Schema médico + Google Business Profile |
| GEO | Optimización para ChatGPT / Gemini / Perplexity |
| Mobile | Mobile-first (68% búsquedas salud son mobile) |
| CMS | Panel para editar contenido |
| Extras | WhatsApp flotante + forms + landings por servicio |

**Tiempo:** 6 semanas
**Precio:** USD 600
**Estética de referencia:** López Ibor

---

## 4. STACK PROPUESTO PARA LA WEB REAL

**A decidir al arrancar.** Opciones razonables:
- Next.js 14 App Router + Tailwind + CMS headless (Sanity/Payload) — si Juan quiere tener el código
- Astro + CMS — si prioriza performance y SEO puro
- WordPress/Webflow — si el cliente va a editar mucho sin intervención

**Decisión recomendada:** Next.js + Payload CMS self-hosted en Vercel. Consistente con FabrIQ / GymApp / Glarino.

---

## 5. CONSIDERACIONES CLAVE DEL NEGOCIO

- **Nicho médico regulado** — contenido debe cumplir buenas prácticas de salud digital
- **Schema.org médico** — `MedicalOrganization`, `Physician`, `MedicalProcedure` obligatorios
- **Targeting por ubicación** — búsquedas locales CABA
- **Audiencia sensible** — lenguaje no estigmatizante, tono profesional cálido
- **GEO (Generative Engine Optimization)** — contenido estructurado para que IA lo cite

---

## 6. GIT

Repo local con 10+ commits trackeando iteraciones de la propuesta. Al pasar a ejecución, crear repo nuevo (`prosam-web/` separado) — no mezclar propuesta con proyecto.

---

## 7. CUANDO ARRANQUE EL DESARROLLO

1. Crear nuevo repo: `workspace/prosam-web/`
2. Copiar manual de marca acordado a `recursos/`
3. Setup Next.js + Payload + Vercel + dominio del cliente
4. Primer milestone: home + schema médico + Google Business
5. Actualizar este CLAUDE.md cuando se pase de propuesta a ejecución
