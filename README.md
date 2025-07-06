# 📝 To-Do App FullStack (Django + React)

Proyecto de práctica con React.  
Aplicación web que permite crear, ver, completar, editar y eliminar tareas.

---

## ⚙️ Tecnologías usadas

- Backend: Django + Django REST Framework
- Base de datos: PostgreSQL
- Frontend: React + HTML + CSS
- API RESTful con Axios

---

## 🚀 ¿Qué funcionalidades incluye?

- ✅ Ver listado de tareas
- ➕ Crear nuevas tareas
- ✅/❌ Marcar tareas como completadas o pendientes
- ✏️ Editar texto de la tarea
- 🗑️ Eliminar tareas (con confirmación)
- 🎨 Estilos personalizados con CSS

---

## 🧠 Cómo usar la aplicación

1. Al iniciar, verás una lista con tus tareas actuales.
2. Puedes:
   - Agregar una nueva tarea desde el formulario superior.
   - Hacer clic sobre una tarea para marcarla como completada o pendiente.
   - Editar el texto de una tarea con el botón ✏️.
   - Eliminar una tarea con el botón 🗑️ (te pedirá confirmación).
3. Las tareas se actualizan automáticamente al realizar cualquier acción.

---

## 📦 Instalación

### 🐍 Backend (Django)

```bash
cd todoproject
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```

### ⚛️ Frontend (React)
```bash
Copiar
Editar
cd frontend
npm install
npm start
```
