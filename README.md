# Sagás Sales Reports

Reportes versionados de estrategia de ventas de Sagás.

## Publicación actual

- Reporte: Sagás: estrategia de ventas en ejecución
- Snapshot de datos: 2026-09-09 12:08 America/Santiago
- Versión estable: `reports/2026-09-09-budget-reduction/`
- `index.html` siempre apunta a la versión más reciente publicada.

## Convención para futuras versiones

Cada actualización debe:

1. Mantener una copia inmutable en `reports/YYYY-MM-DD/`; si hay más de un checkpoint el mismo día, usar `reports/YYYY-MM-DD-descriptor/`.
2. Reemplazar `index.html` y `artifact.json` con la versión vigente.
3. Conservar sólo datos agregados sin correos, teléfonos ni direcciones.
4. Registrar el cambio en un commit antes de publicar GitHub Pages.

El reporte es un snapshot, no una conexión de datos en vivo.
