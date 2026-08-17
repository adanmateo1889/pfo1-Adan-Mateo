# PFO1 — Landing de portafolio personal

Landing page individual desarrollada para la **Práctica Formativa Obligatoria 1 (PFO1)** de la Tecnicatura en Desarrollo de Software.

El objetivo del proyecto es presentar de forma breve mi perfil como estudiante, mis habilidades, algunos proyectos de mi formación y una vía de contacto, incorporando además un enlace visible a mi perfil de GitHub.

## 🌐 Sitio publicado

**Vercel:** `PEGAR_AQUI_LA_URL_DE_VERCEL`

> Esta URL debe completarse después de publicar el repositorio en Vercel.

## 👨‍💻 GitHub

**Perfil:** `https://github.com/tu-usuario`

> Reemplazar `tu-usuario` por el nombre real de usuario de GitHub antes de entregar.

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

Antes de la entrega final voy a verificar nuevamente los enlaces, reemplazar los datos pendientes por mis datos reales, probar el sitio en diferentes tamaños de pantalla y confirmar que la versión publicada en Vercel coincida con el repositorio.

## 🖼️ Uso de imágenes e IA

La imagen `assets/perfil.svg` es una ilustración gráfica creada específicamente para esta práctica con asistencia de IA. No representa una fotografía real.

Si posteriormente reemplazo esta ilustración por una fotografía propia procesada, editada o generada con IA, actualizaré esta sección indicando la herramienta y el tipo de intervención realizada.

## 🚀 Publicación en Vercel

1. Crear un repositorio público en GitHub.
2. Subir los archivos de este proyecto.
3. Ingresar a Vercel.
4. Elegir **Add New → Project**.
5. Importar el repositorio de GitHub.
6. Mantener la configuración de proyecto estático.
7. Seleccionar **Deploy**.
8. Copiar la URL publicada y agregarla en este README.

## 🧪 Verificación antes de entregar

- [ ] Reemplazar `https://github.com/tu-usuario` en `index.html`.
- [ ] Reemplazar `github.com/tu-usuario` en el texto visible de la sección Contacto.
- [ ] Reemplazar la URL de GitHub en este README.
- [ ] Completar la URL de Vercel.
- [ ] Revisar el nombre y los textos personales.
- [ ] Abrir todos los enlaces.
- [ ] Probar la landing en celular y escritorio.
- [ ] Verificar que el repositorio sea público.
- [ ] Confirmar que el README sea visible desde GitHub.
- [ ] Entregar únicamente el enlace al repositorio público.

## 📝 Historial de commits sugerido

Para que el proceso quede documentado de forma clara, se puede mantener un historial similar a este:

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
