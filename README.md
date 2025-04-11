DESCRIPCION DEL PROYECTO 
Este proyecto implementa un sistema de gestión de inventario para una tienda de tecnología llamada TechZone utilizando PostgreSQL. El sistema permite registrar y gestionar información de productos, clientes, proveedores y ventas. Incluye funcionalidades como:

![Captura de pantalla 2025-04-11 152710](https://github.com/user-attachments/assets/aef6c77f-ad20-4c49-9684-9e8d6a65eb90)


Gestión de stock y productos.

Registro de clientes y proveedores.

Registro y control de ventas.

Consultas avanzadas para análisis de ventas y clientes.

Procedimiento almacenado que valida ventas y controla stock automáticamente.

El siguiente modelo E-R muestra las entidades, relaciones y cardinalidades del sistema. El modelo está normalizado hasta la 3FN para evitar redundancias.

Instrucciones para Importar y Ejecutar en PostgreSQL 1.Clonar o descargar este repositorio.

2.Abrir tu cliente PostgreSQL favorito (pgAdmin, DBeaver, o desde terminal).

Consultas Incluidas (queries.sql) 1.Productos con stock menor a 5 unidades.

2.Ventas totales de un mes específico.

3.Cliente con más compras realizadas.

4.Los 5 productos más vendidos.

5.Ventas realizadas en un rango de 3 días y un mes.

6.Clientes que no han comprado en los últimos 6 meses.
