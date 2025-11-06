# 🎓 TP Angular - Gestión de Estudiantes

## 📋 Descripción
Migración de una aplicación JavaScript a Angular con funcionalidad CRUD completa para la gestión de estudiantes. Trabajo práctico entregable para la materia de Desarrollo Web.

## 🚀 Características
- ✅ **Listar estudiantes** - Visualización en tabla con diseño responsive
- ✅ **Agregar estudiantes** - Formulario de alta con validaciones
- ✅ **Editar estudiantes** - Modificación de datos en tiempo real
- ✅ **Eliminar estudiantes** - Borrado con confirmación
- ✅ **Diseño profesional** - Bootstrap 5 para interfaz moderna
- ✅ **API REST completa** - JSON Server como backend simulado

## 🛠️ Tecnologías Utilizadas
- **Angular 17+** - Framework principal con componentes standalone
- **TypeScript** - Lenguaje de programación
- **Bootstrap 5** - Framework de estilos y componentes UI
- **JSON Server** - API REST simulada para desarrollo
- **RxJS** - Manejo de observables y programación reactiva
- **Angular HttpClient** - Consumo de APIs REST

## 📥 Instalación y Configuración

### Prerrequisitos
- Node.js 18+ 
- Angular CLI 17+
- npm (Node Package Manager)

### Pasos para ejecutar
Instalar dependencias:
npm install

Instalar JSON Server globalmente (si no lo tienes):
npm install -g json-server

Ejecutar JSON Server (Terminal 1):
json-server --watch db.json --port 3000
La API estará disponible en: http://localhost:3000/students

Ejecutar Angular (Terminal 2):
ng serve
La aplicación estará disponible en: http://localhost:4200

## 🏗️ Estructura del Proyecto

AngularFinal/
├── src/
│ ├── app/
│ │ ├── components/
│ │ │ ├── student-list/ # Lista principal de estudiantes
│ │ │ ├── student-form/ # Formulario de creación
│ │ │ └── student-edit/ # Formulario de edición
│ │ ├── models/
│ │ │ └── student.model.ts # Interface del modelo Student
│ │ ├── services/
│ │ │ └── api.service.ts # Servicio para consumo de API
│ │ ├── app.component.ts # Componente raíz
│ │ ├── app.config.ts # Configuración de la aplicación
│ │ └── app.routes.ts # Configuración de rutas
│ ├── assets/
│ └── environments/
├── db.json # Base de datos simulada
├── angular.json # Configuración de Angular
└── package.json # Dependencias del proyecto

## 📡 API Endpoints
La aplicación consume los siguientes endpoints:
- GET /students - Obtener todos los estudiantes
- POST /students - Crear nuevo estudiante
- PATCH /students/:id - Actualizar estudiante existente
- DELETE /students/:id - Eliminar estudiante

## 🎯 Funcionalidades Implementadas

### Gestión de Estudiantes
- **Visualización**: Tabla con todos los estudiantes registrados
- **Creación**: Formulario con campos: DNI, Apellido, Nombre, Email
- **Edición**: Modal de edición con pre-carga de datos
- **Eliminación**: Botón de eliminar con confirmación
- **Selección**: Click en fila para ver detalles completos

### Características Técnicas
- **Arquitectura**: Componentes standalone de Angular
- **Estado**: Manejo reactivo del estado de la aplicación
- **Validaciones**: Validación de formularios en tiempo real
- **Manejo de errores**: Alertas para errores de API
- **Responsive**: Diseño adaptable a diferentes dispositivos

## 👨‍💻 Autor
**Ignacio Gutierrez**
## 📄 Notas
- Este proyecto fue desarrollado como trabajo práctico académico
- Utiliza una API simulada (JSON Server) para desarrollo
- La estructura sigue las mejores prácticas de Angular

---

