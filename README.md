# alejandravaloracion2

# 📚 Sistema de Gestión de Control Universitario

Este proyecto consiste en el diseño e implementación de una base de datos relacional para la administración de procesos académicos, desarrollada como parte de la **Evaluación 2**. El sistema permite gestionar estudiantes, docentes, asignaturas y los procesos de matriculación.

## 🚀 Características del Proyecto
- [cite_start]**Diseño Relacional:** Estructura de 5 tablas con integridad referencial completa. [cite: 2]
- [cite_start]**Restricciones de Integridad:** Uso de `CHECK`, `UNIQUE` y `DEFAULT` para asegurar la calidad de la data. [cite: 9, 12, 20]
- [cite_start]**Optimización:** Implementación de índices para consultas de alto rendimiento. [cite: 24, 48]
- [cite_start]**Abstracción:** Vistas personalizadas para facilitar el reporte de inscripciones. [cite: 50]

## 🛠️ Tecnologías Utilizadas
- **Motor de DB:** Microsoft SQL Server 2022.
- **Lenguaje:** T-SQL.
- **Gestor:** SQL Server Management Studio (SSMS).

## 📂 Estructura de la Base de Datos
1.  [cite_start]**Alumnos:** Registro de identidad y contacto institucional. [cite: 5]
2.  [cite_start]**Profesores:** Información sobre especialidad y honorarios. [cite: 7, 9]
3.  [cite_start]**Asignaturas:** Catálogo de materias y créditos académicos. [cite: 11, 12]
4.  [cite_start]**OfertaAcademica:** Relación entre docentes y materias disponibles. [cite: 14, 15]
5.  [cite_start]**Matriculacion:** Registro histórico de alumnos inscritos en la oferta. [cite: 18, 19]

## 📋 Instrucciones de Uso
1. Ejecute el script de creación contenido en `database_design.sql`.
2. [cite_start]Ejecute los scripts de inserción para poblar el sistema con datos de prueba. [cite: 25, 29, 33]
3. Utilice las vistas y subconsultas proporcionadas para generar reportes académicos.
