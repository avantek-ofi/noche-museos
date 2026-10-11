# 🌙 Noche de los Museos — Experiencias Interactivas

Repositorio general de las experiencias interactivas desarrolladas por **Avantek** para la **Noche de los Museos**, destinadas al **Departamento de Ingeniería en Sistemas de Información de UTN Buenos Aires**.

El proyecto reúne distintos minijuegos y experiencias que utilizan **visión por computadora y tracking corporal** para permitir que las personas jueguen utilizando movimientos de la cabeza o del cuerpo frente a una cámara.

La propuesta busca acercar distintas tecnologías de una forma lúdica, visual e interactiva a quienes visiten el espacio del Departamento durante la Noche de los Museos.

---

## 🎮 Experiencias

### 🧱 The Wall

Juego de movimiento corporal completo.

El participante debe colocarse frente a la cámara e intentar adaptar la posición de su cuerpo a distintas siluetas y desafíos que aparecen en pantalla.

La interacción se realiza mediante **tracking corporal en tiempo real**, sin necesidad de teclado, mouse o controles externos.

**Tecnologías principales:**

- Python
- OpenCV
- MediaPipe
- Pose Tracking
- Procesamiento de video en tiempo real

**Repositorio:**

👉 [noche-museos-the_wall](https://github.com/Avantek/noche-museos-the_wall)

---

### 🐦 Head Flappy

Juego inspirado en la mecánica de Flappy Bird en el que el participante controla al personaje mediante los **movimientos de su cabeza**.

La cámara detecta la posición del jugador y traduce sus movimientos en acciones dentro del juego.

El objetivo es atravesar obstáculos y conseguir la mayor cantidad de puntos posible.

**Tecnologías principales:**

- Python
- OpenCV
- MediaPipe
- Head Tracking
- Procesamiento de video en tiempo real

**Repositorio:**

👉 [noche-museos-head_flappy](https://github.com/Avantek/noche-museos-head_flappy)

---

### 🏃 Body Runner

Juego estilo endless runner controlado mediante movimientos corporales.

El participante utiliza su cuerpo para controlar al personaje y realizar distintas acciones dentro del juego, como:

- desplazarse hacia los costados;
- esquivar obstáculos;
- saltar;
- agacharse.

La experiencia toma como referencia las mecánicas de juegos del género endless runner, utilizando el **cuerpo del jugador como controlador**.

**Tecnologías principales:**

- Python
- OpenCV
- MediaPipe
- Full Body Tracking
- Procesamiento de video en tiempo real

**Repositorio:**

👉 [noche-museos-body_runner](https://github.com/Avantek/noche-museos-body_runner)

---

## 🧠 Tecnologías

Las distintas experiencias comparten principalmente:

- **Python**
- **OpenCV**
- **MediaPipe**
- Computer Vision
- Pose Tracking
- Head Tracking
- Procesamiento de imágenes y video en tiempo real
- Interfaces gráficas orientadas a videojuegos

Cada experiencia se mantiene en un repositorio independiente para permitir su desarrollo, prueba y ejecución de manera separada.

---

## 🗂️ Organización del proyecto

```text
noche-museos
│
├── noche-museos-the_wall
│   └── Juego de posiciones mediante tracking corporal
│
├── noche-museos-head_flappy
│   └── Juego controlado mediante movimiento de cabeza
│
└── noche-museos-body_runner
    └── Endless runner controlado mediante el cuerpo
