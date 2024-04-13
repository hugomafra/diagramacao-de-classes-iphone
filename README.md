# 📱 Diagramação de classes do iPhone

## 📋 Descrição
Neste repositório, você encontrará uma implementação abrangente de um desafio de modelagem de software que tem como objetivo representar de forma detalhada e precisa as funcionalidades de um iPhone. Este projeto utiliza princípios de programação orientada a objetos e técnicas de modelagem UML para criar uma estrutura robusta e versátil que permite que um dispositivo iPhone desempenhe os três papéis distintos e cruciais: Reprodutor Musical, Aparelho Telefônico e Navegador na Internet.

Este repositório não apenas fornece o código-fonte em Java para as classes e interfaces correspondentes, mas também inclui uma documentação completa, insights de design e instruções detalhadas sobre como executar o código e explorar o diagrama UML associado. Ao explorar este projeto, eu tive a oportunidade de aprender e aplicar melhores práticas de engenharia de software, desenvolvendo um entendimento profundo de como a modelagem e a programação orientada a objetos podem ser utilizadas para criar sistemas complexos e funcionais.


## 📊 Diagrama UML
<p align="center">
  <img src="https://private-user-images.githubusercontent.com/114294017/322202225-291df9eb-f285-486d-85f9-a947a1921b66.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTMwMDg1NjcsIm5iZiI6MTcxMzAwODI2NywicGF0aCI6Ii8xMTQyOTQwMTcvMzIyMjAyMjI1LTI5MWRmOWViLWYyODUtNDg2ZC04NWY5LWE5NDdhMTkyMWI2Ni5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNDEzJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDQxM1QxMTM3NDdaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0wZDI4OTlmN2RkNzM0YzMwNTlkOTM5OTliYTgwMzBmNmVjZDE3MjUyYzVkMzhjN2IyMjI5OTQ4NWIyYmVhYjZhJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.OJA8AbGj6LbT5ullkWMoYAH23pi0nnioyB4hdRB72gE"/>
</p>


Nesta seção, apresentamos uma explicação detalhada de cada classe representada no diagrama de classe do projeto. Cada classe desempenha um papel específico e contribui para a funcionalidade global do sistema.

### `iPhone`

A classe `iPhone` é a classe principal que representa o dispositivo como um todo. Ela implementa as interfaces `ReprodutorMusical`, `AparelhoTelefonico` e `NavegadorInternet`. Isso permite que o iPhone desempenhe os papéis de reprodutor musical, aparelho telefônico e navegador na Internet. 

### `ReprodutorMusical`

A interface `ReprodutorMusical` define os métodos necessários para controlar a reprodução de música, como `tocar()`, `pausar()` e `selecionarMusica()`. As classes que implementam essa interface são capazes de reproduzir músicas.

### `AparelhoTelefonico`

A interface `AparelhoTelefonico` define os métodos para realizar chamadas telefônicas e enviar mensagens, incluindo `ligar()`, `atender()` e `iniciarCorreioVoz()`. As classes que implementam essa interface podem funcionar como dispositivos telefônicos.

### `NavegadorInternet`

A interface `NavegadorInternet` define métodos para a navegação na web, como `exibirPagina()`, `adicionarNovaAba()` e `atualizarPagina()`. As classes que implementam essa interface podem atuar como navegadores da Internet.

Cada classe ou interface desempenha um papel específico no sistema e contribui para a versatilidade do dispositivo iPhone, tornando-o capaz de realizar uma variedade de funções.

Se você deseja explorar mais detalhes do diagrama de classes [clique aqui](docs/iPhone-modelagem.pdf) para ser redirecionado ao arquivo PDF correspondente.

## 💡 Como usar
Clone o repositório em sua máquina local usando o comando git clone.
Abra o projeto em sua IDE Java preferida.
Explore o código-fonte e o diagrama UML para entender como as classes estão relacionadas e como cada papel é implementado.
Consulte o README.md para informações detalhadas sobre o desafio, escolhas de design e instruções para execução.

Este repositório foi uma valiosa fonte de aprendizado para mim, em busca de aprofundar seus conhecimentos em modelagem de software, programação orientada a objetos e design de sistemas de software complexos.
