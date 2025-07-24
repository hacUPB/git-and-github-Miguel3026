# Como crear un repositorio remoto y sincronizarlo con Git

Para crear un repositorio remoto y sincronizarlo con tu repositorio local, sigue estos pasos:

1. **Crea un repositorio en GitHub**:
   - Ingresa a la plataforma y haz clic en "Nuevo repositorio".
   - Asigna un nombre y crea el repositorio.

2. **Obtén la URL del repositorio remoto** (por ejemplo: `https://github.com/usuario/nombre-repo.git`).

3. **Enlaza tu repositorio local con el remoto** usando el siguiente comando en la consola: "git remote add origin URL_DEL_REPOSITORIO"


4. **Envía tus cambios locales al repositorio remoto**: "git push -u origin main"