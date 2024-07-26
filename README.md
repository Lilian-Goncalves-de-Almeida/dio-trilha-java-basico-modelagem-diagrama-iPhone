# dio-trilha-java-basico-modelagem-diagrama-iPhone
Desafio DIO Programação Orientada a Objetos Modelagem e Diagramação de um Componente iPhone


## Diagrama UML (Mermaid)
```mermaid
classDiagram
    class ReprodutorMusical {
        -musicaAtual:Musica
        -musicas:List<Musica>
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
        -linkAtual:URL
        -linksAbertos:List<URL>
        +exibirPagina(String url)
        +adicionarNovaAba(URL url)
        +atualizarPagina()
    }

    class iPhone {
        #reprodutor:ReprodutorMusical
        #telefone:AparelhoTelefonico
        #navegador:NavegadorInternet
    }

    class Musica {
        -titulo:String
        -autor:String
    }

    class URL {
        -link:String
    }

    iPhone --> ReprodutorMusical
    iPhone --> AparelhoTelefonico
    iPhone --> NavegadorInternet
    Musica --> ReprodutorMusical
    URL --> NavegadorInternet
```


## Refencias

[Desafio Dio](https://github.com/glysns/trilha-java-basico/desafios/poo/README.md)
