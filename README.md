# Diagramação de Classes do iPhone
Este desafio envolve a criação de um diagrama UML para modelar as classes e interfaces Java que representam as funcionalidades do iPhone em três papéis principais: Reprodutor Musical, Aparelho Telefônico e Navegador na Internet.

![uml-iphone drawio](https://github.com/reissjoao/desafio-diagrama-classes-iphone/assets/106037010/2aeb30f8-55a0-4439-88d3-b44cc22b7f05)

## ``Classe iPhone``

A classe iPhone representa o iPhone e possui três atributos que representam os papéis do iPhone: reprodutor, telefone e navegador. Abaixo, uma descrição dos métodos dessa classe:

### ``Interface ReprodutorMusical``

A interface ReprodutorMusical define os métodos relacionados à funcionalidade de reprodução de música:

- tocar(): Inicia ou retoma a reprodução de música.
- pausar(): Pausa a reprodução de música.
- selecionarMusica(musica: String): Permite ao usuário selecionar uma música específica para ser reproduzida.

### ``Interface AparelhoTelefonico``

A interface AparelhoTelefonico define os métodos relacionados à funcionalidade telefônica:

- ligar(numero: String): Permite ao usuário ligar para um número especificado.
- atender(): Permite ao usuário atender uma chamada recebida.
- iniciarCorreioVoz(): Inicia a função de correio de voz.

### ``Interface NavegadorInternet``

A interface NavegadorInternet define os métodos relacionados à funcionalidade de navegação na Internet:

- exibirPagina(url: String): Exibe uma página da web com base em uma URL especificada.
- adicionarNovaAba(): Adiciona uma nova aba ao navegador para abrir e visualizar várias páginas da web simultaneamente.
- atualizarPagina(): Atualiza a página da web atualmente exibida no navegador.

### Diagrama realizado através do site https://www.draw.io/.
