# Logistics System Requirements: Pre-requisites

For the logistics procedures to function, several foundational data sets and configurations must be in place.

## Organizational Requirements
- **Structure**: The organization must be defined by "Centros de Costo" (Cost Centers).
- **Hierarchy**: Clear reporting lines for approvals (Head of Cost Center, Logistics Area).
- **User Profiles**: Every user must be linked to a Cost Center and granted specific permissions (e.g., "Registro de Pedido", "Autorización", "Gestión de Almacén").

## Master Data Requirements
- **Institutional Catalog**: A comprehensive list of items (Bienes/Servicios) with unique codes, units of measure, and estimated prices.
- **Budgetary Integration (SIAF)**:
    - **Metas**: Specific institutional goals.
    - **Fuentes de Financiamiento**: Sources of funding.
    - **Clasificadores de Gasto**: Spending categories.
- **Supplier Database**: Pre-registered providers for Purchase Orders.

## Operational Prerequisites
- **Warehouse Definition**: Physical spaces must be defined in the system with hierarchical locations (Zonas, Estantes).
- **Initial Inventory**: The system requires an "Inventario Inicial" to be registered and confirmed (Conforme) before any exit movements (Salidas) can occur for existing stock.
- **Accounting Links**: Every item must be mapped to a "Cuenta Contable" (Accounting Account) to maintain financial synchronization.
