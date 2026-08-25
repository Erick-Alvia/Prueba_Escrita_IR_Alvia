# Prueba Práctica - Unidad IV

## Ingeniería de Requisitos (ISR-401)

**Estudiante:** Alvia Villegas Erick Adalberto  
**Docente:** Ing. Guerrero Ulloa Gleiston Cicerón  
**Universidad:** Universidad Técnica Estatal de Quevedo  

---

## Descripción

Repositorio correspondiente a la Prueba Práctica de la Unidad IV de la asignatura Ingeniería de Requisitos (ISR-401).

El trabajo desarrolla el caso **Sistema de Gestión de Pedidos** mediante diez actividades prácticas relacionadas con modelado UML, especificación y validación de requisitos, priorización MoSCoW, pruebas de aceptación, trazabilidad y gestión del cambio.

---
## Contenido del desarrollo

* **P1. Modelo de datos - Diagrama de clases UML:** Definición de clases (`Cliente`, `Pedido`, `Linea_Pedido`, `Producto`), atributos, operaciones, multiplicidades e identificadores.
* **P2. Modelo funcional - Diagrama de actividades UML:** Modelado del proceso "Registrar pedido" usando carriles de responsabilidad, decisiones, flujos alternativos y convergencia.
* **P3. Modelo de comportamiento - Máquina de estados UML:** Ciclo de vida del Pedido integrando un superestado para factorizar la acción de anulación.
* **P4. Consistencia entre las tres perspectivas:** Tabla de verificación cruzada entre P1, P2 y P3 para corrección de inconsistencias.
* **P5. Especificación de requisitos con esquema de atributos:** Definición de requisitos funcionales y no funcionales estructurados bajo el estándar ISO/IEC 25010:2023.
* **P6. Priorización MoSCoW:** Clasificación estratégica de requisitos evaluando valor de negocio vs. viabilidad técnica.
* **P7. Validación por inspección ISO/IEC/IEEE 29148:** Lista de comprobación de calidad, detección de defectos y versión corregida (retrabajo).
* **P8. Pruebas de aceptación trazadas:** Diseño de casos de prueba (`TC-01` a `TC-04`) con entradas y criterios de éxito claros.
* **P9. Matriz de trazabilidad:** Matriz bidireccional que conecta requisitos con fuentes, modelos UML, pruebas y dependencias.
* **P10. Gestión del cambio y línea base:** Simulación de una Solicitud de Cambio (`RFC-01`), análisis de impacto, resolución del CCB y congelamiento de Baseline v1.0.

---

## Compilación

El documento fue desarrollado en **LaTeX** y compilado mediante **pdfLaTeX** por medio de la terminal del computador con el uso de MikTex.

### Compilador
`pdfLaTeX`

### Archivo principal
`main.tex`

## Figuras y Evidencias

### Carpeta `Figuras/`
* `Class_Diagram.png`: Diagrama de clases UML del dominio.
* `Activity_DIagram.png`: Diagrama de actividades del proceso de registro.
* `Machine_State.png`: Diagrama de estados del ciclo de vida del pedido.

### Carpeta `Evidencias/`
* `Resumen_Cuestionario.png`: Captura del resumen del cuestionario en el SGA.
* `Revision_Intento.png`: Captura de evaluación y revisión del intento SGA.

### Orden de compilación
Ejecutar en la terminal del computador (se recomienda tener instalado MikTex):
dentro del terminal colocar el siguiente comando cd "Ruta donde se encuentra su archivo en el explorador"; 

ej: `cd "C:\Users\GAMEMAX\OneDrive\Documentos\00_Git\Prueba"`

luego colocar el siguiente comando: 

`pdflatex main.tex`

Volver a ejecutar permite actualizar correctamente la numeración, referencias internas y demás elementos generados por LaTeX:

`pdflatex main.tex`

## Dependencias

El documento utiliza los siguientes paquetes de LaTeX:

* `inputenc`
* `babel`
* `geometry`
* `graphicx`
* `booktabs`
* `array`
* `tabularx`
* `enumitem`
* `xcolor`
* `titlesec`
* `fancyhdr`
* `hyperref`
* `float`

---

## Estructura del repositorio

```text
SGCV-IA-Practica-U4/
├── main.tex
├── Prueba_Corte_IV__Ingenieria_de_requerimientos_AlviaErick.pdf
├── README.md
├── Figuras/
│   ├── Class_Diagram.png
│   ├── Activity_DIagram.png
│   └── Machine_State.png
└── Evidencias/
    ├── Resumen_Cuestionario.png
    └── Revision_Intento.png

