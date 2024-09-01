
# Florentino - Gestión de Tienda de Muebles

Este repositorio contiene un sistema de gestión de tienda de muebles desarrollado en Odoo, llamado **Florentino**. Este sistema está diseñado para manejar diferentes aspectos de la operación de una tienda de muebles, incluyendo la gestión de productos, inventarios, ventas, y mucho más.

## Características Principales

- **Gestión de Productos:** Permite la creación y administración de productos de muebles con detalles específicos como tipo de mueble, materiales, colores, y dimensiones.
- **Control de Inventario:** Gestión detallada del inventario, seguimiento de existencias, y control de stock.
- **Gestión de Ventas:** Funcionalidades completas para manejar el ciclo de ventas, desde la cotización hasta la facturación.
- **Reportes Personalizados:** Generación de reportes para análisis de ventas, inventarios, y desempeño del negocio.
- **Integración con Módulos Odoo:** Fácil integración con otros módulos de Odoo para extender las capacidades del sistema según sea necesario.

## Requisitos

- **Odoo 15** o superior.
- **Python 3.8** o superior.
- Dependencias adicionales listadas en `requirements.txt`.

## Instalación

1. **Clona este repositorio** en tu máquina local:
   ```bash
   git clone https://github.com/MarcoTenCortes/Florentino.git
   ```

2. **Navega al directorio del proyecto:**
   ```bash
   cd Florentino
   ```

3. **Instala las dependencias necesarias** usando `pip`:
   ```bash
   pip install -r requirements.txt
   ```

4. **Configura la base de datos** en tu instancia de Odoo, asegurándote de tener acceso a la base de datos donde se almacenará la información del sistema.

5. **Carga los módulos** del sistema en tu instancia de Odoo. Esto se puede hacer a través de la interfaz de Odoo o mediante la línea de comandos:
   ```bash
   odoo -i nombre_del_modulo -d nombre_de_la_base_de_datos
   ```

6. **Inicia el servidor de Odoo** para comenzar a usar el sistema:
   ```bash
   odoo -r tu_usuario -w tu_contraseña -d nombre_de_la_base_de_datos
   ```

## Uso

Una vez instalado, puedes acceder al sistema desde la interfaz web de Odoo y comenzar a utilizar las funcionalidades desarrolladas para la gestión de tu tienda de muebles.

## Contribución

Las contribuciones son bienvenidas. Por favor, realiza un fork del repositorio, crea una nueva rama para tu característica o corrección de errores, y abre un Pull Request para revisar tus cambios.


## Contacto

Para preguntas o soporte, puedes contactar al desarrollador principal:

- **Nombre:** Marco Tenorio Cortes
- **Email:** marcotencortes@hotmail.com
