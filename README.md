# diagrama-UML-Iphone
criar um diagrama UML que represente as funcionalidades do componente iPhone

Este projeto contém a modelagem e a diagramação UML do componente iPhone, abrangendo suas funcionalidades como Reprodutor Musical, Aparelho Telefônico e Navegador na Internet.

## Funcionalidades a Modelar

### Reprodutor Musical
- **Métodos**:
  - `tocar()`
  - `pausar()`
  - `selecionarMusica(String musica)`

### Aparelho Telefônico
- **Métodos**:
  - `ligar(String numero)`
  - `atender()`
  - `iniciarCorreioVoz()`

### Navegador na Internet
- **Métodos**:
  - `exibirPagina(String url)`
  - `adicionarNovaAba()`
  - `atualizarPagina()`
 

// Interface ReprodutorMusical
public interface ReprodutorMusical {
    void tocar();
    void pausar();
    void selecionarMusica(String musica);
}

// Interface AparelhoTelefonico
public interface AparelhoTelefonico {
    void ligar(String numero);
    void atender();
    void iniciarCorreioVoz();
}

// Interface NavegadorNaInternet
public interface NavegadorNaInternet {
    void exibirPagina(String url);
    void adicionarNovaAba();
    void atualizarPagina();
}

// Classe iPhone que implementa as interfaces
public class iPhone implements ReprodutorMusical, AparelhoTelefonico, NavegadorNaInternet {
    // Métodos de ReprodutorMusical
    @Override
    public void tocar() {
        // Implementação do método tocar
        System.out.println("Tocando música.");
    }


    @Override
    public void pausar() {
        // Implementação do método pausar
        System.out.println("Música pausada.");
    }

    @Override
    public void selecionarMusica(String musica) {
        // Implementação do método selecionarMusica
        System.out.println("Música selecionada: " + musica);
    }

    // Métodos de AparelhoTelefonico
    @Override
    public void ligar(String numero) {
        // Implementação do método ligar
        System.out.println("Ligando para: " + numero);
    }

    @Override
    public void atender() {
        // Implementação do método atender
        System.out.println("Atendendo chamada.");
    }

    @Override
    public void iniciarCorreioVoz() {
        // Implementação do método iniciarCorreioVoz
        System.out.println("Iniciando correio de voz.");
    }

    // Métodos de NavegadorNaInternet
    @Override
    public void exibirPagina(String url) {
        // Implementação do método exibirPagina
        System.out.println("Exibindo página: " + url);
    }

    @Override
    public void adicionarNovaAba() {
        // Implementação do método adicionarNovaAba
        System.out.println("Nova aba adicionada.");
    }

    @Override
    public void atualizarPagina() {
        // Implementação do método atualizarPagina
        System.out.println("Página atualizada.");
    }

 
![diagrama-uml-iphone](https://github.com/ThomasAlmeidaOne/diagrama-UML-Iphone/assets/87451474/fa433662-0f06-4605-bbc0-380e30927107)

 
