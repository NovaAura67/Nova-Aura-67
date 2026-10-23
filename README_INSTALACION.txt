NOVA AURA 67 V1.8 PWA — PAQUETE DE PUBLICACIÓN

1. Descomprime este ZIP.
2. Abre config.js y reemplaza PEGA_AQUI_TU_CLAVE_PUBLICABLE por la clave PUBLICABLE de Supabase (NO uses service_role ni secret).
3. En GitHub > NovaAura67/Nova-Aura-67 > Code > Add file > Upload files, carga todos los archivos y la carpeta assets, conservando los nombres.
4. Confirma cambios en main. GitHub Pages debe estar configurado para main / (root).
5. Abre https://novaaura67.github.io/Nova-Aura-67/ y fuerza recarga Ctrl+Shift+R.
6. Administración: https://novaaura67.github.io/Nova-Aura-67/admin.html
7. Ingresa con el correo y la contraseña del usuario Supabase Auth ya registrado y autorizado en nova_admin_users.

NOTAS IMPORTANTES
- El ZIP no contiene contraseñas ni claves secretas.
- No basta con abrir index.html localmente para probar la conexión: publica en GitHub Pages.
- Las pantallas públicas se pueden consultar sin conexión tras su primera carga, pero encuestas y sincronización necesitan internet.
- No se modificó el SQL ya ejecutado en Supabase.
- Esta versión corrige la referencia OFFICIAL_LOGO ausente en index.html y añade archivos PWA.
- La autenticación administrativa usa Supabase Auth y la tabla nova_admin_users: no se guarda contraseña en HTML.
- Para votaciones oficiales se requieren controles adicionales de identidad y antiabuso.
