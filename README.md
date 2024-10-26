classDiagram
    class ReprodutorMusical {
        +tocar()
        +pausar()
        +selecionarMusica(String Castlevania)
    }

    class AparelhoTelefonico {
        +atender()
        +iniciarCorreioVoz()
        +ligar(Int 11994502042)
    }

    class NavegadorInternet {
        +exibirPagina(String google.com.br)
        +adicionarNovaAba()
        +atualizarPagina()
    }

    class iPhone {
        +ligar()
        +desligar()
    }

    iPhone --> ReprodutorMusical
    iPhone --> AparelhoTelefonico
    iPhone --> NavegadorInternet
