# Sesión especial: Aprender Java de manera autodidacta

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/java/java-original.svg" width="78" height="78" alt="Java" />
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/intellij/intellij-original.svg" width="64" height="64" alt="IntelliJ IDEA" />
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/eclipse/eclipse-original.svg" width="64" height="64" alt="Eclipse" />
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" width="64" height="64" alt="Git" />
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/github/github-original.svg" width="64" height="64" alt="GitHub" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Objetivo-Aprender_Java_por_tu_cuenta-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Aprender Java" />
  <img src="https://img.shields.io/badge/Modalidad-Práctica-2563EB?style=for-the-badge" alt="Modalidad práctica" />
  <img src="https://img.shields.io/badge/Enfoque-Autodidactismo-6C63FF?style=for-the-badge" alt="Autodidactismo" />
</p>

> **Objetivo de la sesión:** aprender a avanzar en Java cuando encuentras un concepto, error o problema que todavía no sabes resolver.

Esta sesión no busca enseñarte una instrucción nueva de Java de principio a fin.

Busca algo más importante:

> **que aprendas qué hacer cuando Java te presenta algo que todavía no conoces.**

Hasta ahora has trabajado con temas como variables, tipos de datos, condicionales, ciclos, métodos y orientación a objetos.

Pero llegará un momento en el que aparecerán conceptos como:

```text
ArrayList
Excepciones
Interfaces
Archivos
Colecciones
Streams
Lambdas
JUnit
Maven
Spring
APIs
```

No necesitas esperar a que alguien te explique cada uno.

Puedes aprender a investigarlos, probarlos y comprenderlos por tu cuenta.

---

## 1. Aprender Java no significa memorizar Java

Aprender Java no consiste en recordar de memoria cada instrucción.

Puedes olvidar exactamente cómo se escribe un método, un `ArrayList` o una excepción.

Lo importante es saber:

```text
qué necesitas hacer;
qué concepto necesitas;
dónde investigarlo;
cómo probarlo;
cómo comprobar si funciona;
cómo explicarlo después.
```

Un desarrollador no necesita saber todo.

Necesita saber **cómo avanzar cuando todavía no sabe algo**.

---

## 2. Ser autodidacta no significa aprender solo

Ser autodidacta no significa:

```text
"No puedo preguntar."
"No puedo utilizar Internet."
"No puedo pedir ayuda."
"Tengo que resolver todo sin apoyo."
```

Significa que tú tomas un papel activo en tu aprendizaje.

Cuando encuentras algo que no sabes hacer, no te detienes inmediatamente.

Primero intentas comprender el problema.

Por ejemplo:

> "No entiendo Java."

es demasiado general.

Pero:

> "Entiendo `if`, pero no sé cuándo usar `switch`."

ya es algo que puedes investigar.

O:

> "Sé utilizar `while`, pero no entiendo por qué mi menú no termina."

también es investigable.

---

## 3. El ciclo para aprender Java por tu cuenta

Puedes utilizar este ciclo cada vez que aparezca un concepto nuevo:

```text
QUIERO HACER ALGO EN JAVA
          ↓
IDENTIFICO QUÉ NO SÉ
          ↓
FORMULO UNA PREGUNTA
          ↓
BUSCO INFORMACIÓN
          ↓
CREO UN EJEMPLO PEQUEÑO
          ↓
COMPILO
          ↓
OBSERVO EL RESULTADO
          ↓
ME EQUIVOCO
          ↓
CORRIJO
          ↓
LO EXPLICO
          ↓
LO UTILIZO EN OTRO PROBLEMA
```

El error no rompe este ciclo.

**El error forma parte del aprendizaje de Java.**

---

## 4. Convierte un problema grande en una pregunta pequeña

Imagina que quieres crear un sistema para registrar tareas.

Podrías pensar:

```text
"No sé hacer este programa."
```

Eso no ayuda mucho.

Pero puedes dividirlo:

```text
¿Cómo guardo varios textos?
¿Cómo agrego un nuevo elemento?
¿Cómo recorro todos los elementos?
¿Cómo elimino uno?
¿Cómo sé cuántos elementos hay?
```

Ahora cada pregunta puede investigarse por separado.

Muy probablemente descubrirás una clase llamada:

```java
ArrayList
```

Eso es aprendizaje autodidacta:

**convertir un problema grande en preguntas pequeñas.**

---

## 5. Aprende a buscar Java correctamente

