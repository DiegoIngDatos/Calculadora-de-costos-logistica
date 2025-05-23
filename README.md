# Calculadora-de-costos-logistica

Herramienta interactiva para el cálculo detallado de costos logísticos en operaciones de exportación e importación. Construida en Python con Jupyter Notebook e interactiva mediante `ipywidgets`, esta herramienta facilita la introducción de datos y el cálculo automático de costos unitarios y totales.

## Características

- **Interfaz gráfica de usuario**: Diseño intuitivo que permite ingresar todos los costos asociados de manera sencilla.
- **Cálculo en tiempo real**: Obtiene los costos totales por kilo, caja y pallet automáticamente.
- **Almacenamiento de datos**: Los resultados se guardan en un archivo Excel para su posterior análisis.
- **Descarga del informe**: El archivo generado se puede descargar directamente desde la herramienta.
- **Validación de datos**: Verificación de entrada para evitar errores en los cálculos.

## Funcionalidades

1. **Inicio Rápido**:
   - Rellena los campos de cliente y ubicación.
   - Ingresa los costos asociados a cada componente logístico (aduanas, flete, handling, etc.).
   - Haz clic en el botón "Calcular costo total" para obtener los resultados.

2. **Resultados Detallados**:
   - Costo total por kilogramo.
   - Costo por caja (basado en 3 kg por caja).
   - Costo por pallet (basado en 132 cajas por pallet).

3. **Datos Persistentes**:
   - Los resultados se almacenan automáticamente en un archivo Excel llamado `detalles_costos.xlsx`.
   - Si el archivo ya existe, los nuevos datos se agregan al final del archivo existente.
   - El archivo puede ser descargado directamente desde la herramienta.
