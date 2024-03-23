# Simulador de Carrera de Hilos

Este es un simulador de carrera de hilos desarrollado en Python utilizando la biblioteca tkinter para la interfaz gráfica. El programa crea una carrera entre múltiples corredores representados como rectángulos en una ventana gráfica, donde cada corredor avanza de manera aleatoria en intervalos de tiempo.

## Requisitos

- Python 3.x
- tkinter (instalado por defecto en la mayoría de las distribuciones de Python)

## Ejecución

Para ejecutar el simulador de carrera de hilos, simplemente ejecuta el script `carrera_de_hilos.py`. Esto abrirá una ventana gráfica donde podrás ver la carrera de los corredores.

```bash
python carrera_de_hilos.py 
```
o
``` 
python main.py
```

## Descripción del Código

El código está estructurado de la siguiente manera:

- **CarreraDeHilos**: Clase principal que inicializa la interfaz gráfica y controla la lógica de la carrera.
- **crear_corredores**: Método para crear los corredores (rectángulos) en la ventana gráfica.
- **color_aleatorio**: Método para generar colores aleatorios para los corredores.
- **comenzar_carrera**: Método que inicia la carrera y crea un hilo para cada corredor.
- **correr**: Método que simula el movimiento de los corredores y actualiza sus posiciones en la ventana gráfica.

## Contribuciones

Las contribuciones son bienvenidas. Si tienes alguna idea para mejorar este simulador de carrera de hilos, no dudes en abrir un issue o enviar un pull request.

## Autor

Este simulador de carrera de hilos fue creado por Sergio Roman.
