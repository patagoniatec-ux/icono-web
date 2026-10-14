# Estudio Web · Pantalla de inicio

Escritorio personal adaptable a computadora y celular. Incluye buscador de Google, herramientas y redes, tarjetas de sitios con enlaces de administración y GitHub, categorías editables, archivo de sitios, tres accesos a carpetas Dropbox y favoritos.

## Uso

- Abrir `index.html` para una vista local o publicar en GitHub Pages.
- Usar **Agregar sitio** y los menús de cada tarjeta para editar, archivar, restaurar o quitar accesos. Quitar un acceso no elimina la web ni el repositorio.
- **Administrar** abre el panel propio del sitio cuando se carga su dirección. Los enlaces pendientes abren el formulario de edición; este escritorio no crea ni autentica los paneles de las otras webs.
- Las carpetas Dropbox son enlaces: crear o elegir cada carpeta en Dropbox y pegar su dirección con el lápiz. No se han creado carpetas ni subido documentos a Dropbox.
- Instagram y TikTok apuntan inicialmente al inicio del servicio; editar para cargar los perfiles de Marcelo.
- Cargar los enlaces pendientes de Portal CET 33 e Impresión 3D. Dibujo Técnico utiliza provisionalmente el aula COTV existente y el repositorio dibujo-cad.
- Guardar páginas con **Guardar enlace**. Se filtran por categoría.
- En ⚙ se pueden administrar categorías y herramientas, descargar e importar respaldos JSON.

## Guardado y privacidad

Los cambios y favoritos se guardan con `localStorage` en este navegador y origen. No hay sincronización automática entre dispositivos. Descargar el respaldo e importarlo en el otro dispositivo permite trasladar la organización. Borrar los datos del navegador elimina el guardado local. En modo privado puede desaparecer al cerrar la sesión.

El sitio y sus accesos iniciales son públicos; los cambios personales se mantienen en el navegador. No guardar contraseñas ni tokens. Abrir Gmail, Dropbox y otros servicios requiere la sesión correspondiente; el escritorio no recibe sus credenciales.

## GitHub Pages

Se incluye un flujo de publicación en `.github/workflows/pages.yml`. En **Settings → Pages → Build and deployment → Source**, elegir **GitHub Actions** y ejecutar el flujo **Publicar Estudio Web**. Los archivos se publican tal cual, sin dependencias ni compilación.

URL prevista: https://patagoniatec-ux.github.io/icono-web/

## Acceso directo

En el pie del sitio, **Crear acceso directo** explica cómo agregarlo al escritorio de Windows o a la pantalla principal del teléfono. Incluye manifest, iconos PNG y un service worker que conserva la pantalla para uso sin conexión tras la primera carga. Buscar en Google o abrir servicios externos requiere internet.

## Archivos

- `index.html`: estructura y formularios accesibles.
- `style.css`: diseño adaptable.
- `app.js`: edición, categorías, favoritos, respaldo e instalación.
- `assets/`: portadas de la propuesta visual e iconos locales.
- `manifest.webmanifest`, `sw.js`: acceso instalado y caché local.
- `.github/workflows/pages.yml`: publicación de GitHub Pages.

No requiere servidor, claves API ni planes pagos.
