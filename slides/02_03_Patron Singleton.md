---
title: Patron Singleton
theme: league
slideNumber: true
---

# Patrones de diseño

## Patron Singleton

<small>
Created by <br/>

[rmarku]("https://t.me/rmarku") <i class="fab fa-telegram"></i> 

</small>
---
### Patron Singleton

Este patron **Creacional** permite asegurarse que una clase tendrá solamente
una instancia, mientras provee una forma de aceder desde cualquier lado a esta
instancia.

---
### Patron Singleton

#### Motivación

Algunas veces es importante que una clase tenga solo una instancia. Cuando el recurso que ocupa
es uno solo. Por ejemplo la conexión a la Base de datos debe ser única, un archivo de logs debe
ser abierto solo una vez, el acceso a un conversor A/D debe ser uno solo, etc.

---
### Patron Singleton

```cpp
class Log{
    Log(){
        ofstream of("log.txt");
    }
}
...
Log lo();
ll.log("error");
...

Log lo();               // Error, archivo en uso.
ll.log("conectando");

```
---
### Patron Singleton

```cpp
class Log{
    Log(){
        ofstream of("log.txt");
    }
}
...
int main(){
    Log lo();
    MiClase mc(lo);
    ll.log("error");
}
...
lo.log("conectando");

```
---
#### Aplicabilidad:

Se debe usar Singleton cuando:

* Debe haber exactamente una instancia de una clase, y debe ser accesible a clientes desde cualquier lugar.

---
#### Patron Singleton

#### Estructura

![img](http://www.plantuml.com/plantuml/proxy?fmt=svg&src=https://raw.githubusercontent.com/UCC-ArquitecturaSoftwareI/DesignPatternDiagrams/master/Creacionales/singleton.txt)

---
### Patron Singleton

#### Participantes

Se compone de dos elementos principales

* **SINGLETON**: 
  * Define una instancia de la clase y deja a los clientes acceder a esta única instancia.
  * Puede ser responsable de crear su propia instancia.

---

#### DEMO

#### Estructura

![img](http://www.plantuml.com/plantuml/proxy?fmt=svg&src=https://raw.githubusercontent.com/UCC-ArquitecturaSoftwareI/DesignPatternDiagrams/master/Creacionales/singleton_example.txt)

---
# DEMO
