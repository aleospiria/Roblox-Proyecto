# 🚀 Momentum Leap Simulator

> **Roblox Incremental / Progression Simulator**

Momentum Leap Simulator es un juego de progreso incremental en Roblox donde el jugador gana *Momentum* al moverse, aumentando su velocidad y potencia de salto para recorrer mapas cada vez más largos, obtener mascotas multiplicadoras y realizar *Rebirths* que aceleran el progreso.

---

## 📌 Estado del proyecto

🟡 **En diseño / preproducción**
Actualmente se está definiendo el concepto, mecánicas base y estructura técnica antes de iniciar el desarrollo en Roblox Studio.

---

## 🎮 Concepto general

El jugador comienza con estadísticas básicas. Cada paso genera *Momentum*, lo que permite correr más rápido y saltar más lejos. A través de circuitos y rampas, el jugador obtiene **Victorias**, que sirven para desbloquear zonas, comprar mascotas y realizar **Rebirths**.

El objetivo es simple: **llegar cada vez más lejos, más rápido y de forma más eficiente**.

---

## 🔁 Core Gameplay Loop

```
Moverse / Saltar
   ↓
Ganar Momentum
   ↓
Aumentar Velocidad / Distancia
   ↓
Completar circuitos
   ↓
Ganar Victorias
   ↓
Comprar Mascotas / Upgrades
   ↓
Rebirth
   ↓
Progreso más rápido
   ↺
```

---

## 🧠 Mecánicas principales

### 🏃 Movimiento

* Cada paso = +Momentum
* El Momentum afecta:

  * Velocidad de movimiento
  * Fuerza de salto

### 🛣️ Mapas / Circuitos

* Mapas lineales con rampas y checkpoints
* La distancia alcanzada determina las **Victorias**

### 🏆 Victorias

* Moneda principal de progresión
* Se obtienen al completar circuitos o llegar a checkpoints
* Se usan para:

  * Comprar mascotas
  * Desbloquear zonas
  * Realizar Rebirths

---

## 🐾 Sistema de Mascotas

### Equipamiento

* Máximo 3 mascotas equipadas
* Cada mascota otorga multiplicadores de Momentum

### Rarezas

| Rareza    | Multiplicador |
| --------- | ------------- |
| Common    | x1.1          |
| Rare      | x1.3          |
| Epic      | x1.6          |
| Legendary | x2.0+         |

> **Futuro:** Fusión, evolución y mascotas exclusivas por Rebirth

---

## 🔁 Sistema de Rebirth

* Resetea:

  * Momentum
* Mantiene:

  * Mascotas
  * Zonas desbloqueadas
* Beneficio:

  * Multiplicador permanente de Momentum

Ejemplo:

* Rebirth 1 → x1.5
* Rebirth 2 → x2.0

---

## 📈 Progresión

* Inicio: progreso rápido y constante
* Medio: decisiones estratégicas (mascotas, rutas)
* Tardío: optimización de multiplicadores

---

## 🧩 Escalabilidad futura

* Nuevos mapas y biomas
* Eventos temporales
* Leaderboards
* Modo AFK
* Logros

---

## 💰 Monetización (opcional)

* Gamepasses:

  * +1 mascota equipada
  * Auto Momentum
* Boosts temporales
* Mascotas cosméticas

> ⚠️ El juego no será *pay-to-win*

---

## 🧪 MVP (Primera versión jugable)

✔ 1 mapa
✔ 1 stat principal (Momentum)
✔ Mascotas básicas
✔ 1 Rebirth
✔ 1 circuito

---

## 👥 Colaboración

Roles sugeridos:

* 🧠 Game Designer
* 🧑‍💻 Scripter
* 🎨 Builder
* 🎵 Sonido / UI (opcional)

---

## 📂 Estructura del repositorio (propuesta)

```
Momentum-Leap-Simulator/
│
├── docs/
│   ├── game-design.md
│   ├── progression-formulas.md
│   └── roadmap.md
│
├── roblox/
│   ├── scripts/
│   ├── modules/
│   └── ui/
│
├── assets/
│
└── README.md
```

---

## 📜 Licencia

Pendiente de definir.

---

## ✨ Autor

Proyecto creado y documentado como ejercicio de diseño y programación en Roblox.

---

> **Nota:** Este documento está vivo y evolucionará junto con el proyecto.
