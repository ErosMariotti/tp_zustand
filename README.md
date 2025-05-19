# 🗒️ App de Gestión de Tareas - Zustand

Eros Mariotti.

Una **SPA** para gestionar tareas (CRUD) con React, Vite y Zustand.

---

## 🚀 Tecnologías

- **Framework**: React 18  
- **Bundler**: Vite  
- **State-management**: Zustand  
- **Lenguaje**: TypeScript  
- **Estilos**: CSS Modules  
- **HTTP client**: Axios  
- **DB de prueba**: JSON-Server

---

## 🎯 Funcionalidades

1. Listar tareas  
2. Agregar nueva tarea  
3. Editar tarea existente  
4. Eliminar tarea  
5. Persistencia en memoria (Zustand)

---

## 📁 Estructura del proyecto

/
├─ public/
│ └─ index.html
├─ src/
│ ├─ components/
│ │ ├─ ListTareas/
│ │ └─ Header/
│ ├─ http/
│ │ └─ tareas.ts
│ ├─ store/
│ │ └─ tareaStore.ts
│ ├─ styles/
│ ├─ App.tsx
│ └─ main.tsx
├─ db.json
├─ package.json
├─ tsconfig.json
└─ vite.config.ts

## 📝 Uso

- Listar: Verás todas las tareas al cargar.
- Agregar: Clic en “Agregar tarea”, completa y guarda.
- Editar: Abre modal para editar.
- Eliminar: Borra la tarea.
