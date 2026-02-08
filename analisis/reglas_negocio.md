# Reglas de Negocio Consolidadas

Estas reglas representan los "guardrails" o controles estrictos que el sistema impone para garantizar el rigor administrativo.

## Reglas de Planificación (CMN)
1. **Techo Presupuestal**: Un pedido programado no puede exceder la cantidad ni el monto planificado en el CMN para ese mes específico.
2. **Previsión Obligatoria**: Si un ítem tiene contratos vigentes, debe marcarse como "Obligación de Pago" antes de planificar nuevas compras.

## Reglas de Solicitud (Pedidos)
1. **Justificación de Excepción**: Si se solicita un bien que ya estaba en el plan pero como "No Programado", el sistema exige una justificación obligatoria.
2. **Saldo SIAF en Tiempo Real**: No se puede autorizar un pedido de compra si no existe saldo disponible suficiente en la Meta/Rubro correspondiente del SIAF.
3. **Flujo de Aprobación**: Ningún pedido puede ser atendido por almacén si no cuenta con el V°B° del Jefe del Centro de Costo y la Autorización de Logística.

## Reglas de Almacén
1. **Control de Calidad (QC)**: Solo los ítems en estado `Liberado` pueden generar un incremento oficial de stock (Entrada).
2. **Prioridad Cronológica**: La fecha de atención de un pedido no puede ser anterior a la fecha de la última PECOSA generada (garantiza orden correlativo).
3. **Consistencia de Inventario**: No se pueden realizar salidas (PECOSA) si el Inventario Inicial no ha sido cerrado y marcado como `Conforme`.
4. **Vinculación Patrimonial**: Los ítems marcados como Activos Fijos deben generar obligatoriamente un registro en el módulo de Patrimonio antes de su disposición final.
