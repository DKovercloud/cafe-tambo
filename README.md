# ☕ Café Tambo

Página web de una cafetería de especialidad en Barranco, Lima. Es un negocio ficticio que creé como demo de diseño web: una landing page de una sola página, rápida, adaptable a celular y lista para publicar.

🔗 **Demo en vivo:** https://dkovercloud.github.io/cafe-tambo/

<img width="1148" height="716" alt="image" src="https://github.com/user-attachments/assets/c71d1b14-6640-4d1c-b9e8-f0614239d251" />


## Qué incluye

- **Hero** con propuesta de valor, botones de acción y una taza de café en SVG con vapor animado.
- **Estado en tiempo real:** muestra si el local está abierto o cerrado según la hora de Lima, sin importar desde dónde se visite la página.
- **Menú con pestañas** (bebidas, para comer y granos para llevar), hecho con JavaScript sin librerías.
- **Horario** que resalta automáticamente el día actual.
- **Pedidos por WhatsApp** con mensaje prellenado.
- **Sección "Nosotros"** y datos de contacto con enlace a Google Maps.
- **Diseño responsive:** se ve bien en celular, tablet y computadora.

## Detalles técnicos

- **Accesibilidad:** HTML semántico, atributos ARIA, foco visible con teclado y respeto por `prefers-reduced-motion` para quienes prefieren sin animaciones.
- **SEO:** etiquetas meta, Open Graph y datos estructurados JSON-LD (`CafeOrCoffeeShop`) para buscadores.
- **CSS moderno:** variables CSS, Grid, Flexbox y `clamp()` para tipografía fluida.
- **Sin dependencias:** un solo archivo `index.html`, sin frameworks ni herramientas de compilación.

## Tecnologías

- HTML5
- CSS3
- JavaScript (vanilla)
- Google Fonts (Bricolage Grotesque e Instrument Sans)
- SVG inline

## Cómo verla en tu computadora

1. Clona el repositorio:
   ```bash
   git clone https://github.com/DKovercloud/cafe-tambo.git
   ```
2. Abre el archivo `index.html` en tu navegador.

No necesita instalar nada.

## Personalizarla para tu negocio

Si quieres una página parecida para tu cafetería, restaurante o emprendimiento, cambia estos datos en `index.html`:

- Nombre, textos y menú
- Número de WhatsApp (en los enlaces `wa.me`)
- Dirección y teléfono
- Horario (objeto `horario` en el script y tabla de la sección "Visítanos")
- Colores en las variables de `:root`

## Nota

Café Tambo es un negocio ficticio. El teléfono, la dirección y los precios son datos de ejemplo.

## Autor

**Alonso López**, estudiante de Ingeniería de Software en la UPC (Lima, Perú).
Perfil de GitHub: [@DKovercloud](https://github.com/DKovercloud)
