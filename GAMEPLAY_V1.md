# Nexo — Gameplay V1

## Objetivo
Convertir matemáticas de 4.º de Primaria en una experiencia de juego móvil donde el aprendizaje sea la mecánica, no una capa de preguntas sobre un quiz.

## Lo que tomamos de juegos que ya funcionan

### Brawl Stars
- Objetivos clarísimos y de muy corto alcance.
- Feedback visual inmediato.
- Partidas/retos finitos.
- Variedad frecuente de modos.
- Progreso y recompensas tras jugar.
- Eventos y pequeñas sorpresas que cambian la rutina.

**Aplicación en Nexo:** cada microactividad debe tener una misión evidente en 1-2 segundos, durar poco y terminar con una reacción visual clara.

### Stumble Guys
- Controles mínimos.
- Aprendizaje por hacer.
- Rondas cortas.
- Cambio de escenario/mecánica entre rondas.
- Progresión y recompensa después de jugar.

**Aplicación en Nexo:** no tutoriales largos. La interacción se entiende tocando, arrastrando o moviendo.

### Minecraft
- Manipulación directa del mundo.
- Construir, romper, combinar y transformar.
- Sensación de propiedad.
- Libertad dentro de reglas simples.

**Aplicación en Nexo:** las matemáticas deben convertirse en objetos: porciones, bloques, monedas, recipientes, caminos, vallas, grupos.

### Roblox
- Identidad y personalización.
- Muchísima variedad dentro de una misma identidad/plataforma.
- El avatar y los objetos obtenidos dan continuidad entre experiencias.

**Aplicación en Nexo:** compañero/avatar persistente y elementos cosméticos desbloqueables. El niño juega a cosas distintas, pero siente que todo pertenece a su mundo.

### Duolingo
- Camino guiado: no exige decidir qué estudiar.
- Lecciones pequeñas.
- Racha, XP, quests y progreso visible.
- Mezcla contenido nuevo y repaso.
- Objetivo diario fácil de completar.

**Aplicación en Nexo:** sesión diaria finita de 8-10 minutos y el sistema decide qué viene después.

---

## Principios de diseño Nexo

1. La misión debe entenderse visualmente antes de leer.
2. Una pantalla = una acción principal.
3. No más de 1-2 frases cortas por reto.
4. El niño debe tocar/manipular algo cada pocos segundos.
5. Evitar cadenas largas de opción múltiple.
6. Cada habilidad curricular debe mapearse a una mecánica apropiada.
7. Fallar debe provocar una segunda oportunidad comprensible, no castigo.
8. Dificultad adaptativa invisible.
9. La sesión siempre termina.
10. El padre recibe aprendizaje; el niño recibe juego.

---

## Core loop diario

**Entrar → misión inmediata → 5-7 microjuegos → recuperación de un error → boss → recompensa → fin.**

Duración objetivo: 8-10 minutos.

La sesión no tiene scroll infinito.

---

## 10 mecánicas V1

### 1. Pizzería de fracciones
**Habilidad:** fracciones.
**Acción:** tocar/cortar/arrastrar porciones.
**Ejemplo:** “Sirve 3/4”. El niño construye físicamente 3/4 de una pizza.
**Variantes:** pizza, chocolate, tarta, barra de energía.

### 2. Reparto
**Habilidad:** división.
**Acción:** arrastrar objetos a personajes o cajas.
**Ejemplo:** 20 galletas y 4 personajes; repartir exactamente lo mismo.
**Aprendizaje invisible:** 20 ÷ 4 = 5.

### 3. Turbo multiplicación
**Habilidad:** tablas y cálculo mental.
**Acción:** conducir/mover un personaje hacia la puerta correcta.
**Ejemplo:** objetivo 42; puertas 6×7, 8×6 y 9×5.
**Sistema:** combo por aciertos consecutivos.

### 4. Caja registradora
**Habilidad:** dinero.
**Acción:** seleccionar/arrastrar monedas y billetes.
**Ejemplo:** pagar 7,35 € o devolver cambio desde 10 €.
**Variantes:** tienda, kiosco, mercado, máquinas.

