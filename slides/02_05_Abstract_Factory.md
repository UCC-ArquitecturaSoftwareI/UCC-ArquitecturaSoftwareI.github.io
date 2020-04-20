---
title: Patron Abstract Factory
theme: league
slideNumber: true
---

# Patrones de diseño

## Abstract Factory

<small>
Created by <br/>

[rmarku]("https://t.me/rmarku") <i class="fab fa-telegram"></i> 

</small>
---
### Abstract Factory

Este patron **Creacional** que permite crear una familia de objetos relacionados sin especificar la clase concreta.

---
### Abstract Factory

#### Motivación

Algunas veces un sistema debe tener grupos o conjuntos de objetos que están relacionados entre ellos y el cliente
no debe conocer las clases concretas que debería instanciar.

---
#### Aplicabilidad:

Se debe usar Abstract Factory cuando:

* Un sistema debe ser independiente de la forma en que sus productos son creados, compuestos o representados.
* Un sistema debe ser configurado con una de muchas familias de objetos disponibles.
* Una familia de productos están diseñados para trabajar en conjunto y se debe asegurar ese trabajo en conjunto.

---
#### Abstract Factory

#### Estructura

![img](http://www.plantuml.com/plantuml/svg/hP51IyD048NlyolcLaMIqlo0qcoX9y5IU_6ufeCD9hjXCZaKxNztYTaLkrrGyJA7UO_lxUoRpt2hXQt1KZtkT-LwZnit7dPFE9i3h7hHB4FROFdS2-jASEE6vHD0_rgRJhDkyRus9AUEqB8SBK3LwBx7TLEJ4G2nBoH7Odm3HEqneoTG9-XeGRohcBJGbkrXgAIykRsoLUFs36vCSTOuWz24MlmZg_W3w_opmpqhHFl58jeKZlahgBf4g0YgHkXdKvXboyj2hadXoMbD0KHrP4ENlSS1qLSdVE1Z8v8NWgD8Ehn5fI0gE698-hGypvTVnQNqq45yypT0aT93PR0YSnZQvWC0)

<!--

-->
---
### Abstract Factory

#### Participantes

* **Abstract Factory**: Declara interfaz para las operaciones que crean productos abstractos (métodos de fabricación)
* **Concrete Factory**: Implementa los métodos de fabricación de productos concretos
* **Abstract Product**: Declara la interfaz utilizada por el cliente para un tipo de producto concreto

---
### Abstract Factory

#### Participantes

* **Concrete Product**: Define un producto creado por el método de fabricación de una fábrica concretaImplementa la interfaz Producto Abstracto
* **Client**: Usa sólo las interfaces declaradas por Fábrica Abstracta y Productos Abstractos

---

#### DEMO

#### Estructura

![img](http://www.plantuml.com/plantuml/svg/hP71RhCm48Jl-nHxo_-h8dc3A90gfqYjKYuzEcGLKB2Dx4KAQddt8Z3KaCgNzkB3xEYROTYiy5MmqGhZv2qznViK3ztpSdh7rGPWPraOhcM9yTco4HdZeNkqQG3ihL2LC4BYiL34JKMe3USQ82ykX2GhRb2IF9En05afhCLzMP1Y0DPNufmCVW2Y6D639yr9aalfxuXFcI71bDJCMltxxsiftJdHzrvi0T11ZiKrvpyXFGjp-mse3N_j09ZtTfhVm4ajX6akUZ634ttUg7N0uPzW56rdq_lwaEufKn0y3XtLLVIvOBaHmoRmsph75EGDCvvSgnx-qwK_B721tklrUZiVBEJnmnyjtvK2XgdBZjIbbkKN)

<!--
![img](http://www.plantuml.com/plantuml/proxy?fmt=svg&src=https://raw.githubusercontent.com/UCC-ArquitecturaSoftwareI/DesignPatternDiagrams/master/Creacionales/abstract_factory_example.txt)

-->
---
# DEMO
