# AplicacionCuestionarios

Aplicación web para creación y gestión de cuestionarios en línea.  
Backend Flask + Frontend Vue 3.

---

## Requisitos previos

- Python 3.10+
- Node.js 18+
- Git

---

## Instalación y ejecución

### 1. Clonar el repositorio

```bash
git clone https://github.com/0ElaLe/AplicacionCuestionarios.git
cd AplicacionCuestionarios
```

### 2. Configurar el backend

```bash
cd backend
python -m venv .venv
```

**Activar el entorno virtual:**

```bash
# Windows
.venv\Scripts\activate

# Mac / Linux
source .venv/bin/activate
```

```bash
pip install -r requirements.txt
```

### 3. Inicializar la base de datos

```bash
# Primero arranca Flask para crear las tablas, luego Ctrl+C para pararlo
python app.py

# Luego corre la migración
python migrate_v2.py
```

### 4. Arrancar el backend

```bash
python app.py
```

La API quedará disponible en: `http://localhost:5000`

---

### 5. Configurar e iniciar el frontend

Abre una segunda terminal desde la raíz del proyecto:

```bash
cd frontend-vue
npm install
npm run dev
```

El frontend quedará disponible en: `http://localhost:5173`

---

## Integrantes

- Alejandro Iram Ramírez Nava
- Erick José Fabián Sandoval
- Abril Minerva Estrada Montaño