Una búsqueda poco útil:

```text
Java no funciona
```

Una mejor:

```text
Java do while menu
```

Todavía mejor:

```text
Java do while menu repeat until user selects exit
```

Otro ejemplo:

```text
Java Scanner nextLine after nextInt
```

Otro:

```text
Java ArrayList add remove size
```

Otro:

```text
Java NumberFormatException parseInt
```

### Regla práctica

Cuando busques información, intenta escribir:

```text
Java + concepto + problema
```

Por ejemplo:

```text
Java String compare ignore case
Java method return double
Java for loop ArrayList
Java inheritance example
Java NullPointerException
```

---

## 6. La documentación de Java es una herramienta de trabajo

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/java/java-original.svg" width="90" alt="Java" />
</p>

No necesitas memorizar todas las clases y métodos de Java.

Para eso existe la documentación.

Documentación oficial:

<https://docs.oracle.com/en/java/>

Cuando encuentres una clase nueva, puedes investigar:

```text
¿Qué representa?
¿Qué constructores tiene?
¿Qué métodos ofrece?
¿Qué recibe cada método?
¿Qué devuelve?
```

Por ejemplo, si encuentras:

```java
ArrayList<String> nombres = new ArrayList<>();
```

puedes investigar la clase `ArrayList`.

No necesitas leer toda la documentación.

Busca únicamente aquello que necesitas.

---

## 7. Primero prueba el concepto aislado

Cuando quieres aprender algo nuevo, evita introducirlo inmediatamente en un programa grande.

Supón que quieres entender `ArrayList`.

Puedes comenzar con:

```java
import java.util.ArrayList;

public class PruebaArrayList {

    public static void main(String[] args) {

        ArrayList<String> nombres = new ArrayList<>();

        nombres.add("Ana");
        nombres.add("Luis");

        System.out.println(nombres);
    }
}
```

Este programa no intenta resolver un sistema completo.

Tiene un solo propósito:

> **entender cómo crear una lista y agregar elementos.**

A esto podemos llamarlo un **experimento mínimo**.

---

## 8. Después modifica el experimento

No te limites a ejecutar el código.

Experimenta.

Por ejemplo:

```java
nombres.add("Carlos");
```

Después:

```java
nombres.remove("Ana");
```

Después:

```java
System.out.println(nombres.size());
```

Después:

```java
System.out.println(nombres.get(0));
```

Cada cambio debe responder una pregunta.

```text
¿Qué hace add()?
¿Qué hace remove()?
¿Qué devuelve size()?
¿Qué ocurre con get(0)?
```

Aprender programación implica **probar hipótesis**.

---

## 9. Cambia valores para comprobar si realmente entiendes

Observa:

```java
int edad = 18;

if (edad >= 18) {
    System.out.println("Mayor de edad");
}
```

No te limites a ejecutar el ejemplo.

Prueba:

```java
edad = 15;
```

Después:

```java
edad = 18;
```

Después:

```java
edad = 25;
```

Pregunta:

```text
¿Qué cambia?
¿Por qué?
¿Qué ocurre exactamente cuando edad vale 18?
```

Modificar datos es una de las formas más sencillas de verificar comprensión.

---

## 10. Aprende preguntando "¿qué pasa si...?"

Cada vez que estudies Java, utiliza esta pregunta:

> **¿Qué pasa si cambio esto?**

Ejemplo:

```java
for (int i = 0; i < 5; i++) {
    System.out.println(i);
}
```

Prueba cambiar:

```java
i < 5
```

por:

```java
i <= 5
```

Después:

```java
i += 2
```

Después:

```java
int i = 1;
```

No memorices únicamente la estructura.

Descubre cómo se comporta.

---

## 11. Aprende a leer el código antes de ejecutarlo

Antes de presionar **Run**, intenta predecir qué ocurrirá.

Por ejemplo:

```java
int numero = 3;

while (numero > 0) {
    System.out.println(numero);
    numero--;
}

System.out.println("Fin");
```

Antes de ejecutarlo, pregúntate:

```text
¿Qué imprimirá primero?
¿Cuántas veces se ejecutará el ciclo?
¿Cuál será el valor final de numero?
```

Después ejecuta el programa.

Si tu predicción fue incorrecta, acabas de encontrar algo que necesitas comprender mejor.

---

## 12. El compilador también te enseña Java

Cuando Java muestra un error, no significa simplemente:

