# Dashboard de Fondeo

Dashboard de cuenta para traders de una empresa de fondeo: balance, gráfico de equity, objetivos de trading (profit target, consistencia, pérdida diaria, pérdida máxima), calendario de PnL, trades, estadísticas y scaling plan.

Incluye un **Panel de pruebas** (botón azul abajo a la derecha) para cargar números ficticios: datos de la cuenta, reglas, P&L por día y escenarios rápidos (aprobada, falla de consistencia, cuenta quemada). Los cambios se guardan en el `localStorage` del navegador.

## Estructura

- `index.html`: la app completa (HTML, CSS y JS sin dependencias ni build).

## Correr en local

Abrí `index.html` en el navegador, o:

```bash
npx serve .
```

## Deploy

Sitio estático. En Vercel no requiere build command ni output directory: cada push a `main` despliega a producción.
