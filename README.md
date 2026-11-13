# Empire Gym · Sitio web (muestra)

Landing page de **Empire Gym**, gimnasio en El Quisco (Isidoro Dubournais 2010 esq. La Montaña). Muestra preparada por [Tu Plan Digital](https://tuplandigital.cl) bajo el **Plan Web**.

## Stack

- HTML + CSS puro, sin dependencias ni build.
- Animaciones y preguntas frecuentes (`<details>`) solo con CSS; un script mínimo abre y cierra el menú móvil sin desplazar la página.
- Respeta `prefers-reduced-motion`.
- SEO local: metadatos, Open Graph y datos estructurados `ExerciseGym` (dirección y horarios).

## Estructura

```
index.html          Página única
css/styles.css      Estilos (variables de color al inicio)
assets/img/         Logo y fotos del gimnasio (tomadas de su Instagram)
```

## Secciones

Inicio · Nosotros · Zonas · Pilares · Planes + Promo Dúo · Preguntas · Reseñas (enlace a Google Maps) · Llamado a la acción · Ubicación con mapa · Footer

## Contenido a confirmar con el cliente

- Precios: Spartan $35.000, Élite $40.000 y Estudiante $30.000 (asumidos como mensuales), y la vigencia de la Promo Dúo.
- Contacto: hoy todo va al DM de Instagram (`https://ig.me/m/empires.gym`). Si tienen WhatsApp, se cambia en los botones.
- Reseñas: sumar 3 reseñas reales de Google Maps.
- Fotos en mayor resolución del gimnasio.

## Desarrollo local

```bash
npx serve .
```

## Créditos de imágenes

- Fondo del hero: foto de Anastase Maragos en [Unsplash](https://unsplash.com/photos/man-lifting-barbell-in-dark-gym-4dlhin0ghOk) (licencia Unsplash). Si no carga, usa una foto propia del gimnasio como respaldo.
- Resto de imágenes: publicaciones de @empires.gym.
