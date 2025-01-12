# Diseño Digital en VLSI

## Descripción General
Este curso se enfoca en los pasos y herramientas del flujo de diseño digital en VLSI, desde la descripción a nivel RTL hasta la generación del layout final (GDS), utilizando herramientas open-source como OpenROAD.

## Objetivos
- Comprender el flujo de diseño digital VLSI y las herramientas involucradas.
- Implementar un diseño completo desde RTL hasta GDS.
- Realizar verificación física y ajustes para tapeout.

## Duración
14 semanas (clases de 2 horas por semana).

## Temario

### Semana 1-2: Introducción al Flujo de Diseño Digital
- Componentes del flujo RTL-to-GDS.
- Configuración de herramientas: Verilog, ngspice y OpenROAD.
- **Práctica**: Simular una celda estándar y analizar tiempos de propagación.

### Semana 3-4: Diseño RTL y Simulación
- Implementación de módulos combinacionales y secuenciales básicos.
- **Práctica**: Diseñar y simular un multiplexor y una FSM en Verilog.

### Semana 5-6: Síntesis Lógica
- Uso de Yosys para la síntesis lógica.
- Análisis de netlists y optimización de constraints.
- **Práctica**: Sintetizar un diseño combinado (multiplexor + FSM).

### Semana 7-8: Floorplanning y Planificación Física
- Configuración de parámetros de diseño en OpenROAD.
- **Práctica**: Generar un floorplan para un bloque funcional.

### Semana 9-10: Colocación y Ruteo
- Colocación de componentes y diseño del clock tree (CTS).
- Ruteo básico con OpenROAD.
- **Práctica**: Diseñar y rutear un bloque funcional pequeño.

### Semana 11-12: Verificación Física
- Verificación de reglas de diseño (DRC) y correlación layout-esquemático (LVS).
- **Práctica**: Corregir errores y hacer LVS clean.

### Semana 13: Generación de GDS
- Ajustes finales y generación del archivo GDS.
- **Práctica**: Crear el archivo GDS de un bloque completo.

### Semana 14: Proyecto Final
- Diseño completo desde RTL a GDS: Implementar un módulo funcional complejo (e.g., controlador UART).

## Evaluación
- Entregables prácticos semanales (50%).
- Proyecto final (50%).