```text
"Está mal."
```

Significa que tienes información para investigar.

Ejemplo:

```text
cannot find symbol
```

Pregúntate:

```text
¿Qué símbolo no encontró?
¿Es una variable?
¿Es un método?
¿Es una clase?
¿Está escrito correctamente?
¿Existe en este alcance?
```

Otro ejemplo:

```text
';' expected
```

Otro:

```text
incompatible types
```

Otro:

```text
method ... cannot be applied to given types
```

El mensaje del compilador es una pista.

**Léelo antes de modificar código al azar.**

---

## 13. Las excepciones también son información

Tu programa puede compilar y aun así fallar durante la ejecución.

Por ejemplo:

```java
String texto = "hola";
int numero = Integer.parseInt(texto);
```

Esto puede producir:

```text
NumberFormatException
```

No necesitas conocer de memoria esa excepción.

Puedes investigarla:

```text
Java NumberFormatException parseInt
```

Después crea un ejemplo mínimo.

```java
public class PruebaConversion {

    public static void main(String[] args) {

        String texto = "123";

        int numero = Integer.parseInt(texto);

        System.out.println(numero);
    }
}
```

Después cambia:

```java
"123"
```

por:

```java
"hola"
```

Ahora puedes observar qué provoca el error.

---

## 14. No copies código sin hacerle preguntas

Encontrar código en Internet no es necesariamente malo.

El problema aparece cuando haces esto:

```text
buscar
↓
copiar
↓
pegar
↓
funcionó
↓
terminé
```

En lugar de eso:

```text
buscar
↓
leer
↓
copiar o adaptar
↓
ejecutar
↓
modificar
↓
explicar
↓
reconstruir
```

Después de utilizar un ejemplo, deberías poder responder:

```text
¿Qué hace esta variable?
¿Por qué existe este ciclo?
¿Qué recibe este método?
¿Qué devuelve?
¿Qué pasa si elimino esta línea?
¿Qué pasa si cambio esta condición?
```

---

## 15. Reconstruye el código sin mirar

Después de comprender un ejemplo, ciérralo.

Intenta escribirlo nuevamente.

Por ejemplo, después de practicar:

```java
ArrayList<String> tareas = new ArrayList<>();
tareas.add("Estudiar Java");
```

cierra el ejemplo.

Ahora intenta reconstruirlo.

Si no recuerdas la sintaxis exacta, no pasa nada.

Investiga únicamente la parte que olvidaste.

Así comienzas a distinguir entre:

```text
"No recuerdo la sintaxis."
```

y:

```text
"No entiendo el concepto."
```

Son problemas diferentes.

---

## 16. Utiliza inteligencia artificial para aprender Java

<p align="center">
  <img src="https://cdn.simpleicons.org/openai/412991" width="72" alt="OpenAI" />
  &nbsp;&nbsp;&nbsp;
  <img src="https://cdn.simpleicons.org/githubcopilot/8957E5" width="72" alt="GitHub Copilot" />
</p>

Una inteligencia artificial puede ayudarte a estudiar Java.

Pero la forma en que preguntas cambia lo que aprendes.

### Poco útil para aprender

```text
Haz este programa.
```

### Mejor

```text
Estoy aprendiendo ciclos en Java.
No me des la solución completa.
Explícame qué debo revisar para construir un menú que se repita.
```

### Mejor todavía

```text
Este es mi código Java.
El menú debería terminar cuando el usuario escriba 4.
No me des un programa nuevo.
Ayúdame a identificar qué parte de mi condición está causando el problema.
```

La IA debe ayudarte a **pensar**, no reemplazar tu pensamiento.

---

## 17. Puedes pedir ayuda por niveles

Cuando estés bloqueado, no necesitas pedir inmediatamente la solución completa.

### Nivel 1 — Concepto

```text
¿Qué concepto de Java necesito para resolver este problema?
```

### Nivel 2 — Explicación

```text
Explícame ese concepto con un ejemplo pequeño.
```

### Nivel 3 — Pista

```text
Dame una pista, pero no escribas todavía la solución.
```

### Nivel 4 — Revisión

```text
Revisa mi código y dime dónde está el problema.
```

### Nivel 5 — Comparación

```text
Muéstrame dos formas de resolverlo y explícame la diferencia.
```

### Nivel 6 — Evaluación

```text
Hazme preguntas para comprobar si realmente lo entendí.
```

