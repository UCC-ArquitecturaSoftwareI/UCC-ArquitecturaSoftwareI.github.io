---
title: Filmina - Patron Adapter
theme: league
slideNumber: true
---

# Patrones de diseño

## Adapter

<small>
Created by <br/>

[rmarku]("https://t.me/rmarku") <i class="fab fa-telegram"></i> 

</small>
---
### Adapter

Este patron **Estructural** que permite que dos clases con interfaces incompatibles colaboren.

---
### Adapter

#### Motivación

* Reutilizar clases con interfaces incompatibles

---
#### Aplicabilidad:

Se debe usar Adapter cuando:

* Se debe utilizar una clase existente y la interfaz no es compatible
* Se desea crear clases reusables que cooperan con clases no relacionadas
* Se desea utilizar diversas subclases existentes pero resulta im práctico adaptar sus interfaces mediante
 la extensión de todas ellas (utilizar un objeto adaptador de la clase padre)
---
#### Adapter

#### Estructura

![img](http://www.plantuml.com/plantuml/proxy?fmt=svg&src=https://raw.githubusercontent.com/UCC-ArquitecturaSoftwareI/DesignPatternDiagrams/master/Estructurales/adapter.txt)

---
### Adapter

#### Participantes

* **Adapter**: Interface con la que va a trabajar el cliente
* **Concrete Adapter**: Una clase que presenta la interface del Adapter, pero puede comunicarse con el Adaptee
* **Cliente**: Contiene la lógica de negocio del programa
* **Adaptee**: Es una clase util que el cliente quiere utilizar pero no puede hacerlo directamente.
---

#### DEMO

#### Estructura

![img](http://www.plantuml.com/plantuml/proxy?fmt=svg&src=https://raw.githubusercontent.com/UCC-ArquitecturaSoftwareI/DesignPatternDiagrams/master/Estructurales/adapter_example.txt)

---
# DEMO
