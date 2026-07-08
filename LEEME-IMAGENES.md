# Cómo agregar las imágenes — Hotel Rubí

El sitio ya está listo para recibir fotos reales. **No necesitas tocar el código.**
Cada lugar donde falta una imagen se ve como un recuadro con marco dorado punteado
que dice el nombre exacto del archivo que debe llevar, por ejemplo:

    🖼  Coloca aquí: img/hero.jpg

### Cómo funciona

1. Toma o consigue la foto.
2. Renómbrala **exactamente** como se indica en el recuadro (respetando mayúsculas/minúsculas).
3. Guárdala dentro de la carpeta `img/` del sitio.
4. Recarga la página: la foto sustituye automáticamente al recuadro. No hay que editar HTML ni CSS.

### Formato recomendado
- JPG o WEBP, buena calidad pero comprimidas (idealmente menos de 400 KB cada una).
- Orientación horizontal para héroes y tarjetas de habitación; el sitio recorta automáticamente
  para que siempre se vea bien (no importa si la foto no es exactamente del tamaño sugerido).

---

## Lista completa de imágenes

### Página de Inicio (`index.html`)
| Archivo | Uso | Tamaño sugerido |
|---|---|---|
| `img/hero.jpg` | Foto principal de portada (fachada de noche o exterior) | 1920×1080 |
| `img/room-king.jpg` | Tarjeta destacada — Suite King | 800×600 |
| `img/room-matrimonial.jpg` | Tarjeta destacada — Matrimonial | 800×600 |
| `img/room-familiar4.jpg` | Tarjeta destacada — Familiar 4 | 800×600 |

### Sobre Nosotros (`sobre-nosotros.html`)
| Archivo | Uso | Tamaño sugerido |
|---|---|---|
| `img/hero-about.jpg` | Portada de la página | 1920×900 |
| `img/about.jpg` | Foto vertical junto al texto de la historia | 800×1000 |

### Habitaciones (`habitaciones.html`)
| Archivo | Uso | Tamaño sugerido |
|---|---|---|
| `img/hero-habitaciones.jpg` | Portada de la página | 1920×900 |
| `img/room-king.jpg` | (mismo archivo que en Inicio) | 800×600 |
| `img/room-matrimonial.jpg` | (mismo archivo que en Inicio) | 800×600 |
| `img/room-familiar3.jpg` | Tarjeta — Familiar 3 | 800×600 |
| `img/room-familiar4.jpg` | (mismo archivo que en Inicio) | 800×600 |
| `img/room-familiar6.jpg` | Tarjeta — Familiar 6 | 800×600 |

### Detalle de cada habitación
Cada página de detalle tiene una foto de portada y 3 fotos de galería:

| Habitación | Portada | Galería |
|---|---|---|
| Suite King | `img/hero-king.jpg` | `img/king-1.jpg`, `img/king-2.jpg`, `img/king-3.jpg` |
| Matrimonial | `img/hero-matrimonial.jpg` | `img/matrimonial-1.jpg`, `img/matrimonial-2.jpg`, `img/matrimonial-3.jpg` |
| Familiar 3 | `img/hero-familiar3.jpg` | `img/familiar3-1.jpg`, `img/familiar3-2.jpg`, `img/familiar3-3.jpg` |
| Familiar 4 | `img/hero-familiar4.jpg` | `img/familiar4-1.jpg`, `img/familiar4-2.jpg`, `img/familiar4-3.jpg` |
| Familiar 6 | `img/hero-familiar6.jpg` | `img/familiar6-1.jpg`, `img/familiar6-2.jpg`, `img/familiar6-3.jpg` |

(Portada horizontal 1920×900, galería 800×600.)

### Galería (`galeria.html`)
| Archivo | Uso |
|---|---|
| `img/hero-galeria.jpg` | Portada de la página (1920×900) |
| `img/galeria-1.jpg` … `img/galeria-9.jpg` | Cuadrícula de 9 fotos del hotel (áreas comunes, habitaciones, exterior, detalles) — 800×800 aprox. |

### Contacto (`contacto.html`)
| Archivo | Uso |
|---|---|
| `img/hero-contacto.jpg` | Portada de la página (recepción o entrada) — 1920×900 |

---

## Prioridad si no tienes todas las fotos todavía

Si quieres subir el sitio pronto sin esperar a tener el set completo, con estas
6 imágenes ya se ve muy bien:

1. `img/hero.jpg` — la más importante, es lo primero que se ve.
2. `img/room-king.jpg`, `img/room-matrimonial.jpg`, `img/room-familiar4.jpg`
3. `img/about.jpg`
4. 4-6 fotos para `img/galeria-1.jpg` en adelante.

El resto de los recuadros seguirán mostrando el nombre del archivo pendiente
hasta que los agregues — el sitio nunca se ve "roto".
