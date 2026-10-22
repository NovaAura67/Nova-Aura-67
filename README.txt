NOVA AURA 67 V1.7 - PUBLICACIÓN

1. Subir index.html, admin.html y config.js juntos a la raíz de GitHub Pages.
2. Crear un proyecto Supabase y ejecutar schema.sql en SQL Editor.
3. Configurar supabaseUrl y supabaseAnonKey (clave PUBLICA, nunca service_role) en config.js.
4. Crear usuario en Supabase Authentication > Users. Agregar su UUID a nova_admin_users usando SQL Editor (como propietario del proyecto).
5. Iniciar sesión en admin.html y cargar/publicar contenido.
6. En index.html solo se entrega código público; admin.html sigue siendo URL conocida, pero necesita login y RLS.
7. No publiques credenciales privadas. GitHub Pages es público.
8. Las imágenes se guardan como data URLs dentro de JSON: límite de tamaño. Para producción con muchas imágenes migrar a Supabase Storage.
9. La función de votación requiere RPC y controles antiabuso adicionales para elecciones formales; no usar para elecciones oficiales sin auditoría.
10. V1.5 y V1.6 permanecen intactas.

Estado: prototipo listo para configuración; no está desplegado ni se han ejecutado pruebas de navegador o conectividad reales.
