# Proyecto LaTeX — Sistema de Información para Tutorías

Este repositorio contiene el proyecto en **LaTeX** para el curso **Metodologías y Desarrollo de Software I**, correspondiente al documento del **Sistema de Información para Tutorías** de la **Escuela Profesional de Ingeniería Informática y de Sistemas**.

## Descripción General

El documento se compone en formato **académico** y usa un **estilo personalizado** desarrollado en el archivo `formato.sty`.  

### Archivos principales

- **main.tex:**  
  Archivo raíz del proyecto. Carga las secciones, define los datos del trabajo (título, autores, semestre, etc.) y organiza la estructura general del documento.

- **formato.sty:**  
  Define los estilos del documento: márgenes, encabezados, pie de página, formato de tablas, tipografía, bibliografía y comandos personalizados (como `\titulo`, `\asignatura`, `\semestre`, etc.).

- **portada.tex:**  
  Archivo con la plantilla de la carátula, usa las variables definidas en `main.tex` mediante los comandos personalizados del `.sty`.

- **sections/**  
  Carpeta modular que organiza cada parte del informe en un archivo separado.  
  Esto facilita el trabajo colaborativo y mantiene el documento limpio.

## Compilación

### Requisitos

Para compilar el proyecto se necesita:

- **MiKTeX** o **TeX Live** actualizado.  
- **VS Code** con la extensión **LaTeX Workshop** o **Overleaf** en línea.

### Compilación en VS Code

1. Abrir la carpeta del proyecto en VS Code.  
2. Asegurarse de tener MiKTeX instalado y con permisos para instalar paquetes automáticamente.  
3. Compilar con el comando `Ctrl + Alt + B` (o desde el botón de “Build LaTeX Project”).  
4. El archivo resultante `main.pdf` se generará en la raíz del proyecto.

Si aparecen advertencias de paquetes, MiKTeX preguntará si desea instalarlos: seleccionar **Yes/Always**.
