# Fundamentos de Procesamiento Digital de Imagenes

Todo lo mencionado, viene del capitulo 1 y 2 del libro del curso.

## Que es una imagen digital?

- Una imagen es una funcion: f(x,y)
  - Coordenadas: (x, y)
  - El valor es la intensidad

## Pipeline de procesamiento de imagenes

1. Adquisición
2. Mejora
3. Restauración
4. Procesamiento de color
5. Ondículas / multirresolución
6. Compresión
7. Procesamiento morfológico
8. Segmentación ⭐
9. Representación y descripción
10. Reconocimiento

## Procesamiento vs Vision

- Procesamiento → Mejorar imagen
- Vision → Entender la imagen

## Componentes

1. Sensor (camara)
2. Digitalizador
3. Computadora + Software
4. Almacenamiento

## Muestreo y Cuantificacion

### Muestreo

- Afecta a la resolución espacial.
- Pixeles continuos → Pixeles discretos
- Mas pixeles = Mas detalle

### Cuantificacion

- Afecta a la resolución de los niveles de gris
- Niveles de intensidad continuos → niveles de intensidad discretos
- Fórmula: Niveles de gris = `2^k`

## Tipos de Resolucion

| Tipo            | Significado                     |
| --------------- | ------------------------------- |
| Espacial        | Detalles de la imagen (pixeles) |
| Niveles de gris | Precision de la intensidad      |

Pistas:

- Borroso → baja resolucion espacial
- Bandas → baja resolucion de niveles de gris

## Relaciones de Pixeles

### Vecinos

- 4-vecinos → arriba, abajo, izquierda, derecha
- 8-vecions → + diagonales

### Conectividad

- Conectividad 4
- Conectividad 8
- Conectividad M (previene ambiguedad)

## Mediciones de Distancia

| Tipo               | Idea           |
| ------------------ | -------------- |
| Euclideana         | Linea Recta    |
| Bloque de ciudad   | Manhattan      |
| Tablero de Ajedrez | Movimiento Max |

## Transformaciones de Intensidad

- Negativa
- Transformacion de Registro
- Ley de potencias (gamma)

(Usado para realce)

## Ruido

- Variación aleatoria de la intensidad

### Tipos

- Gaussiano
- Sal y Pimienta
