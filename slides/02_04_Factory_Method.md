---
title: Patron Factory Method
theme: league
slideNumber: true
---

# Patrones de diseño

## Factory Method

<small>
Created by <br/>

[rmarku]("https://t.me/rmarku") <i class="fab fa-telegram"></i> 

</small>
---
### Factory Method

Este patron **Creacional** provee una interface para crear objetos en una superclase, pero
permite a las subclases alterar el tipo de objeto que se creará.

---
### Factory Method

#### Motivación

Algunas veces un sistema debe presentar de distinta manera un mismo tipo de información, por ejemplo, una
imagen que puede ser leída de distintos tipos de archivos de imagen.

---
#### Aplicabilidad:

Se debe usar Factory Method cuando:

* Una clase no puede anticipar que tipo de objeto debe ser creado
* Una clase quiere que sus subclases especifiquen que objeto se debe crear

---
#### Factory Method

#### Estructura

![img](http://www.plantuml.com/plantuml/proxy?fmt=svg&src=https://raw.githubusercontent.com/UCC-ArquitecturaSoftwareI/DesignPatternDiagrams/master/Creacionales/factory_method.txt)

---
### Factory Method

#### Participantes

* **Producto**: declara la interface de todos los productos que pueden ser creados
* **Concrete Product**: son las diferentes implementaciones del Producto
* **Creator**: declara el método factory que retornará un nuevo objeto producto.
* **Concrete Creator**: Sobrescribe el método factory, pera crear un producto concreto
---

#### DEMO

#### Estructura

![img](http://www.plantuml.com/plantuml/proxy?fmt=svg&src=https://raw.githubusercontent.com/UCC-ArquitecturaSoftwareI/DesignPatternDiagrams/master/Creacionales/factory_method_example.txt)

---
# DEMO
