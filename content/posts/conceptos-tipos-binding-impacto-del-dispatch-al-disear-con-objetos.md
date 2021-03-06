---
title: "conceptos-tipos-binding-impacto-del-dispatch-al-disear-con-objetos"
date:  2018-06-20T19:27:10-03:00
---


* Relacionar el concepto de multiple dispatch con el patrón [double dispatch](http://www.mimuw.edu.pl/~sl/teaching/00_01/Delfin_EC/Patterns/DoubleDispatch.htm) que se suele utilizar en lenguajes con dispatch simple como Java o Smalltalk (también se puede mirar el patrón Visitor, un uso común del double dispatch).
* ¿Hay binding dinámico en los métodos de clase de Java? ¿Y en Smalltalk? ¿Puede establecer alguna relación con el patrón Singleton?
* ¿Por qué ¿Hay polimorfismo / binding dinámico cuando invocamos un constructor en Java? ¿Cómo nos damos cuenta? ¿Cómo se relaciona eso con el patrón Factory Method? ¿Cómo cambia todo esto en un lenguaje como Smalltalk?
* ¿Cómo es el binding al acceder a un atributo Java o Smalltalk? ¿Cómo se relaciona con las buenas prácticas de programación que proponen usar sólo variables privadas y acceder a ellas mediante métodos *accessors (getters) *y *mutators (setters)?*