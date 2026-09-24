# NOT IMPORTANT 🫠

Un juego web caótico en Canvas 2D hecho con puro HTML5, Vanilla JavaScript y CSS, combinando recolección arcade, plataformas vertical infinito, parkour con bunny hop y un modo shooter por oleadas.

## 🎮 Jugar en línea

[ jugar HachiUwu en itch.io ](https://f0id5lay3r2099.itch.io/hachiuwu)

## ⚠️ Aviso legal y de atribución

Este proyecto incluye varios recursos externos y referencias culturales, y no pretende afirmar ser propiedad de terceros. En particular:

- Los efectos de sonido de las armas provienen de recursos aleatorios de internet que no se recuerdan exactamente de qué página se sacaron; estos sonidos no son originales del proyecto ni han sido creados específicamente para él.
- La música y la sensación general de las armas/combate están inspiradas o basadas en la estética y estilo de Hotline Miami; no es una versión oficial ni una reproducción autorizada del material original.
- Los sprites, personajes y otros gráficos incluidos en el juego pertenecen o están basados en assets de otras compañías, estudios o creadores externos.
- Este proyecto es un fan game / homenaje de estilo retro y no busca apropiarse del contenido original de terceros.
- Si algún dueño de un asset, sprite, música o sonido desea que se retire o se reemplace ese material, puede avisar y se revisará lo necesario.

---

## 🎮 Modos de Juego

1. **OG**:
   - El modo clásico de esquivar bombas y recoger comida cayendo del cielo.
   - Si tocas una bomba, sale screamer directo.

2. **Plataformas**:
   - Plataformeo vertical procedural.
   - Sube la mayor altura posible rebotando entre plataformas flotantes (hierba, nieve, hielo, metal, etc.).
   - Si caes al vacío, pal río.

3. **Sin Plataformas**:
   - Supervivencia en suelo plano esquivando o atrapando drops a alta velocidad.

4. **Shooter (Modo Oleadas)**:
   - Inspirado en shooters tipo Hotline Miami / side-scroller.
   - Sistema de rondas incrementales con spawn de enemigos armados.
   - Apuntado con ratón o joystick táctil en 360°.
   - Regeneración de vida (HP) al matar cuerpo a cuerpo o tras 4s sin recibir daño.
   - Drops de armas y cajas de munición.

---

## 🎮 Controles

### Teclado & Ratón (PC)

| Acción | Tecla / Control |
| :--- | :--- |
| **Moverse a la izquierda** | `A` o `Flecha Izquierda` |
| **Moverse a la derecha** | `D` o `Flecha Derecha` |
| **Saltar / Doble salto** | `W`, `Espacio` o `Flecha Arriba` |
| **Bunny Hop** | Saltar justo al tocar el suelo para acumular velocidad (hasta 2.2x) |
| **Apuntar** | Movimiento del cursor del ratón |
| **Disparar** | `Clic Izquierdo` o tecla `R` |
| **Pausa** | Tecla `P` o `ESC` |
| **Abrir consola dev** | `F2`, `~`, `º` o botón CHEAT CONSOLE (tras desbloquear) |

### Móvil / Pantalla táctil

- **Joystick virtual**: control de desplazamiento lateral y dirección de apuntado.
- **Botón ↑**: salto / doble salto.
- **Botón R**: disparo continuo en modo Shooter.

---

## 🐾 Personajes

- **Hachi** (*Chiikawa*): disponible desde el inicio. Balance estándar.
- **Natsuki** (*Doki Doki Literature Club*): disponible desde el inicio. Sprites completos con salto y carrera.
- **Usagi**: se desbloquea alcanzando **20 puntos** de récord.
- **Plusheen**: se desbloquea alcanzando **30 puntos** de récord.

---

## 🔫 Arsenal & Armas (Modo Shooter)

El juego incluye armas de fuego y cuerpo a cuerpo (melee con daño letal `999`):

- **Pistolas**: Pistola Negra, Pistola Pequeña, Pistola estándar, Pistola Oscura, Arma Verde.
- **Rifles & Automáticas**: Metralleta, Rifle Auto Negro, Rifle Automático, Rifle Compacto, Rifle Largo Pesado.
- **Escopetas**: Escopeta Ráfaga (burst de 3 disparos), Escopeta Roja, Escopeta Pesada.
- **Armas arrojadizas / explosivos**: Granada Circular, Cuchillo Arrojadizo.
- **Cuerpo a cuerpo (instakill & leech HP)**: Katana, Katana Larga, Machete, Martillo, Tubo, Barra de Metal.

---

## 💻 Terminal & Cheats de Desarrollador

Presiona el botón **CONSOLA** en el menú o la tecla rápida si ya tienes privilegios root:

- **Desbloqueo maestro**: escribe `amo a pau osi` para activar el modo desarrollador en vivo (`DEV_UNLOCKED`).
- **Comandos principales**:
  - `help`: despliega todos los comandos.
  - `iddqd`: score máximo (9999) y desbloqueo de todos los personajes.
  - `god`: activa/desactiva invencibilidad.
  - `heal <n>`: restaura salud al jugador.
  - `speed <n>`: modifica la velocidad base.
  - `give <arma>`: otorga cualquier arma (`shotgun`, `katana`, `rifle_auto`, etc.).
  - `ammo <n>`: suma munición de reserva.
  - `nuke`: limpia la pantalla detonando enemigos, balas e ítems.
  - `screamer`: detona el jakeo troll de Foxy y Chiikawa.
  - `meme on/off`: activa el codificador en idioma MEME-CESAR para el bot parlante.
  - `clear` / `exit`: gestiona y cierra la terminal.

> ⚠️ **Advertencia**: escribir 5 comandos no reconocidos activará la detección del *Pendejómetro*, disparando el screamer automáticamente.

---

## 📁 Estructura de Recursos Requeridos

Para que el juego cargue al 100% sus texturas y audio, coloca en la misma carpeta raíz:

```text
.
├── index.html
├── bg.png
├── items.png
├── hachi.png
├── natsuki.png
├── usagi.png
├── plusheen.png
├── plattaforms.png
├── armas.png
├── municion.png
├── foxy.gif
├── chiikawadance.gif
├── chiikawacry.gif
├── hotline.mp3
├── scream.mp3
├── cry.mp3
├── pistol.mp3
├── shotgun.mp3
├── mg.mp3
├── reload.mp3
└── empty.mp3
```

---

## 🚀 Cómo Ejecutar

1. Clona o descarga este repositorio.
2. Asegúrate de tener los assets en la misma carpeta.
3. Abre `index.html` en cualquier navegador moderno (Chrome, Firefox, Brave, Edge).
4. O monta un servidor local rápido con Python:

```bash
python -m http.server 8000
```

Y luego abre `http://localhost:8000`.

---

## 🧩 Resumen

`juegokiutkawaiuwu` es un proyecto de juego web caótico, rápido, con varios modos, humor absurdo, referencias meme y estética retro. Está pensado para jugar en navegador con controles simples.
