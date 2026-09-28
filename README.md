# BallTrack Releases

Este repositorio está destinado **exclusivamente** a almacenar los archivos compilados listos para distribución (Releases) de la aplicación BallTrack Desktop. 

**NO CONTIENE CÓDIGO FUENTE (SRC)**. 
De esta manera, la página web oficial (`BallTrackWEB`) puede consumir el archivo `releases.json` o clonar directamente de este repositorio sin exponer los modelos ONNX/NCNN o la lógica privada de la aplicación base.

## Estructura

- `releases.json`: Archivo con los metadatos de las versiones disponibles (usado por la web para los enlaces de descarga).
- Archivos `.zip` o `.exe` compilados (ej. `BallTrack_v1.0.0_windows_x64.zip`).
