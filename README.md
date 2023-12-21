# Juego de Batalla Naval en LAN

Este proyecto implementa un juego clásico de batalla naval para dos jugadores en Python. Los jugadores colocan estratégicamente sus barcos en un tablero y se turnan para realizar disparos, intentando hundir los barcos del oponente.

## Descripción del Proyecto

El juego utiliza sockets para permitir la comunicación entre dos jugadores, uno actuando como servidor y otro como cliente. Los jugadores pueden ejecutar el juego en modo servidor o cliente, estableciendo una conexión para jugar en red.

## Reglas del Juego

- Cada jugador tiene una flota de barcos de diferentes tamaños.
- Los jugadores se turnan para realizar disparos a través de coordenadas en un tablero.
- ○ indica un disparo que impactó un barco.
- ● indica la ubicación de los propios barcos del jugador.
- ~ disparaste y no había nada en esa coordenada

  
## Requisitos

- Python 3.x
- Biblioteca Pygame (para la versión que incluye sonido al realizar disparos)

## Instrucciones de Uso
### Instalar Pygame en las pc
```bash
python -m pip install pygame
```

### Servidor
```bash
python batalla.py -s
```
###Cliente
```bash
python batalla.py -c direccionipdelservidor
```

