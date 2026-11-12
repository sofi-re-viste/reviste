# Re-vist(e) · moda circular

Web de la tienda de moda circular de Sofía Faga (proyecto escolar).

## Publicar la web (una sola vez)

1. En GitHub entrá a **Settings > Pages**.
2. En *Source* elegí **Deploy from a branch**, rama `main`, carpeta `/ (root)` y tocá **Save**.
3. En un par de minutos la web queda en `https://sofi-re-viste.github.io/reviste/`.

## Editar los productos desde una planilla de Google

1. Abrí Google Sheets y creá una planilla nueva.
2. **Archivo > Importar > Subir** y elegí `productos.csv` de este repositorio (descargalo antes). Elegí *Reemplazar hoja actual*.
3. **Archivo > Compartir > Publicar en la web**. Elegí la hoja y el formato **Valores separados por comas (.csv)**. Tocá **Publicar** y copiá el link.
4. En GitHub abrí `config.js`, tocá el lápiz para editar y pegá el link entre las comillas de `PLANILLA_CSV`. Guardá con **Commit changes**.

Listo: desde ahora cada cambio en la planilla aparece en la web. Google tarda unos **5 minutos** en actualizar la versión publicada.

### Columnas de la planilla

| Columna | Qué poner | Ejemplo |
|---|---|---|
| nombre | Nombre de la prenda | Jean mom fit |
| categoria | Se usa para los filtros | Pantalones |
| talle | Talle | 38 |
| estado | Como nuevo / Muy bueno / Buen estado | Muy bueno |
| precio | Precio de venta, sin puntos ni $ | 18000 |
| precio_nuevo | Lo que cuesta nueva (opcional, muestra el ahorro) | 55000 |
| descripcion | Texto del detalle | Tiro alto y pierna recta. |
| foto | Link de Google Drive, link de una imagen, o nombre de un archivo de la carpeta `fotos` | jean.jpg |
| dibujo | Si no hay foto: remera, vestido, jean, campera, sweater, pollera, camisa, cartera, short | jean |
| color | Color del dibujo: rosa, bordo, salvia, petroleo, jean, crema, blanco, negro, gris, marron | jean |
| rayas | Color de rayas del dibujo (opcional) | bordo |
| vendido | Escribí **si** cuando se venda | si |

- Para **agregar** una prenda, sumá una fila. Para **sacarla**, borrá la fila.
- **Fotos desde Google Drive:** subí la foto a Drive, tocá *Compartir* > *Cualquier persona con el enlace* y pegá ese link en la columna `foto`.

## Datos de contacto

El WhatsApp, Instagram, email y horarios están en `index.html`, en la sección *Contacto* (buscá `wa.me`).
