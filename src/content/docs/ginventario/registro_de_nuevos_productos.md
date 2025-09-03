---
title: Creación de un Nuevo Producto
description: Guía para registrar un nuevo producto en el sistema de gestión de inventario.
---

# 🛒 Creación de un Nuevo Producto

El sistema permite registrar nuevos productos dentro del inventario para llevar un control detallado de entradas, salidas y trazabilidad de materiales.  
Este proceso reemplaza los registros manuales por un flujo digital, seguro y centralizado.

---

![Pantalla de inicio de sesión](/public/formulario_p.png)

## 📥 Entradas necesarias

Al momento de crear un producto, el sistema solicita los siguientes datos:

- **Nombre del producto** (ejemplo: "Tornillo 3/8")  
- **Descripción** (características relevantes)  
- **Categoría** (ejemplo: herramienta, material de oficina, insumo de limpieza)  
- **Unidad de medida** (ejemplo: unidad, caja, kg, litro)  
- **Cantidad inicial** (stock con el que se registra el producto)  
- **Proveedor** (opcional, si aplica)  

---

## ⚙️ Proceso

1. El usuario accede al módulo **Productos** desde el menú principal.  
2. Selecciona la opción **Agregar Nuevo Producto**.  
3. El sistema despliega un formulario con los campos requeridos.  
4. El usuario completa los datos y confirma la acción.  
5. El sistema valida la información ingresada (campos obligatorios y formato).  
6. Si todo es correcto, se registra el producto en la base de datos y queda disponible en el inventario.  

---

## 📤 Salidas (Resultados)

- ✅ El producto aparece en la **lista de inventario** con su información básica.  
- 📊 El sistema puede incluirlo en **reportes estadísticos** de entradas/salidas.  
- 🔒 Los permisos de rol definen quién puede **crear, editar o eliminar** productos.  
- 📝 Se guarda un **log de auditoría** con la acción realizada (usuario, fecha y hora).  

---

## 🔗 Enlaces Relacionados

- [Gestión de Inventario](./inventario.md)  
- [Control de Movimientos](./movimientos.md)  
- [Gestión de Proveedores](./proveedores.md)  
