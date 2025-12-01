# Parámetros de Fusión en Agujeros Negros Binarios  
# Binary Black Hole Merger Parameters

========================================================================================
##Antes de ejecutar cualquier codigo es importante instalar las siguientes librerias##
========================================================================================

- !pip install cryptography==41.0.5
- !pip install --upgrade pyopenssl pydrive2
- !pip install astropy gwpy
- !pip install -U pyopenssl

-----
======================================================================
##Los Codigos estan pensados para ejecutarse en el siguiente orden##
======================================================================

- Extraer Señales
- Zoom del Evento
- Filtros de señales
- Q-Transform
- Primera Aproximacion Masa Chirp
- Segundo Ajuste Masa Chirp
- Verifica Rangos Robusto Masa Chirp
- Calculo Masa Final
- Calculo de los Spines

**Algunos Codigos dependen directamente de otros anteriores, por lo que ejecutarlos en otro orden podría generar problemas, así que es necesario editarlos en caso de Necesitar unicamente uno de ellos

-----
Este repositorio contiene herramientas y scripts para el análisis de eventos de **fusión de Agujeros Negros Binarios (BBH)** usando datos públicos de la **LIGO–Virgo Collaboration**, permitiendo estimar parámetros clave como:

- Masa chirp  
- Masa final del remanente  
- Spin final  
- Limpieza, filtrado y transformación de señales  
- Visualizaciones de Q–Transform, zooms del evento y espectrogramas  

-----

## Resumen del Proyecto

Este proyecto implementa una serie de módulos para analizar señales gravitacionales reales y extraer los parámetros físicos más relevantes de una fusión BBH.  

Los scripts están organizados por etapas del análisis:

- **Preprocesamiento de datos**  
- **Filtrado de ruido y whitening**  
- **Transformaciones en frecuencia (FFT, Q-Transform, espectrogramas)**  
- **Estimación de parámetros (masa chirp, masa final, spin)**  
- **Visualización y diagnóstico de eventos**

El objetivo es construir un pipeline reproducible que permita explorar, estudiar y comparar eventos observados con predicciones teóricas.

-----
##English Version
-----

========================================================================================
##Before running any code it is important to install the following libraries##
========================================================================================

- !pip install cryptography==41.0.5
- !pip install --upgrade pyopenssl pydrive2
- !pip install astropy gwpy
- !pip install -U pyopenssl

-----
======================================================================
##The codes are designed to be executed in the following order##
======================================================================

- Extract Signals
- Event Zoom
- Signal Filters
- Q-Transform
- First Approximation of the Chirp Mass
- Second Fit of the Chirp Mass
- Verify Robust Ranges for the Chirp Mass
- Final Mass Calculation
- Spin Calculation

**Some codes depend directly on previous ones, so running them in a different order may cause issues. Therefore, it is necessary to edit them if you need to run only one of them.

-----

## Project Overview

This repository provides tools for analyzing **Binary Black Hole Merger (BBH)** gravitational-wave events using open LIGO–Virgo data. It enables the estimation of key quantities such as:

- Chirp mass  
- Final black hole mass  
- Final spin  
- Signal filtering and preprocessing  
- Q-Transform visualizations and event zoom tools  

The project is modular, allowing users to reproduce or extend each step of the analysis pipeline.


