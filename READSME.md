# Los principales comandos que se utilizan en Git

**Git** es una herramienta que permite llevar el control de versiones de un proyecto, facilitando el trabajo colaborativo y el seguimiento de los cambios en el código.

## 🟢 git init  
Inicializa un nuevo repositorio en la carpeta actual.  
Crea una carpeta oculta llamada `.git` donde se guarda el historial del proyecto.
```bash
git init
🟢 git add
Agrega los archivos modificados al área de preparación (staging area).

bash
Copiar código
# Agregar un archivo específico
git add archivo.txt

# Agregar todos los archivos
git add .
🟢 git commit
Guarda los cambios confirmados en el historial del repositorio, con un mensaje descriptivo.

bash
Copiar código
git commit -m "Agrego el archivo de configuración"
🟢 git status
Muestra el estado actual del repositorio: qué archivos han sido modificados o están listos para commit.

bash
Copiar código
git status
🟢 git log
Muestra el historial de commits realizados, con autor, fecha y mensaje.

bash
Copiar código
git log
🟢 git branch
Permite listar, crear o eliminar ramas del proyecto.

bash
Copiar código
# Listar ramas
git branch

# Crear una nueva rama
git branch nueva-rama
🟢 git checkout
Permite cambiar de una rama a otra o restaurar versiones anteriores de archivos.

bash
Copiar código
git checkout main
🟢 git merge
Combina los cambios de una rama con otra.

bash
Copiar código
git merge nueva-rama
🟢 git remote add origin
Conecta el repositorio local con un repositorio remoto (por ejemplo, en GitHub).

bash
Copiar código
git remote add origin https://github.com/usuario/repositorio.git
🟢 git push
Envía los commits locales al repositorio remoto (sube tus cambios a GitHub).

bash
Copiar código
git push -u origin main
🟢 git pull
Descarga y combina los cambios desde el repositorio remoto al local.

bash
Copiar código
git pull origin main
🚀 Pasos para enviar tu proyecto a GitHub
Inicializa el repositorio local

bash
Copiar código
git init
Agrega los archivos del proyecto

bash
Copiar código
git add .
Confirma los cambios con un mensaje

bash
Copiar código
git commit -m "Primer commit del proyecto"
Conecta tu repositorio local con GitHub
(Copia el enlace de tu repositorio desde GitHub)

bash
Copiar código
git remote add origin https://github.com/usuario/repositorio.git
Sube los cambios a GitHub

bash
Copiar código
git push -u origin main