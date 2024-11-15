# Guía Básica de Comandos Git

Este archivo proporciona una explicación clara y sencilla sobre algunos de los comandos más utilizados en Git, una herramienta esencial para el control de versiones en proyectos de desarrollo. Si eres nuevo en Git o deseas entender mejor cómo utilizar estos comandos, esta guía te será útil.

<div align="center">
    <img src="https://upload.wikimedia.org/wikipedia/commons/9/91/Octicons-mark-github.svg" alt="GitHub Logo" width="150"/>
</div>

---

## Comandos de Git

### 1. git init
El comando `git init` se usa para inicializar un nuevo repositorio Git en tu directorio local. Esto crea una carpeta oculta llamada `.git` que contiene la estructura y los archivos necesarios para que Git pueda rastrear los cambios en tu proyecto.

**Uso**:
```bash
git init
```

### 2. git add .
El comando git add . agrega todos los archivos modificados y nuevos al área de preparación (staging area). Esto significa que los archivos estarán listos para ser confirmados (committed) en el próximo paso.

**Uso**:
```bash
git add .
```

### 3. git commit -m "descripción del commit"
El comando git commit guarda los cambios que se encuentran en el área de preparación en el historial de Git. Usando el parámetro -m, puedes agregar un mensaje breve que describa los cambios realizados en el commit.

**Uso**:
```bash
git commit -m "Descripción del commit"
```

### 4. git push
El comando git push se utiliza para enviar tus cambios locales a un repositorio remoto, como GitHub o GitLab. Es esencial para compartir tu trabajo con otros colaboradores o simplemente hacer una copia de seguridad de tu código.

**Uso**:
```bash
git push origin main
```

### 5. git pull
El comando git pull descarga los cambios más recientes desde el repositorio remoto y los fusiona con tu rama local. Es útil cuando deseas mantener tu repositorio local actualizado con el trabajo realizado por otros colaboradores.

**Uso**:
```bash
git pull origin main
```

### 6. git remote -v
El comando git remote -v se utiliza para mostrar las URLs de los repositorios remotos asociados con tu repositorio local. Es útil para verificar las conexiones remotas y asegurarse de que estás trabajando con el repositorio correcto.

**Uso**:
```bash
git remote -v
```
