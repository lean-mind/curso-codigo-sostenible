# Listado de problemas del repositorio

Listado de ejemplos de código real para trabajar en mob programming, pairing o debate con code reviews.

* Ejercicio de diseño
    * Diseñar e implementar con TDD un motor de plantillas tipo Handlebars. Prestar especial atención a los casos límites como ausencia de variables o de valores, así como el soporte de estructuras de datos complejas, no solamente strings.

* Responsabilidades y principios de diseño, ejercicio para pensar y refactorizar:
    * Repositorio: https://github.com/lean-mind/savvily-orders-manager/commits/main
    * Commit: 5a0a372d66991ecc355008cd464b1c254e162f7e
    * Método de partida: OrderResource.java, linea 38, process order - controller.
    * Tiempo estimado de trabajo: 2+ horas

* Refactorizar
  * Repositorio: https://github.com/lean-mind/savvily-orders-manager/commits/main
  * Commit: 36cd23d216f455ee6aefee1c284616f8d52ef31c
  * Método de partida: MailService.java, línea 20, send an order - service.
  * Tiempo estimado de trabajo: 2+ horas

* Responsabilidades y principios de diseño, refactorizar
  * Repositorio: https://github.com/lean-mind/savvily-orders-manager/commits/main
  * Commit: 0a178e7fe849b2513195b36ba68308dff8e391e7
  * Método de pártida: OrderHandlerService.java, línea 35, process order - service
  * Posibles cuestiones a plantear:
    * ¿Hace falta OrderTransformer? ¿Está bien implementado?
    * ¿OrderRestService? ¿Qué problemas tiene?
    * ¿Qué te parece cómo se están gestionando las dependencias?, ¿son adecuadas?
  * Tiempo estimado de trabajo: 2+ horas