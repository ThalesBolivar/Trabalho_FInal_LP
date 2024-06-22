# Sistema de Venda de Ingressos

Este projeto é um sistema para a venda de ingressos online. Ele permite que usuários comprem ingressos para eventos de maneira fácil e rápida.

## Instalação

### Pré-requisitos
- [IntelliJ IDEA](https://www.jetbrains.com/idea/)
- [Java Development Kit (JDK) 17](https://www.oracle.com/java/technologies/javase-downloads.html)
- [JavaFX](https://openjfx.io/)

### Passos para Instalação
1. Clone o repositório:
    ```sh
    git clone https://github.com/<seu-usuario>/<seu-repositorio>.git
    ```
2. Abra o IntelliJ IDEA e importe o projeto:
    - File > Open > Selecione o diretório do projeto

3. Configure o JDK:
    - O projeto está configurado para usar o JDK 17:
      - File > Project Structure > Project > Project SDK > Escolha o JDK 17

4. Adicione as bibliotecas JavaFX ao projeto:
    - Siga as instruções em [JavaFX Getting Started](https://openjfx.io/openjfx-docs/) para configurar JavaFX no IntelliJ IDEA.

## Funcionalidades

- **Gerenciamento de Carrinho de Compras**: Implementado em `Carrinho.java`, permite aos clientes selecionar e gerenciar itens para compra.
- **Gerenciamento de Clientes**: `Cliente.java` trata das informações e operações relacionadas aos clientes que utilizam o sistema.
- **Controle de Estoque**: `Estoque.java` gerencia o inventário de produtos disponíveis para venda.
- **Opções de Forma de Pagamento**: `FormaPagamento.java` define as opções de pagamento disponíveis para os clientes.
- **Registro e Gestão de Vendas**: `Venda.java` gerencia o processo de vendas, incluindo a criação de pedidos e faturas.
- **Gestão de Pessoas**: `Pessoa.java` e `Vendedor.java` representam clientes e vendedores no sistema.
- **Interface de Usuário**: Telas implementadas em `ui` facilitam interações como cadastro, visualização de carrinho, gestão de estoque, login e pagamentos.

## Desenvolvimento

O desenvolvimento do sistema está em andamento para incluir funcionalidades como pesquisa de eventos, compra de ingressos online, geração de QR codes para ingressos e histórico de compras de usuários.

## Contribuição

Para contribuir com o projeto, siga estes passos:

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`)
3. Faça commit das suas alterações (`git commit -m 'Adiciona nova feature'`)
4. Faça push para a branch (`git push origin feature/nova-feature`)
5. Abra um Pull Request

## Autores

- **Thales Augusto e Tarik Sampaio** 

## Agradecimentos

- Agradecimentos ao professor João Paulo Aramuni pelas orientações e conhecimentos compartilhados, fundamentais para a entrega deste trabalho final.
