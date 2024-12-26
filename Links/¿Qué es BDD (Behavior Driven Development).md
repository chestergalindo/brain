[[ReadItLater]] [[Article]]

# ¿Qué es BDD (Behavior Driven Development)

BDD (*Behavior Driven Development)*, es una estrategia de desarrollo dirigido por comportamiento, que ha evolucionado desde TDD (Test Driven Development), aunque no se trata de una técnica de testing.

A diferencia de TDD, BDD se define en un idioma común entre todos los *stakeholders*, lo que mejora la comunicación entre equipos tecnológicos y no técnicos. Tanto en TDD como en BDD, las pruebas se deben definir antes del desarrollo, aunque en BDD, las pruebas se centran en el usuario y el comportamiento del sistema, a diferencia del TDD que se centra en funcionalidades.

Antes de seguir, recomiendo que leas el artículo sobre “[¿Qué problema hay en utilizar TDD?](https://www.itdo.com/blog/que-problema-hay-en-utilizar-tdd/)”.

> ¿Quieres ser el primero a saber de las novedades de nuestro Blog? [Suscríbete](https://itdo.us19.list-manage.com/subscribe?u=094cb94633bc6e25e5166ca63&id=e912e62ec3) a la nuestra newsletter!

## Características BDD

La principal ventaja es que todas las definiciones BDD se escriben en un idioma común. El principal objetivo es que el equipo describa los detalles de cómo se debe comportar la aplicación a desarrollar, y de esta forma será comprensible por todos.

A diferencia de BDD, TDD funciona apropiadamente siempre que la dirección de la organización esté familiarizada con estas pruebas unitarias, en definitiva que sus habilidades técnicas sean lo suficientemente sólidas, y no siempre es así.

En estas circunstancias, la BDD tiene la ventaja de que las pruebas unitarias se pueden escribir en un lenguaje común utilizado por todas las partes interesadas. Este acceso a una comunicación más clara y con la mínima jerga tecnológica, es probablemente la mayor ventaja del uso de BDD, lo que hace posible que la colaboración entre los equipos técnicos y no técnicos se ejecute con mayor eficiencia.

## ¿Que debo tener en cuenta antes de implementar BDD?

-   Cada requisitos debe convertirse en historias de usuario, defiendo ejemplos concretos.
-   Cada ejemplo debe ser un escenario de un usuario en el sistema.
-   Ser consciente de la necesidad de definir "la especificación del comportamiento de un usuario" en lugar de "la prueba unitaria de una clase".
-   Comprender la fórmula [‘Given-When-Then’](https://martinfowler.com/bliki/GivenWhenThen.html) u otras como las historias de usuario [‘Role-Feature-Reason'](https://www.agilealliance.org/glossary/user-story-template/). Veamos que tratan estas fórmulas.

Para definir los casos BDD para una historia de usuario se deben definir bajo el patrón ‘Given-When-Then’, que se define como:

-   **Given ‘dado’:** Se especifica el escenario, las precondiciones.
-   **When ‘cuando’:** Las condiciones de las acciones que se van a ejecutar.
-   **Then ‘entonces’:** El resultado esperado, las validaciones a realizar.

Un ejemplo práctico sería:

-   **Given:** Dado que el usuario no ha introducido ningún dato en el formulario.
-   **When:** Cuando hace clic en el botón Enviar.
-   **Then:** Se deben mostrar los mensajes de validación apropiados.

Este patrón también se utiliza en BDD para ayudar a la creación de historias de usuarios. Esta se define como:

-   ******As a**** ‘****Como’:****** Se especifica el tipo de usuario.
-   ******I want**** ‘****deseo’:****** Las necesidades que tiene.
-   ******So that ‘para que’:****** Las características para cumplir el objetivo.

Un ejemplo práctico de historia de usuario sería: - **Como** cliente interesado, **deseo** ponerme en contacto mediante el formulario, **para que** atiendan mis necesidades.

## Herramientas de definición BDD

La herramienta más destacada, basado en el patrón ‘Given-When-Then’ es [Cucumber](https://cucumber.io/), un framework de test con soporte BDD. En Cucumber, las especificaciones de BDD están escritas en lenguaje Gherkin, basado en ‘Given-When-Then’. En otras palabras, Gherkin presenta el comportamiento de la aplicación, a partir de la cual Cucumber puede generar los casos de prueba de la aplicación.

Hay muchas otras herramientas, tantas como lenguajes de programación:

-   **Java:** JBehave, JDave, Instinct, beanSpec
-   **C:** CSpec
-   **C#:** NSpec, NBehave
-   **.NET:** NSpec, NBehave, SpecFlow
-   **PHP:** PHPSpec, Behat
-   **Ruby:** RSpec, Cucumber
-   **JavaScript:** JSSpec, jspec
-   **Phython:** Freshen

## Ventajas de BDD (Behavior Driven Development)

Si estás pensando en implementar BDD en tus desarrollos, aquí te dejo algunas ventajas que beneficiarán al equipo de trabajo:

1.  Ya no estás definiendo 'pruebas', sino que está definiendo 'comportamientos'.
2.  Mejora la comunicación entre desarrolladores, testers, usuarios y la dirección.
3.  Debido a que BDD se específíca utilizando un lenguaje simplificado y común, la curva de aprendizaje es mucho más corta que TDD.
4.  Como su naturaleza no es técnica, puede llegar a un público más amplio.
5.  El enfoque de definición ayuda a una aceptación común de las funcionalidades previamente al desarrollo.
6.  Esta estrategia encaja bien en las metodologías ágiles, ya que en ellas se especifican los requisitos como historias de usuario y de aceptación.

## Conclusión

BDD te permite desarrollar, probar y pensar el código desde la perspectiva del usuario. Debes tener la mentalidad de implementar 'ejemplos del mundo real' en lugar de implementar solo 'funcionalidades'. Las ventajas son muy considerable para integrar a todo el equipo con un objetivo común, además de empatizar con el usuario final de tus desarrollos.

**¿Qué estrategia de desarrollo implementas? ¿Utilizas metodología  TDD o  BDD*****?*** **¿Quizás ambas? ¿Tienes alguna experiencia para compartir?**

Photo by [Randy Fath](https://unsplash.com/@randyfath?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)