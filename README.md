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
![Untitled diagram-2024-10-26-152614](https://github.com/user-attachments/assets/23b61fe3-f264-400b-b214-d20345fc4705)
