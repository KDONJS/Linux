#comandos de inicio de la terminal
 - pwd => muestra la ruta actual
    - ls -l => lista los archivos y carpetas
    - cd => cambiar de directorio
    - cd .. => regresa al directorio anterior
    - cd ~ => este comando nos lleva a la carpeta home
    - cd / => este comando nos lleva a la carpeta raiz
    - cd - => este comando nos lleva al ultimo directorio que visitamos
    - mkdir => crea una carpeta
    - touch => crea un archivo
    - rm => elimina un archivo
    - rm -r => elimina una carpeta
    - rm -rf => elimina una carpeta y su contenido
    - mv => mueve un archivo o carpeta
    - cp => copia un archivo o carpeta
    - cat => muestra el contenido de un archivo
    - nano => abre un archivo en el editor nano
    - clear => limpia la terminal
    - history => muestra el historial de comandos ejecutados
    - history -c => limpia el historial de comandos 
    - history -w => guarda el historial de comandos en el archivo .bash_history
    - history -r => lee el historial de comandos guardado
    - history -a => agrega el historial de comandos al final del archivo
    - history -n => muestra el historial de comandos desde la linea n
    - history -d => elimina el historial de comandos en la linea n
    - history -p => muestra el historial de comandos en formato de comandos
    - history -s => agrega el historial de comandos en la linea n
    - history -t => muestra el historial de comandos con la fecha y hora
    - sudo => ejecuta un comando como administrador
    - sudo -i => ejecuta la terminal como administrador
    - sudo -s => ejecuta la terminal como administrador y muestra el usuario
    - sudo -u => ejecuta un comando como otro usuario
    - sudo -l => muestra los permisos del usuario
    - sudo -k => elimina la autenticacion del usuario
    - sudo -v => verifica la autenticacion del usuario

[ 1 ]: # Path: comandosInicio.md

| Nombre | Version | Año | Desarrollador    |
|--------|---------|-----|------------------|
| Ubuntu | 20.04   | 2020 | Canonical       |
| Debian | 10      | 2019 | Debian          |
| Fedora | 32      | 2020 | Red Hat         |
| CentOS | 8       | 2019 | Red Hat         |
| OpenSuse| 15.1    | 2019 | Suse           |
| Arch   | 2020.06.01 | 2020 | Arch Linux   |
| Manjaro| 20.0.3  | 2020 | Manjaro         |
| Mint   | 19.3    | 2019 | Linux Mint      |
| Kali   | 2020.1  | 2020 | Offensive Security | 
| Parrot | 4.8     | 2020 | Parrot Security |

#comandos de git 

    - git init => inicializa un repositorio
    - git add => agrega un archivo al repositorio
    - git commit => guarda los cambios en el repositorio
    - git status => muestra el estado del repositorio
    - git log => muestra el historial de cambios
    - git log --oneline => muestra el historial de cambios en una sola linea
    - git log --graph => muestra el historial de cambios en forma de grafo
    - git log --decorate => muestra el historial de cambios con decoracion
    - git log --all => muestra el historial de cambios de todas las ramas
    - git log --author => muestra el historial de cambios de un autor
    - git log --grep => muestra el historial de cambios con un patron
    - git log -S => muestra el historial de cambios con un patron
    - git log --since => muestra el historial de cambios desde una fecha
    - git log --until => muestra el historial de cambios hasta una fecha
    - git log --after => muestra el historial de cambios despues de una fecha
    - git log --before => muestra el historial de cambios antes de una fecha
    - git log --oneline --graph --decorate --all --author --grep -S --since --until --after --before
    - git diff => muestra las diferencias entre el repositorio y el directorio de trabajo
    - git diff --staged => muestra las diferencias entre el repositorio y el area de preparacion
    - git diff --cached => muestra las diferencias entre el repositorio y el area de preparacion
    - git diff --name-only => muestra las diferencias entre el repositorio y el directorio de trabajo en forma de nombre de archivos
    - git diff --name-status => muestra las diferencias entre el repositorio y el directorio de trabajo en forma de nombre de archivos y estado
    - git diff --stat => muestra las diferencias entre el repositorio y el directorio de trabajo en forma de estadisticas
    - git diff --summary => muestra las diferencias entre el repositorio y el directorio de trabajo en forma de resumen
    - git diff --patch => muestra las diferencias entre el repositorio y el directorio de trabajo en forma de parche
    - git diff --color-words => muestra las diferencias entre el repositorio y el directorio de trabajo en forma de palabras con color
    - git diff --word-diff => muestra las diferencias entre el repositorio y el directorio de trabajo en forma de palabras
    - git diff --word-diff-regex => muestra las diferencias entre el repositorio y el directorio de trabajo en forma de palabras con un patron
    - git diff --check => muestra las diferencias entre el repositorio y el directorio de trabajo en forma de comprobacion 
    - git diff --binary => muestra las diferencias entre el repositorio y el directorio de trabajo en forma de binario
    - git diff --raw => muestra las diferencias entre el repositorio y el directorio de trabajo en forma de crudo
    - git diff --abbrev => muestra las diferencias entre el repositorio y el directorio de trabajo en forma de abreviacion
    - git diff --full-index => muestra las diferencias entre el repositorio y el directorio de trabajo en forma de indice completo
    - git diff --src-prefix => muestra las diferencias entre el repositorio y el directorio de trabajo en forma de prefijo de origen
    - git diff --dst-prefix => muestra las diferencias entre el repositorio y el directorio de trabajo en forma de prefijo de destino
    - git diff --no-prefix => muestra las diferencias entre el repositorio y el directorio de trabajo en forma de sin prefijo
    - git diff --diff-algorithm => muestra las diferencias entre el repositorio y el directorio de trabajo en forma de algoritmo de diferencias
    - git rebase => reorganiza los commits
    - git rebase --continue => continua el rebase
    - git rebase --abort => aborta el rebase
    - git rebase --skip => salta el rebase
    - git rebase --onto => reorganiza los commits en un rango
    - git rebase --interactive => reorganiza los commits de forma interactiva
    - git rebase --merge => reorganiza los commits de forma interactiva con merge 
    - git rebase --preserve-merges => reorganiza los commits de forma interactiva con merge y preservando los merges
    - git rebase --root => reorganiza los commits de forma interactiva desde la raiz
    - git rebase --exec => reorganiza los commits de forma interactiva con un comando
    - git rollback => reorganiza los commits de forma interactiva con un comando

    #tabla de comandos de git

| Comando | Descripcion |
|---------|-------------|
| git init | inicializa un repositorio |
| git add | agrega un archivo al repositorio |
| git commit | guarda los cambios en el repositorio |
| git status | muestra el estado del repositorio |
| git log | muestra el historial de cambios |
| git log --oneline | muestra el historial de cambios en una sola linea |
| git log --graph | muestra el historial de cambios en forma de grafo |
| git log --decorate | muestra el historial de cambios con decoracion |
| git log --all | muestra el historial de cambios de todas las ramas |
| git log --author | muestra el historial de cambios de un autor |
| git log --grep | muestra el historial de cambios con un patron |
| git log -S | muestra el historial de cambios con un patron |
| git log --since | muestra el historial de cambios desde una fecha |
| git grep --until | muestra el historial de cambios hasta una fecha |
| git log --after | muestra el historial de cambios despues de una fecha |
| git log --before | muestra el historial de cambios antes de una fecha |
