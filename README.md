# Tarjeta de perfil responsiva

Proyecto de una tarjeta de perfil creada con HTML y CSS, siguiendo un enfoque mobile-first. Se adapta a móviles, tabletas y pantallas de escritorio.

## Archivos

- `index.html`: estructura y contenido de la tarjeta.
- `styles.css`: estilos base y ajustes responsivos.
- `avatar.svg`: ilustración usada como avatar.

## Cómo abrir el proyecto

No necesitas instalar dependencias ni compilar archivos. Abre `index.html` directamente en un navegador, o usa una extensión como Live Server en Visual Studio Code para recargar los cambios automáticamente.

## Diseño responsivo

- **Desde 320 px:** tarjeta de ancho disponible, estadísticas apiladas y botones táctiles.
- **Desde 768 px:** aumenta el espacio, el avatar crece y las estadísticas y acciones se muestran en fila.
- **Desde 1024 px:** la tarjeta queda centrada y limita su ancho máximo a `32rem`.

Para comprobar los tamaños, abre las herramientas de desarrollo del navegador, activa el modo dispositivo y prueba anchos de 320, 768 y 1024 px.

## Personalización

- Edita el nombre, rol, biografía y estadísticas en `index.html`.
- Para cambiar la imagen, modifica el atributo `src` de `.card__avatar` y coloca el nuevo archivo en la carpeta del proyecto.
- Ajusta colores, espaciado y puntos de corte en `styles.css`.
