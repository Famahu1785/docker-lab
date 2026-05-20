# 🐳 Docker Lab — Entorno de Desarrollo con WSL2

## 👥 Autores
| Nombre | Código |
|--------|--------|
| Jhoan Fabricio Hurtado Marín | 202459472 |
| Juan Stevan Cruz | 202459437 |

## 🎯 Objetivo
Construir un entorno profesional de desarrollo usando Docker Compose sobre WSL2 + Ubuntu en Windows, integrando múltiples servicios que simulan una arquitectura real de producción.

## 🏗️ Arquitectura# Docker Lab

## Objetivo
Entorno profesional con Docker Compose en WSL2.

## Servicios
- Nginx (puerto 8080)
- Node.js API (puerto 3000)
- PostgreSQL (puerto 5432)
- pgAdmin (puerto 5050)
- Jupyter Lab (puerto 8888)

## Levantar entorno
docker compose up -d

## 🚀 Servicios
| Servicio | Puerto | Función |
|----------|--------|---------|
| Nginx | 8080 | Servidor web estático |
| Node.js API | 3000 | Backend REST con Express |
| PostgreSQL | 5432 | Base de datos relacional |
| pgAdmin 4 | 5050 | Administración gráfica de PostgreSQL |
| Jupyter Lab | 8888 | Notebooks de Python |

## ⚙️ Requisitos
- Windows 10/11 con WSL2 habilitado
- Ubuntu instalado en WSL2
- Docker Desktop con integración WSL2 activa
- Git

## 📦 Instalación y uso

### 1. Clonar el repositorio
```bash
git clone https://github.com/Famahu1785/docker-lab.git
cd docker-lab
```

### 2. Crear archivo de variables de entorno
```bash
cp .env.example .env
# Editar .env con tus credenciales
```

### 3. Levantar el entorno
```bash
docker compose up -d
```

### 4. Verificar contenedores
```bash
docker ps
```

## 🌐 Acceso a servicios
- Nginx: http://localhost:8080
- Node.js API: http://localhost:3000
- pgAdmin: http://localhost:5050
- Jupyter Lab: http://localhost:8888

## 🛑 Apagar entorno
```bash
docker compose down
```

## 📁 Estructura del proyecto
