# Procedimiento: Programación Multianual de Necesidades (CMN)

El "Cuadro Multianual de Necesidades" (CMN) es el procedimiento de planificación fundamental donde el sistema modela la identificación y priorización de las necesidades institucionales.

## Descripción
Este procedimiento permite que cada Centro de Costo planifique los bienes, servicios y obras requeridos para cumplir con sus metas durante un período multianual (típicamente 4 años en este sistema).

## Sub-procedimientos
1. **Identificación de Necesidades**: Registro inicial de ítems requeridos por el Centro de Costo.
2. **Clasificación y Priorización**: Categorización de ítems y determinación de su importancia relativa a las restricciones presupuestarias.
3. **Consolidación**: Agregación de necesidades en toda la organización.
4. **Aprobación**: Autorización final de las necesidades planificadas.

### Fases de Programación del CMN
```mermaid
graph LR
    Req[Requerido: Requerimiento Inicial] --> Prog[Programado: Ajuste Presupuestal]
    Prog --> Ant[Anteproyecto: Borrador Institucional]
    Ant --> Apr[Aprobado: CMN Final Aprobado]
    
    subgraph Ejecución
        Apr --> Action[Activo para Pedidos]
    end
```

## Pasos Clave
- **Selección de Ítems**: Los ítems se eligen de un catálogo estandarizado (Suministros, Activos Fijos, Servicios, Obras).
- **Mapeo de Metas**: Cada ítem debe estar asociado a una "Meta" presupuestaria específica y a una "Actividad Operativa".
- **Distribución Temporal**: Las necesidades se distribuyen mensualmente a lo largo de los años.
- **Previsión Presupuestaria**: Registro de "Obligaciones de Pago" (contratos vigentes) y "Previsiones Presupuestales" (pronósticos futuros).

## Requisitos del Sistema
- **Autorización de Usuario**: El usuario debe tener asignado un "Centro de Costo" específico en su perfil.
- **Datos Maestros**:
    - **Metas**: Deben estar precargadas desde el Módulo de Configuración (típicamente mediante la interfaz SIAF).
    - **Actividades Operativas**: Deben estar asignadas al Centro de Costo correspondiente.
    - **Fuentes de Financiamiento (FF/Rubro)**: Deben estar configuradas.
- **Consistencia del Catálogo**: Los ítems deben existir en el catálogo institucional del sistema con precios estimados.
