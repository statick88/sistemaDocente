# sistemaDocente

``` mermaid
graph TD;
    A[Autenticación] --> B[Gestión de Roles]
    B --> C[Gestión de Temas]
    C --> D[Registro de Actividades]
    C --> E[Registro de Calificaciones]
    C --> F[CRUD de Tareas]
    F --> G[Marcar como impartida]
    F --> H[Indicar actividad pendiente]
    F --> I[Registrar observaciones]
    C --> J[Reporte en PDF]
    C --> K[Interfaz de Usuario]
    D --> K
    E --> K
    F --> K
    J --> K
    K --> L[Agregar, editar y eliminar temas]
    K --> M[Registrar actividades]
    K --> N[Gestionar tareas]
    N --> O[Marcar como realizada]
    N --> P[Nueva actividad]
    K --> Q[Generar reporte en PDF]
  ```
