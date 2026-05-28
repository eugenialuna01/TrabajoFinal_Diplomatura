# ⚽ TorneoPro

> Sistema web de gestión de torneos deportivos desarrollado con MERN Stack.

---

## 🏆 Características

- ✅ Gestión de torneos
- ✅ Gestión de equipos
- ✅ Gestión de jugadores
- ✅ Gestión de partidos
- ✅ Tabla de posiciones automática
- ✅ Sistema de roles y permisos
- ✅ Dashboard administrativo
- ✅ Integración con APIs deportivas

---

# 👥 Roles del sistema

## 👤 Usuario

- Ver torneos
- Ver equipos
- Ver jugadores
- Ver partidos
- Ver tabla de posiciones

---

## 🧑‍🏫 Entrenador

- Crear equipos
- Editar equipos
- Crear jugadores
- Editar jugadores
- Eliminar jugadores
- Ver partidos
- Ver standings

---

## 👑 Administrador

- CRUD de torneos
- CRUD de equipos
- CRUD de jugadores
- CRUD de partidos
- Gestión de usuarios
- Gestión de standings

---

# 🔐 Permisos dinámicos

```txt
tournament:create
team:update
player:delete
match:read
standings:read
user:update
```

---

# ⚙️ Tecnologías utilizadas

## 🎨 Frontend

- React.js
- Vite
- Tailwind CSS
- React Hook Form
- React Router DOM
- SweetAlert2
- React Toastify

---

## 🖥 Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication

---

# 📊 Funcionalidades deportivas

## ⚽ Partidos

- Crear fixtures
- Cargar resultados
- Actualizar estado de partidos

---

## 📈 Tabla de posiciones

Cálculo automático de:

- Puntos
- Victorias
- Empates
- Derrotas
- Diferencia de gol

---

# 🌍 Integración externa

La aplicación permite importar información real desde:

- ⚽ TheSportsDB API

---

# 🚀 Instalación

## 1️⃣ Clonar repositorio

```bash
git clone https://github.com/TU_USUARIO/TU_REPO.git
```

---

## 2️⃣ Instalar dependencias

### Frontend

```bash
cd frontend
npm install
```

### Backend

```bash
cd backend
npm install
```

---

# ▶️ Ejecutar proyecto

## Backend

```bash
npm run dev
```

## Frontend

```bash
npm run dev
```

---

# 🔑 Variables de entorno

Crear `.env` en backend:

```env
PORT=5000
MONGO_URL=TU_MONGO_URI
JWT_SECRET=SECRET_KEY
```

---

# 👨‍💻 Autor

Desarrollado por Eugenia Luna 💻

###👥 Usuarios del sistema
La aplicación posee distintos tipos de usuarios con permisos específicos.

##👤 Usuario
El usuario común puede visualizar la información general del sistema.
Permisos:
✔ Ver torneos
✔ Ver equipos
✔ Ver jugadores
✔ Ver partidos
✔ Ver tabla de posiciones

##🧑‍🏫 Entrenador
El entrenador puede administrar su equipo y sus jugadores.
Permisos:
✔ Ver torneos
✔ Ver equipos
✔ Crear equipos
✔ Editar equipos
✔ Ver jugadores
✔ Crear jugadores
✔ Editar jugadores
✔ Eliminar jugadores
✔ Ver partidos
✔ Ver tabla de posiciones

👑 Administrador
El administrador posee control total del sistema.
Permisos:
🏆 Torneos
✔ Crear torneos
✔ Editar torneos
✔ Eliminar torneos
✔ Ver torneos
👥 Equipos
✔ Crear equipos
✔ Editar equipos
✔ Eliminar equipos
✔ Ver equipos
🧑‍🤝‍🧑 Jugadores
✔ Crear jugadores
✔ Editar jugadores
✔ Eliminar jugadores
✔ Ver jugadores
⚽ Partidos
✔ Crear partidos
✔ Cargar resultados
✔ Eliminar partidos
✔ Ver partidos
📊 Tabla de posiciones
✔ Ver tabla
✔ Actualizar tabla
👤 Usuarios
✔ Ver usuarios
✔ Editar usuarios
✔ Eliminar usuarios

🔐 Sistema de permisos
La aplicación implementa un sistema de autorización basado en permisos dinámicos.
Ejemplos:
tournament:createteam:updateplayer:deletematch:readstandings:readuser:update
Esto permite controlar exactamente qué puede hacer cada usuario dentro del sistema. 🔒

🧠 Tecnologías utilizadas
🎨 Frontend
⚛️ React.js
⚡ Vite
🎨 Tailwind CSS
📝 React Hook Form
🔔 React Toastify
🍬 SweetAlert2
🛣 React Router DOM
📦 Context API

🖥 Backend
🟢 Node.js
🚂 Express.js
🍃 MongoDB
🧩 Mongoose
🔑 JWT Authentication
🌐 REST API

📊 Funcionalidades destacadas
⚽ Gestión de partidos
✔ Crear fixtures
✔ Registrar resultados
✔ Actualización automática de standings

📈 Tabla de posiciones automática
La aplicación calcula automáticamente:
🏅 Puntos
⚽ Goles a favor
🥅 Goles en contra
📉 Diferencia de gol
🎯 Victorias, empates y derrotas

🌍 Integración externa
La plataforma puede importar información real de equipos deportivos mediante APIs externas como:
⚽ TheSportsDB
Esto permite cargar equipos reales automáticamente en la base de datos. 🔥

🎯 Objetivo del proyecto
El objetivo principal de TorneoPro es ofrecer una solución moderna para la gestión integral de competiciones deportivas, aplicando buenas prácticas de desarrollo full stack, autenticación, control de permisos y diseño responsivo. 🚀
