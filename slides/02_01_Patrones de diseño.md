---
title: Patrones de diseño
theme: league
slideNumber: true
---

# Patrones de diseño

<small>
Created by <br/>

[rmarku]("https://t.me/rmarku") <i class="fab fa-telegram"></i> 

</small>
---

### Patrones de diseño

* Es una solución general reusable a un problema que ocurre comúnmente
en un contexto dado en el diseño de software.
* Es la descripción de un problema junto con la solución a dicho problema.
* Definen una solución a un problema recurrente

---

### Patrones de diseño

Christopher Alexander

_"Each pattern describes a problem which occurs over and over again 
in our environment, and then describes the core of the solution to
that problem, in such a way that you can use this solution a million
times over, without ever doing it the same way twice"_

---

### Patrones de diseño

Para describir un patron de diseño se suele utilizar las siguientes características:

* Nombre del Patrón
* El problema que intenta solucionar
* La solución
* Las consecuencias

---

### Patrones de diseño

Clasificación de los patrones

Los patrones se pueden clasificar según varios criterios:

* Según su Propósito
* Según su Scope

---
<table style="text-align: center" >
    <tr>
        <td></td>
        <td></td>
        <td colspan="3"  style="border-bottom: solid 1px #ddd;text-align: center"><h1>Purpose</h1></td>
    </tr>
    <tr>
        <td></td>
        <td style="border-right: solid 1px #ddd;"></td>
        <td style="border-bottom: solid 1px #ddd;border-right: solid 1px #ddd;"><h2>Creational</h2></td>
        <td style="border-bottom: solid 1px #ddd;border-right: solid 1px #ddd;"><h2>Structural</h2></td>
        <td style="border-bottom: solid 1px #ddd;"><h2>Behavioral</h2></td>
    </tr>
    <tr>
        <td rowspan="2"><h1>Scope</h1></td>
        <td style="border-bottom: solid 1px #ddd;border-right: solid 1px #ddd;"><h2>Class</h2></td>
        <td style="border-bottom: solid 1px #ddd;border-right: solid 1px #ddd;">Factory Method</td>
        <td style="border-bottom: solid 1px #ddd;border-right: solid 1px #ddd;">Adapter</td>
        <td style="border-bottom: solid 1px #ddd;">Interpreter<br>Template Method</td>
    </tr>
    <tr style="border-bottom: solid 1px #ddd;">
        <td style="border-right: solid 1px #ddd;"><h2>Object</h2></td>
        <td style="border-right: solid 1px #ddd;">
            Abstract Factory<br>
            Builder<br>
            Prototype<br>
            Singleton
        </td>
        <td style="border-right: solid 1px #ddd;">
            Adapter<br>
            Bridge<br>
            Composite<br>
            Decorator<br>
            Facade<br>
            Flyweight<br>
            Proxy
        </td>
        <td>
            Chain of Responsibility<br>
            Command<br>
            Iterator<br>
            Mediator<br>
            Memento<br>
            Observer<br>
            State<br>
            Strategy<br>
            Visitor
        </td>
    </tr>
</table>

