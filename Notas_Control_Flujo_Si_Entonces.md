# 🤖 ¿Qué es el Control de Flujo?

Imagina que tienes una receta de cocina. Las instrucciones te dicen en qué orden hacer las cosas: primero picas la cebolla, luego salteas la carne, y así sucesivamente.  
En programación, **el control de flujo** es exactamente eso: el orden en que se ejecutan las instrucciones en un programa.  
Es como el GPS de tu robot, indicándole qué camino tomar.

---

## 🧭 Tipos de Control de Flujo

Nos enfocaremos en los que permiten tomar **decisiones**, que son clave para programar comportamiento inteligente en robots:

- **Secuencial**  
  Las instrucciones se ejecutan una tras otra, en orden. Como seguir una línea recta.

- **Condicional (Decisión)**  
  El programa evalúa una condición:  
  “¿Es esto verdad? Si sí, hago esto. Si no, hago aquello.”  
  *Aquí entra el famoso `if-else`.*

- **Repetición (Bucle)**  
  Ideal cuando se necesita ejecutar algo varias veces sin repetir código.  
  Por ejemplo, mover un brazo robótico cinco veces.

---

## ⚙️ `if-else`: La Decisión del Robot

Piensa en tu robot con un cerebro lógico. Solo entiende preguntas de *sí o no*, y actúa dependiendo de la respuesta.

**Estructura básica:**

```plaintext
IF (condición verdadera):
    haz esto
ELSE:
    haz esto otro
```
🌱 Ejemplo 1: Robot Jardinero
El robot mide la humedad del suelo con un sensor.

```plaintext
SI (humedad es baja):
    encender bomba de agua
SINO:
    apagar bomba o no hacer nada
```
👉 El robot solo riega si es necesario, evitando inundaciones. Inteligente, ¿no?

♻️ Ejemplo 2: Robot de Reciclaje
El robot identifica colores para clasificar objetos en una cinta transportadora.

```plaintext
SI (objeto es azul):
    empujar al contenedor de plástico
SINO:
    dejar que el objeto siga su camino
```
Aquí el robot usa if-else para decidir qué acción tomar según el color del objeto.

🧠 Puntos Clave
if-else sirve para tomar decisiones programadas.

* Las condiciones deben poder evaluarse como verdaderas o falsas.

* IF = acción si se cumple la condición.

* ELSE = acción si no se cumple.

Con if-else, puedes darle a tu robot una inteligencia reactiva frente a su entorno. ¡Es una herramienta esencial para hacer robots más útiles y autónomos!

💡 ¿Y tú?
¿Se te ocurre otro ejemplo donde un robot pueda usar if-else en la vida diaria? ¡Tu idea puede ser el próximo gran paso en programación educativa!


Ejercicios: ¡Tu Día a Día en IF-ELSE!
Aquí tienes algunos escenarios de la vida cotidiana. Intenta pensar cómo los convertirías en una sentencia IF-ELSE. Te doy el primero como ejemplo:

Ejemplo:

Situación: Por la mañana, tienes que decidir si llevar un paraguas.

Condición: ¿Está lloviendo afuera?

* Si es VERDADERO (está lloviendo): Llevo el paraguas.

* Si es FALSO (no está lloviendo): No llevo el paraguas.

Ahora, ¡es tu turno! Piensa en la condición y en las acciones para cada situación:

```
Situación: Vas a salir a la calle y tienes que decidir si ponerte un abrigo.

Condición: ¿Es...?

Si es VERDADERO: ...

Si es FALSO: ...
```
```

Situación: Estás en casa y tienes hambre. Quieres comer algo.

Condición: ¿Es...?

Si es VERDADERO: ...

Si es FALSO: ...
```
```

Situación: Es de noche y tienes que decidir si encender la luz de tu habitación.

Condición: ¿Es...?

Si es VERDADERO: ...

Si es FALSO: ...
```
```

Situación: Estás jugando un videojuego y tu personaje se encuentra con un enemigo.

Condición: ¿Es...?

Si es VERDADERO: ...

Si es FALSO: ...
```
```

Situación: Quieres usar tu teléfono celular.

Condición: ¿Es...?

Si es VERDADERO: ...

Si es FALSO: ...
```
