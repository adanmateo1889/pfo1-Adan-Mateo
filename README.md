# PFO1 — Landing de portafolio personal

Landing page individual desarrollada para la **Práctica Formativa Obligatoria 1 (PFO1)** de la Tecnicatura en Desarrollo de Software.

El objetivo del proyecto es presentar de forma breve mi perfil como estudiante, mis habilidades, algunos proyectos de mi formación y una vía de contacto, incorporando además un enlace visible a mi perfil de GitHub.

## 🌐 Sitio publicado

**Vercel:** https://pfo1-adan-mateo.vercel.app/


## 👨‍💻 GitHub

**Perfil:** https://github.com/adanmateo1889


## 🧩 Tecnologías utilizadas

- HTML5
- CSS3
- Google Fonts
- Flexbox
- CSS Grid
- Diseño responsive
- Transiciones y animaciones CSS
- Git y GitHub
- Vercel para el despliegue

## 📁 Estructura del proyecto

```text
PFO1_portafolio_personal/
├── index.html
├── styles.css
├── README.md
└── assets/
    └── perfil.svg
```

## ✅ Requisitos implementados

- `<!DOCTYPE html>` y metaetiquetas principales.
- Estructura semántica con `header`, `nav`, `main`, `section` y `footer`.
- Cuatro comentarios explicativos en el HTML.
- Navegación interna mediante anclas.
- Imagen local con atributo `alt`.
- Labels visibles en todos los campos del formulario.
- Atributos de accesibilidad y etiquetas ARIA cuando resultan pertinentes.
- Google Fonts con **Inter** y **Space Grotesk**.
- Uso combinado de **CSS Grid** y **Flexbox**.
- Unidades relativas, `clamp()` y media queries para un diseño responsive.
- Variables CSS para mantener coherencia visual.
- Transiciones en enlaces, botones, campos y tarjetas.
- Animación personalizada en la tarjeta principal.
- Regla `prefers-reduced-motion` para respetar preferencias de accesibilidad.
- Enlace visible al perfil de GitHub.

## 🎨 Decisiones de diseño

Elegí una estética oscura con un color de acento verde agua para generar contraste y una apariencia asociada al mundo tecnológico sin depender de una plantilla externa.

Utilicé **CSS Grid** en las zonas donde necesitaba distribuir contenido en columnas, como el hero, las habilidades, los proyectos y el contacto. Elegí **Flexbox** para elementos de una sola dimensión, como la navegación, los botones, las etiquetas y el footer.

El diseño utiliza tamaños fluidos con `clamp()` y unidades relativas para que la composición pueda adaptarse progresivamente a distintos anchos de pantalla. Además, las media queries reorganizan las grillas en tablets y celulares.

La jerarquía tipográfica combina **Space Grotesk** en títulos y **Inter** en textos de lectura. También utilicé variables CSS para centralizar colores, radios, sombras y medidas recurrentes.

## ♿ Accesibilidad

Tomé algunas decisiones para mejorar la accesibilidad:

- enlace “Saltar al contenido principal”;
- texto alternativo en la imagen;
- labels asociados a cada input mediante `for` e `id`;
- foco visible en campos y controles;
- navegación con `aria-label`;
- listas con descripciones ARIA cuando agregan contexto;
- contraste alto entre fondo y texto;
- soporte para `prefers-reduced-motion`.

## 🤖 Declaración de uso de Inteligencia Artificial

Para desarrollar esta PFO utilicé **ChatGPT de OpenAI**, mediante un **plan ChatGPT Plus**.

Ya tenía experiencia previa utilizando esta herramienta para realizar consultas, organizar ideas, revisar consignas y recibir apoyo durante trabajos académicos y ejercicios de programación.

En esta práctica utilicé la IA para:

- analizar la consigna y la rúbrica;
- proponer una estructura inicial para la landing;
- generar una primera versión del HTML y del CSS;
- revisar que estuvieran presentes los requisitos técnicos solicitados;
- proponer mejoras de accesibilidad y diseño responsive;
- generar la ilustración SVG utilizada como imagen de perfil;
- organizar una primera versión de este README.

La IA no fue utilizada como sustituto de la revisión personal. Revisé la estructura del proyecto, la relación entre HTML y CSS, el contenido mostrado, la legibilidad, la navegación, el comportamiento responsive y la coherencia con la consigna. También seleccioné qué habilidades y proyectos resultaban apropiados para mostrar en un portafolio académico.

Antes de la entrega final verifiqué los enlaces, reemplacé los datos pendientes por mis datos reales, probé el sitio en diferentes tamaños de pantalla y confirmé que la versión publicada en Vercel coincidiera con el repositorio.

## 🖼️ Uso de imágenes e IA

La imagen `assets/perfil.svg` es una ilustración gráfica creada específicamente para esta práctica con asistencia de IA. No representa una fotografía real.

La ilustración se mantuvo como recurso visual del portafolio y su uso quedó documentado en este README para asegurar la trazabilidad del uso de IA.

## 🚀 Publicación en Vercel

El proyecto fue publicado en Vercel a partir del repositorio de GitHub.

**URL publicada:** https://pfo1-adan-mateo.vercel.app/

La versión desplegada corresponde al contenido del repositorio utilizado para esta entrega.

## 🧪 Verificación final

- [x] Enlace al perfil de GitHub actualizado.
- [x] URL de Vercel incorporada al README.
- [x] Nombre y textos personales revisados.
- [x] Enlaces principales verificados.
- [x] Landing revisada en distintos tamaños de pantalla.
- [x] Repositorio configurado como público.
- [x] README visible desde GitHub.
- [x] Versión publicada en Vercel verificada.

## 📝 Organización sugerida del historial de commits

Como criterio de organización del proceso, el historial de commits puede seguir una estructura clara y progresiva como la siguiente:

```text
feat: crear estructura semántica inicial
style: agregar diseño base y google fonts
feat: incorporar secciones de habilidades y proyectos
feat: agregar formulario y enlace a github
style: implementar responsive y animaciones
docs: completar readme y declaración de uso de ia
fix: revisar accesibilidad y enlaces finales
```

## Autor

**Adan Mateo Israel**  
Estudiante de la Tecnicatura en Desarrollo de Software
