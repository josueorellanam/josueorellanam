| **Módulo**               | **Caso de Prueba**               | **Entrada de Prueba** | **Resultado Esperado** | **Resultado Obtenido** | **Estado** |
|-------------------------|---------------------------------|----------------------|----------------------|----------------------|---------|
| Registro de productos   | Validar ingreso de producto    | Código: "P001", Nombre: "Laptop", Cantidad: 10 | Producto registrado correctamente | Producto registrado correctamente | ✅ Aprobado |
| Edición de productos    | Modificar datos de producto    | Código: "P001", Nombre: "Laptop Pro" | Datos actualizados correctamente | Error en actualización | ❌ Rechazado |
| Entrada de inventario   | Validar actualización de stock | Código: "P001", Cantidad: 5 | Stock actualizado | Stock actualizado | ✅ Aprobado |
| Salida de inventario    | Validar reducción de stock     | Código: "P001", Cantidad: 3 | Stock reducido correctamente | Error en validación | ❌ Rechazado |
| Reporte de existencias  | Generar reporte de inventario  | Fecha: "2025-06-05" | Reporte generado correctamente | Error en generación | ❌ Rechazado |
| Gestión de usuarios     | Creación de nuevo usuario      | Usuario: "admin", Contraseña: "1234" | Usuario creado correctamente | Usuario creado correctamente | ✅ Aprobado |
