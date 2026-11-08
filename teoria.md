# Teoría · Pieza 13: Periféricos e interfaces externas

**Grupo:** David Membrives Muñoz

## Conceptos clave

**Periférico** → todo lo que conecto al PC desde fuera (teclado, monitor, pendrive…).

Hay 3 tipos, según hacia dónde van los datos:
- **Entrada** → meten datos en el PC: teclado, ratón, micro, webcam.
- **Salida** → sacan datos del PC: monitor, impresora, altavoces.
- **Mixtos (E/S)** → las dos cosas: pendrive, disco externo, pantalla táctil.

**Interfaz externa** → cómo se conecta el periférico al PC = conector + cable + reglas para entenderse.

- **USB-C** → solo es la **forma** del conector (pequeño y se mete por los dos lados). OJO: no dice la velocidad.
- **Thunderbolt** → de Intel, usa el conector USB-C. Muy rápido y siempre lleva vídeo.
- **HDMI** → vídeo + audio. Lo típico en teles, consolas y proyectores.
- **DisplayPort (DP)** → vídeo para monitores de PC. Puedo encadenar varios monitores.
- **USB Power Delivery (PD)** → para cargar por USB-C. Máx. **240 W**.
- **Hz** → imágenes por segundo del monitor. + Hz = se ve más suave.
- **Gbps** → velocidad de la conexión (gigabits por segundo).

## Tabla resumen

| Tipo | Dato clave | Cuándo se usa |
|---|---|---|
| USB 2.0 | 480 Mbps (lento) | Teclado, ratón, impresora |
| USB 3.2 | 5 / 10 / 20 Gbps | Pendrives, discos externos |
| USB4 | 40 u 80 Gbps | SSD rápidos, docks |
| Thunderbolt 4 | 40 Gbps + carga 100 W | Portátil con dock o monitor |
| Thunderbolt 5 | 80 Gbps (120 con Boost) + 240 W | Equipos profesionales |
| HDMI 2.1 | 48 Gbps | Teles y consolas |
| HDMI 2.2 | 96 Gbps | Teles y monitores nuevos |
| DisplayPort 2.1 | 80 Gbps | Monitores de PC / gaming |

## Datos importantes

- **USB-C ≠ velocidad** → es la forma del conector (¡cae seguro!).
- Nombres nuevos de USB → **USB 5Gbps, 10Gbps, 20Gbps, 40Gbps y 80Gbps** (dicen la velocidad directamente).
- Carga máx. por USB-C → **240 W**.
- TB5 = doble que TB4 → **80 vs 40 Gbps**.
- Tele → **HDMI** · Monitor de PC → **DisplayPort**.
- Todo es **retrocompatible** → lo nuevo funciona en lo viejo, pero a la velocidad de lo viejo.
- **Regla del más lento** → manda lo más lento de los 3: puerto, cable o aparato.
- Averías típicas:
  - cable USB-C que carga pero **no da imagen** → es de solo carga.
  - monitor a **60 Hz** en vez de 144 → cable antiguo o no cambié los Hz en Windows.
  - portátil carga **lento** → cargador con pocos vatios.

## Preguntas tipo test

1. ¿Cuál de estos es un periférico de entrada?
   - a) Monitor
   - b) Impresora
   - c) Teclado ← correcta
   - d) Altavoces
   - Explicación: el teclado mete datos en el PC; los otros los sacan.

2. ¿Cuál de estos es un periférico mixto (entrada y salida)?
   - a) Ratón
   - b) Pendrive ← correcta
   - c) Micrófono
   - d) Proyector
   - Explicación: en el pendrive guardo y leo datos → hace las dos cosas.

3. ¿Qué indica que un puerto sea USB-C?
   - a) Que va a 40 Gbps
   - b) Solo la forma del conector ← correcta
   - c) Que es Thunderbolt
   - d) Que carga a 240 W
   - Explicación: USB-C es la forma; la velocidad depende de lo que haya detrás.

4. ¿Cuál es la potencia máxima de carga por USB-C con USB Power Delivery?
   - a) 15 W
   - b) 60 W
   - c) 100 W
   - d) 240 W ← correcta
   - Explicación: la versión actual de USB PD llega a 240 W.

5. ¿Qué conexión se usa normalmente para conectar una consola a una tele?
   - a) HDMI ← correcta
   - b) USB 2.0
   - c) Ethernet
   - d) DisplayPort
   - Explicación: HDMI lleva imagen + sonido y es lo estándar en teles y consolas.

6. ¿Qué velocidad tiene Thunderbolt 5 (sin modo Boost)?
   - a) 10 Gbps
   - b) 40 Gbps
   - c) 80 Gbps ← correcta
   - d) 480 Mbps
   - Explicación: TB5 = 80 Gbps, el doble que TB4 (40 Gbps).

7. Conecto un disco de USB 40Gbps a un puerto de USB 10Gbps. ¿A qué velocidad irá como máximo?
   - a) 40 Gbps
   - b) 10 Gbps ← correcta
   - c) 50 Gbps
   - d) No funcionará
   - Explicación: es retrocompatible y manda el más lento → 10 Gbps.

8. Un cable USB-C carga el portátil pero no da imagen en el monitor. ¿Causa más probable?
   - a) El monitor está roto
   - b) Es un cable que solo sirve para cargar ← correcta
   - c) Falta el driver del teclado
   - d) El cable es demasiado rápido
   - Explicación: no todos los cables USB-C llevan vídeo; muchos solo cargan.
