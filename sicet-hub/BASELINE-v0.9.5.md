# SICET HUB v0.9.5 — BASELINE ESTABLE

Estado de referencia para restauracion.

- Worker: electronics-telmo-sync
- Dominio: https://api.electronicstelmo.com
- Endpoint MCP: https://api.electronicstelmo.com/mcp
- LIVE: desactivado
- Tiendanube: conservar KV/tokens existentes
- YouTube: conservar credenciales/tokens existentes
- Meta: no forma parte del baseline
- WhatsApp: no forma parte del baseline
- Google Shopping: gestionado mediante Tiendanube

## Gate obligatorio antes de evolucionar
1. Panel responde.
2. MCP responde.
3. Lectura real de Tiendanube responde.
4. Estado de YouTube responde sin romper el nucleo.
5. Ningun secreto se almacena en GitHub.

A partir de este baseline, cada integracion nueva debe quedar aislada y no puede impedir que respondan las rutas anteriores.
