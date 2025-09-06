# Construindo um Editor de Texto com `iced`

Este projeto é uma reprodução do tutorial do YouTube "Building a text editor with syntax highlighting using Iced". O objetivo foi acompanhar o vídeo e reproduzir o projeto para aprofundar meu conhecimento e aprender a utilizar a biblioteca GUI `iced` para Rust.

## Sobre o Projeto

O projeto consiste na criação de um editor de texto simples com funcionalidade de realce de sintaxe. Durante o desenvolvimento, foram explorados os seguintes conceitos da biblioteca `iced`:

* Estrutura básica de uma aplicação `iced`.
* Uso de *widgets* e organização de *layouts* (como `Text`, `TextEditor`, `Container`, `Column`, `Row`, `Button`).
* Tratamento de eventos e o sistema de passagem de mensagens baseado na arquitetura Elm.
* Execução de operações assíncronas (como leitura e escrita de arquivos) sem bloquear a interface do usuário.
* Personalização da aplicação com temas, fontes e ícones.
* Integração de realce de sintaxe.
* Uso de assinaturas (`Subscriptions`) para eventos externos, como atalhos de teclado.

O tutorial, ministrado pelo próprio criador do `iced`, Hector, é um excelente recurso para quem deseja iniciar ou aprofundar seus conhecimentos em desenvolvimento de aplicações GUI com Rust.

## Referência

* **Tutorial no YouTube:** [Building a text editor with syntax highlighting using Iced](https://www.youtube.com/watch?v=gcBJ7cPSALo)
