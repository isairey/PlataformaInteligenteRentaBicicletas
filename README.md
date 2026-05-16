<div align="center">

<img width="220" src="./Assets/logo.png" />

# 🚴 CYCLERR — Bicycle Rental Management System

### Plataforma inteligente de renta y gestión de bicicletas 🚀

<p align="center">
  <b>CYCLERR</b> es un sistema web dinámico desarrollado para administrar servicios de renta de bicicletas, permitiendo a los usuarios alquilar, extender tiempos de uso y transferir bicicletas entre usuarios mediante una plataforma moderna y eficiente.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/BicycleRental-WebPlatform-2E8B57?style=for-the-badge">
  <img src="https://img.shields.io/badge/JSP-JavaWeb-orange?style=for-the-badge&logo=openjdk&logoColor=white">
  <img src="https://img.shields.io/badge/Servlets-Backend-red?style=for-the-badge">
  <img src="https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
</p>

<p align="center">
  <a href="#-acerca-del-proyecto">Acerca</a> •
  <a href="#-módulos-del-sistema">Módulos</a> •
  <a href="#-características">Características</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-vista-previa">Vista previa</a>
</p>

</div>

---

# 🌌 Acerca del proyecto

**CYCLERR** es un sistema web orientado a la administración de bicicletas de alquiler y movilidad urbana, diseñado para facilitar el préstamo y devolución de bicicletas desde distintas ubicaciones de forma automatizada.

La plataforma permite a los usuarios:

- 🚴 Rentar bicicletas
- 📍 Seleccionar puntos de entrega
- ⏱️ Extender tiempo de uso
- 🔄 Transferir bicicletas a otros usuarios
- 👥 Gestionar cuentas
- 📊 Administrar operaciones
- 🔐 Gestionar accesos
- 🌐 Optimizar movilidad urbana

---

# ✨ Características

## 🚲 Gestión de bicicletas

- 🚴 Registro de bicicletas
- 📍 Gestión de estaciones
- ⚙️ Administración de disponibilidad
- 📋 Información detallada
- 🛠️ Control de mantenimiento

---

## 👥 Gestión de usuarios

- 👤 Registro de clientes
- 🔐 Inicio de sesión
- 📄 Gestión de perfiles
- 📊 Historial de rentas
- ⚡ Administración centralizada

---

## ⏱️ Sistema de renta

- 📅 Reservación de bicicletas
- ⌛ Extensión de tiempo
- 🔄 Transferencia de bicicletas
- 📍 Devolución flexible
- 📋 Gestión de alquileres

---

## 📊 Panel administrativo

- 📈 Dashboard administrativo
- 🚴 Supervisión de bicicletas
- 👥 Gestión de usuarios
- 📅 Administración de reservas
- 🔐 Gestión de permisos

---

# 👨‍💼 Módulos del sistema

## 🚴 Bicycle Module

Este módulo administra las bicicletas registradas dentro del sistema.

### Funcionalidades:

- ➕ Registro de bicicletas
- 📍 Gestión de ubicaciones
- ⚙️ Administración de disponibilidad
- 🛠️ Mantenimiento de bicicletas
- 📋 Información detallada

---

## 👤 User Module

Este módulo es utilizado por los usuarios que desean rentar bicicletas.

### Funcionalidades:

- 🔐 Inicio de sesión
- 🚲 Rentar bicicletas
- ⏱️ Extender tiempo de uso
- 🔄 Transferir bicicletas
- 📄 Consultar historial

---

## 🛠️ Admin Module

Este módulo funciona como administrador principal del sistema.

### Funcionalidades:

- 👥 Gestión de usuarios
- 🚴 Supervisión del sistema
- 📊 Dashboard administrativo
- 📅 Gestión de rentas
- 🔐 Administración de accesos

---

# 🛠️ Tecnologías utilizadas

## 🎨 Frontend

<p>
  <img src="https://skillicons.dev/icons?i=html,css,js" />
</p>

- HTML5
- CSS3
- JavaScript

---

## ⚙️ Backend

<p>
  <img src="https://skillicons.dev/icons?i=java" />
</p>

- JSP
- Java Servlets
- Arquitectura MVC
- Gestión de sesiones

---

## 🗄️ Base de datos

<p>
  <img src="https://skillicons.dev/icons?i=mysql" />
</p>

- MySQL
- Relaciones SQL
- Persistencia de datos
- Gestión de alquileres

---

## 🧰 Herramientas

<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode" />
</p>

- Git
- GitHub
- Visual Studio Code
- XAMPP / WAMP

---

# 📂 Estructura del proyecto

```bash
PlataformaInteligenteRentaBicicletas/
│
├── Assets/                   # Recursos gráficos
├── database/                 # Scripts SQL
├── src/                      # Código fuente Java
├── WebContent/               # Archivos JSP y frontend
├── controllers/              # Servlets y controladores
├── models/                   # Modelos del sistema
├── views/                    # Interfaces JSP
├── login.jsp                 # Inicio de sesión
├── index.jsp                 # Página principal
├── README.md
└── LICENSE
```

---

# ⚡ Instalación

## 📋 Requisitos

- Java JDK 8+
- Apache Tomcat
- MySQL
- XAMPP / WAMP
- Navegador moderno

---

# 🚀 Configuración del proyecto

