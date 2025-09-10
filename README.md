<h1 align="center">📱 ORGANIZACION TOTAL</h1>

<p align="center">
  <b>Aplicación móvil integral para la planificación y organización personal</b>  
</p>

<p align="center">
  Gestiona tu vida diaria en un solo lugar: rutinas, comidas, ejercicios, pagos, servicios y tareas.  
</p>

---

## 1. Nombre del Proyecto
**ORGANIZACION TOTAL** – Aplicación móvil integral que permite al usuario planificar y organizar todos los aspectos de su vida, incluyendo rutinas diarias, comidas, ejercicios, pagos, servicios y tareas.

---

## 2. Visión del Proyecto
Ofrecer a los usuarios una herramienta completa y confiable para gestionar su vida diaria de manera organizada, mejorando la productividad, el bienestar y la disciplina personal, con capacidad de adaptarse a futuras funcionalidades y módulos adicionales.

---

## 3. Integrantes del Equipo

| Integrante | Rol en Scrum                | Responsabilidades Técnicas                     |
|------------|-----------------------------|------------------------------------------------|
| **Braulio** | Product Owner + Desarrollador | Definir la visión del producto, priorizar el backlog, coordinar requerimientos, desarrollo de funcionalidades. |
| **Kevin**   | Scrum Master + Desarrollador  | Facilitar el proceso Scrum, eliminar impedimentos, asegurar buenas prácticas, desarrollo de backend y soporte técnico. |
| **Oscar**   | Desarrollador Principal       | Implementación del frontend en Flutter, diseño de la interfaz de usuario, integración con la lógica de negocio. |

---

## 4. Justificación de la Metodología
Se utiliza **Scrum**, una metodología ágil que permite organizar el desarrollo en sprints cortos, priorizar funcionalidades según necesidades del usuario, y recibir retroalimentación continua. Esto garantiza entregas rápidas y mejora la adaptabilidad del proyecto.

---

## 5. Arquitectura de la Aplicación Móvil
La aplicación se basa en **Clean Architecture + MVVM**, lo que permite:  
- Separar claramente la UI de la lógica de negocio y los datos.  
- Facilitar pruebas unitarias y de integración.  
- Escalar la aplicación fácilmente agregando nuevos módulos sin afectar el código existente.  

**Capas principales:**  
- **UI (View):** Interfaz de usuario en Flutter.  
- **ViewModel:** Gestiona la lógica de presentación y comunica la UI con el dominio.  
- **Dominio (Use Cases):** Contiene la lógica de negocio y reglas de la aplicación.  
- **Datos (Repository):** Gestiona el almacenamiento y la recuperación de información desde la base de datos o servicios externos.

---

## 6. Framework de Desarrollo
Se utiliza **Flutter (Dart)**, un framework multiplataforma que permite crear aplicaciones móviles para **Android** e **iOS** con un solo código base, garantizando interfaces rápidas, adaptativas y consistentes.

---

## 7. Patrón de Diseño
Se aplica **MVVM** (Model-View-ViewModel) para mantener separada la UI de la lógica de negocio, facilitando mantenimiento, pruebas y escalabilidad de la aplicación.

---

## 8. Plan de Desarrollo
1. Análisis de requerimientos y definición de módulos: Rutinas, Tareas, Pagos, Comidas, Ejercicios.  
2. Diseño de arquitectura y estructura de base de datos.  
3. Desarrollo del backend y APIs necesarias.  
4. Desarrollo del frontend móvil en Flutter con interfaces intuitivas.  
5. Integración de módulos y funcionalidades completas.  
6. Pruebas unitarias, de integración y de usabilidad.  
7. Ajustes finales y despliegue.

---

## 9. Estrategias de Prueba
- **Pruebas unitarias:** Validar funciones y componentes individuales.  
- **Pruebas de integración:** Asegurar la comunicación correcta entre módulos.  
- **Pruebas funcionales:** Verificar que la app cumpla los requerimientos.  
- **Pruebas de usabilidad:** Evaluar experiencia del usuario y facilidad de uso.  
- **Pruebas de rendimiento:** Garantizar rapidez y estabilidad en dispositivos móviles.

---

## 10. Estrategias de Versionamiento
Se utiliza **Git** con **Git Flow**:  
- `main` → Versión estable de producción.  
- `develop` → Integración de nuevas funcionalidades antes de pasar a main.  
- `feature/*` → Desarrollo de nuevas funciones.  
- `release/*` → Preparación para despliegue.  
- `hotfix/*` → Corrección de errores críticos.

---

## 11. Conclusión
**ORGANIZACION TOTAL** es una solución integral para la gestión de la vida diaria, combinando múltiples funcionalidades en una sola aplicación móvil. Gracias a la combinación de **Clean Architecture + MVVM** y **Flutter**, la aplicación es escalable, mantenible y preparada para futuras mejoras, asegurando una experiencia completa y confiable para el usuario.
