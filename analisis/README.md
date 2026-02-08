# Análisis del Sistema Logístico (SIGA-MEF)

Este directorio contiene la ingeniería inversa conceptual del sistema logístico basada en el manual de usuario. El objetivo es comprender cómo se modela la logística institucional, desde la planificación hasta la entrega física de bienes.

## Índice de Documentación

### 1. [Prerrequisitos del Sistema](requisitos/prerrequisitos.md)
Define la base necesaria para que los procesos funcionen:
- Estructura organizacional (Centros de Costo).
- Datos maestros (Catálogo, Metas presupuestales).
- Configuraciones operacionales iniciales.

### 2. Procedimientos Core
Detalle de los módulos principales modelados por el sistema:
- **[Programación de Necesidades](procedimientos/programacion_necesidades.md)**: El modelo de planificación multianual (CMN).
- **[Gestión de Pedidos](procedimientos/gestion_pedidos.md)**: El ciclo de vida de las solicitudes y su autorización lógica.
- **[Operaciones de Almacén](procedimientos/operaciones_almacen.md)**: El flujo físico de bienes (Recepción, Entrada, PECOSA e Inventario).

### 3. Flujos de Trabajo Integrados
- **[Ciclo de Vida Logístico](flujos_de_trabajo/ciclo_vida_logistica.md)**: Diagramas y explicaciones de cómo se conectan todos los procedimientos anteriores en un flujo continuo de gestión pública.

## Metodología
Este análisis se ha realizado abstrayendo las funciones del manual de usuario para identificar las reglas de negocio, las dependencias presupuestarias y los puntos de control que rigen el sistema.
