## 2. Pruebas de Software

En esta sección exploramos cómo se pueden clasificar las pruebas según distintos criterios.

### 2.1. Según su forma

* **Pruebas dinámicas**: Implican la ejecución del programa para evaluar su comportamiento real.
* **Pruebas estáticas**: Se realizan sin ejecutar el código, analizando directamente el código fuente o la documentación.

### 2.2. Según la estrategia

#### Estrategias de prueba

* **Caja negra**: Se evalúan las funcionalidades del sistema desde el exterior, sin tener en cuenta su implementación interna.
* **Caja blanca**: Se analiza el funcionamiento interno del código. Se centra en la estructura y flujo lógico del software.

#### Técnicas de prueba de caja negra

* **Particiones de equivalencia**: Se divide el conjunto de entradas en clases de equivalencia (válidas e inválidas). Probar con un valor representativo de cada clase es suficiente.
  * *Ejemplo:* Para una edad entre 0 y 99, las clases serían: [0-99] (válida), menor que 0 (inválida), y mayor que 99 (inválida).
* **Análisis de valores límite**: Se prueban los límites del rango permitido y valores justo fuera de este.
  * *Ejemplo:* Con el mismo rango de edad (0 a 99), se probarían los valores -1, 0, 99 y 100.

#### Técnicas de prueba de caja blanca

* **Cobertura de código**: Se diseñan pruebas para cubrir todas las instrucciones, decisiones y caminos posibles del código.
* **Pruebas de bucles**: Evalúan distintos escenarios de ejecución de bucles:
  * No ejecutar el bucle.
  * Ejecutarlo una vez.
  * Ejecutarlo dos veces.
  * Ejecutarlo varias veces (menos de n).
  * Ejecutarlo n-1, n y n+1 veces.

### 2.3. Según el tipo de prueba

#### Pruebas funcionales

Evalúan si el software cumple con los requisitos especificados.

* **Pruebas unitarias**: Verifican el funcionamiento de componentes individuales (clases, funciones...).
* **Pruebas de regresión**: Se realizan tras cambios en el código para confirmar que no se han introducido errores nuevos.
* **Pruebas de integración**: Comprueban que los distintos módulos interactúan correctamente entre sí.
* **Pruebas de humo**: Ensayos preliminares para detectar errores críticos. El nombre proviene del mundo del hardware (encender un circuito y ver si echa humo).
* **Pruebas del sistema**: Evalúan el sistema completo, incluyendo la interacción entre subsistemas y con sistemas externos.
* **Pruebas alfa y beta**:
  * *Alfa*: Realizadas internamente por el equipo de desarrollo en una versión inestable.
  * *Beta*: Llevadas a cabo por usuarios reales con una versión más estable.
* **Pruebas de aceptación**: El cliente comprueba que el sistema cumple con los requisitos establecidos.

#### Pruebas no funcionales

Evalúan características adicionales del software.

* **Usabilidad**: Se analiza si el sistema es fácil de usar e intuitivo.
* **Rendimiento**: Mide la velocidad de respuesta bajo condiciones específicas.
* **Estrés**: Se somete al sistema a cargas extremas para observar su punto de fallo.
* **Seguridad**: Se verifican posibles vulnerabilidades y medidas de protección.
* **Compatibilidad**: Se comprueba el funcionamiento en distintos dispositivos, sistemas operativos o versiones.
* **Portabilidad**: Se evalúa la facilidad con la que el software puede adaptarse a otros entornos tecnológicos.

### 2.4. Según el mecanismo de ejecución

* **Manual**: Las pruebas son realizadas por una persona, que ejecuta casos y valida resultados.
* **Automatizado**: Se utilizan herramientas que ejecutan pruebas automáticamente y comparan los resultados con los esperados.
