# B02 - Unreal Engine 5 Fundamentals: Arquitectura, Gameplay Framework, Git LFS y C++ con Data-Only Prefabs

Desembarco práctico en Unreal Engine 5 trabajando desde el primer día sobre un proyecto con base C++ (Método Espejo) y usando Blueprints únicamente como Data-Only Prefabs (contenedores de datos en el panel Details para asignar mallas 3D, sonidos y parámetros UPROPERTY, con Event Graph vacío y 0 espagueti de nodos, alineado con UE6): construcción progresiva del Juego 2 («Obstacle & Crypt Escape 3D», plataformas móviles, trampas y puzles físicos estilo Obstacle Assault + Crypt Raider) sobre Toybox Sci-Fi/Ruinas con apertura en <12 s (Shared DDC), jerarquía UWorld/AActor/UActorComponent, Gameplay Framework, Enhanced Input, raycasting en C++ (LineTraceSingleByChannel para agarrar reliquias y activar placas de presión) e interfaz UMG.

---

## Cápsulas de Sesión y Etiquetas de Paracaídas (`s1-b02-template`)

- **Proyecto / Toybox:** Juego 2 (Base Pieza 2): «Obstacle & Crypt Escape 3D» — Juego 3D de plataformas móviles, trampas cinemáticas y escape room con puzles físicos en UE5 C++ (kit Sci-Fi/Ruinas iluminado con Lumen + Data-Only Prefabs).
- **Capas 70 / 20 / 10:** • 70 % Base (completado en las 20 h de aula): Nivel jugable de principio a fin en UE5 C++ con Data-Only Prefabs (Event Graph vacío), plataformas móviles C++, Enhanced Input, raycast de agarre y HUD básico. · • 20 % Reto autónomo: Puzle físico de múltiples placas de presión y puertas acopladas por interfaz C++ + audio espacial. · • 10 % Extra Portfolio: Segundo tramo de nivel con trampas sincronizadas, temporizador de speedrun y telemetría de muerte.
- **Plataforma docente (vídeo indexado y entregas):** [https://ikasyn.com/titulo-videojuegos](https://ikasyn.com/titulo-videojuegos)

| Sesión | Subbloque | Horas | Título | Tag Inicio (`sync_checkpoint`) | Tag Fin |
|:---:|:---:|:---:|---|---|---|
| `S1-11` | `B02.1` | 2 h | Juego 2 (Obstacle & Crypt Escape en UE5 C++) · Día 1: AActor en C++ y Data-Only Prefabs | `scripts\sync_checkpoint.bat s1-11-start` | `s1-11-end` |
| `S1-12` | `B02.1` | 2 h | Juego 2 · Trampas cinemáticas en C++, Git LFS y puntos de control (Tags de Paracaídas) | `scripts\sync_checkpoint.bat s1-12-start` | `s1-12-end` |
| `S1-13` | `B02.1` | 2 h | Juego 2 · Transformaciones locales/mundo, volúmenes de colisión y checkpoints en C++ | `scripts\sync_checkpoint.bat s1-13-start` | `s1-13-end` |
| `S1-14` | `B02.2` | 2 h | Juego 2 · Gameplay Framework en C++: AGameModeBase, ACharacter y posesión | `scripts\sync_checkpoint.bat s1-14-start` | `s1-14-end` |
| `S1-15` | `B02.2` | 2 h | Juego 2 · Control en C++ con Enhanced Input: sprint, salto doble, dash y cámara 3D | `scripts\sync_checkpoint.bat s1-15-start` | `s1-15-end` |
| `S1-16` | `B02.2` | 2 h | Juego 2 · Interfaces C++ (UInterface) para objetos interactivos sin Cast acoplado | `scripts\sync_checkpoint.bat s1-16-start` | `s1-16-end` |
| `S1-17` | `B02.3` | 2 h | Juego 2 · Raycasting en C++ (LineTraceSingleByChannel) y agarre físico (Crypt Raider) | `scripts\sync_checkpoint.bat s1-17-start` | `s1-17-end` |
| `S1-18` | `B02.3` | 2 h | Juego 2 · Placas de presión, pesaje de reliquias y puertas secretas en C++ | `scripts\sync_checkpoint.bat s1-18-start` | `s1-18-end` |
| `S1-19` | `B02.4` | 2 h | Juego 2 · HUD reactivo con UMG alimentado desde C++ y audio espacial 3D | `scripts\sync_checkpoint.bat s1-19-start` | `s1-19-end` |
| `S1-20` | `B02.4` | 2 h | Cierre Juego 2: Playtest cruzado en el laboratorio del campus y arranque del Juego 3 | `scripts\sync_checkpoint.bat s1-20-end` | `s1-20-end` |
