# 🚀 Escalamiento Horizontal y Vertical con Docker, Node.js y Nginx

## 📌 Descripción
Este proyecto implementa una aplicación Node.js desplegada con Docker Compose, demostrando los conceptos de **escalamiento horizontal** (múltiples instancias) y **escalamiento vertical** (asignación de recursos).

Nginx actúa como balanceador de carga distribuyendo las solicitudes entre múltiples contenedores.

---

## ⚙️ Tecnologías utilizadas
- Node.js
- Docker
- Docker Compose
- Nginx

---

## 📂 Estructura del proyecto
- `compose.yaml` → configuración de servicios Docker
- `Dockerfile` → construcción de la imagen Node.js
- `src/server.js` → aplicación Node.js
- `docker/nginx/nginx.conf` → configuración del balanceador Nginx
- `README.md` → documentación

---

## 🧩 Ejecución del proyecto

### 🔹 1. Construir y levantar contenedores
```bash
docker compose up --build -d
