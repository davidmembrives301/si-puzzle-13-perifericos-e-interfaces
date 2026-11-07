# Guion de exposición · Pieza 13 (12-13 min + 2-3 min de preguntas)

Apoyo visual: el propio README proyectado (las 3 imágenes de `img/`) y, si se puede, piezas reales del taller: un cable USB-C de solo carga, uno Thunderbolt o USB 40Gbps, un cable HDMI y un DisplayPort, y un pendrive.

| Min. | Quién | Apartado | Qué decir (ideas, no leer) | Apoyo |
|---|---|---|---|---|
| 0:00-2:00 | David | 1. Qué es | Definición de periférico. Entrada / salida / mixto con un ejemplo de cada uno que tengamos en la mano. Interfaz = conector + cable + protocolo. Frase gancho: "USB-C es una forma, no una velocidad". | Pendrive, ratón, cable USB-C |
| 2:00-4:00 | David | 2. Cómo funciona | Recorrer el esquema de izquierda a derecha: periférico → cable (serie, pares diferenciales) → controlador → PCIe → RAM/driver. Plug & Play, USB PD y Alt Mode. | `img/esquema.png` |
| 4:00-6:00 | Pablo | 3. Características | Gbps vs GB/s (dividir entre 8). Vatios. Resolución, Hz, ms, cd/m², contraste. Cómo se mide (CrystalDiskMark, tester USB-C, TestUFO). | Tabla del apartado 3 |
| 6:00-8:30 | Pablo | 4. Estándares | Gráfica de barras: USB de 0,48 a 80 Gbps con los nombres nuevos, Thunderbolt 5 (80/120 Gbps, 240 W), HDMI 2.2 (96 Gbps, Ultra96), DisplayPort 2.1 (80 Gbps, DP80, MST). Tipos de panel. | `img/velocidades.png`, cables HDMI y DP |
| 8:30-10:30 | Pablo | 5. Modelo real | Dell U2724DE: leer 4-5 datos de la ficha y decir si son buenos. Idea clave: un solo cable Thunderbolt = imagen + USB + red + 90 W. Para quién sí y para quién no. | `img/modelo.png` |
| 10:30-12:30 | David | 6. Averías y errores | Demostración: cable de solo carga que no da imagen. Monitor a 60 Hz. Cargador lento. Eslabón más lento. | Cable de solo carga |
| 12:30-13:00 | David | Cierre | Tres ideas para recordar: USB-C ≠ velocidad, manda el eslabón más lento, mirar Gbps y W en el cable. | — |
| 13:00-15:00 | Todos | Preguntas | Cualquiera debe poder responder sobre cualquier apartado. | — |

## Preguntas que puede hacer el profesor (y respuesta corta)

- ¿Diferencia entre USB4 y Thunderbolt 4? Los dos van a 40 Gbps por USB-C, pero Thunderbolt 4 garantiza unos mínimos (vídeo, PCIe, 100 W de carga en portátiles) y en USB4 algunas funciones son opcionales.
- ¿Por qué 10 Gbps no son 10 GB/s? Porque 1 byte son 8 bits, más la pérdida por codificación y protocolo: en la práctica, unos 1 GB/s.
- ¿HDMI o DisplayPort para un PC gaming? DisplayPort: está pensado para monitores, tiene MST y las gráficas lo priorizan. HDMI, para TV y consola.
- ¿Por qué todas las interfaces son serie? Porque en paralelo los hilos se desincronizan e interfieren a alta frecuencia; en serie, con pares diferenciales, se alcanzan muchos más Gbps.
- ¿Cómo sé si un cable USB-C da 240 W? Por el logo certificado del USB-IF, que indica la velocidad y la potencia (p. ej. "40Gbps / 240W").