### 5. Laboratorio de medidas
**Habilidad:** capacidad, masa y longitud.
**Acción:** llenar, pesar o ajustar.
**Ejemplo:** llenar un recipiente hasta 750 ml sin pasarse.
**Feedback:** indicador visual, no respuesta A/B/C.

### 6. Constructor
**Habilidad:** perímetro, área y geometría.
**Acción:** colocar piezas o bloques.
**Ejemplo:** construir una valla con perímetro 18 m.
**Variantes:** jardín, casa, circuito, mosaicos.

### 7. Ordena el mundo
**Habilidad:** numeración, comparación y series.
**Acción:** drag & drop.
**Ejemplo:** ordenar cuatro plataformas de menor a mayor para crear un puente.

### 8. Cazador de datos
**Habilidad:** gráficos y estadística.
**Acción:** observar un escenario y actuar sobre el dato.
**Ejemplo:** gráfico vivo de criaturas; capturar la categoría con mayor frecuencia.
**Objetivo:** leer información, no contestar un cuestionario.

### 9. Camino probable
**Habilidad:** probabilidad.
**Acción:** elegir caminos/objetos basándose en probabilidades visibles.
**Ejemplo:** dos cofres transparentes con distintas proporciones de fichas; elegir dónde es más probable obtener una dorada.

### 10. Boss matemático
**Habilidad:** mezcla de 2-3 microhabilidades ya practicadas.
**Acción:** secuencia corta de interacciones diferentes.
**Ejemplo:** cargar energía con multiplicación, abrir una puerta repartiendo objetos y terminar construyendo una fracción.
**Regla:** nunca introducir conocimiento nuevo en el boss.

---

## Meta-juego V1

Un compañero persistente, no infantilizado, que:
- reacciona a aciertos y errores;
- gana energía durante la sesión;
- evoluciona por constancia;
- desbloquea accesorios cosméticos;
- aparece en la pantalla inicial y final;
- no requiere compras ni cajas aleatorias para el MVP.

El progreso académico y el progreso del personaje son distintos:
- **Aprendizaje:** dominio real por microhabilidad.
- **Juego:** XP, energía, accesorios y evolución visual.

Nunca bajar dominio por no entrar un día.

---

## Adaptación

Cada microhabilidad mantiene un score de dominio.

La siguiente actividad se elige aproximadamente así:
- 40% habilidad en aprendizaje actual;
- 25% repaso espaciado;
- 20% debilidad detectada;
- 15% contenido fácil/fluido para mantener ritmo.

Si falla:
1. no mostrar un párrafo;
2. hacer visible el concepto;
3. dar una segunda interacción simplificada;
4. guardar el error para otra sesión.

---

## Ritmo de una sesión V1

0:00 — entrada directa / compañero
0:05 — calentamiento fácil
0:30 — microjuego 1
1:30 — microjuego 2
2:30 — microjuego 3
3:30 — microjuego 4
4:30 — sorpresa/bonus corto
5:00 — microjuego 5
6:00 — recuperación de dificultad previa
7:00 — boss
8:30 — recompensa, progreso y cierre

El tiempo es orientativo; la sesión termina por objetivos, no por temporizador estricto.

---

## Lo que NO hacemos

- feed infinito;
- anuncios;
- chat abierto;
- leaderboards globales en el MVP;
- castigar con pérdida de racha;
- cajas de loot;
- copiar personajes o estética de otros juegos;
- preguntas de cuatro botones como mecánica dominante;
- texto largo;
- convertir todo en puntos sin aprendizaje real.

---

## Primera implementación

Para validar gameplay antes de ampliar currículo:

1. Pizzería de fracciones.
2. Reparto/división.
3. Turbo multiplicación.
4. Constructor/perímetro.
5. Boss que combine las anteriores.
6. Compañero sencillo + energía + recompensa final.

Si estas seis piezas son divertidas, extendemos el mismo lenguaje de juego al resto del mapa curricular.