## 1️⃣ Clonar repositorio

```bash
git clone https://github.com/isairey/PlataformaInteligenteRentaBicicletas.git
```

---

## 2️⃣ Configurar servidor

Iniciar servicios:

```bash
Apache
MySQL
Tomcat
```

---

## 3️⃣ Crear base de datos

Crear base:

```bash
cycle
```

---

## 4️⃣ Importar SQL

Importar:

```bash
PlataformaInteligenteRentaBicicletas/database/cycle.sql
```

---

## 5️⃣ Configurar proyecto

Mover proyecto hacia:

```bash
xampp/htdocs/PlataformaInteligenteRentaBicicletas/
```

---

## 6️⃣ Ejecutar proyecto

Abrir:

```bash
http://localhost/PlataformaInteligenteRentaBicicletas
```

---

# 📊 Funcionalidades principales

## 🚴 Gestión de bicicletas

- Registro de bicicletas
- Administración de disponibilidad
- Gestión de estaciones
- Mantenimiento del sistema

---

## 👥 Administración de usuarios

- Registro y autenticación
- Gestión de perfiles
- Historial de alquileres
- Roles administrativos

---

## ⏱️ Gestión de alquileres

- Reservas en tiempo real
- Extensión de tiempo
- Transferencia de bicicletas
- Control de devoluciones

---

# 📸 Vista previa

## 🖥️ Interfaces del sistema

<div align="center">

### 🚴 Página principal
![Home](https://images.unsplash.com/photo-1507035895480-2b3156c31fc8?q=80&w=1200&auto=format&fit=crop)

### 🔐 Inicio de sesión
![Login](https://images.unsplash.com/photo-1522202176988-66273c2fd55f?q=80&w=1200&auto=format&fit=crop)

### 🚲 Gestión de bicicletas
![Bikes](https://images.unsplash.com/photo-1485965120184-e220f721d03e?q=80&w=1200&auto=format&fit=crop)

### 📅 Sistema de renta
![Rental](https://images.unsplash.com/photo-1511994298241-608e28f14fde?q=80&w=1200&auto=format&fit=crop)

### 📊 Dashboard administrativo
![Dashboard](https://images.unsplash.com/photo-1460925895917-afdab827c52f?q=80&w=1200&auto=format&fit=crop)

### 👥 Gestión de usuarios
![Users](https://images.unsplash.com/photo-1521737604893-d14cc237f11d?q=80&w=1200&auto=format&fit=crop)

### 🔄 Cyclerr Pass On
![PassOn](https://images.unsplash.com/photo-1517649763962-0c623066013b?q=80&w=1200&auto=format&fit=crop)

### 📍 Estaciones de bicicletas
![Stations](https://images.unsplash.com/photo-1508975551575-810f0d6e8d0d?q=80&w=1200&auto=format&fit=crop)

</div>

---

# 🧠 Objetivos del proyecto

## 🎯 Aprendizaje y administración

- Desarrollo web Java
- Arquitectura MVC
- Gestión de movilidad urbana
- Bases de datos relacionales
- CRUD administrativos
- Sistemas de autenticación
- Automatización de alquileres

---

# 🚧 Roadmap

## 🔮 Próximas mejoras

- 📱 Aplicación móvil
- ☁️ Infraestructura cloud
- 💳 Pagos electrónicos
- 📍 Geolocalización GPS
- 🚴 Rastreo inteligente
- 🌐 API REST moderna
- 🔔 Notificaciones en tiempo real

---

# 👨‍💻 Contributors
<div align="center">

 <table>
  <tr>
    <td align="center">
      <img src="Assets/contributors/dhar.jpeg" width="140px;" />
      <br />
      <sub><b>Dharshini</b></sub>
    </td>

    <td align="center">
      <img src="Assets/contributors/sanjitha.jpeg" width="140px;" />
      <br />
      <sub><b>Sanjitha</b></sub>
    </td>

    <td align="center">
      <img src="Assets/contributors/senthil.jpeg" width="140px;" />
      <br />
      <sub><b>Senthil Kumar</b></sub>
    </td>

    <td align="center">
      <img src="Assets/contributors/sivasanjayraahul.jpeg" width="140px;" />
      <br />
      <sub><b>Sivasanjay Raahul</b></sub>
    </td>
  </tr>
 </table>

</div>

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas ❤️

## Cómo contribuir

1. Fork del proyecto

```bash
git checkout -b feature/nueva-funcionalidad
```

2. Commit

```bash
git commit -m "✨ Nueva funcionalidad"
```

3. Push

```bash
git push origin feature/nueva-funcionalidad
```

4. Pull Request 🚀

---

# 👨‍💻 Desarrollador

<div align="center">

## Isai Reyes — Full Stack Developer

Desarrollador apasionado por plataformas web, movilidad urbana y sistemas inteligentes 🚀

</div>

---

# 🌟 Apoya el proyecto

⭐ Dale una estrella  
🍴 Haz fork  
📢 Comparte el proyecto

---

# 📜 Licencia

Proyecto open source bajo licencia MIT orientado al aprendizaje y administración de sistemas de renta de bicicletas.

---

<div align="center">

### 🚴 CYCLERR — gestión inteligente de movilidad y alquiler de bicicletas 🚀

</div>
