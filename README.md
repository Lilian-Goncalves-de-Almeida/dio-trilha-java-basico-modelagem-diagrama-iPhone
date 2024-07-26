# dio-trilha-java-basico-modelagem-diagrama-iPhone
Desafio DIO Programação Orientada a Objetos Modelagem e Diagramação de um Componente iPhone


## Diagrama UML (Mermaid)
```mermaid
classDiagram
    class ReprodutorMusical {
        +exemploMetodo1()
        +exemploMetodo2(String exemplo)
    }

    class AparelhoTelefonico {
        +exemploMetodo1()
        +exemploMetodo2(String exemplo)
    }

    class NavegadorInternet {
        +exemploMetodo1()
        +exemploMetodo2(String exemplo)
    }

    class iPhone {
    }

    iPhone --> ReprodutorMusical
    iPhone --> AparelhoTelefonico
    iPhone --> NavegadorInternet
```


## Refencias

[Desafio Dio](https://github.com/glysns/trilha-java-basico/desafios/poo/README.md)
