# medirayn.com

Sitio web público de **MEDIRAYN** — control y reducción de ausentismo laboral, auditoría de reposos médicos, bienestar corporativo (call center activo, terapias in company, masoterapia, primeros auxilios) y el programa escolar **Salud en Aula**.

Página estática de una sola pieza (`index.html`), sin dependencias de build.

## Publicar con GitHub Pages

1. **Settings → Pages** en este repositorio.
2. **Source:** `Deploy from a branch` → branch `main`, carpeta `/ (root)`.
3. El archivo `CNAME` ya apunta a `medirayn.com`. En tu proveedor de DNS, configura:
   - Un registro `A` apuntando el dominio raíz a las IPs de GitHub Pages (`185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`), o
   - Un `CNAME` de `www` hacia `medirayn.github.io` (ajusta según cómo esté configurado el resto del dominio).
4. Activa "Enforce HTTPS" en Settings → Pages una vez el DNS propague.

## Pendientes a revisar

- Confirmar/actualizar el número de WhatsApp y el email de contacto en la sección de contacto (`#contacto`) si cambian.
- El formulario de contacto es solo de interfaz (no envía datos a ningún backend todavía) — conectar a un servicio de formularios o backend propio cuando se defina.
- Revisar textos legales (política de privacidad, términos) antes de producción.
