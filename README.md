# El Especiero

Página de stock, ventas y caja para el negocio de especias.
Los datos se guardan en Firebase (Firestore) y se actualizan en vivo en todos los celulares.

## Archivos

- `index.html`: la página completa.
- `firestore.rules`: las reglas de acceso para pegar en Firebase.

## Cómo publicarla

1. **Firebase:** crear el proyecto, crear la base Firestore, pegar las reglas y copiar la configuración web.
2. **index.html:** pegar la configuración en el bloque `firebaseConfig`, casi al final del archivo.
3. **GitHub:** crear un repositorio y subir los archivos.
4. **Vercel:** importar el repositorio y tocar Deploy.

Cada vez que cambies algo en GitHub, Vercel publica la nueva versión solo.
