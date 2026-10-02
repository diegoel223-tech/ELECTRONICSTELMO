# SICET HUB — Electronics Telmo

Fuente maestra del proyecto SICET HUB.

## Baseline estable
- Version: v0.9.5
- Worker: electronics-telmo-sync
- Dominio: https://api.electronicstelmo.com
- LIVE: desactivado durante restauracion y validacion

## Regla de versiones
Los cambios nuevos se desarrollan y validan separados del baseline estable. No se reemplaza la base estable hasta verificar panel, MCP, Tiendanube y conectores activos.

## Arquitectura comercial
- Tiendanube: catalogo comercial maestro
- Google Shopping: sincronizacion mediante Tiendanube
- SICET HUB: API y orquestacion
- Meta: modulo separado
- WhatsApp: fuera de la restauracion inicial

No guardar secretos, tokens ni claves privadas en este repositorio.
