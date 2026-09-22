# Nexo — Blueprint pedagógico V1
## 4.º de Primaria · Matemáticas · Cataluña

### Objetivo
Que ningún reto del producto nazca de “esto parece de 4.º”.  
Cada reto debe quedar anclado a:

1. un **sentido matemático oficial**;
2. un **bloque competencial**;
3. un **grado de demanda cognitiva**;
4. una **microhabilidad curricular**;
5. una **mecánica de juego** apropiada;
6. una **evidencia observable** de que el niño comprende.

---

## 1. Marco oficial que usamos

### Sentidos matemáticos
- NUM — Sentido numérico
- MES — Sentido de la medida
- ESP — Sentido espacial
- ALG — Sentido algebraico
- EST — Sentido estocástico

### Bloques competenciales
- REP — Resolución de problemas
- RAP — Razonamiento y prueba
- CON — Conexiones
- COR — Comunicación y representación

### Complejidad cognitiva
**Básico**
- identificar y comprender información;
- usar representaciones sencillas;
- realizar cálculos y procedimientos rutinarios;
- resolver problemas sencillos.

**Intermedio**
- analizar datos;
- organizar información;
- conectar conocimientos;
- utilizar modelos sencillos;
- elaborar razonamientos.

**Superior**
- planificar;
- valorar alternativas;
- diseñar estrategia;
- justificar;
- detectar errores;
- resolver situaciones que combinan varias ideas.

### Reparto objetivo para una sesión de Nexo
No copiamos la prueba oficial literalmente, pero tomamos su equilibrio como referencia:

- ~40% resolución de problemas
- ~30% razonamiento y prueba
- ~15% conexiones
- ~15% comunicación/representación

Y por demanda cognitiva:

- ~30% básico
- ~45% intermedio
- ~25% superior

Una sesión de juego no debe convertirse en diez cálculos rutinarios.

---

## 2. Regla de oro de generación

La IA **no genera “un ejercicio de cuarto”**.

Recibe una ficha cerrada:

- skill_id
- sentido
- bloque
- nivel cognitivo
- magnitudes/rango permitidos
- representación permitida
- estructura matemática
- dificultad
- distractores/error típico permitido
- mecánica de juego
- criterio exacto de éxito

La IA solo puede variar:
- escenario;
- personajes;
- valores dentro del rango;
- disposición visual;
- texto breve;
- assets narrativos.

Nunca puede cambiar la matemática subyacente.

---

# 3. Familias de retos válidas para el MVP

## NUM-01 · Números naturales hasta 9.999
**Currículo**
- lectura, representación, composición y descomposición;
- recta numérica;
- estimación y aproximación.

**Juego**
### Puente de números
Hay plataformas numeradas. El niño debe colocarlas para construir un puente:
- ordenar de menor a mayor;
- insertar un número en su posición;
- elegir qué número está más cerca de una marca.

**No hacer**
“¿Cuál es mayor? A/B/C/D” como mecánica principal.

---

## NUM-02 · Estrategias de cálculo
**Currículo**
- suma/resta hasta 9.999;
- multiplicación;
- división;
- elegir la operación adecuada;
- relaciones entre operaciones.

**Juego**
### Fábrica
Una máquina recibe piezas y debe producir un objetivo.

Ejemplos estructurales:
- completar un grupo faltante;
- distribuir objetos;
- elegir entre sumar/restar/multiplicar/dividir según la situación;
- encontrar dos caminos de cálculo equivalentes.

**Debe medir**
No solo resultado, también estrategia.

---

## NUM-03 · Tablas y estructura multiplicativa
**Currículo**
- modelo rectangular;
- patrones de tablas;
- estrategias para obtener resultados no automatizados.

**Juego**
### Hangar de drones
Construir una formación rectangular de drones:
- 6 filas × 4 columnas;
- cambiar filas/columnas y comprobar que la cantidad se conserva;
- descubrir relaciones como 6×8 usando 6×4 dos veces.

**Evitar**
Ráfaga infinita de “7×8”.

---

## NUM-04 · División
**Currículo**
- diferentes representaciones;
- reparto y agrupación;
- conexión con multiplicación.

**Juego**
### Reparto de suministros
Objetos físicos deben distribuirse:
- reparto equitativo;
- crear grupos de tamaño fijo;
- encontrar cuántos grupos caben;
- detectar un reparto incorrecto.

