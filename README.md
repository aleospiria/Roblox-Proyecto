# 🛹 Skate Pro Simulator

> **Roblox Incremental / Progression Skateboarding Game**

Skate Pro Simulator es un juego de progresión incremental en Roblox centrado en **skateboarding**, donde el jugador incrementa su **Momentum** mientras recorre un circuito de skate cada vez más exigente.

El *Momentum* representa la **inercia, fluidez y control** del jugador sobre la tabla, y se transforma dinámicamente en **velocidad efectiva**, determinando la distancia de los saltos, el control en rampas y la capacidad de completar el circuito.

---

## 🎮 Concepto general

El jugador comienza con un skate básico y un **Momentum muy bajo**, lo que resulta en poca velocidad y saltos prácticamente imposibles.

Al patinar de forma continua, cada metro recorrido incrementa el Momentum, representando la energía acumulada al mantener el movimiento.

### El Momentum:

* Aumenta al patinar de forma fluida
* Disminuye al caer, frenar bruscamente o perder el equilibrio

La **velocidad efectiva** del jugador se calcula en tiempo real a partir del Momentum actual.

A mayor Momentum:

* Mayor velocidad
* Saltos más largos
* Mejor control en rampas

A medida que el jugador mantiene Momentum suficiente, puede superar más secciones del circuito y alcanzar **checkpoints**, los cuales otorgan **Victorias**.

Completar el circuito completo concede un lote mayor de Victorias, recompensando la ejecución limpia y continua.

---

## 🪙 Victorias (Moneda principal)

Las Victorias funcionan como la moneda principal del juego y permiten comprar mascotas, nuevas tablas de skate y desbloquear progresión meta.

### Obtención de Victorias

* Alcanzar checkpoints
* Completar el circuito completo

### Ejemplo de progresión

* 1er checkpoint → **+1 Victoria**
* 2 checkpoints → **+2 Victorias**
* Circuito completo → **+4 Victorias**

---

## 🔁 Gameplay Loop

```
Patinar
   ↓
Acumular Momentum
   ↓
Convertir Momentum en Velocidad
   ↓
Saltos más largos y controlados
   ↓
Alcanzar checkpoints
   ↓
Ganar Victorias
   ↓
Comprar Mascotas / Skates
   ↓
Mantener Momentum más fácilmente
   ↓
Completar el circuito con mayor eficiencia
   ↺
```

---

## 🧠 Mecánicas principales

### 🛹 Skateboarding, Momentum y Movimiento

* **Momentum** es la estadística central del juego
* Cada metro recorrido patinando = **+Momentum**

El Momentum:

* Aumenta con movimiento continuo
* Disminuye al caer o frenar

El jugador **no controla directamente la velocidad**, sino que gestiona su Momentum.

La **velocidad efectiva** se deriva del Momentum y afecta:

* Velocidad de desplazamiento
* Distancia de salto
* Control en rampas y aterrizajes

El gameplay premia mantener el flujo y penaliza los errores, simulando la sensación real de montar skate.

---

## 🛣️ Mapas / Circuitos

* Circuitos lineales con rampas, gaps y checkpoints
* El progreso dentro del circuito depende del Momentum sostenido
* Caer reduce Momentum, pero **no reinicia el progreso ganado**

---

## 🐾 Sistema de Mascotas

### Equipamiento

* Máximo **3 mascotas equipadas**
* Cada mascota otorga:

  * Multiplicadores de ganancia de Momentum

### Compra

* Se compran con Victorias
* Mascota inicial:

  * Costo: **3 Victorias**

### Rarezas

| Rareza    | Multiplicador |
| --------- | ------------- |
| Common    | x1.2          |
| Rare      | x1.5          |
| Epic      | x2.0          |
| Legendary | x3.0          |

> **Futuro:** fusión, evolución y mascotas exclusivas por Rebirth

---

## 🛹 Tablas de Skate

Las tablas influyen directamente en la progresión del jugador mediante multiplicadores.

### Ejemplo

* **Skate inicial**

  * Ganancia de Victorias: x1.0

* **Segundo skate**

  * Costo: **10 Victorias**
  * Ganancia de Victorias: **x1.5**

> En el futuro podrán existir tablas exclusivas o cosméticas.

---

## 📈 Progresión del jugador

### Inicio

* Momentum bajo
* Velocidad reducida
* Saltos cortos

### Medio

* Mejor gestión del Momentum
* Desbloqueo gradual del circuito
* Decisiones estratégicas (mascotas y tablas)

### Tardío

* Momentum alto y estable
* Optimización de multiplicadores
* Ejecuciones limpias del circuito completo

---

## 🧪 MVP (Primera versión jugable)

✔ 1 mapa
✔ 2 stats principales (Momentum y velocidad efectiva)
✔ Mascotas básicas
✔ 1 circuito completo

