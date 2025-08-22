Sistema de Gerenciamento de Eventos

Projeto academico para universidade São Judas, desenvolvido em Java(primeiro projeto). 
Este projeto oferece funcionalidades básicas para criação, listagem, participação e cancelamento de eventos por usuários.

Funcionalidades

- Cadastro de eventos com:
  - Nome
  - Endereço
  - Categoria
  - Horário (com suporte a data e hora)
  - Descrição
- Listagem de eventos
- Participação e cancelamento de eventos por usuários
- Salvamento e carregamento de eventos via arquivo (`events.data`)

Estrutura do Projeto

- `Evento`: Representa um evento com participantes.
- `Usuario`: Representa um usuário com dados pessoais.
- `ArquivoUtil`: Lê e salva eventos usando serialização de objetos.
- `Sistema`: Controla a lógica principal do sistema.
- `Main`: Classe principal com interface de texto para interação com o usuário.

## 🛠️ Requisitos

- Java 8** ou superior
- IDE ou terminal com suporte para compilação e execução de código Java

Como Executar

1. Clone o repositório:

Como entrar na bash:
Git clone https://github.com/DFM210383/sistema-eventos-java.git
cd sistema-eventos-java
