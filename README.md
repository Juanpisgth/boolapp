# BoolApp

Calculadora de álgebra booleana con simplificación paso a paso, tablas de verdad y escáner opcional con Gemini.

## Probar localmente

Abre `index.html` en un navegador o sirve la carpeta con una extensión de servidor local de VS Code. El modo instalable y el uso sin conexión requieren HTTPS o `localhost`.

## Publicar con GitHub Pages

1. Sube este proyecto a un repositorio de GitHub.
2. En el repositorio, abre **Settings > Pages**.
3. En **Build and deployment**, elige **Deploy from a branch**, selecciona la rama principal y la carpeta `/(root)`, y pulsa **Save**.
4. Cuando termine la publicación, abre la URL que aparece en esa página de configuración. GitHub Pages sirve el sitio con HTTPS.

Al abrir el sitio publicado en un navegador compatible, puedes instalar BoolApp desde el icono de instalación o el menú del navegador. En iPhone/iPad, usa **Compartir > Añadir a pantalla de inicio**. La calculadora funciona sin conexión después de la primera carga; el escáner de Gemini necesita conexión y una clave API configurada en el dispositivo.

La clave API se guarda en el almacenamiento local del navegador y no está incluida en el repositorio. No publiques una clave personal dentro del código.
