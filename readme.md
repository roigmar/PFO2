# Academia de Oficios Laguna — Comparativa de Agentes IA

## Datos del estudiante

- **Nombre:** Marcela Roig
- **Materia:** Desarrollo de sistemas web Front End
- **Año:** 2026

---

## Deploy unificado

[https://pfo-2-seven.vercel.app/]

---

## Estructura del proyecto

```
/
├── index.html              ← Portada con los tres accesos
├── prompt.html             ← Visualización del prompt utilizado
├── wallpaper.png           ← Fondo visual del proyecto
├── README.md
├── codex/
│   └── index.html          ← Landing generada por Codex (OpenAI) — GPT-5
├── antigravity/
│   └── index.html          ← Landing generada por Antigravity IDE — Gemini 3.5 Flash (Medium)
└── screenshots/
    ├── Hero-Codex.png
    ├── Servicios-Codex.png
    ├── Testimonios-Codex.png
    ├── Nosotros-Codex.png
    ├── Header-Codex.png
    ├── Formulario-Codex.png
    ├── Hero-Antigravity.png
    ├── Servicios-Antigravity.png
    ├── Testimonios-Antigravity.png
    ├── Nosotros-Antigravity.png
    ├── Header-Antigravity.png
    ├── Formularios-Antigravity.png
    └── juanito.jpg
```

---

## Agentes utilizados

**Agente 1 — Codex (OpenAI)**
Plataforma: Codex, agente de programación de OpenAI
Modelo: GPT-5

**Agente 2 — Antigravity IDE**
Plataforma: Antigravity IDE
Modelo: Gemini 3.5 Flash (Medium)

---

## Inspiración
A fin de generar un trabajo que, pese a ser fgenerado mediante IA, tuviera una estética pensada y se alejara un poco de un producto masificado e impersonal busqué inspiración en una obra de la serie "Juanito Laguna" de Antonio Berni: "Juanito Dormido". Elegí precisamente este artista por que lo considero un  representante de los opuesto a estos tiempos y esta modernidad. Su obras de estilo "collage" con sus tramas, texturas y colores crean universos únicos e irrepetibles, a difrencia de las creaciones mediante IA sin más búsqueda que lo funcional.
Utilicé Nano Banana para generar un fondo que representara esas gamas y esas texturas y luego de esa imágen generé la paleta de colores y parte de las directrices utilizadas en prompt. 
De esta misma fuente de inspiración fue que surgió la temática del contenido de las landing: oficios como contraposición a IA.
![Juanito Dormido](screenshots/juanito.jpg)
![Portada](screenshots/Portada.png)


## Prompt utilizado

```
You are an expert frontend developer. Build a complete landing page for "Academia de Oficios Laguna", a vocational training school in Buenos Aires, Argentina. Output a single self-contained HTML file (all CSS and JS embedded). No frameworks. No external files except Google Fonts.

## VISUAL STYLE
Aesthetic: Argentine social realism — worn materials, layered textures, human craftsmanship.
Palette: teal #4A8B8C, rust #8B3A2A, linen #E8D5B0, brown #6B4C35, charcoal #1A1A18, off-white #F2E8D5.
Fonts (Google Fonts): Playfair Display (headings), Source Sans 3 (body), Special Elite (labels).
Background: simulate industrial collage textures using only CSS layered gradients and SVG noise filter. No image files.
Signature element: course cards styled as hand-cut paper pieces — unique irregular clip-path polygon per card, slight random rotation (±2deg), paper-grain texture via CSS, no border-radius, shadow suggesting physical lift.

## SECTIONS (in order)

1. HEADER — Logo "Academia de Oficios Laguna", nav links: Inicio | Sobre Nosotros | Cursos | Testimonios | Contacto. Sticky, semi-transparent, backdrop-blur. Mobile hamburger menu.

2. HERO — Full viewport. Headline: "Capacitaciones que abren puertas al futuro". Subheadline: "Aprendé habilidades con alta demanda laboral y preparate para acceder a nuevas oportunidades profesionales." CTA button "Inscribite Hoy" styled as an ink stamp.

3. SOBRE NOSOTROS — Body text: "En Academia de Oficios Laguna creemos que cada persona merece la oportunidad de desarrollar su potencial y construir un futuro mejor. Inspirados por los valores de esfuerzo, superación y transformación social, ofrecemos programas de formación diseñados para brindar herramientas concretas para el mundo laboral." Stats: 2.500+ estudiantes | 85% inserción laboral | 30 cursos | 10 años.

4. CURSOS — 6 hand-cut paper cards: (1) Desarrollo Web y Programación, (2) Diseño Gráfico y Marketing Digital, (3) Electricidad Domiciliaria, (4) Carpintería y Fabricación de Muebles, (5) Reparación de Computadoras y Dispositivos Móviles, (6) Emprendedurismo y Gestión de Negocios. Each with a short description and relevant icon. Below the cards, list 7 benefits as inline tags: Certificación oficial · Presencial y virtual · Profesores especializados · Proyectos reales · Bolsa de empleo · Asesoramiento · Inserción laboral.

5. TESTIMONIOS — 3 torn-paper cards: María González ("Gracias a Academia Laguna conseguí mi primer trabajo como diseñadora gráfica apenas dos meses después de finalizar el curso."), Lucas Fernández ("Los contenidos son prácticos y los profesores tienen experiencia real en el sector. Hoy trabajo como técnico en reparación de computadoras."), Sofía Ramírez ("El curso de programación me permitió iniciar una carrera profesional que antes veía imposible.").

6. CONTACTO — Title: "Solicitá información sobre nuestros cursos". Fields: nombre, email, teléfono, curso de interés (dropdown), mensaje. Button "Enviar Consulta" as ink stamp. Visual mockup only, no backend.

7. FOOTER — Av. Nueva Esperanza 1250, Buenos Aires | +54 11 4000-0000 | contacto@academialaguna.edu.ar | SVG social icons: Facebook, Instagram, LinkedIn, YouTube | © 2026 Academia de Oficios Laguna.

## TECHNICAL
- Mobile-first, responsive at 375 / 768 / 1280px.
- Smooth scroll, IntersectionObserver fade-in on sections.
- Semantic HTML5, WCAG AA contrast.
- Each clip-path polygon must be unique (hardcode different values per card).
- Output only the final HTML file. No explanations, no comments.
```

---

## Capturas de pantalla

### Codex — GPT-5

![Codex Hero](screenshots/Hero-Codex.png)
![Codex Servicios](screenshots/Servicios-Codex.png)
![Codex Testimonios](screenshots/Testimonios-Codex.png)
![Codex Nosotros](screenshots/Nosotros-Codex.png)
![Codex Header](screenshots/Header-Codex.png)
![Codex Formulario](screenshots/Formulario-Codex.png)

### Antigravity IDE — Gemini 3.5 Flash (Medium)

![Antigravity Hero](screenshots/Hero-Antigravity.png)
![Antigravity Servicios](screenshots/Servicios-Antigravity.png)
![Antigravity Testimonios](screenshots/Testimonios-Antigravity.png)
![Antigravity Nosotros](screenshots/Nosotros-Antigravity.png)
![Antigravity Header](screenshots/Header-Antigravity.png)
![Antigravity Formularios](screenshots/Formularios-Antigravity.png)