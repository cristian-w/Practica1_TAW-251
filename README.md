# Practica1_TAW-251
Partiendo de una copia del [siguiente repositorio](https://github.com/LiaRos-ai/RegistroUniversitario?)   
Se agregan partes de código en las clases: 
- EstudianteController.java
- IEstudianteService.java
- EstudianteRepository.java
- EstudianteServiceImpl.java
## Estructura del Proyecto
- **controller/** Contiene los controladores REST
- **service/** Contiene la lógica de negocio
- **repository/** Simula una base de datos en memoria
- **dto/** Contiene los objetos de transferencia de datos (DTO)
- **model/** Define las entidades del dominio
## Endpoints Disponibles
### Estudiantes
- `GET /api/estudiantes` - Obtener todos los estudiantes
- `GET /api/{id}` - Obtener un estudiante por ID
- `POST /api/estudiante` - Crear un nuevo estudiante
- `PUT /api/{id}` - Actualizar un estudiante
- `DELETE /api/{id}` - Eliminar un estudiante    
  
Nota: Se usa la version 21 de Java
