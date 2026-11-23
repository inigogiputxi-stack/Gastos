# Mis gastos (PWA)
1. Crea un repositorio en GitHub y sube TODO el contenido de esta carpeta a la raíz (no la carpeta en sí).
2. Settings → Pages → Source: "Deploy from a branch" → rama main, carpeta / (root) → Save.
3. Espera 1-2 min y abre https://TU_USUARIO.github.io/TU_REPO/
4. Ordenador: icono de instalar en la barra de Chrome/Edge. iPhone/iPad: Safari → Compartir → Añadir a pantalla de inicio (tiene que ser Safari).
5. Al cambiar index.html, sube también sw.js con V="gastos-v3" (v4...) o los dispositivos seguirán con la versión antigua.
Excel esperado: hoja "Gastos" con columnas Fecha, Ámbito, Comercio, Categoría, Importe, Moneda, Cambio a EUR, Importe EUR, Transferencia propia.
Los datos se guardan solo en el navegador del dispositivo; guarda siempre el Excel como copia.
Hoja "Listas" del Excel: edita categorías, tope del plan (%), tipo (suscripción/comisión/fijo) y personas. La app las lee al cargar el Excel.