**Nivel superior**
Mostrar un reparto hecho por otro personaje y pedir reparar el error.

---

## NUM-05 · Fracciones sencillas
**Currículo**
- mitades, cuartos, octavos;
- tercios y sextos;
- relación entre representaciones;
- fracciones en contextos cotidianos.

**Juego**
### Cocina / fábrica de piezas
No limitarse a pizza.

Mecánicas:
- construir 3/4;
- encontrar dos representaciones equivalentes visualmente;
- continuar una recta numérica por fracciones;
- seleccionar qué objeto representa una fracción;
- comparar mediante manipulación.

**Rangos MVP**
1/2, 1/3, 2/3, 1/4, 2/4, 3/4, octavos y sextos sencillos.

---

# 4. Medida

## MES-01 · Longitud
**Currículo**
km, m, cm, mm en contextos reales.

**Juego**
### Taller de reparación
Una pieza debe encajar en un hueco.
El niño usa una regla visual o compara medidas.

Retos:
- escoger instrumento;
- leer regla;
- convertir unidades sencillas;
- comparar dos longitudes expresadas en unidades distintas.

---

## MES-02 · Tiempo y calendario
**Currículo**
- intervalos cortos con reloj;
- duraciones de más de un día con calendario;
- 12/24 horas.

**Juego**
### Misión a tiempo
Un personaje tiene una hora de salida y debe llegar X minutos antes.

El niño manipula:
- reloj;
- línea temporal;
- calendario.

No mostrar primero la operación.
La operación emerge de la escena.

---

## MES-03 · Masa y capacidad
**Currículo**
kg/g, l/ml; estimación y medición.

**Juego**
### Laboratorio
- equilibrar balanza;
- llenar recipiente;
- escoger recipiente adecuado;
- detectar una estimación absurda.

---

## MES-04 · Estimación
**Currículo**
referentes personales y razonabilidad.

**Juego**
### ¿Te la juegas?
Antes de medir, el niño apuesta por una estimación.
Después comprueba con instrumento.

Esto permite medir:
- estimación;
- tolerancia;
- revisión de la propia respuesta.

---

# 5. Espacio

## ESP-01 · Posición y desplazamiento
**Currículo**
puntos de referencia, coordenadas y códigos.

**Juego**
### Mapa de aventura
El niño mueve un personaje por cuadrícula:
- llegar a coordenada;
- seguir secuencia;
- escoger recorrido válido;
- comparar rutas;
- describir un recorrido.

Inspirado en el tipo de razonamiento que aparece en pruebas reales de 4.º, pero con mapas y situaciones originales.

---

## ESP-02 · Formas y propiedades
**Currículo**
triángulos, cuadriláteros, polígonos, círculos y sólidos; elementos y relaciones.

**Juego**
### Escáner 3D
Girar objetos y:
- identificar caras;
- encontrar ejes de simetría;
- clasificar;
- montar/desmontar sólidos.

---

## ESP-03 · Simetría, giro y traslación
**Juego**
### Taller de robots
Completar la mitad faltante de una armadura;
girar una pieza;
trasladar un patrón para encajarlo.

---

## ESP-04 · Perímetro
**Currículo**
calcular perímetros en problemas cotidianos.

**Juego**
### Constructor
No “2×(a+b)” aislado.

Escenarios:
- vallar jardín;
- colocar cinta alrededor de cartel;
- diseñar circuito;
- comparar dos diseños con igual perímetro.

**Nivel superior**
Encontrar dos formas diferentes que usen exactamente la misma cantidad de valla.

---

# 6. Álgebra

## ALG-01 · Patrones
**Currículo**
crear, continuar y predecir series; reconocer regularidades.

**Juego**
### Reactor de patrones
El sistema muestra una secuencia visual/numeral.
El niño:
- completa;
- crea una extensión;
- encuentra el elemento lejano;
- descubre la regla.

---

## ALG-02 · Igualdad y relaciones
**Currículo**
=, ≠, <, > y equivalencias.

**Juego**
### Balanza
Manipular objetos/números para equilibrar ambos lados.

Muy importante:
“=” significa equivalencia, no “ahora viene la respuesta”.

---

## ALG-03 · Algoritmos y secuencias
**Currículo**
secuencias ordenadas, ensayo-error, bucles/condicionales sencillos.

