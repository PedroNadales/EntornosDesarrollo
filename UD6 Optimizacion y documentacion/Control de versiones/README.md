## 3. Control de versiones

Un sistema de control de versiones es una herramienta que ayuda a guardar y organizar los cambios que se hacen en los archivos de un proyecto. Permite que varias personas trabajen juntas, compartiendo y recibiendo cambios fácilmente

Existen varios sistemas de control de versiones, como CVS, Subversion, Mercurial y Git, pero el más usado hoy en día es Git

Git es moderno, rápido y distribuido. Esto significa que no necesita un único servidor central; cada persona puede tener una copia completa del proyecto y trabajar en ella. Cuando alguien copia un proyecto para hacer su propia versión, eso se llama "fork"

Estos sistemas ayudan a evitar errores, permiten volver a versiones anteriores si algo sale mal y facilitan la colaboración entre desarrolladores

## 3.1. Flujo de trabajo con Git (versión más simple)

**Guardar cambios (Commit)**
Cuando creas o modificas archivos, usas git add para prepararlos y luego git commit para guardar esos cambios en el historial del proyecto. Así, puedes volver a ese punto si lo necesitas más adelante

**Ramas (Branches)**
Con Git puedes trabajar en diferentes líneas de desarrollo llamadas ramas. La rama principal suele llamarse main o master. Puedes crear nuevas ramas con git branch y cambiar entre ellas con git checkout. Las ramas te permiten trabajar en nuevas funciones sin afectar el resto del proyecto. Es lo que yo suelo hacer en mis proyectos para así poder tener mas control sobre que está acabado y que no.

**Tipos de repositorio**

* **Local:** Es el repositorio en tu propio pc.
* **Remoto:** Es el repositorio en un servidor o en la nube, al que pueden acceder varias personas o tu mismo desde otro ordenador.

Puedes bajar los cambios del remoto con git pull y subir tus cambios con git push. Si solo quieres ver si hay cambios nuevos sin descargarlos, puedes usar git fetch.

**Plataformas y servidores**
Puedes usar servicios como GitHub, Bitbucket, GitLab o SourceForge para alojar tus repositorios remotos. También puedes tener tu propio servidor.

**Hooks**
Son acciones automáticas que puedes programar para que se ejecuten antes o después de ciertos comandos, como antes de hacer un commit o después de fusionar ramas.

**Conflictos**
Si dos personas cambian la misma parte de un archivo, puede haber un conflicto al juntar los cambios. En ese caso, tendrás que elegir qué versión dejar y guardar el archivo corregido con un nuevo commit.

**Otros comandos útiles**

* `git tag`: Poner etiquetas a los commits, por ejemplo, para marcar versiones.
* `git blame`: Ver quién hizo cada cambio en un archivo.
* `git log`: Ver el historial de cambios.
* `git revert` y `git reset`: Deshacer cambios o borrar commits.
* `git mv` y `git rm`: Mover o borrar archivos.

**Pull request (PR)**
En plataformas como GitHub, puedes pedir que tus cambios se unan al proyecto principal usando un "pull request". Así, otros pueden revisar y aprobar tus cambios antes de integrarlos como se realizó en el proyecto en grupo de la segunda Ev. de programación.

**.gitignore**
Este archivo sirve para decirle a Git qué archivos o carpetas no debe tener en cuenta, como archivos temporales o de configuración local y de esa manera no se suben a nuestro repositorio.

## 3.2. Integración con el IDE (IntelliJ)

En IntelliJ puedes:

* Crear proyectos nuevos desde un repositorio.
* Elegir qué archivos añadir, ver cambios y hacer commit, pull y push desde el panel lateral.
* Ver el historial y detalles de los cambios en el panel inferior.
* Cambiar de rama o fusionarlas desde la barra de estado.
* Ver resaltados los cambios y, a veces, quién los hizo, directamente en el código.

[Video a introduccion de control de versiones](https://www.youtube.com/watch?v=wJnPN-x80FM&ab_channel=NahumS%C3%A1nchez)
