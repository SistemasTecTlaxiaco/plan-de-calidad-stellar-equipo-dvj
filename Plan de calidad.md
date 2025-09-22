Materia: Ingeniería en Sistemas Computacionales

Actividad: Plan de Calidad del Proyecto **BlockSys Stellar** – SCF

Estudiantes:

 * Cruz Ramírez Jaczibeth
 * Cruz Ortiz Vanessa
 * Velasco López Daniel

----------

## 1. Introducción
Este documento presenta el **Plan de Calidad** del proyecto **BlockSys Stellar**, una iniciativa desarrollada en el marco del **Stellar Community Fund (SCF)** y orientada a estudiantes y profesionales de **Ingeniería en Sistemas Computacionales**.

El objetivo de BlockSys Stellar es **crear una plataforma académica y práctica** que permita a los usuarios comprender, diseñar e implementar soluciones distribuidas utilizando la red Stellar. A través de este proyecto, se busca reforzar conocimientos en áreas clave como blockchain, sistemas distribuidos, seguridad, bases de datos y desarrollo de software.

Este plan sigue los lineamientos de **MoProSoft** y las buenas prácticas de calidad en desarrollo de software, asegurando que el producto final sea confiable, seguro, mantenible y cumpla con las expectativas de la comunidad académica y tecnológica.

---

## 2. Alcance
El plan de calidad se aplicará a todas las fases del ciclo de vida del proyecto **BlockSys Stellar**:
- Planificación y definición de requisitos.  
- Diseño de arquitectura (sistema, base de datos, contratos inteligentes, APIs).  
- Implementación de módulos (backend, frontend y contratos en Stellar).  
- Pruebas unitarias, de integración, de seguridad y de aceptación.  
- Despliegue en red Stellar (testnet/mainnet).  
- Documentación y entrega a la comunidad.  

El alcance incluye tanto los componentes técnicos (software) como la documentación académica y los materiales de apoyo para estudiantes y desarrolladores.

---

## 3. Gestión de la Calidad del Proyecto

### 3.1. Objetivos de Calidad
- Garantizar que los módulos de BlockSys Stellar funcionen correctamente y de manera integrada.  
- Cumplir con estándares de **seguridad, escalabilidad y rendimiento** propios de soluciones sobre Stellar.  
- Desarrollar una experiencia de usuario intuitiva para estudiantes y desarrolladores.  
- Generar documentación clara, completa y útil para fines académicos y profesionales.  

### 3.2. Métricas de Calidad

**Métricas de Código**
- Cobertura de pruebas unitarias: **≥80%**.  
- Cumplimiento de estándares de estilo (lint): **100% del código revisado**.  
- Errores críticos en QA: **<5 por versión**.  

**Métricas de Requisitos y Diseño**
- Cumplimiento de requisitos funcionales: **≥95%**.  
- Retroalimentación de estudiantes en pruebas piloto: **≥4/5 estrellas**.  

**Métricas de Desempeño**
- Tiempo promedio de respuesta en transacciones Stellar: **≤5 segundos**.  
- Disponibilidad del sistema: **≥99% durante pruebas de carga**.  

---

## 4. Procedimientos y Actividades de Calidad

### 4.1. Procedimientos de Revisión
- **Revisión de Requisitos:** Validación de requisitos con el equipo de desarrollo y docentes de Ingeniería en Sistemas.  
- **Revisión de Diseño:** Validación de arquitectura (smart contracts, APIs, base de datos, UI/UX).  
- **Revisión de Código (Code Review):** Todos los cambios deben ser revisados y aprobados antes de integrarse a la rama principal.  

### 4.2. Políticas de Pruebas
- **Pruebas Unitarias:** En contratos inteligentes y módulos del backend.  
- **Pruebas de Integración:** Validación del flujo completo de transacciones en Stellar.  
- **Pruebas de Seguridad:** Auditoría de vulnerabilidades comunes (ej. overflow, reentrancy).  
- **Pruebas de Usabilidad (UAT):** Grupo de estudiantes prueba la interfaz y reporta mejoras.  
- **Pruebas de Carga:** Simulación de múltiples transacciones simultáneas para validar estabilidad.  

---

## 5. Gestión de la Configuración y Liberación

- **Control de Versiones:**  
  - Uso de **GitHub** con ramas: `main` (producción), `develop` (desarrollo), `feature/*`.  
  - Pull requests obligatorios con revisiones de calidad.  

- **Etiquetado de Versiones:**  
  - Estándar **SemVer (ej. v1.0.0)**.  
  - Registro de cambios (*changelog*).  

- **Plan de Liberación:**  
  - Cada versión documenta nuevas funcionalidades y correcciones.  
  - Publicación de versiones en GitHub Releases y canales SCF.  
  - Pruebas previas en **Stellar Testnet** antes de migrar a mainnet.  

---

## 6. Documentación

El proyecto contará con documentación actualizada y accesible para la comunidad:  
- **Documentación de Código:** Comentarios y guías técnicas.  
- **Manual del Usuario:** Instrucciones para registro, transacciones y consultas.  
- **Documentación Técnica:**  
  - Diagramas de arquitectura del sistema.  
  - Flujos de datos y procesos.  
  - Esquema de interacción con la red Stellar.  
- **Guías Académicas:** Material de apoyo para estudiantes de Ingeniería en Sistemas.  

---

## 7. Roles y Responsabilidades

- **Líder de Calidad:** Supervisa la implementación del plan y valida métricas.  
- **Equipo de Desarrollo:** Implementa requisitos, realiza pruebas unitarias y mantiene documentación.  
- **Tester/QA:** Ejecuta pruebas de seguridad, carga y aceptación.  
- **Docentes/Usuarios Piloto:** Validan la calidad académica y técnica del proyecto.  

---

## 8. Gestión de Riesgos de Calidad

| Riesgo | Impacto | Mitigación |  
|--------|---------|------------|  
| Vulnerabilidades en contratos inteligentes | Alto | Auditorías externas y revisiones de seguridad |  
| Baja adopción por complejidad técnica | Medio | Simplificar interfaz y guías académicas |  
| Retrasos en entregables | Medio | Uso de metodologías ágiles (Scrum/Kanban) |  
| Problemas de integración con Stellar Horizon | Alto | Pruebas continuas en testnet antes de producción |  

---

## 9. Control y Seguimiento
- Reuniones semanales de revisión de calidad.  
- Seguimiento con tableros Kanban (Trello, Jira o GitHub Projects).  
- Reportes de calidad por sprint:  
  - Cobertura de pruebas.  
  - Defectos encontrados.  
  - Retroalimentación de usuarios.  

---

## 10. Conclusión
El Plan de Calidad de **BlockSys Stellar** establece las bases para desarrollar un proyecto académico y profesional que integre los conocimientos de Ingeniería en Sistemas Computacionales con la tecnología blockchain de Stellar.  

La combinación de **estándares de calidad, métricas claras, pruebas rigurosas y documentación accesible** garantiza que el producto sea confiable, seguro, útil y con impacto tanto en la comunidad educativa como en el ecosistema Stellar.