---

## 18. Aprende a reconocer qué tipo de problema tienes

Cuando algo no funciona, intenta clasificarlo.

### Problema de sintaxis

Ejemplo:

```java
System.out.println("Hola")
```

### Problema de lógica

El programa compila, pero hace algo diferente a lo esperado.

### Problema de tipo de dato

Ejemplo:

```java
int edad = "20";
```

### Problema de entrada

Ejemplo:

```java
Scanner
nextInt()
nextLine()
```

### Problema de alcance

Una variable existe dentro de un bloque, pero intentas utilizarla fuera.

### Problema de ejecución

Ejemplo:

```text
NumberFormatException
NullPointerException
IndexOutOfBoundsException
```

Saber qué tipo de problema tienes hace que investigar sea mucho más fácil.

---

## 19. El protocolo de desbloqueo para Java

Cuando te quedes atascado, prueba este orden:

```text
1. Lee el mensaje de error completo.
2. Identifica qué esperabas que ocurriera.
3. Observa qué ocurrió realmente.
4. Localiza la línea o bloque relacionado.
5. Reduce el problema.
6. Busca "Java + concepto + problema".
7. Consulta documentación o ejemplos.
8. Crea un programa mínimo.
9. Modifica una sola cosa.
10. Vuelve a ejecutar.
11. Pide una pista si sigues bloqueado.
12. Explica qué intentaste.
```

No necesitas hacer siempre los doce pasos.

El objetivo es evitar:

```text
"No funciona."
```

y convertirlo en:

```text
"Mi programa compila, pero el do-while no termina cuando escribo 4.
Revisé la condición y probé cambiar == por !=.
Creo que el problema está en esta línea."
```

Eso es una pregunta técnica mucho mejor.

---

## 20. Aprende Java por capas

No intentes dominar todo al mismo tiempo.

Puedes avanzar por capas:

```text
Sintaxis
↓
Variables y tipos
↓
Operadores
↓
Condicionales
↓
Ciclos
↓
Métodos
↓
Arreglos
↓
Clases y objetos
↓
Herencia y composición
↓
Colecciones
↓
Excepciones
↓
Archivos
↓
Pruebas
↓
Frameworks
```

Cada concepto nuevo se apoya en conceptos anteriores.

Si algo se vuelve demasiado difícil, revisa qué conocimiento previo está faltando.

---

# Actividad práctica: aprender `ArrayList` por tu cuenta

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/java/java-original.svg" width="90" alt="Java" />
</p>

En esta actividad no recibirás primero una explicación completa de `ArrayList`.

Tu objetivo es practicar el proceso de aprendizaje.

## Reto

Investiga cómo utilizar:

```java
ArrayList
```

Debes descubrir cómo:

```text
1. Importar ArrayList.
2. Crear una lista de String.
3. Agregar elementos.
4. Mostrar todos los elementos.
5. Obtener un elemento.
6. Eliminar un elemento.
7. Conocer el tamaño de la lista.
8. Recorrerla con un ciclo.
```

Puedes utilizar:

```text
Documentación de Java
Buscadores
Stack Overflow
Inteligencia artificial
Ejemplos
Compañeros
Tutor
```

### Regla

> **No basta con que el código funcione. Debes poder explicar por qué funciona.**

---

# Producto: Lista de tareas en Java

Crea:

```text
ListaDeTareas.java
```

El programa debe almacenar tareas utilizando `ArrayList`.

Primera versión:

```text
=== MIS TAREAS ===

1. Estudiar Java
2. Realizar práctica
3. Revisar ejercicios

Total: 3
```

Después intenta agregar:

```text
Agregar tarea
Eliminar tarea
Mostrar tareas
Salir
```

No importa si no completas todo.

Lo importante es identificar:

```text
qué pudiste resolver;
qué tuviste que investigar;
qué error apareció;
cómo lo resolviste;
qué necesitas aprender después.
```

---

# Segundo reto: aprende un método nuevo de `String`

Selecciona uno que todavía no utilices regularmente.

Por ejemplo:

```java
contains()
startsWith()
endsWith()
substring()
replace()
trim()
isEmpty()
```

Tu reto es:

```text
1. Descubrir qué hace.
2. Crear un ejemplo mínimo.
3. Probarlo con diferentes valores.
4. Explicarlo con tus propias palabras.
5. Utilizarlo en un pequeño programa.
```

---

# Tercer reto: aprende una excepción

