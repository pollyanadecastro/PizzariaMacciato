# Pizzaria Macciato - Sistema de Gestão de Pedidos

## Descrição

Este é um sistema de gerenciamento de pedidos de uma pizzaria, desenvolvido em Python. O sistema permite o cadastro de pedidos, exibindo a lista de pedidos cadastrados e a escolha de sabores e tamanhos de pizzas. É um sistema simples, orientado a objetos, desenvolvido para fins educacionais.

## Funcionalidades

1. **Cadastrar Pedido**: Permite o cadastro de um novo pedido, incluindo nome do cliente, número de telefone, endereço de entrega, sabor e tamanho da pizza.
2. **Exibir Lista de Pedidos**: Mostra a lista de todos os pedidos cadastrados.
3. **Sair**: Encerra o programa.

## Instruções de Uso

### Requisitos

- Python 3.x instalado.

### Executando o Programa

1. Clone o repositório ou copie o código para um arquivo Python (`pizzaria.py`).
2. Abra o terminal ou prompt de comando.
3. Navegue até o diretório onde o arquivo `pizzaria.py` está salvo.
4. Execute o comando:
   ```sh
   python pizzaria.py
   ```
5. Siga as instruções apresentadas no terminal para interagir com o sistema.

### Navegação pelo Menu

- **Cadastrar Pedido**: Digite `1` e siga as instruções para inserir as informações do cliente e detalhes do pedido.
- **Exibir Lista de Pedidos**: Digite `2` para visualizar a lista de pedidos cadastrados.
- **Sair**: Digite `3` para encerrar o programa.

## Estrutura do Código

### Classe `Pedido`

Representa um pedido de pizza.

**Atributos:**
- `nome_cliente`: Nome do cliente.
- `telefone_cliente`: Número de telefone para contato.
- `endereco_cliente`: Endereço de entrega.
- `sabor_pizza`: Sabor da pizza escolhida.
- `tamanho_pizza`: Tamanho da pizza escolhida.

### Classe `Pizzaria`

Gerencia os pedidos da pizzaria.

**Atributos:**
- `lista_pedidos`: Lista que armazena os pedidos cadastrados.
- `lista_sabores`: Lista de sabores de pizzas disponíveis.

**Métodos:**
- `cadastrar_pedido()`: Coleta informações do cliente e do pedido e o cadastra na lista de pedidos.
- `exibir_pedidos()`: Exibe a lista de pedidos cadastrados.
- `executar_programa()`: Executa o menu principal do sistema.

### Função `main()`

Cria uma instância da classe `Pizzaria` e executa o programa.

## Autores

Este projeto foi desenvolvido por:
- Filipe Augusto Gama Pinheiro de Melo
- Pollyana de Castro Rodrigues
