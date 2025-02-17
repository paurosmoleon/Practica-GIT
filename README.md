# Practica-GIT
# Guía para trabajar con Git y GitHub

## 1. Configurar Git en tu equipo
Antes de empezar, configura tu identidad en Git con:
```bash
git config --global user.name "Tu Nombre"
git config --global user.email tuemail@example.com
```

## 2. Crear un nuevo repositorio en GitHub
1. Accede a GitHub.
2. Haz clic en **"New Repository"**.
3. Asigna un nombre al repositorio y selecciona la opción **"Initialize this repository with a README"**.

## 3. Clonar el repositorio en tu equipo
Para descargar el repositorio en tu equipo, usa:
```bash
git clone URL_DEL_REPOSITORIO
cd NOMBRE_DEL_REPOSITORIO
```

## 4. Trabajo Individual con Git

### 4.1 Crear un archivo de prueba y hacer un commit
Añade un archivo de prueba y guárdalo en el repositorio local:
```bash
echo "# Proyecto Web" > index.html
git add index.html
git commit -m "Añadir archivo index.html"
```

### 4.2 Subir cambios al repositorio remoto
Para enviar tus cambios a GitHub:
```bash
git push origin main
```

### 4.3 Actualizar el repositorio local con los cambios remotos
Si hay cambios en el repositorio remoto, descárgalos con:
```bash
git pull origin main
```

