# 🧾 CRM de Clientes — Svelte + FastAPI + PostgreSQL

Un sistema básico de CRM (Customer Relationship Management) para gestionar clientes, creado como proyecto de práctica con tecnologías modernas y alto rendimiento.

## 🚀 Tecnologías utilizadas

- [Svelte](https://svelte.dev/) — Frontend reactivo y ligero
- [FastAPI](https://fastapi.tiangolo.com/) — Backend rápido y moderno en Python
- [PostgreSQL](https://www.postgresql.org/) — Base de datos relacional

---

## 📦 Estructura del proyecto

crm-cliente/
- backend/ # FastAPI
- frontend/ # Svelte
- README.md


---

## 📥 Instalación

### 🔧 Requisitos previos

- Python 3.10+
- Node.js y npm
- PostgreSQL corriendo localmente
- (Opcional) virtualenv

---

### ⚙️ Backend — FastAPI

1. Entra a la carpeta del backend:
```bash
$ cd backend
```
2.  Crea un entorno virtual (opcional pero recomendado):
```bash
$ python -m venv venv
$ source venv/bin/activate  # En Windows: venv\Scripts\activate
```

3. Instala FastAPI:
```bash
$ pip install "fastapi[standard]"
```

4. Corre el servidor:
```bash
$ fastapi dev main.py
```
    

       

🌐 Frontend — Svelte

1.    Entra a la carpeta del frontend:

```bash
$ cd frontend
```


2. Instala las dependencias:
```bash
$ npm install
```


3. Ejecuta el servidor de desarrollo:
```bash
$ npm run dev
```

Por defecto, estará disponible en http://localhost:5173
