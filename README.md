# BoardGame Social - Proyecto Scrum

![Status](https://img.shields.io/badge/Estado-En%20Desarrollo-yellow)
![Metodología](https://img.shields.io/badge/Metodología-Scrum-blue)
![Sprints](https://img.shields.io/badge/Sprints-2-orange)
![License](https://img.shields.io/badge/Licencia-MIT-green)

## Tabla de Contenidos

- [Descripción del Proyecto](#descripción-del-proyecto)
- [Objetivos](#objetivos)
- [Características Principales](#características-principales)
- [Metodología Scrum](#metodología-scrum)
- [Product Backlog](#product-backlog)
- [Sprints](#sprints)
- [Historias de Usuario](#historias-de-usuario)
- [Tecnologías](#tecnologías)
- [Equipo Scrum](#equipo-scrum)
- [Instalación](#instalación)
- [Roadmap](#roadmap)
- [Contribución](#contribución)
- [Licencia](#licencia)

---

## Descripción del Proyecto

**BoardGame Social** es una aplicación web de red social dedicada a los entusiastas de los juegos de mesa. La plataforma permite a los usuarios conectar con otros jugadores, descubrir nuevos juegos, organizar partidas y encontrar compañeros de juego mediante un sistema de **skill matching**.

> [!NOTE]
> Este proyecto es parte de un curso de metodología Scrum y está limitado a **2 sprints** debido a restricciones de tiempo y presupuesto académico.

---

## Objetivos

### Objetivo General
Desarrollar una plataforma social funcional que conecte a jugadores de juegos de mesa mediante un sistema de matching basado en preferencias y habilidades.

### Objetivos Específicos
1. Crear una interfaz de usuario intuitiva y atractiva
2. Implementar un sistema de perfiles de usuario
3. Desarrollar el algoritmo de skill matching
4. Permitir la búsqueda y filtrado de juegos de mesa
5. Facilitar la organización de eventos y partidas

---

## Características Principales

### Funcionalidades Core

- **Perfiles de Usuario**: Creación y personalización de perfiles con preferencias de juego
- **Catálogo de Juegos**: Base de datos de juegos de mesa con información detallada
- **Skill Matching**: Algoritmo que conecta usuarios con intereses y niveles similares
- **Organización de Partidas**: Sistema para crear y unirse a eventos de juego
- **Sistema de Valoraciones**: Calificación de juegos y experiencias de juego
- **Chat en Tiempo Real**: Comunicación entre usuarios (planificado para futuras versiones)

### Ventajas

- Interfaz moderna y responsive
- Fácil de usar para usuarios de todos los niveles
- Sistema de recomendaciones personalizado
- Comunidad activa de jugadores

### Limitaciones Actuales

> [!CAUTION]
> Debido al alcance limitado del proyecto académico:
> - Solo se implementarán las funcionalidades básicas en 2 sprints
> - El sistema de chat en tiempo real queda fuera del alcance inicial
> - La aplicación móvil nativa no está contemplada en esta fase

---

## Metodología Scrum

Este proyecto sigue la metodología **Scrum** con las siguientes ceremonias:

### Ceremonias Scrum

1. **Sprint Planning**: Planificación al inicio de cada sprint (2 semanas)
2. **Daily Standup**: Reuniones diarias de 15 minutos
3. **Sprint Review**: Demostración del incremento al final del sprint
4. **Sprint Retrospective**: Análisis de mejoras para el próximo sprint

### Artefactos Scrum

- **Product Backlog**: Lista priorizada de funcionalidades
- **Sprint Backlog**: Tareas seleccionadas para el sprint actual
- **Incremento**: Producto funcional al final de cada sprint

---

## Product Backlog

| ID | Historia de Usuario | Prioridad | Estimación | Sprint |
|----|---------------------|-----------|------------|--------|
| US-01 | Registro e inicio de sesión | Alta | 8 pts | Sprint 1 |
| US-02 | Creación de perfil de usuario | Alta | 5 pts | Sprint 1 |
| US-03 | Visualización de catálogo de juegos | Alta | 8 pts | Sprint 1 |
| US-04 | Sistema de búsqueda y filtros | Media | 5 pts | Sprint 1 |
| US-05 | Algoritmo de skill matching | Alta | 13 pts | Sprint 2 |
| US-06 | Creación de eventos/partidas | Media | 8 pts | Sprint 2 |
| US-07 | Sistema de valoraciones | Media | 5 pts | Sprint 2 |
| US-08 | Notificaciones básicas | Baja | 3 pts | Sprint 2 |

---

## Sprints

### Sprint 1: Interfaz y Funcionalidades Básicas
**Duración**: 2 semanas  
**Objetivo**: Desarrollar la interfaz principal y las funcionalidades básicas de usuario

#### 📌 Tareas Principales
- [x] Diseño de mockups y wireframes
- [x] Configuración del entorno de desarrollo
- [x] Implementación del sistema de autenticación
- [x] Desarrollo de la página de inicio
- [x] Creación del catálogo de juegos
- [x] Sistema de búsqueda y filtros básicos
- [x] Diseño responsive

#### 🎯 Entregables
- Interfaz de usuario funcional
- Sistema de login/registro
- Catálogo de juegos navegable

---

### Sprint 2: Skill Matching y Funcionalidades Sociales
**Duración**: 2 semanas  
**Objetivo**: Implementar el sistema de matching y funcionalidades sociales

#### 📌 Tareas Principales
- [ ] Desarrollo del algoritmo de skill matching
- [ ] Implementación de perfiles detallados
- [ ] Sistema de creación de eventos
- [ ] Funcionalidad de unirse a partidas
- [ ] Sistema de valoraciones
- [ ] Notificaciones básicas
- [ ] Testing y corrección de bugs

#### 🎯 Entregables
- Sistema de matching funcional
- Gestión de eventos y partidas
- Aplicación completa y testeada

---

## Historias de Usuario

### US-01: Registro de Usuario
```
Como nuevo usuario
Quiero poder registrarme en la plataforma
Para acceder a las funcionalidades de la red social
```
**Criterios de Aceptación:**
- El usuario puede crear una cuenta con email y contraseña
- Se valida el formato del email
- La contraseña debe tener al menos 8 caracteres
- Se envía un email de confirmación

---

### US-02: Creación de Perfil
```
Como usuario registrado
Quiero crear y personalizar mi perfil
Para que otros usuarios conozcan mis preferencias de juego
```
**Criterios de Aceptación:**
- El usuario puede agregar foto de perfil
- Puede seleccionar sus juegos favoritos
- Puede indicar su nivel de experiencia
- Puede agregar una biografía breve

---

### US-03: Búsqueda de Juegos
```
Como usuario
Quiero buscar juegos de mesa en el catálogo
Para descubrir nuevos juegos que me interesen
```
**Criterios de Aceptación:**
- El usuario puede buscar por nombre del juego
- Puede filtrar por categoría, número de jugadores y duración
- Los resultados se muestran con información relevante
- Puede ver detalles completos de cada juego

---

### US-05: Skill Matching
```
Como usuario
Quiero que el sistema me recomiende otros jugadores
Para encontrar compañeros de juego compatibles
```
**Criterios de Aceptación:**
- El algoritmo considera preferencias de juego
- Tiene en cuenta el nivel de experiencia
- Muestra un porcentaje de compatibilidad
- Permite enviar solicitudes de amistad

---

## Tecnologías

### Frontend
- **HTML5** - Estructura
- **CSS3** - Estilos y diseño responsive
- **JavaScript** - Interactividad
- **Bootstrap 5** - Framework CSS (opcional)

### Backend
- **Node.js** - Entorno de ejecución
- **Express.js** - Framework web
- **MongoDB** - Base de datos NoSQL

### Herramientas de Desarrollo
- **Git** - Control de versiones
- **GitHub** - Repositorio remoto
- **VS Code** - Editor de código
- **Postman** - Testing de API
- **Trello/Jira** - Gestión de proyecto Scrum

### Testing
- **Jest** - Testing unitario
- **Cypress** - Testing E2E

---

## Equipo Scrum

### Roles

| Rol | Responsabilidad |
|-----|-----------------|
| **Product Owner** | Define y prioriza el Product Backlog |
| **Scrum Master** | Facilita el proceso Scrum y elimina impedimentos |
| **Development Team** | Desarrolla el incremento del producto |

> [!TIP]
> En proyectos académicos pequeños, es común que los miembros del equipo asuman múltiples roles.

---

## Instalación

### Prerequisitos
```bash
Node.js >= 14.x
npm >= 6.x
MongoDB >= 4.x
```

### Pasos de Instalación

1. **Clonar el repositorio**
```bash
git clone https://github.com/tu-usuario/boardgame-social.git
cd boardgame-social
```

2. **Instalar dependencias**
```bash
npm install
```

3. **Configurar variables de entorno**
```bash
cp .env.example .env
# Editar .env con tus configuraciones
```

4. **Iniciar la base de datos**
```bash
mongod
```

5. **Ejecutar la aplicación**
```bash
npm start
```

6. **Acceder a la aplicación**
```
http://localhost:3000
```

---

## Roadmap

### Completado (Sprint 1)
- Diseño de interfaz
- Sistema de autenticación
- Catálogo de juegos

### En Progreso (Sprint 2)
- Algoritmo de skill matching
- Sistema de eventos

### Futuras Versiones
- Chat en tiempo real
- Aplicación móvil
- Sistema de logros y gamificación
- Integración con APIs de juegos de mesa
- Marketplace de juegos

---

## Contribución

Este es un proyecto académico, pero las sugerencias son bienvenidas:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

---

## Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.

---

## Contacto

**Equipo de Desarrollo**
- Email: equipo@boardgamesocial.com
- GitHub: [@tu-usuario](https://github.com/tu-usuario)

---

## Agradecimientos

- A nuestro profesor de Scrum por la guía en el proyecto
- A la comunidad de juegos de mesa por la inspiración
- A todos los que contribuyen al proyecto

---

---

**Hecho por el equipo de BoardGame Social**

![Scrum](https://img.shields.io/badge/Powered%20by-Scrum-blue?style=for-the-badge)
