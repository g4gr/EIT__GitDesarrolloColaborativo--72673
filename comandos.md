

## Comandos de trabajo de bash

- `cd` > Permite cambiar de directorio.
- `cd ..` > Permite subir un nivel de directorio desde el actual.
- `ls` > Permite ver el historial de directorios.

- `ls -a` > Permite ver todos los directorios y archivos.
- `ls -h` > Permite ver el historial de directorios.
- `ls -l` > Permite listar los archivos con informacion del sistema.

- `mkdir` > Permite crear directorios.
- `touch` > Permite crear archivos.

- `mv` > Permite mover archivos y directorios.
- `cp` > Permite copiar archivos y directorios.

--
### Comandos peligrosos
Porque ? Porque no son reversibles. Unos los borra y nunca mas los puede recuperar.

- `rm` > Permite borrar archivos.
- `rm -h` > Permite ver el historial de directorios.
- `rm -f` > Permite borrar archivos de forma forzada.
- `rm -d` > Permite borrar directorios.
- `rm -r` > Permite borrar directorios de forma recursiva.

## Comandos de Git

- `git init` > Era comando que permite crear un nuevo repositório git ( Crear la carpeta oculta '.git' ).
- `git status` > Permite ver el estado del repositório git y las ramas ( No es necesario estar en la rama 'main' ).
- `git log` > Permite ver el historial de commits.
- `git show` > Permite ver el historial de commits con mas informacion (diferencias entre commits).
- `git show --oneline` > Permite ver el historial de commits en linea.

- `git config --local user.name "[ Tu nombre ]"` > Permite configurar el nombre de usuario.
- `git config --local user.email "[ Tu correo ]"` > Permite configurar el correo.
- `git config --local core.editor "vim"` > Permite configurar el editor.


---
## Como crear un template usando Perplexity

¡Claro, con gusto te explicaré cómo crear un template para los commits en Git! Los comandos necesarios son los siguientes:

## Crear un template para los commits

### Paso 1: Crear el archivo de template
Primero, debes crear un archivo que contendrá el template para tus commits. Puedes hacerlo con tu editor de texto favorito. Por ejemplo, puedes crear un archivo llamado `.gitCommitTemplate` en la raíz de tu proyecto.

### Paso 2: Definir el contenido del template
Dentro del archivo, puedes definir la estructura que deseas que tengan tus commits. Aquí te doy un ejemplo de un template básico:

```
# Tipo de cambio (feat, fix, docs, style, refactor, test, chore)

# Descripción corta del cambio (máximo 50 caracteres)

# Descripción más detallada del cambio (opcional)

# Ticket relacionado (si aplica)
```

Puedes personalizar este template según tus necesidades, agregando más secciones o cambiando el formato.

### Paso 3: Configurar Git para usar el template
Ahora, debes indicarle a Git que use este archivo como template para tus commits. Puedes hacerlo con el siguiente comando:

```
git config --local commit.template .gitCommitTemplate
```

Este comando establece el archivo `.gitCommitTemplate` como el template predeterminado para tus commits.

### Paso 4: Probar el template
A partir de ahora, cada vez que ejecutes `git commit`, Git abrirá tu editor de texto con el template precargado. Simplemente debes completar las secciones y guardar el archivo para crear el commit.

Y eso es todo. Con estos pasos, habrás configurado un template personalizado para tus commits en Git. Esto te ayudará a mantener una estructura consistente y mejorar la calidad de tus mensajes de commit.

¡Espero que esta explicación haya sido clara y útil! Si tienes alguna otra pregunta, no dudes en consultarme.

---
