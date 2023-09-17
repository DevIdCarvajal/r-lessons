# 1. Introducción

## Índice

[1. Conceptos previos](#1-conceptos-previos)  
[2. Instalación](#2-instalacion)  
[3. Hola Mundo](#3-hola-mundo)  
[4. Gestión de paquetes](#4-gestion-de-paquetes)

## 1. Conceptos previos

### Definición

- R es un entorno de software libre y gratuito.
- Lenguaje interpretado.
- Sistema totalmente planificado y coherente.
- Enfocado a la computación estadística y gráfica.
- Multiplataforma.
- Proyecto colaborativo mantenido por la comunidad.

### Características

- Manejo y almacenamiento efectivo de los datos.
- Operadores para cálculos con matrices.
- Herramientas para el análisis de datos.
- Utilidades gráficas para la visualización de datos.
- Un lenguaje de programación completo: control de flujo, funciones, etc.
- Integración con otros lenguajes y bases de datos.

### Usos

- Visualizaciones de datos de alta calidad.
- Cuadros de mando para visualizar y analizar datos.
- Informes automáticos.
- Herramientas de análisis estadístico.

### Fases del tratamiento de datos

1. **Adquisición desde fuentes disponibles**: Bases de datos, archivos de texto, etc.
2. **Preparación**: Eliminación de duplicados, datos incorrectos, valores extremos, etc.
3. **Análisis**: Construcción de modelos predictivos, de clasificación, de agrupamiento, etc.
4. **Comunicación de resultados**: Realización de informes, presentación y conclusiones.
5. **Aplicación de resultados obtenidos**: Utilización de modelos predictivos, etc.

## 2. Instalación

- R: [Comprehensive R Archive Network (CRAN)](https://cloud.r-project.org/)
- RStudio: [RStudio Desktop](https://posit.co/download/rstudio-desktop/)

## 3. Hola Mundo

1. Abrir RStudio
2. Crear un fichero nuevo: File > New File > R Script ( `Ctrl + Mayus + N` )
3. Escribir:

        "Hola Mundo"

4. Ejecutar línea actual: Code > Run Selected Line(s) ( `Ctrl + Enter` )

## 4. Gestión de paquetes

Para instalar nuevos paquetes, puede hacerse desde la consola de R de esta forma:

    install.packages("lubridate")

Para activarlos en la sesión de trabajo actual:

    library(lubridate)

Para ver los paquetes instalados actualmente:

    installed.packages()

Para eliminar un paquete:

    remove.packages("lubridate")

## Referencias

[¿Qué es R y para qué se usa?](https://www.unir.net/ingenieria/revista/lenguaje-r-big-data/)  
[R Packages: A Beginner's Tutorial](https://www.datacamp.com/tutorial/r-packages-guide)