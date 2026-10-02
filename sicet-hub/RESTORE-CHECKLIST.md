# SICET HUB — Restore gate

Baseline: v0.9.5

## No modificar durante restauracion
- KV y tokens de Tiendanube
- credenciales y token de YouTube
- dominio api.electronicstelmo.com
- secretos de Cloudflare

## Validacion obligatoria
- panel `/` responde
- `/mcp` responde
- lectura real de productos Tiendanube responde
- `/api/youtube/status` responde
- LIVE permanece desactivado

## Fuera del restore
- Meta
- WhatsApp
- cambios de Google Merchant

Solo despues de completar este gate se integra Meta desde la rama `sicet-hub-meta`.
