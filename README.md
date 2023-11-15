# cuda-line-detector

Este proyecto implementa la Transformada de Hough utilizando CUDA para la detección de líneas en imágenes. La implementación incluye versiones secuenciales y paralelas, aprovechando la arquitectura de GPU para acelerar el proceso.

## Integrantes del Equipo:

- José Rodrigo Barrera García (20807)
- Marco Pablo Orozco Saravia (20857)
- Santiago Taracena Puga (20017)

## Requisitos:

- CUDA Toolkit
- OpenCV (para visualización de resultados)
- CMake (opcional, para la compilación)

## Compilación:

Si estás utilizando CMake, puedes compilar el proyecto de la siguiente manera:

```md
mkdir build
cd build
cmake ..
make
```

## Uso:

El programa se ejecuta desde la línea de comandos y toma dos argumentos:

```md
./hough <pgm-image> <threshold>
```

- <pgm-image>: Ruta de la imagen en formato PGM que se utilizará para la detección de líneas.
- <threshold>: Umbral para seleccionar las líneas detectadas basadas en su peso.

## Resultados:

El programa generará una imagen de salida llamada output.jpg que mostrará las líneas detectadas.

## Contribuciones:

Las contribuciones son bienvenidas. Si encuentras algún problema o tienes sugerencias de mejora, por favor abre un problema o envía un pull request.

## Licencia:

Este proyecto está bajo la Licencia MIT - consulta el archivo LICENSE para más detalles.
