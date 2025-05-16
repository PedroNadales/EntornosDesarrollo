Cuando un código funciona, una forma de mejorarlo es buscar los *code smells* y eliminarlos. Un *code smell* (hediondez del código) es una señal de que algo en el código podría estar mal diseñado, aunque no impida que funcione. Es como cuando abres la nevera y algo huele mal: sabes que hay un problema, aunque todavía no veas exactamente cuál

Las refactorizaciones son técnicas para mejorar el diseño del código sin cambiar cómo funciona. Sirven para solucionar los *code smells* y hacer el código más claro, fácil de mantener y menos propenso a errores en el futuro

## 2.1 Refactorizaciones habituales:

* *Composing Methods*: crear métodos para reducir código duplicado y organizar mejor el código.
* *Extract Method*: cuando varias líneas de código cumplen una función concreta, se pueden extraer a un nuevo método con un nombre descriptivo. Esto ayuda a que el código sea más fácil de entender y mantener

En resumen, identificar *code smells* y aplicar refactorizaciones ayuda a tener un código más limpio y de mejor calidad.

## 2.1.2. Code Smells

Los "code smells" son señales que nos dicen que el código puede estar mal hecho. Aunque el código funcione, puede ser difícil de entender, cambiar o arreglar en el futuro.

## Bloaters

Los "bloaters" son clases o funciones que se han hecho muy grandes y complicadas. Por eso, trabajar con ellas se vuelve difícil.

## Long Method

Un "long method" es un método que tiene muchas líneas de código o hace muchas cosas diferentes. Si un método es muy largo, puede ser complicado de entender. Aunque no hay un número exacto, si tiene más de 50 líneas, ya puede ser demasiado. Lo importante es que no haga demasiadas tareas a la vez

## 2.3. Análisis del código

Podemos analizar el código de dos formas:

* **Análisis dinámico:** Usando pruebas unitarias para ver si el código funciona bien cuando se ejecuta.
* **Análisis estático:** Usando linters o páginas web para revisar el código sin ejecutarlo, buscando errores o problemas de calidad.

**Linters**

Un linter es un programa que revisa el código y señala errores de estilo, partes que no se usan o posibles problemas. El primer linter se usó para el lenguaje C, pero hoy existen para muchos lenguajes. Algunos ejemplos:

* lint: para C
* sonar: para Java
* JSLint, ESLint: para JavaScript

**Continuous Inspection**

Son páginas web o servicios que revisan automáticamente el código cada vez que lo subes a un repositorio. Así, se puede ver la calidad de nuestro código de forma continua. Ejemplos:

* SonarQube ([pagina de SonarQube](https://www.sonarsource.com/products/sonarqube/))

  ![sonar logo ](https://assets-eu-01.kc-usercontent.com/5dddefee-e8bb-013a-3b4e-7907971cf825/8e59bcad-6e39-41dc-abd9-a0e251e8d63f/Sonar%20%282%29.svg?w=128&h=32&auto=format&fit=clip)
* Scrutinizer ([Pagina de Scrutinizer](https://scrutinizer-ci.com))

  ![Scrutinizer](https://scrutinizer-ci.com/rt_assets/images/logo.png)

Estas herramientas ayudan a detectar errores y mantener el código limpio y fácil de entender
