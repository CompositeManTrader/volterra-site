# VOLTERRA — Sitio de marca

Sitio web institucional de **VOLTERRA**, investigación cuantitativa de volatilidad.
Multipágina, estático, sin build: HTML + CSS + JavaScript vanilla.

## Estructura

```
index.html          Inicio (hero + hub)
metodologia.html    Metodología, proceso y gobernanza
modelos.html        Monitor en vivo + hoja de ruta de modelos
contacto.html       El especialista + acceso institucional
assets/styles.css   Estilos compartidos (sistema de diseño)
assets/app.js       Lógica compartida (malla interactiva, monitor, formulario…)
```

## Sistema de diseño

- **Paleta:** obsidiana `#07080A` · oro champán `#C9A35C` (institución) · jade `#66E0C2` (dato vivo).
- **Tipografía:** Space Grotesk (titulares) · Inter (cuerpo) · JetBrains Mono (datos).
- **Estética:** liquid glass sobre fondo oscuro, profundidad ambiental, microinteracciones de precisión.

## Desarrollo local

Cualquier servidor estático sirve. Por ejemplo:

```bash
python -m http.server 8080
# abrir http://localhost:8080
```

## Despliegue (Vercel)

Repositorio listo para Vercel sin configuración: **Framework = Other**, sin build command,
**Root Directory = `.`** (raíz). Cada `git push` a `main` redespliega automáticamente.

---

Material de investigación y posicionamiento de marca. No constituye asesoramiento financiero
ni oferta de servicios de inversión.
