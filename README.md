# dio-trilha-java-basico-modelagem-diagrama-iPhone
Desafio DIO Programação Orientada a Objetos Modelagem e Diagramação de um Componente iPhone


## Diagrama UML (Mermaid)
```mermaid
classDiagram
    class ReprodutorMusical {
        +tocar()
        +pausar()
        +selecionarMusica(String musica)
    }

    class AparelhoTelefonico {
        +ligar(String numero)
        +atender()
        +iniciarCorreioVoz()
    }

    class NavegadorInternet {
        +exibirPagina(String url)
        +adicionarNovaAba()
        +atualizarPagina()
    }

    class iPhone {
    }

    iPhone --> ReprodutorMusical
    iPhone --> AparelhoTelefonico
    iPhone --> NavegadorInternet
```


## Refencias

[Desafio Dio](https://github.com/glysns/trilha-java-basico/desafios/poo/README.md)
