# Procedimiento: Consulta de Inventario y Stock de Seguridad

## 1. Objetivo
Verificar la disponibilidad de materiales antes de confirmar una cotización de Odoo.

## 2. Reglas de Negocio
* **Bodega Principal:** "Cali - Sede Sur".
* **Stock de Seguridad:** Nunca se debe vender si el inventario proyectado (Forecasted) baja de 5 unidades. Si ocurre, se debe crear una solicitud de compra inmediata.

## 3. Pasos a seguir
1. Abrir el módulo de **Inventario** (Inventory).
2. Ir a **Productos** -> **Productos**.
3. En la barra de búsqueda, ingresar el código SKU o el nombre del artículo.
4. Revisar la tarjeta del producto, específicamente el campo **A Mano** (On Hand) y **Proyectado** (Forecasted).
