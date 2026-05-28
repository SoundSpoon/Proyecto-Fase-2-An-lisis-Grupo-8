# 🚀 Setup del Proyecto (Python + Jupyter)

Este proyecto puede ejecutarse localmente sin Docker utilizando Python y Jupyter Notebook.

---

# 📋 Requisitos

Instalar previamente:

- [Git](https://git-scm.com/)
- Python 3.10+ recomendado
- Jupyter Notebook

Verificar instalación:

```bash
git --version
python --version
```

---

# 📥 Clonar el repositorio

```bash
git clone https://github.com/SoundSpoon/Proyecto-Fase-2-An-lisis-Grupo-8.git
```

Entrar a la carpeta:

```bash
cd Proyecto-Fase-2-An-lisis-Grupo-8
```

---

# 📦 Crear entorno virtual (recomendado)

## Windows

```bash
python -m venv venv
venv\Scripts\activate
```

## Linux / Mac

```bash
python3 -m venv venv
source venv/bin/activate
```

---

# 📚 Instalar dependencias

Si existe un archivo `requirements.txt`:

```bash
pip install -r requirements.txt
```

Si no existe:

```bash
pip install jupyter numpy pandas matplotlib seaborn scikit-learn xgboost
```

---

# 📓 Abrir Jupyter Notebook

Ejecutar:

```bash
jupyter notebook
```

o:

```bash
jupyter lab
```

Abrir en el navegador:

```text
http://localhost:8888
```

---

# 🔄 Flujo normal de trabajo

Cada vez que quieras trabajar:

## Entrar a la carpeta

```bash
cd Proyecto-Fase-2-An-lisis-Grupo-8
```

## Activar entorno virtual

### Windows

```bash
venv\Scripts\activate
```

### Linux / Mac

```bash
source venv/bin/activate
```

## Abrir Jupyter

```bash
jupyter notebook
```

---

# 🌿 Git básico

Ver cambios:

```bash
git status
```

Guardar cambios:

```bash
git add .
git commit -m "mensaje"
```

Subir cambios:

```bash
git push
```

Actualizar proyecto:

```bash
git pull
```

---

# ✅ Recomendaciones

- Usar entorno virtual (`venv`)
- No instalar librerías globalmente
- Trabajar siempre dentro de la carpeta del proyecto
- Mantener actualizado el archivo `requirements.txt`

---

# ⚡ Setup rápido

```bash
git clone https://github.com/SoundSpoon/Proyecto-Fase-2-An-lisis-Grupo-8.git

cd Proyecto-Fase-2-An-lisis-Grupo-8

python -m venv venv
```

## Windows

```bash
venv\Scripts\activate
```

## Linux / Mac

```bash
source venv/bin/activate
```

```bash
pip install -r requirements.txt

jupyter notebook
```
