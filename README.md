# 📝 Java API Tasks  
API REST simple desarrollada con **Spring Boot** para la gestión de tareas (Tasks).  
Este proyecto forma parte de mi portfolio y demuestra conocimientos en desarrollo backend, arquitectura básica, buenas prácticas y consumo de APIs.

---

## 🚀 Tecnologías utilizadas
- **Java 17**
- **Spring Boot**
- **Spring Web**
- **Spring Data JPA**
- **H2 Database** (base en memoria)
- **Maven**
- **Postman** (para pruebas)

---

## 📌 Funcionalidades
- Crear tareas  
- Listar todas las tareas  
- Obtener tarea por ID  
- Actualizar tarea  
- Eliminar tarea  

Cada tarea contiene:
- `id` (Long)  
- `title` (String)  
- `description` (String)  
- `completed` (boolean)  

---

## 📂 Estructura del proyecto

src/
└── main/
├── java/com/example/tasks/
│ ├── controller/
│ ├── service/
│ ├── model/
│ └── repository/
└── resources/
├── application.properties
└── data.sql (opcional)

---

## 🛠 Cómo ejecutar el proyecto

### 1. Clonar repositorio
```bash
git clone https://github.com/TU_USUARIO/java-api-tasks.git
