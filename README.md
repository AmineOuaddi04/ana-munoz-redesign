# Ana Muñoz · concepto de rediseño

Demo editorial local de Peluquería Ana Muñoz, Av. de Colón 9, Logroño.

El archivo **05-ana-munoz-demo.zip** contiene el proyecto completo: código fuente, web estática compilada, fotografías, fuente tipográfica y licencia, documentación y scripts de apertura para Windows.

Descarga el ZIP desde este repositorio y descomprímelo. Haz clic derecho en `Abrir-demo.ps1` y elige **Ejecutar con PowerShell**. Alternativa con Node 22 o posterior, desde la carpeta extraída:

```
node serve.mjs
```

Abre http://127.0.0.1:4174/. No necesita instalar dependencias. Para reconstruir y comprobar enlaces:

```
node build.mjs
node check.mjs
```

8 páginas, índice contextual de servicios, navegación y contacto con diálogo, galería de archivo, composición específica para móvil, FAQs, metadatos y JSON-LD. Comprobados 222 recursos/enlaces locales y 10 anchos de pantalla, sin desbordamiento horizontal. Se han revisado en navegador apertura, servicios, Ana, eventos, salón, contacto, menú, Escape, ciclo de foco y galería. Queda una revisión final en dispositivos y navegadores reales antes de producción.

## Qué falta para publicar

1. Fotografías actuales autorizadas de cortes, color, eventos, Ana y equipo. Los espacios pendientes están señalados. Las cuatro fotografías auténticas utilizadas son archivo de noviembre de 2020; vigencia e identidades no se han confirmado y no se ha obtenido permiso de reutilización en producción.
2. Confirmar servicios concretos, biografía, precios, procesos de consulta privada, maquillaje/desplazamientos, horarios y canal de citas. Los datos no verificados llevan `[CONFIRM WITH CLIENT: ...]`.
3. Completar avisos legales y el mapa de rutas históricas; validar accesibilidad y rendimiento final con las fotos definitivas. Elegir hosting, revisar canonicals y redirecciones y habilitar indexación al publicar.

La demo no modifica la web actual, no envía formularios, no reserva citas, no contacta al salón y no contiene fotografías falsas de trabajos o clientes. Está configurada para no indexarse. La dirección, contactos, horarios y valoración de Google corresponden a la consulta pública del 2/10/2026. El ZIP incluye procedencia y límites de uso de las imágenes en `FUENTES_FOTOGRAFIAS.json`.
