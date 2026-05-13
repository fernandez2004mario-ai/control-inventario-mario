# Documento de visión y alcance

## Nombre del sistema

Sistema de Control de Inventario Básico

## Problema actual

En la institución, el control de inventario se realiza mediante registros manuales, planillas o información distribuida entre distintas áreas. Esto genera dificultad para saber qué artículos se encuentran disponibles, cuáles están asignados, cuáles están en reparación y cuáles han sido dados de baja.

Además, al no existir un historial centralizado, se vuelve complejo revisar quién realizó un movimiento, cuándo se asignó un artículo, cuándo fue devuelto o si existe stock suficiente para cubrir las necesidades internas.

## Objetivo del sistema

El objetivo del sistema es centralizar el control de inventario institucional, permitiendo registrar artículos, controlar entradas y salidas, asignar bienes a usuarios, supervisar el stock mínimo y mantener trazabilidad de los movimientos realizados.

## Alcance del proyecto

El sistema permitirá registrar artículos, consultar disponibilidad, controlar entradas y salidas, asignar elementos a funcionarios, registrar devoluciones, cambiar estados y mantener un historial auditable de movimientos.

En esta primera etapa, el proyecto se enfocará en definir la estructura base, los roles, el flujo principal y las funcionalidades mínimas del MVP.

## Usuarios y roles

### Usuario solicitante

Es quien consulta disponibilidad o solicita un artículo del inventario. Puede revisar información básica de los elementos disponibles, pero no puede modificar registros.

### Encargado de inventario

Es quien administra los movimientos del inventario. Puede registrar artículos, actualizar stock, asignar elementos, registrar devoluciones y cambiar estados.

### Administrador

Es quien mantiene la configuración general del sistema. Puede administrar usuarios, roles, permisos, categorías y revisar reportes generales del inventario.

## MVP

El MVP considera una primera versión funcional del sistema con las siguientes características:

1. Inicio de sesión de usuarios.
2. Registro de artículos o materiales.
3. Consulta del inventario disponible.
4. Registro de entradas de stock.
5. Registro de salidas o asignaciones.
6. Control de stock mínimo.
7. Cambio de estado de artículos.
8. Historial de eventos auditables.

## Flujo principal del usuario

1. El encargado de inventario inicia sesión en el sistema.
2. Registra un nuevo artículo indicando nombre, categoría, cantidad, ubicación y estado.
3. Un usuario solicitante consulta la disponibilidad del artículo.
4. El encargado registra la salida o asignación del artículo.
5. El sistema actualiza el stock disponible.
6. Cuando el artículo es devuelto, el encargado registra la devolución.
7. El sistema guarda el historial del movimiento realizado.

## Eventos auditables

El sistema debe registrar como mínimo los siguientes eventos:

1. Inicio de sesión de un usuario.
2. Registro de un nuevo artículo.
3. Entrada de stock.
4. Salida o asignación de un artículo.
5. Devolución de un artículo.
6. Cambio de estado de un artículo.
7. Baja de un artículo del inventario.

## Importancia institucional

Este sistema es importante porque permite mejorar el orden interno, reducir errores en el control de bienes, evitar pérdidas de información y mantener una trazabilidad clara sobre los movimientos del inventario. Además, ayuda a tomar mejores decisiones sobre compras, reposición de materiales y asignación de recursos.
