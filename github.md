  
1. **Inicializar un repositorio Git**:
```bash
git init
```
Este comando inicializa un nuevo repositorio Git en el directorio actual.

2. **Agregar archivos al área de preparación (staging)**:
```bash
git add <nombre_archivo>   # Agregar un archivo específico
git add .                  # Agregar todos los archivos modificados
```
Estos comandos agregan los cambios de los archivos al área de preparación para ser confirmados en el próximo commit.

3. **Confirmar (commit) los cambios**:
```bash
git commit -m "Mensaje del commit"
```
Este comando guarda los cambios confirmados en el repositorio con un mensaje descriptivo.

4. **Vincular tu repositorio local con un repositorio en GitHub**:
```bash
git remote add origin <url_repositorio_github>
```
Este comando establece una conexión entre tu repositorio local y un repositorio remoto en GitHub.

5. **Subir (push) tus cambios al repositorio remoto en GitHub**:
```bash
git push -u origin master
```
Este comando envía tus cambios confirmados al repositorio remoto en la rama principal (por defecto, 'master').

6. **Clonar un repositorio desde GitHub**:
```bash
git clone <url_repositorio_github>
```
Este comando crea una copia local de un repositorio remoto en GitHub en tu máquina.

7. **Actualizar tu repositorio local con los cambios del repositorio remoto**:
```bash
git pull origin master
```
Este comando descarga los cambios del repositorio remoto y los fusiona con tu repositorio local.

8. **Verificar el estado de tu repositorio**:
```bash
git status
```
Este comando muestra el estado actual de los archivos en tu repositorio (archivos modificados, agregados, etc.).

9. **clonar un repositorio**:
```bash
git clone
```


10. **Crear una nueva rama**:
```bash
git branch <nombre_rama>
```
Este comando crea una nueva rama en tu repositorio.

11. **Cambiar a una rama específica**:
```bash
git checkout <nombre_rama>
```
Este comando te permite cambiar entre diferentes ramas en tu repositorio. También puedes crear y cambiar a una nueva rama en un solo paso usando:
```bash
git checkout -b <nombre_nueva_rama>
```

12. **Ver todas las ramas en tu repositorio**:
```bash
git branch
```
Este comando te muestra todas las ramas presentes en tu repositorio local. La rama actual se destacará con un asterisco (*).

13. **Eliminar una rama**:
```bash
git branch -d <nombre_rama>
```
Este comando elimina la rama especificada. Ten en cuenta que para eliminar una rama, primero debes cambiarte a otra rama.

14. **Fusionar una rama con la rama actual**:
Primero, asegúrate de estar en la rama en la que deseas fusionar los cambios. Luego, ejecuta:
```bash
git merge <nombre_rama_a_fusionar>
```
Este comando fusiona los cambios de la rama especificada en la rama actual.

15. **Verificar el estado de tu repositorio**:
```bash
git status
```
Este comando te muestra el estado actual de tu repositorio, incluidas las ramas en las que te encuentras y cualquier archivo modificado o pendiente de confirmar.

16. **hace un pull a el repo para recibir todos  los archivos necesarios que no tengas en tu proyecto**:
```bash
git pull
```
