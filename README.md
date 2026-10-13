# Un regalo para mi amor 💖

Una pequeña app web de cumpleaños, diseñada para móviles y lista para instalarse en la pantalla de inicio de Android o iPhone. No necesita instalar programas de programación ni usar una tienda de aplicaciones.

## Qué incluye

- Cuatro temas: rosa romántico, lavanda, jardín y noche estrellada.
- Carta de cumpleaños personalizable.
- Lista interactiva de razones por las que quieres a tu novia.
- Cuenta atrás opcional para su cumpleaños.
- Sorpresa con confeti y diseño adaptable a móvil.
- Un enlace personalizado para compartir el nombre, la carta, las razones, la fecha y el tema.
- Funciones básicas sin conexión después de la primera carga, gracias al service worker.

## Guía fácil: ponerla en internet gratis con GitHub Pages

### 1. Descarga y descomprime

1. Descarga el archivo ZIP que acompaña a este proyecto.
2. En Windows, abre la carpeta **Descargas**.
3. Haz clic derecho sobre el ZIP y selecciona **Extraer todo**.
4. Entra en la carpeta extraída. Debes ver `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png` y `icon-512.png`.

### 2. Crea una cuenta gratuita de GitHub

1. Abre https://github.com en el navegador.
2. Crea una cuenta o inicia sesión.
3. Confirma tu correo si te lo solicita.

### 3. Crea el espacio de tu app

1. Abre https://github.com/new.
2. En **Repository name**, escribe `regalo-cumple`.
3. Elige **Public** (GitHub Pages gratuito necesita un repositorio público en este flujo).
4. Puedes activar **Add a README file**.
5. Pulsa **Create repository**.

**Importante:** el código del proyecto estará visible públicamente. No pongas contraseñas, direcciones, secretos ni datos privados en los archivos del proyecto.

### 4. Sube los archivos

1. En el repositorio nuevo, pulsa **Add file** y después **Upload files**.
2. Abre la carpeta extraída del ZIP en el Explorador de archivos de Windows.
3. Arrastra los archivos de la app a la página de GitHub. Asegúrate de subir `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png` e `icon-512.png` en la raíz del repositorio, no dentro de otra carpeta.
4. Baja hasta el final y pulsa **Commit changes**.

### 5. Activa la página web

1. En tu repositorio, entra en **Settings**.
2. En el menú lateral, abre **Pages**.
3. En **Build and deployment**, busca **Source** y selecciona **Deploy from a branch**.
4. En **Branch**, elige `main` y la carpeta `/(root)`.
5. Pulsa **Save**.
6. Espera a que termine la publicación. La dirección suele tener este formato:
   `https://TU-USUARIO.github.io/regalo-cumple/`
   Sustituye `TU-USUARIO` por tu nombre de usuario de GitHub. La dirección exacta aparece en la página **Settings → Pages**.

### 6. Personaliza el regalo y comparte el enlace

1. Abre la dirección publicada.
2. Pulsa **Personalizar**.
3. Escribe el nombre o apodo de tu novia, elige su cumpleaños, redacta tu carta y escribe una razón por línea.
4. Pulsa **Guardar cambios**.
5. Pulsa **Crear enlace para ella** y comparte el enlace copiado por WhatsApp u otro chat.

El enlace lleva dentro el texto personalizado y el tema, por lo que ella podrá verlo desde su móvil. Cualquiera que reciba ese enlace podrá leer esos textos: compártelo solo con quien quieras. El botón no sube tus textos a una base de datos; están codificados dentro del enlace.

### 7. Añádela a la pantalla de inicio

**En Android:** abre el enlace en Chrome. Abre el menú de tres puntos y selecciona **Instalar app** o **Añadir a pantalla de inicio** si aparece.

**En iPhone:** abre el enlace en Safari, pulsa **Compartir**, después **Añadir a pantalla de inicio** y finalmente **Añadir**. Si aparece **Abrir como app web**, actívalo.

## Solución de problemas

- **La página no aparece todavía:** espera un poco y revisa `Settings → Pages` para ver el estado y la dirección publicada.
- **No se ve el botón de instalación:** primero abre la dirección publicada con `https://`, no el archivo local del ordenador. En iPhone usa Safari.
- **El enlace personalizado no se copia:** abre la app publicada con HTTPS. Si el navegador bloquea el portapapeles, la app muestra el enlace en un cuadro de texto para copiarlo manualmente.
- **He hecho cambios pero ella no los ve:** vuelve a abrir **Personalizar**, guarda los cambios y crea un enlace nuevo. Cada enlace conserva la configuración que tenía al crearse.

## Archivos

- `index.html`: diseño, textos e interacciones.
- `manifest.webmanifest`: nombre e iconos de instalación.
- `sw.js`: caché básica para abrir la app cuando no hay conexión después de haberla cargado una vez.
- `icon-192.png` y `icon-512.png`: iconos de la app.
