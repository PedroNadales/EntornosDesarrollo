# Integración y Distribución Continua

Las siglas **CI / CD** hacen referencia a la **Integración Continua (Continuous Integration)** y a la **Distribución Continua (Continuous Distribution)**, aunque **CD** también puede referirse a la **Entrega Contínua (Continuous Delivery)**.

La **integración** es un proceso por el cual los cambios que realiza un desarrollador y debe hacerse en base a la relevancia del código, integrando primero aquel código que realice funciones principales y después el que realice subfunciones (**descendente**) o viceversa (**ascendente**).

**Integración Continua** se produce se produce con la mayor frecuencia posible y de forma automatizada gracias a los tests.

La **Distribución Contínua** consiste en subir al repositorio de forma automática los cambios en el momento en que se hayan integrado

Por ultimo el proceso de **Entrega continua** pone automáticamente en producción la versión de la aplicación que hay en el repositorio una vez que este se actualiza.

Servicios de CI:

* [Jenkins](https://www.jenkins.io/) servidor de automatización de código abierto líder, proporciona cientos de complementos para respaldar la creación, la implementación y la automatización de cualquier proyecto.

  ![](https://www.jenkins.io/images/logos/jenkins/jenkins.svg)
* [Bamboo](https://www.atlassian.com/es/software/bamboo) ofrece resistencia, fiabilidad y escalabilidad a equipos de todos los tamaños.

  ![Bamboo](https://wac-cdn.atlassian.com/misc-assets/adg4-nav/HeaderLogoBamboo.svg)
* [TravisCI](https://www.travis-ci.com/) servicio de integración continua distribuido y alojado que se utiliza para crear y probar proyectos de software alojados en GitHub y Bitbucket

  ![Mr T of Travis CI](https://www.travis-ci.com/wp-content/uploads/2024/08/cropped-travis-ci-mascot-1-480x480-1-64-64.png)
* [CircleCI](https://circleci.com/) para crear, probar e implementar fácilmente código listo para producción.

![](https://images.g2crowd.com/uploads/product/image/social_landscape/social_landscape_f12938338549ef6246b98aaa6418267e/circleci.png)
