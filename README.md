# Ruta de Estudio Refinería

App web instalable (PWA) con el plan de estudio de ingeniería química para procesos de refinación: 4 bloques, 36 semanas y 4 entregables, con seguimiento de avance.

## Archivos

| Archivo | Para qué sirve |
| --- | --- |
| `index.html` | La app completa |
| `manifest.webmanifest` | Nombre, colores e íconos al instalarla |
| `sw.js` | Permite usarla sin conexión |
| `icons/` | Íconos de la app (180, 192 y 512 px) |

## Publicarla en GitHub Pages

1. En GitHub, crea un repositorio nuevo y público, por ejemplo `ruta-refineria`.
2. Entra al repositorio y elige **Add file > Upload files**.
3. Arrastra `index.html`, `manifest.webmanifest`, `sw.js`, `README.md` y la carpeta `icons` completa. Confirma con **Commit changes**.
4. Ve a **Settings > Pages**. En **Source** elige **Deploy from a branch**, rama `main`, carpeta `/ (root)`, y guarda.
5. Espera uno o dos minutos. La dirección será `https://TU-USUARIO.github.io/ruta-refineria/`.

## Instalarla en el iPhone

1. Abre la dirección en **Safari**.
2. Toca **Compartir** y luego **Añadir a pantalla de inicio**.
3. Abre la app desde el ícono nuevo. La primera vez necesita conexión; después funciona sin internet.

## Tu avance

- El avance se guarda solo en el dispositivo donde lo marcas. No se sincroniza entre el iPhone y el computador.
- Safari y la app instalada guardan datos por separado: marca tu avance siempre desde el ícono instalado.
- En **Resumen > Copia de seguridad** puedes exportar el avance a un archivo e importarlo en otro dispositivo.

## Actualizar la app

Sube los archivos nuevos al repositorio y cambia el número de versión en la primera línea de `sw.js` (`ruta-refineria-v1` a `ruta-refineria-v2`).
