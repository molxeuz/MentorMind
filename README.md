# AIStudyMate - Asistente de Estudio Inteligente con IA

## 📌 Descripción del Proyecto
**AIStudyMate** es un asistente de estudio inteligente desarrollado en Python con programación orientada a objetos (POO) y una interfaz gráfica en Tkinter. Su objetivo es ayudar a los estudiantes a organizar sus tareas, recibir recordatorios, resolver problemas y mejorar su aprendizaje con inteligencia artificial.

## 🚀 Características
### 📋 Gestión de Tareas y Recordatorios
- Agregar tareas con título, descripción, fecha de entrega, categoría, prioridad y estado.
- Organizar las tareas por prioridad y fecha de vencimiento.
- Recordatorios automáticos para tareas próximas.
- Calendario visual para ver tareas pendientes.

### 🧠 Ayuda en la Resolución de Problemas
- Conexión con la **API de DeepSeek** para búsqueda avanzada de información.
- Soluciones paso a paso en matemáticas, ciencias y lenguas.
- Sugerencias de estructura y gramática para redacción.

### 🎯 Modo de Repaso Inteligente
- Creación automática de preguntas de práctica basadas en las tareas del usuario.
- Cuestionarios personalizados con machine learning según el desempeño.

### 📅 Calendario y Notificaciones Inteligentes
- Organización del estudio en función de los hábitos del usuario.
- Notificaciones previas a fechas límite importantes.

### 📚 Recomendaciones de Recursos
- Sugerencia de videos, libros y artículos según la tarea ingresada.
- Sistema de notas y organización de recursos por materia.

## 🛠️ Tecnologías Utilizadas
- **Python (POO)** – Para la estructura del asistente.
- **Tkinter** – Para la interfaz gráfica.
- **SQLite** – Para la base de datos de tareas y recordatorios.
- **DeepSeek API** – Para inteligencia artificial en generación de contenido y búsqueda de información.

## 🔧 Arquitectura del Proyecto
### 📂 Clases Principales
- **Tarea**: Representa una tarea con sus atributos clave.
- **GestorTareas**: Administra la creación, edición y eliminación de tareas.
- **Recordatorio**: Representa un recordatorio asociado a una tarea.
- **GestorRecordatorios**: Maneja la programación de notificaciones.
- **AsistenteIA**: Se conecta con DeepSeek para procesar consultas.
- **GestorConsultas**: Optimiza las solicitudes a la API y almacena respuestas.
- **Pregunta / Cuestionario**: Para la generación de repaso inteligente.
- **GestorRepaso**: Administra cuestionarios y adapta la dificultad.
- **Calendario**: Representa la planificación de estudio.
- **GestorNotificaciones**: Programa y envía alertas.
- **Recurso / GestorRecursos**: Para sugerir material de apoyo.
- **Usuario**: Representa al estudiante con sus preferencias y hábitos.
- **BaseDatos**: Maneja la persistencia de datos en SQLite.
- **InterfazGrafica**: Controla la visualización con Tkinter.

## 💰 ¿Es posible hacerlo gratuitamente?
Sí, **DeepSeek API** ofrece acceso gratuito con limitaciones. Para mantener el asistente gratuito:
- Se optimizarán las consultas a la API para reducir llamadas innecesarias.
- Se usará **SQLite** para almacenar respuestas reutilizables.

## 🚀 Instalación y Uso
### 1️⃣ Requisitos Previos
- Tener **Python 3.8+** instalado.
- Instalar dependencias con:
  ```bash
  pip install -r requirements.txt
  ```

### 2️⃣ Ejecución del Proyecto
```bash
python main.py
```

### 3️⃣ Configuración de API DeepSeek (Opcional)
Si deseas integrar la IA, necesitarás una **API Key** de DeepSeek. Agrégala en un archivo `.env`:
```env
DEEPSEEK_API_KEY=tu_api_key_aqui
```

## 🛠️ Futuras Mejoras
- Implementación de integración con Google Calendar.
- Mejora en la visualización del historial de consultas.
- Ampliación del soporte para más idiomas.

## 👨‍💻 Integrantes del Proyecto
- **Mateo**
- **Moises**
- **Andres**
- **Samuel**

## 📜 Licencia
Este proyecto es de código abierto bajo la licencia **MIT**.