Investiga una de estas excepciones:

```text
NumberFormatException
NullPointerException
IndexOutOfBoundsException
ArithmeticException
```

Debes responder:

```text
¿Cuándo puede ocurrir?
¿Cómo puedo provocar el error intencionalmente?
¿Qué mensaje aparece?
¿Cómo puedo evitarlo?
```

No necesitas memorizar la excepción.

Necesitas aprender a investigarla.

---

# Documenta lo que aprendiste

Crea:

```text
APRENDIZAJE.md
```

Y responde:

```markdown
# Lo que aprendí de Java

## ¿Qué concepto investigué?

## ¿Qué quería lograr?

## ¿Qué no entendía al principio?

## ¿Qué búsqueda utilicé?

## ¿Qué ejemplo mínimo construí?

## ¿Qué error apareció?

## ¿Cómo lo resolví?

## ¿Qué puedo hacer ahora que antes no podía?

## ¿Qué quiero aprender después?
```

---

# GitHub como bitácora de tu aprendizaje de Java

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/github/github-original.svg" width="80" alt="GitHub" />
</p>

GitHub no es el tema principal de esta sesión.

Pero puede ayudarte a guardar evidencia de tu progreso.

Una estructura posible:

```text
java-learning/
│
├── variables/
├── condicionales/
├── ciclos/
├── metodos/
├── arreglos/
├── poo/
├── arraylist/
├── excepciones/
└── README.md
```

Cada carpeta puede contener pequeños experimentos.

Con el tiempo tendrás un repositorio que muestra **cómo aprendiste Java**, no solamente proyectos terminados.

---

# Recursos para aprender Java

## Documentación oficial

<https://docs.oracle.com/en/java/>

## Java Tutorials

<https://docs.oracle.com/javase/tutorial/>

## Stack Overflow

<https://stackoverflow.com/>

## Roadmap de Java

<https://roadmap.sh/java>

## GitHub

<https://github.com/>

---

# Regla de oro

Antes de aceptar una solución encontrada o generada, pregúntate:

```text
¿Entiendo qué hace?
¿Entiendo por qué funciona?
¿Puedo modificarla?
¿Puedo explicarla?
¿Puedo volver a construirla?
¿Puedo utilizar el mismo concepto en otro problema?
```

Si la respuesta es sí, probablemente estás aprendiendo.

Si la respuesta es no, todavía tienes algo que investigar.

---

# Reto para continuar después de la sesión

Elige **un concepto de Java que todavía no conozcas**.

Algunas opciones:

```text
ArrayList
HashMap
HashSet
try-catch
Excepciones personalizadas
Lectura de archivos
Interfaces
Clases abstractas
Enums
Generics
Streams
Lambdas
JUnit
Maven
Spring Boot
```

No intentes dominarlo.

Tu objetivo inicial será responder:

```text
¿Qué es?
¿Qué problema resuelve?
¿Cuál es el ejemplo más pequeño que puedo crear?
¿Qué métodos o instrucciones básicas necesito?
¿Qué error puedo encontrar?
¿Dónde está su documentación?
¿Qué podría construir con esto?
```

Después crea un pequeño programa.

---

# Cierre

<p align="center">
  <img src="https://img.shields.io/badge/Leer-Entender-7C3AED?style=for-the-badge" alt="Leer y entender" />
  <img src="https://img.shields.io/badge/Programar-Probar-EA580C?style=for-the-badge" alt="Programar y probar" />
  <img src="https://img.shields.io/badge/Equivocarse-Corregir-DC2626?style=for-the-badge" alt="Equivocarse y corregir" />
  <img src="https://img.shields.io/badge/Explicar-Aprender-16A34A?style=for-the-badge" alt="Explicar y aprender" />
</p>

No necesitas conocer todo Java.

Tampoco necesitas recordar de memoria cada método disponible.

Lo que necesitas desarrollar es la capacidad de decir:

> **"Esto todavía no sé hacerlo, pero sé cómo empezar a aprenderlo."**

Esa capacidad será útil no solamente en este curso.

Será útil cada vez que aparezca:

```text
una nueva clase;
una nueva biblioteca;
un nuevo framework;
un error que nunca habías visto;
una nueva versión de Java;
una tecnología que todavía no existe.
```

---

## Pregunta final

> **Si mañana necesitas utilizar una característica de Java que nunca has visto, ¿qué harás primero?**
