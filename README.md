# 🦊 GARU — Ransomware Threat Intelligence Platform

> Plataforma profesional de threat intelligence para ransomware basada en scraping en la red Tor.

---

## 📸 Demo

### 🌐 Dashboard Web
![Dashboard](images/dashboard.png)

### 📊 Generación de gráficas
![Graphs](images/graphs.png)

### 🖥️ CLI de análisis
![CLI](images/cli.png)

### 🗃️ MongoDB UI
![Mongo](images/mongo.png)

---

## 🚨 Problemática

El ransomware es una amenaza crítica cuya información está fragmentada y oculta en la dark web.

---

## 💡 Solución

GARU automatiza:

Recolección → Procesamiento → Almacenamiento → Análisis → Visualización

---

## 🧠 Features

- Scraping en Tor
- MongoDB
- CLI avanzada
- Dashboard web
- Alertas Telegram
- Dockerizado

---

## 🏗️ Arquitectura

```
Tor → Scraper → MongoDB → CLI / Web / Alerts
```

---

## ⚙️ Stack

- Python
- MongoDB
- Docker
- PHP / JS
- Telegram API

---

## 🚀 Instalación

```bash
git clone https://github.com/tuusuario/garu-project.git
cd garu-project
docker-compose up -d
```

---

## 🌐 Servicios

- Web: http://localhost:20000
- Mongo: http://localhost:8081

---

## 📊 Uso

```bash
python3 main.py
```

---

## 🔔 Alertas

Notificaciones en tiempo real vía Telegram.

---

## 📈 Roadmap

- API REST
- ML detección ransomware
- UI moderna

---

## 👥 Autores

Equipo GARU

---

## 📄 Licencia

MIT
