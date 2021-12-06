<p align = "center">
    <img src="images/logo_itam.png" width="300" height="110" />

## <p align = "center"> Maestría en Ciencia de Datos

## <p align = "center"> Aprendizaje de Máquina (Otoño 2021)

---
  
# Proyecto final: Predicción de número de robos de vehículos por AGEB en la Ciudad de México

**Integrantes del equipo**  

| Nombre                          |     CU   | Mail                    | Usuario Gh                                    |
| :-----------------------------: | :------: | :---------------------: | :-------------------------------------------: |
| Nayeli Arenas Morales           | 084351  | nayeli.arenas@itam.mx   | [arenitss](https://github.com/arenitss) |
| Uriel Abraham Rangel Díaz       | 193921   | urangeld@itam.mx        | [urieluard](https://github.com/urieluard)     |
| José Luis Roberto Zárate Cortés | 183347   | jzaratec@itam.mx        | [jlrzarcor](https://github.com/jlrzarcor)     

## Objetivo
Implementar un modelo de aprendizaje de máquina para predecir el número de robo de vehiculos por unidad de extensión geográfica (AGEB) en la Ciudad de México.

## El modelo
Se emplearon dos modelos de aprendizaje de máquina: regresión lineal y regresión logística, que se plantearon con base en un modelo teórico en el que se plantea la implementación de políticas públicas para mitigar los factores de riesgo que mayor relación tienen con la incidencia delictiva. Las variables explicativas que se incluyen en el modelo; así como la variable respuesta fueron obtenidas de dos fuentes (INEGI y Datos de la CDMX). Para hacer el cruce de información entre ambas fuentes se utilizó como base el AGEB, de tal manera que todas las variables requeridas para el modelo se representaron en unidades por AGEB. 

![](images/Modelo.png)

## Contenido del Repositorio

```
├── README.md            <- Documento de referencia para navegar el repositorio del proyecto
│
├── data                 <- Bases de datos utilizadas para realizar el proyecto
│
├── notebooks            <- Notebooks de R y Jupyter utilizados en la ejecución del proyecto
│   ├── images                            <- Imágenes utilizadas en los notebooks
│   ├── BD_reporte.Rmd                    <- Reporte de la descripción y utilización de las fuentes de bases de datos
|   ├── Intro.Rmd                         <- Documento de introducción del proyecto
|   ├── ModProyFinal_ML_eq9@20211206.Rmd  <- Notebook de R con el procedimiento y códgio de implementación de los modelos
|   ├── ModProyFinal_ML_eq9@20211206.html <- Reporte entrega proyecto.
|   ├── Verificando_datos.ipynb           <- Notebook de Jupyter con el procedimiento de manipulación de las bases de datos
│   └── ajuste_param.Rmd                  <- Notebook de ejemplo en R con un procedimiento ajuste de parámetros
│
├── images             <- Imágenes utilizadas en el repositorio
│
└── src/utils          <- Funciones utilizadas en los notebooks
```
