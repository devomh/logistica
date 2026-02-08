# Requisitos del Sistema Logístico: Prerrequisitos

Para que los procedimientos logísticos funcionen, deben establecerse varios conjuntos de datos y configuraciones fundamentales.

## Requisitos Organizacionales
- **Estructura**: La organización debe estar definida por "Centros de Costo".
- **Jerarquía**: Líneas de reporte claras para aprobaciones (Jefe de Centro de Costo, Área de Logística).
- **Perfiles de Usuario**: Cada usuario debe estar vinculado a un Centro de Costo y tener permisos específicos (ej. "Registro de Pedido", "Autorización", "Gestión de Almacén").

## Requisitos de Datos Maestros
- **Catálogo Institucional**: Una lista completa de ítems (Bienes/Servicios) con códigos únicos, unidades de medida y precios estimados.
- **Integración Presupuestaria (SIAF)**:
    - **Metas**: Metas institucionales específicas.
    - **Fuentes de Financiamiento**: Fuentes de recursos.
    - **Clasificadores de Gasto**: Categorías de gasto.
- **Base de Datos de Proveedores**: Proveedores prerregistrados para Órdenes de Compra.

## Prerrequisitos Operacionales
- **Definición de Almacén**: Los espacios físicos deben definirse en el sistema con ubicaciones jerárquicas (Zonas, Estantes).
- **Inventario Inicial**: El sistema requiere que se registre y confirme un "Inventario Inicial" antes de que ocurran movimientos de salida para el stock existente.
- **Vínculos Contables**: Cada ítem debe estar mapeado a una "Cuenta Contable" para mantener la sincronización financiera.
