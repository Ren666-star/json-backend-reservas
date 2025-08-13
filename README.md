# API de Reservas de Mesas (JSON Server)

Este proyecto proporciona una API REST simulada para un sistema de reservas de mesas de restaurante utilizando `json-server`.

## 🚀 Instalación

1. Instala json-server globalmente (si aún no lo tienes):

```bash
npm install -g json-server
```

2. Ejecuta el backend en el puerto 3001:

```bash
json-server --watch db.json --port 3001
```

---

## 📌 Endpoints disponibles

### 🔹 RESERVAS

| Método | Endpoint         | Descripción                                      |
|--------|------------------|--------------------------------------------------|
| GET    | /reservas        | Lista todas las reservas                         |
| GET    | /reservas/:id    | Obtiene una reserva por ID                       |
| POST   | /reservas        | Crea una nueva reserva                           |
| PUT    | /reservas/:id    | Reemplaza completamente una reserva              |
| DELETE | /reservas/:id    | Elimina una reserva                              |


## 👤 Endpoints del recurso `/usuarios`

Este recurso simula una tabla de usuarios para propósitos de login o filtrado por roles.

### 📄 Estructura de un usuario

```json
{
      "id": "1",
      "correo": "admin@admin.com",
      "clave": "admin123",
      "rol": "admin"
}
```

### 🔹 Endpoints disponibles

| Método | Endpoint        | Descripción                          |
|--------|-----------------|--------------------------------------|
| GET    | /usuarios       | Lista todos los usuarios             |
| GET    | /usuarios/:id   | Obtiene un usuario por ID            |
| POST   | /usuarios       | Crea un nuevo usuario                |
| PUT    | /usuarios/:id   | Reemplaza completamente un usuario   |
| DELETE | /usuarios/:id   | Elimina un usuario                   |

---


}

export default App;
```
