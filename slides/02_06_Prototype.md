---
title: Filmina - Patron Prototype
theme: league
slideNumber: true
---

# Patrones de diseño

## Prototype

<small>
Created by <br/>

[rmarku]("https://t.me/rmarku") <i class="fab fa-telegram"></i> 

</small>
---
### Prototype

Este patron **Creacional** permite crear un objeto haciendo una copia de uno ya existente.

---
### Prototype

#### Motivación

Algunas veces, la creación de un objeto es muy compleja, o conlleva mucho tiempo. Para solucionarlo, podemos realizar
copias de un objeto ya creado y solo cambiar sus parámetros al objeto copiado.

---
#### Aplicabilidad:

Se debe usar Prototype cuando:

* Las clases a instanciar son especificadas en tiempo de ejecución, o
* Cuando sólo existe un número pequeño de combinaciones diferentes de estado para las instancias de uan clase.

---
#### Prototype

#### Estructura

![img](http://www.plantuml.com/plantuml/proxy?fmt=svg&src=https://raw.githubusercontent.com/UCC-ArquitecturaSoftwareI/DesignPatternDiagrams/master/Creacionales/prototype.txt)

---
### Prototype

#### Participantes

* **Prototype**: Declara interfaz para clonarse
* **Concrete Prototype**: Implementa una operación para clonarse
* **Cliente**: Crea un nuevo objeto solicitándole al prototipo que se clone

---

#### DEMO

#### Estructura

![img](http://www.plantuml.com/plantuml/proxy?fmt=svg&src=https://raw.githubusercontent.com/UCC-ArquitecturaSoftwareI/DesignPatternDiagrams/master/Creacionales/prototype_example.txt)

---
# DEMO
