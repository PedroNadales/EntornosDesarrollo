## 4. Framework de testing

El proceso de prueba se puede llevar a cabo usando el debugger pero es mucho más apropiado utilizar un **framework** y automatizar el proceso.

un **framework** o **marco de trabajo** es un conjunto de librerías y herramientas que han sido diseñados siguiendo una filosofía de buenas prácticas, de modo que al usarlo se obtenga un resultado de calidad.

Ejempos de frameworks de tests son:

* **.NET**: xUnit
  ![microsoftdotneticono.png](assets/microsoft-dot-net-icono.png)
* **Java**: JUnit, TestNG

  ![javaprogramminglanguageicon.png](assets/java-programming-language-icon.png)
* **C++**: CppUnit, Google Test

  ![cplusplusprogramminglanguageicon.png](assets/c-plus-plus-programming-language-icon.png)
* **PHP**: PHPUnit

  ![phpprogramminglanguageicon.png](assets/php-programming-language-icon.png)
* **JavaScript**: Mocha

  ![](https://static-00.iconduck.com/assets.00/mocha-icon-84x96-f7jgzruh.png)

## Clean Testing

los tests timpios (*Clean Tests*), de forma similar al *código limpio* (*clean code*) siguen una serie de buenas prácticas, como por ejemplo:

1 Usar nombres muy descriptivos para cada test

2 Cada test solo comprueba un solo comportamiento

3 Los test deberían estar estructurados según el **patrón Arrange-Act-Assert (AAA)**:

* **Arrange**: preparación de los elementos necesarios para el test. Esto incluye la inicialización y preparación de los objetos que se van a utilizar.
* **Act**: ejecuta la acción que se va a probar.
* **Assert**: comprueba con aserciones que el resultado es el esperado.

4 Sigue los **principios F.I.R.S.T.**:

* **Fast**: un test debe ser rápido.
* **Independent**: un test debe ser independiente respecto de otros tests o servicios externos. Se debe poder ejecutar sólo.
* **Repeteable**: un test debe poderse repetible en cualquier entorno, usando datos propios y sin depender de factores externos. Si no hay ningún cambio en el código el resultado de un test debe ser siempre el mismo.
* **Self-validating**: cada test debe comprobar por sí solo si falla o se ejecuta correctamente. Es decir, la comprobación debe ser automática, no manual.
* **Thorough**: el test debe ser exhaustivo:
  * Debe cubrir todos los caminos felices (caminos en que no se introducen datos inválidos).
  * Debe cubrir casos límite.
  * Debe cubrir casos negativos.
  * Debe cubrir aspectos ilegales y de seguridad.

![7 Tips To Write Clean And Better Code in 2025 | GeeksforGeeks](https://media.geeksforgeeks.org/wp-content/cdn-uploads/20191216192939/Ratio-of-Time-Spent-Reading-Code-Versus-Writing.png)
