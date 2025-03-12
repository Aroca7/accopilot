# README - Accesibilidad en HTML (WCAG 2.2)

## Español

### Desarrollo del Prompt
Para mejorar la accesibilidad del código HTML según los estándares WCAG 2.2, se redactó un prompt para asistentes de programación como GitHub Copilot. Este prompt incluyó instrucciones detalladas sobre:
- Agregar atributos ARIA a formularios, botones, imágenes y enlaces.
- Usar etiquetas semánticas HTML5 como `<header>`, `<main>`, `<section>`, etc.
- Garantizar textos alternativos descriptivos en imágenes.
- Verificar la estructura correcta del documento con encabezados adecuados.
- Implementar mejoras para la navegación con teclado y el contraste visual.

### Pasos de Validación de Accesibilidad
Se utilizaron diversas herramientas para verificar que el código cumpliera con los niveles A, AA y AAA de WCAG 2.2:
1. **Lighthouse (Google Chrome)**: Se ejecutó un análisis de accesibilidad.
2. **Axe DevTools (Deque)**: Se revisaron errores y advertencias.
3. **WAVE (WebAIM)**: Se analizaron problemas de contraste, semántica y etiquetas ARIA.
4. **ARC Toolkit (TPGi)**: Se verificó la accesibilidad de los elementos interactivos.
5. **Accessibility Insights (Microsoft)**: Se ejecutó el "FastPass" para detectar problemas clave.

### Problemas Encontrados y Soluciones Aplicadas
- **Falta de atributos ARIA en botones y formularios** → Se agregaron `aria-label` y `aria-required`.
- **Uso inadecuado de etiquetas de encabezado** → Se corrigió la jerarquía de `<h1>`, `<h2>`, etc.
- **Enlaces poco descriptivos** → Se mejoró el texto de los enlaces para ser comprensibles fuera de contexto.
- **Contraste insuficiente en algunos elementos** → Se ajustaron los colores para cumplir con las recomendaciones de WCAG.
- **Navegación con teclado limitada** → Se aseguraron accesos correctos a los elementos interactivos.

### Capturas de Pantalla de la Validación
Las capturas de pantalla que demuestran la accesibilidad mejorada del código se encuentran en el siguiente enlace:
[Enlace a las capturas de pantalla]

---

## English

### Prompt Development
To improve HTML code accessibility according to WCAG 2.2 standards, a prompt was created for programming assistants like GitHub Copilot. This prompt included detailed instructions on:
- Adding ARIA attributes to forms, buttons, images, and links.
- Using semantic HTML5 tags such as `<header>`, `<main>`, `<section>`, etc.
- Ensuring descriptive alternative text for images.
- Verifying the correct document structure with appropriate headings.
- Implementing improvements for keyboard navigation and visual contrast.

### Accessibility Validation Steps
Various tools were used to verify that the code met WCAG 2.2 levels A, AA, and AAA:
1. **Lighthouse (Google Chrome)**: Ran an accessibility audit.
2. **Axe DevTools (Deque)**: Reviewed errors and warnings.
3. **WAVE (WebAIM)**: Analyzed contrast issues, semantics, and ARIA tags.
4. **ARC Toolkit (TPGi)**: Checked accessibility of interactive elements.
5. **Accessibility Insights (Microsoft)**: Ran "FastPass" to detect key issues.

### Issues Found and Solutions Applied
- **Lack of ARIA attributes in buttons and forms** → Added `aria-label` and `aria-required`.
- **Improper use of heading tags** → Fixed `<h1>`, `<h2>`, etc., hierarchy.
- **Unclear link text** → Improved link descriptions to be understandable out of context.
- **Insufficient contrast in some elements** → Adjusted colors to meet WCAG recommendations.
- **Limited keyboard navigation** → Ensured correct access to interactive elements.

### Validation Screenshots
Screenshots demonstrating improved code accessibility are available at the following link:
[Link to screenshots]

