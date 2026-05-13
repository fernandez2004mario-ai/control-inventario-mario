# control-inventario-mario
diplomado
# Sistema de Control de Inventario Básico

## Descripción del proyecto

Este proyecto consiste en el diseño inicial de un sistema institucional para el control básico de inventario. Su propósito es registrar, organizar y supervisar los bienes, equipos o materiales disponibles dentro de una institución, permitiendo controlar entradas, salidas, asignaciones y stock mínimo.

El sistema está pensado para instituciones que necesitan administrar recursos como computadores, proyectores, herramientas, insumos, materiales de oficina u otros elementos utilizados por funcionarios o distintas áreas internas.

Actualmente, muchas instituciones llevan este control mediante planillas, correos o registros manuales, lo que puede provocar errores, pérdida de información, falta de trazabilidad y dificultad para saber qué elementos están disponibles, asignados o dados de baja.

## Problema actual

La institución no cuenta con un sistema centralizado para controlar su inventario. Esto genera desorden en el registro de equipos y materiales, dificultad para conocer el stock disponible, falta de seguimiento sobre las asignaciones y poca trazabilidad sobre los movimientos realizados.

## Usuarios principales

- Usuario solicitante: funcionario que consulta disponibilidad o solicita un elemento del inventario.
- Encargado de inventario: persona responsable de registrar entradas, salidas, asignaciones y devoluciones.
- Administrador: usuario encargado de configurar categorías, usuarios, permisos y revisar reportes generales.

## Roles y permisos iniciales

### Usuario solicitante

Puede consultar elementos disponibles y solicitar la asignación de un equipo, material o insumo. No puede modificar registros de inventario ni eliminar información.

### Encargado de inventario

Puede registrar nuevos elementos, actualizar cantidades, asignar bienes a funcionarios, registrar devoluciones, controlar stock mínimo y cambiar el estado de los artículos.

### Administrador

Puede administrar usuarios, asignar roles, crear categorías, revisar reportes generales y acceder al historial completo de movimientos del inventario.

## Funcionalidades mínimas del MVP

El producto mínimo viable considera las siguientes funcionalidades iniciales:

1. Registro e inicio de sesión de usuarios.
2. Registro de artículos, equipos o materiales.
3. Visualización del inventario disponible.
4. Registro de entradas de inventario.
5. Registro de salidas o asignaciones de inventario.
6. Control de stock mínimo.
7. Cambio de estado de un artículo, por ejemplo: disponible, asignado, en reparación o dado de baja.
8. Historial de movimientos realizados sobre cada artículo.

## Eventos auditables

El sistema debe guardar registro de las siguientes acciones importantes:

- Inicio de sesión de usuarios.
- Registro de un nuevo artículo.
- Entrada de stock.
- Salida o asignación de un artículo.
- Devolución de un artículo.
- Cambio de estado de un artículo.
- Baja o eliminación lógica de un artículo.

## Flujo principal del usuario

1. El usuario inicia sesión en el sistema.
2. El encargado de inventario registra un nuevo artículo o actualiza el stock existente.
3. Un usuario solicitante revisa la disponibilidad de un elemento.
4. El encargado asigna el artículo al usuario correspondiente.
5. El sistema registra el movimiento realizado.
6. Cuando el artículo es devuelto, el encargado actualiza su estado en el inventario.

## Estructura del repositorio

```text
/frontend
/backend
/docs
/scripts
README.md
