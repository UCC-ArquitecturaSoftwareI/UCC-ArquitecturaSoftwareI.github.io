---
title: Para comenzar
theme: black
slideNumber: true
---
# Antipatrones

---
## Tipos de antipatrones

* De Programación
* De Metodologias
* De Diseño
* de Organización

---
## Antipatron de Programación

### Complegidad Accidental (Accidental Complexity)

Introducir complejidad inecesaria en una solución

---
## Antipatron de Programación

### Cargo Cult Programing (Culto a la programación)

Usar patrones, metodos, metodologias sin saber por que.


---
## Antipatron de Programación

### Spaguetti Code

Realizar estructuras incomprensibles principalmente por mal uso de las estructuras de código.


---
## Antipatron de Programación

### Hard Code

Incluir constantes supuestas del sistema y el entorno.


---
## Antipatron de Programación

### Soft Code

Guardar logica de negocio en archivos de configuración en vez de en codigo.


---
## Antipatron de Programación

### Lava Flow

Mantener código viejo, malo o redundante, porque sacarlo es muy costoso o no se sabe que consecuencias puede tener.

---
## Antipatron de Programación

### Boat Anchor

Mantener parte del sistema aunque no esté mas en uso.

---
## Antipatron de Programación

### Magic Numbers - Magic Strings

Incluir en el código números en algoritmos o string en comparaciones o eventos.


---
## Antipatron de Programación

### Single function exit point

```
function merge(Persona p){
    var result;
    if(p.edad > 120){
        if(p.edad < 0){
            if(p.nombre.lenght == 0){
                    // todo mi codigo
            }else{
                result = "El nombre es muy corto";
            }
        }else{
            result = "La edad no puede ser menor a 0";
        }
    }else{
        result = "No puede haber una persona tan vieja, verifique la edad";
    }
    return result;
}

```

---
## Antipatron de Programación

### Guard Class

```
function merge(Persona p){
    var result;
    if(p.edad > 120){ 
        return "No puede haber una persona tan vieja, verifique la edad"; 
    }
    if(p.edad < 0){ 
        return "La edad no puede ser menor a 0"; 
    }
    if(p.nombre.lenght == 0){ 
        return "El nombre es muy corto";
    }
    
     // todo mi codigo
}

```

---
## Antipatron de Programación

### Arrow Anti-Pattern

```
if(){
    if(){
        if(){
            if(){
                if(){
                    // Super código acá
                }
            }
        }
    }
}

```
---
## Antipatron de Metodología


* Copy and paste programming
* Tester Driven Development
* Someone else's example
* Programing by permutati

---
## Antipatron de Diseño

* Dependencias circulares
* God Object
* Sequential Coupling
* Base bean