**Juego**
### Programa al robot
Bloques visuales:
- avanzar;
- girar;
- repetir;
- SI ocurre X → hacer Y.

El objetivo es llegar a una meta con el menor número de bloques posible.

---

# 7. Estadística y probabilidad

## EST-01 · Recoger y organizar datos
**Currículo**
tablas de recuento y doble entrada.

**Juego**
### Expedición
Aparecen criaturas/objetos durante un tiempo.
El niño debe registrar los datos correctamente.

Después:
- completar tabla;
- detectar dato mal colocado.

---

## EST-02 · Gráficos
**Currículo**
pictogramas, barras, pasar gráfico ↔ tabla, interpretar.

**Juego**
### Centro de control
Una pantalla recibe datos vivos.

Retos:
- arrastrar datos a barras;
- reconstruir gráfico a partir de tabla;
- encontrar inconsistencia;
- contestar una pregunta que obliga a combinar dos datos.

---

## EST-03 · Azar y probabilidad intuitiva
**Currículo**
imposible/posible/seguro;
más/menos/igual de probable;
predicciones con ruletas, dados, fichas.

**Juego**
### Laboratorio de suerte
Contenedores transparentes con fichas.
El niño apuesta dónde es más probable obtener cierto color y luego ejecuta el experimento.

El objetivo no es memorizar “probabilidad”; es razonar sobre composición.

---

# 8. Patrones de demanda cognitiva

Para CADA microhabilidad necesitamos al menos tres tipos de reto.

## Básico
“Sé hacerlo.”
- identificar;
- ejecutar;
- leer;
- representar.

## Intermedio
“Sé cuándo y cómo usarlo.”
- seleccionar estrategia;
- conectar datos;
- transformar representación;
- resolver una situación estándar.

## Superior
“Sé pensar con ello.”
- detectar error;
- justificar;
- comparar estrategias;
- encontrar varias soluciones;
- crear;
- decidir con información incompleta o combinada.

Una habilidad NO se considera dominada solo por acertar retos básicos.

---

# 9. Evidencias de aprendizaje

Cada actividad guarda más que correcto/incorrecto:

- tiempo hasta primera acción;
- número de intentos;
- respuesta final;
- estrategia elegida;
- manipulaciones realizadas;
- uso de pista;
- error típico;
- capacidad de corregirse;
- rendimiento al volver a aparecer días después.

Eso alimentará la adaptación.

---

# 10. Banco MVP prioritario

Antes de ampliar la aplicación, construir:

### 1. Mapa y recorridos
ESP · REP · básico/intermedio

### 2. Reparto y detección de error
NUM · REP/RAP · básico/superior

### 3. Formación rectangular multiplicativa
NUM · CON/RAP · básico/intermedio

### 4. Fracciones manipulables
NUM · CON/COR · básico/intermedio

### 5. Reloj y calendario
MES · REP · básico/intermedio

### 6. Medidas y equivalencias
MES · REP/RAP · básico/intermedio

### 7. Simetría
ESP · RAP · intermedio

### 8. Perímetro como construcción
ESP · REP/RAP · intermedio/superior

### 9. Tabla ↔ gráfico
EST · COR · básico/intermedio

### 10. Detectar error en datos
EST · RAP · superior

### 11. Patrones
ALG · RAP/COR · intermedio/superior

### 12. Probabilidad manipulativa
EST · RAP · básico/intermedio

---

# 11. Criterio de aceptación de un minijuego

No entra en producción si no podemos responder:

1. ¿Qué microhabilidad oficial mide?
2. ¿Qué bloque competencial trabaja?
3. ¿Qué demanda cognitiva exige?
4. ¿Qué acción física hace el niño?
5. ¿Qué error típico podemos detectar?
6. ¿Qué evidencia guardamos?
7. ¿Cómo hacemos una variante sin cambiar de habilidad?
8. ¿Cómo sabemos cuándo subir de nivel?

Si alguna respuesta es “no sé”, el minijuego aún no está diseñado.

---

# 12. Qué cambia respecto a V1

La versión actual contiene conceptos correctos, pero:
- el nivel fue calibrado informalmente;
- se apoya demasiado en “resultado correcto”;
- no mide suficientemente razonamiento;
- los escenarios sirven de decoración en algunos retos.

La siguiente interfaz debe construirse a partir de este blueprint, no al revés.
